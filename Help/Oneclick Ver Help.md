# Oneclick Ver Revert

Note: If you created a Restore Point you can just use that <3

1. Open [Nsudo](https://github.com/QuakedK/Task-Destroyer/raw/refs/heads/main/Downloads/NSudoLG.exe) and Enable All Privileges.
2. Then type CMD in the Address Bar, then click run and paste the following commands.
```bat
reg import "C:\Oneclick Tools\Task Destoyer\Reg Backup\TaskSchedulerBackup.reg"
rd /s /q "C:\WINDOWS\System32\Tasks"
move "C:\Oneclick Tools\Task Destoyer\Task Folder\Tasks" "C:\WINDOWS\System32\Tasks"
```
# #3 Revert (Without adding back all of the original task)
Note: This method is for those who want to keep all task deleted but still use Task Scheduler for some apps, etc <3

1. Open [Nsudo](https://github.com/QuakedK/Task-Destroyer/raw/refs/heads/main/Downloads/NSudoLG.exe) and Enable All Privileges.
2. Then type CMD in the Address Bar, then click run and paste the following command.
```bat
mkdir "C:\WINDOWS\System32\Tasks\Microsoft\Windows"
```
