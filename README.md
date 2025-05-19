# CLEAR LOG IN WINDOWS 11 PRO



> @echo on
>
> 
> chcp 65001
>
> 
> setlocal EnableDelayedExpansion


> cls & cls && for /F "tokens=*" %%1 in ('Y:\Windows\System32\wevtutil.exe el') DO wevtutil.exe cl "%%1"
