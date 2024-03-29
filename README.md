# Interface to the Operating system 


`OS` is a member of the APLTree library. The library is a collection of classes etc. that aim to support the Dyalog APL programmer. Search GitHub for "apltree" and you will find solutions to many every-day problems Dyalog APL programmers might have to solve.


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

## Requirements

`OS` needs version 18.0 Unicode of Dyalog APL.
