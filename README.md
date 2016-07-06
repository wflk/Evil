# Evil
Executes Mixed .NET and Native DLL via regsvr32 & rundll32

Built with Visual Studio 2015 Community Edition

 To call/execute simply 
 
 rundll32 evil.dll,EntryPoint
 
 regsvr32 /s /u evil.dll -->Calls DllUnregisterServer
 
 [OR] 
 
 regsvr32 /s evil.dll --> Calls DllRegisterServer
 
