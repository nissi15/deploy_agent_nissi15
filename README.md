# Student Attendance Tracker — Project Factory

Bash script that sets up a Student Attendance Tracker workspace from scratch.

## Start here

1. Clone the repository
git clone https://github.com/nissi15/deploy_agent_nissi15.git
cd deploy_agent_nissi15

2. Run the script:
./setup_project.sh

3. Summary of the Project
The script checks if Python3 is installed
It asks for a directory name
Then creates all project files 
lets you update attendance thresholds.
Archives when the user trys to exit(CTRL+C)

## How to trigger the archive

Press `Ctrl+C` at any point during setup. The script catches the interrupt, puts the current state into a `.tar` archive file then deletes the incomplete directory and exits.