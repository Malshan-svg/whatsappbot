Set oShell = CreateObject ("Wscript.Shell") 
Dim strArgs
strArgs = "cmd /c nodewhatsapp.bat"
oShell.Run strArgs, 0, false