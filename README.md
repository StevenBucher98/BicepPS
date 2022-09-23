# Bicep PS Module

This is a quick module I created using `Microsoft.PowerShell.Crescendo` module to wrap the `bicep` native command in Windows. NOTE: This only works on Windows currently

## Installation
- Clone this repo
- Install `bicep` via these [instructions](https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/install#manual-with-powershell)
- Run `Import-Module .\BicepPS.psd1`
- Add above cmd in your Profile with full path to keep it persistently imported.

## Commands
```powershell
CommandType     Name                                               Version    Source
-----------     ----                                               -------    ------
Function        Build-BicepFile                                    0.0.1      BicepPS
Function        Build-BicepParameters                              0.0.1      BicepPS
Function        Get-BicepHelp                                      0.0.1      BicepPS
Function        Get-BicepVersion                                   0.0.1      BicepPS
Function        Invoke-BicepFileDecompile                          0.0.1      BicepPS
Function        Publish-BicepFile                                  0.0.1      BicepPS
Function        Restore-BicepFile                                  0.0.1      BicepPS
```
