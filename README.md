
This uses oh-my-posh
Please install this from https://ohmyposh.dev/docs/installation/windows and follow all instructions there

1. Go to C:\Users\YOURUSERNAME\Documents\WindowsPowerShell or %USERPROFILE%\Documents\WindowsPowerShell
2. Backup Microsoft.PowerShell_profile.ps1
3. Replace Microsoft.PowerShell_profile.ps1 with the one in this project
4. Launch terminal

This will randomise your theme each time you open the command line. If you want to turn this off change the value 

```ps1
[CmdletBinding()]
param (
    [Parameter()][bool]$randomiseThemes = $true
)
```
to
```ps1
[CmdletBinding()]
param (
    [Parameter()][bool]$randomiseThemes = $false
)
```

![Command Line with themes](/img/cmd.jpg "Command line")