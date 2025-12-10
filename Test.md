This is a temporary file with some notes by Sr as he learned how to set up and use a local git remote on a ScanDisk SSD and also a GitHub remote for backup.

#### Test local server from bare repo on skandisk

- line added from MHSRC7

- Now I'm going to copy in files for the original MDNotes

- And need to make a branch for backing up to GitHub
  
  

### Cloning repo from scandisk first time 9Dec25

`PS C:\\Git-scandisk> git clone D:\\GitServer\\MDNotesL.git`

`Cloning into 'MDNotesL'...`

`fatal: detected dubious ownership in repository at 'D:\\GitServer\\MDNotesL.git'`

`'D:\\GitServer\\MDNotesL.git' is owned by:`

`&nbsp; (inconvertible) (S-1-5-21-2418719031-3396233009-648625892-1003)`

`but the current user is:`

`&nbsp; MHS-ROBOTICS-7/Robotics (S-1-5-21-2679690082-1382928851-824412564-1001)`

`To add an exception for this directory, call:`

`&nbsp; git config --global --add safe.directory 'D:\\GitServer\\MDNotesL.git'`

`PS C:\\Git-scandisk> git config --global --add safe.directory 'D:\\GitServer'`

`PS C:\\Git-scandisk> git clone D:\\GitServer\\MDNotesL.git`

`Cloning into 'MDNotesL'...`

`fatal: detected dubious ownership in repository at 'D:\\GitServer\\MDNotesL.git'`

`'D:\\GitServer\\MDNotesL.git' is owned by:`

`&nbsp; (inconvertible) (S-1-5-21-2418719031-3396233009-648625892-1003)`

`but the current user is:`

`&nbsp; MHS-ROBOTICS-7/Robotics (S-1-5-21-2679690082-1382928851-824412564-1001)`

`To add an exception for this directory, call:`

`&nbsp; git config --global --add safe.directory 'D:\\GitServer\\MDNotesL.git'`

`PS C:\\Git-scandisk> git config --global --add safe.directory 'D:\\GitServer\\MDNotesL.git'`

`PS C:\\Git-scandisk> git clone D:\\GitServer\\MDNotesL.git`

`Cloning into 'MDNotesL'...`

`done.`

`PS C:\\Git-scandisk> ls`

`&nbsp; Directory: C:\\Git-scandisk`

`Mode LastWriteTime Length Name`

`d----- 12/9/2025 10:22 AM MDNotesL`

`PS C:\\Git-scandisk> cd MDNotesL`

`PS C:\\Git-scandisk\\MDNotesL> ls`

`&nbsp; Directory: C:\\Git-scandisk\\MDNotesL`

`Mode LastWriteTime Length Name`

* * *

`-a---- 12/9/2025 10:22 AM 48 Test.md`

##### Didn't pull both branches

PS C:\\Git-scandisk\\MDNotesL> git branch

\* main

PS C:\\Git-scandisk\\MDNotesL>

#### But opening the repo up on GitHub Desktop made both branches available



### Changed the name of the repo on Sr laptop and the origin on ScanDisk

- Used Explorer to change file name on my laptop and on ScanDisk, then had to change the location of the remote in GitHub Desktop repo settings


