# Student Attendance Tracker — Project Factory

This script sets up a Student Attendance Tracker workspace from scratch.

---

## Video explanation
```
https://www.youtube.com/watch?v=XrN9DiSehd0
```


## Quick Start

```bash
git clone https://github.com/nissi15/deploy_agent_nissi15.git
cd deploy_agent_nissi15
```
## Run the script
```
./setup_project.sh
```

## What the Script Does

The script checks if Python3 is installed.

It asks for a directory name

Then creates all project files 

lets you update attendance thresholds

Archives when the file is interrupted


## Triggering the Archive (Signal Trap)

Press **Ctrl+C** at any point during setup.

The script catches `SIGINT`, archives whatever has been built so far into `attendance_tracker_{name}_archive.tar`, removes the incomplete directory, and exits. The workspace stays clean.
