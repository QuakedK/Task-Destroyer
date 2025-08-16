# Task Destroyer: The Orca Replacement!
Task Destroyer primary goal is to completely **remove** all of Task Scheduler, whether or not it's Microsoft Task, App Task or any Task!

![New Project (3)](https://github.com/user-attachments/assets/7b18f20a-ed6f-42fc-9a28-2a8f6c1a5c94)
![GitHub Release Downloads](https://img.shields.io/github/downloads/QuakedK/Task-Destroyer/total)

# #1 Usage
Task Destroyer is required to be ran with Nsudo to delete Mircosoft Task without premission issues.

1. Download [Nsudo](https://github.com/M2TeamArchived/NSudo/releases/download/9.0-Preview1/NSudo_9.0_Preview1_9.0.2676.0.zip) (Offical Site) or the Standalone exe from [Downloads](https://github.com/QuakedK/Task-Destroyer/raw/refs/heads/main/Downloads/NSudoLG.exe)
2. Download [Task Destroyer](https://github.com/QuakedK/Task-Destroyer/releases/download/TaskSchedulerDeleter/Task-Destroyer-V1.3.bat).
3. Open [NSudoLG.exe](https://github.com/QuakedK/Task-Destroyer/raw/refs/heads/main/Downloads/NSudoLG.exe) and Enable All Privileges then drop/drag [Task Destroyer](https://github.com/QuakedK/Task-Destroyer/releases/download/TaskSchedulerDeleter/Task-Destroyer-V1.3.bat) into Nsudo then click run.

# #2 Revert
Note: If you created a Restore Point you can just use that <3

1. Open [Nsudo](https://github.com/QuakedK/Task-Destroyer/raw/refs/heads/main/Downloads/NSudoLG.exe) and Enable All Privileges.
2. Then type CMD in the Address Bar, then click run and paste the following commands.
```bat
reg import "C:\Task Destoyer\Reg Backup\TaskSchedulerBackup.reg"
rd /s /q "C:\WINDOWS\System32\Tasks"
move "C:\Task Destoyer\Task Folder\Tasks" "C:\WINDOWS\System32\Tasks"
```
# #3 Revert (Without adding back all of the original task)
Note: This method is for those who want to keep all task deleted but still use Task Scheduler for some apps, etc <3

1. Open [Nsudo](https://github.com/QuakedK/Task-Destroyer/raw/refs/heads/main/Downloads/NSudoLG.exe) and Enable All Privileges.
2. Then type CMD in the Address Bar, then click run and paste the following command.
```bat
mkdir "C:\WINDOWS\System32\Tasks\Microsoft\Windows"
```
