# Lab Setup

1. On @lab.VirtualMachine(DP-200AWindows10_20200402).SelectLink click @lab.CtrlAltDelete to activate the Ctrl + Alt + Delete sequence and bring up the logon page.

    >[!KNOWLEDGE] Any links like the one above will send Ctrl+Alt+Delete to the selected machine. This can also be done the **Commands** menu (lightning bolt) in the upper-left hand corner of the screen.

1. Sign in as +++@lab.VirtualMachine(DP-200AWindows10_20200402).Username+++ with the password +++@lab.VirtualMachine(DP-200AWindows10_20200402).Password+++.

1. @[Download lab files][DownloadFromGit]{powershell}


[DownloadFromGit]:

```
While((Get-Partition -DiskNumber 1).DriveLetter -ne "E"){
Get-Partition -DiskNumber 1 | Set-Partition -NewDriveLetter E
}
git clone "https://github.com/MicrosoftLearning/DP-200-Implementing-an-Azure-Data-Solution.git" "E:\Allfiles" 
```

> [!knowledge] This will copy the latest lab files from Github and configure the directories as needed for the remainder of the lab exercises. You will not see any output on screen.

>[!note] Please allow two to three minutes for the files to download fully to the E: drive. If you do not see the files after waiting three minutes,  right-click in the **Allfiles** folder and then select **Refresh**. 
