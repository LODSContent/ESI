### Lab Setup


1. [] On @lab.VirtualMachine(SEA-DEV).SelectLink click @lab.CtrlAltDelete to activate the Ctrl + Alt + Delete sequence and bring up the logon page.

1. [] Sign in as +++@lab.VirtualMachine(SEA-DEV).Username+++ with the password +++@lab.VirtualMachine(SEA-DEV).Password+++.

1. [] @[Download lab files to E: Drive][DownloadFromGit]{powershell}

    >This will copy the latest lab files from Github and configure the directories as needed for the remainder of the lab exercises. You will not see any output on screen.

1. [] Use File Explorer and navigate to the E: drive. Confirm that there is now an  "AZ-301" folder; this was created from the prior step. 

1. [] Review Taskbar located at the bottom of your Windows 10 desktop. The Taskbar contains the icons for the common applications you will use in the labs:

    - Microsoft Edge

    - File Explorer

    - [Visual Studio Code](https://code.visualstudio.com/)

    - [Microsoft Azure Storage Explorer](https://azure.microsoft.com/features/storage-explorer/)

    - Bash on Ubuntu on Windows

    - Windows PowerShell

    >[!KNOWLEDGE] You can also find shortcuts to these applications in the **Start Menu**.

[DownloadFromGit]:

```
git clone "https://github.com/MicrosoftLearning/AZ-301-MicrosoftAzureArchitectDesign" "E:\AZ-301"
New-Item -Path "E:\" -Name "AZ-301\allfiles\AZ-301T01\Module_01\LabFiles\Starter" -ItemType Directory
New-Item -Path "E:\" -Name "AZ-301\allfiles\AZ-301T01\Module_02\LabFiles\Starter" -ItemType Directory
```
