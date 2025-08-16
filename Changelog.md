# Task Destroyer Changelog

**Task Destroyer V1.0**

6/28/25 <3

*What it did?*
- Checked for Admin Privileges.
- Checked if Trusted Installer was enabled.
- Created or Skipped Restore point.
- Dynamically detected and deleted task with random SID's under "TaskCache\Tree."
- Deleted OneCore, Windows, XblGameSave under Task Scheduler Libary aka "HKLM\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Schedule\TaskCache\Tree\Microsoft\"

---

**Task Destroyer V1.1**

6/29/25 <3

*Added*
- Added Reg Backup's
- Added the Delection of the whole Task Tree.

*Removed*
- Removed Dynamic detected and deletion.
- Removed the deletion of OneCore, Windows, XblGameSave.

---

**Task Destroyer V1.2**

7/3/25 <3

*What it does now?*
New version completely nukes Task Scheduler so much so when opened, it says "The Remote Computer was not found."
And now after restart the folders don't regenerate!

*Added*
- Added Task Folder Backup.
- Added "C:\WINDOWS\System32\Tasks" Deleter
- Added "HKLM\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Schedule\TaskCache" deleter. (Deletes Boot, Logon, Maintenance, Plain, Tasks & Tree Folders)
- Added "HKLM\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Schedule\TaskStateFlags" deleter. (Deletes Task Flags)

*Fixed*
- Fixed the captilization of "Now" in (Task Destoyer Done Screen)
- Fixed the Reg Backup, it now backup's all of "HKLM\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Schedule"

*Removed*
- Removed the deletion of Tree Reg Folder aka "HKLM\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Schedule\TaskCache\Tree"

---

**Task Destroyer V1.2 (Hotfix)**

7/3/25 <3

*Fixed*
- Fixed misaligned Checkmark in "Delete All Microsoft Task"
- Fixed misaligned Checkmark in "Delete System32 Task Folder"
- Fixed Missing Checkmark in Task Destoyer Done Screen.

---

**Task Destroyer V1.3**

8/16/25 <3

*Fixed*
- Fixed all spelling errors of destroyer.
- Fixed Task Destroyer Start Screen misspelling.
- Fixed systemDrive variaable to have a captial S.
- Fixed ❌ and ✅ spacing in "System Protection/Restore Point Failure" and "No Restore Point Selected"

*Removed*
- Removed TrustedInstaller Check, not needed since Ti needs to be enabled before running Task Destroyer.
- Removed exclamation marks from Restore Point Screen.

*Changed*
- Changed Restore ASCII art from ANSI Shadow to Bloody.
- Changed :CheckWindowsDrive goto command to :Check_Windows_Drive

*Added*
- Added Logging for No Console Version.

---

