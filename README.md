# Bicep PS Module

This is a quick module I created using `Microsoft.PowerShell.Crescendo` module to wrap the `bicep` native command in Windows. NOTE: This only works on Windows currently

## Installation
- Clone this repo
- Install `bicep` via these [instructions](https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/install#manual-with-powershell)
- Run `Import-Module .\BicepPS.psd1`
- Add above cmd in your Profile with full path to keep it persistently imported.
