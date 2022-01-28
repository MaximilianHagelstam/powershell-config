# Powershell Config

## Setup

1. Install PowerShell Core from the Microsoft Store
2. Create a folder called **PowerShell** in the Documents folder
3. Download this repo and copy both **Microsoft.PowerShell_profile.ps1** and **prompt.json** into the PowerShell folder
4. Replace <USER_NAME> with your windows user on line 12 in **Microsoft.PowerShell_profile.ps1**
5. Install needed packages:

```
# oh-my-posh
winget install JanDeDobbeleer.OhMyPosh

# Terminal-Icons
Install-Module -Name Terminal-Icons -Repository PSGallery

# PSReadLine
Install-Module PSReadLine -RequiredVersion 2.2.0-beta4 -AllowPrerelease
```

#### If you get the **_Winget Not Recognized Error_** install **App Install** from the Microsoft Store

5. Install Caskaydia Cove Nerd Font [here](https://www.nerdfonts.com/font-downloads)
6. Open your Windows Terminal settings JSON file and replace the contents with the **settings.json** file in this repo

## Inspiration
https://www.youtube.com/watch?v=VT2L1SXFq9U&list=PLgxlRBw2qiJnj82r96untMquylw2YsQ6g&index=16
