# UncommonSense.Nav.Automation 
*PowerShell Utils for Microsoft Dynamics NAV*

###Notes
These functions support virtually all NAV versions - even versions that don't have native PowerShell or CLI (command line interface) support. Due to the technology used, the functions will only work in 32-bit (x86) PowerShell environments.

###Installation
Place the PowerShell script module (UncommonSense.Nav.Automation.psm1) in your module path (typically `C:\Users\{username}\Documents\WindowsPowerShell\Modules`) to make it instantly available in any PowerShell session.

###Get-NAVDevelopmentClient
Retrieves a list of running IDE instances. Pipe the output to Where-Object to filter.

###Start-NAVDevelopmentClient
Starts a NAV development client, using specified file path, servername and database.

###Get-NAVApplicationObjectInfo
Retrieves a list of custom objects containing information about NAV objects, according to the (optional) filters specified. Can receive pipeline input from Get-NAVDevelopmentClient. Note that, for most practical purposes, the `TypeFilter` parameter should be set to at least `<>TableData`.

###Export-NAVApplicationObject
Exports NAV objects from the selected NAV development environment instance. Can receive pipeline input from Get-NAVDevelopmentClient (if you need to export the same object from multiple databases) or Get-NAVApplicationObjectInfo (if you need to export a set of objects from a single database).

###Compile-NAVApplicationObject
Compiles NAV objects from the selected NAV development environment instance. Can receive pipeline input from Get-NAVDevelopmentClient (if you need to compile the same object in multiple databases) or Get-NAVApplicationObjectInfo (if you need to export a set of objects in a single database).

###Examples
```powershell
$ModifiedObjects = Get-NavApplicationObjectInfo `
    -DatabaseServerType SQL `
    -DatabaseServerName sourceservername `
    -DatabaseName sourcedatabasename `
    -TypeFilter '<>TableData' `
    -ModifiedFilter Yes
    
$ModifiedObjects | Export-NAVApplicationObject `
    -DatabaseServerType SQL `
    -DatabaseServer sourceservername `
    -DatabaseName sourcedatabasename `
    -Path sourcepath
        
$ModifiedObjects | Export-NAVApplicationObject `
    -DatabaseServerType SQL `
    -DatabaseServer targetservername `
    -DatabaseName targetdatabasename `
    -Path targetpath
```
###License
This project is licensed under the Apache 2.0 License. Please refer to LICENSE.md for more information.

###Acknowledgements
These functions use the CSide Integration Utilities library written by Thaddeus Ryker, licensed under the Apache 2.0 License. The source is obtainable at http://code.edgerunner.org/dynamics-nav-client-interface-library. 
