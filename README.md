# OS: Interface to the Operating system 

## Overview

This class offers methods that return the same result under Windows, Linux (without the PI) and Mac OS.

Examples are `GetPID` and `KillPID`.

Exceptions are the functions `ShellExecute` (Linux/Mac only) and `WinExecute` (Windows only). They
perform very similar tasks but with very different parameters and results, so they were separated.

## List of methods 

```
Shared Methods:                                                                                                                     
  CreateParms_WinExecute
  GetPID           
  GetSharedLib     
  KillPID          
  ShellExecute     
  Version          
  WinExecute       
```


`OS` needs version 15.0 Unicode of Dyalog APL.