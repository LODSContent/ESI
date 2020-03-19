## Before you start

### Sign in to the lab virtual machine

Log on to @lab.VirtualMachine(AZ-204T00A-SEA-DEV).SelectLink by pressing @lab.CtrlAltDelete and typing in the following credentials:
    
**Username**: +++@lab.VirtualMachine(AZ-204T00A-SEA-DEV).Username+++
    
**Password**: +++@lab.VirtualMachine(AZ-204T00A-SEA-DEV).Password+++

---

## Download the lab files

1. [] @[Download lab files to F: Drive][DownloadFromGit]{powershell}
>This will copy the latest lab files from Github. You will not see any output on screen.

[DownloadFromGit]:

```
start-job -name gitClone -ScriptBlock {git clone "https://github.com/MicrosoftLearning/AZ-204-DevelopingSolutionsforMicrosoftAzure.git" 'C:\Users\Admin\AppData\Roaming\temp\'}
wait-job -name gitClone
move-item 'C:\Users\Admin\AppData\Roaming\temp\Allfiles' 'f:\' -force
```
