🧰 Bash Scripting Suite for System Maintenance

<br>

📄 Project Overview

This project is a Bash scripting suite designed to automate key system maintenance tasks in Linux. It includes scripts for system backups, updates, log monitoring, and a combined maintenance menu for easy execution.

The project was created as part of Assignment 5 (LinuxOS and LSP).
🎯 Objective

To write a suite of Bash scripts that automate system maintenance activities such as:

Performing backups

Updating and cleaning the system

Monitoring system logs

Integrating all scripts into a single executable suite with a user-friendly menu

📅 Day-wise Task Breakdown

<br>

Day 1 – Automated System Backup

Write a script that performs automated system backups (e.g., compressing important directories and saving them with timestamps).

Day 2 – System Update and Cleanup

Create a script that updates all system packages and removes unnecessary files or packages.

Day 3 – Log Monitoring

Develop a script to monitor system logs and generate alerts when certain conditions (like errors or warnings) are detected.

Day 4 – Maintenance Suite Menu

Combine all the scripts into one main script with a simple menu-driven interface allowing the user to choose which maintenance task to perform.

Day 5 – Testing and Error Handling

Test all scripts and add error handling, input validation, and logging functionality for better reliability and debugging.

⚙️ Features

🗂️ Automated system backups with timestamps

🔄 One-click system updates and cleanup

🔍 Log monitoring with alert mechanism

🧭 Interactive menu for maintenance tasks

⚠️ Built-in error handling and logging

🚀 How to Run

Clone the Repository

- git clone https://github.com/Amankr0703/bash-system-maintenance-suite.git
- cd bash-system-maintenance-suite


Give Execution Permission

- chmod +x *.sh


Run the Main Maintenance Menu

./maintenance_suite.sh

🧩 File Structure
<br>
bash-system-maintenance-suite/
│
├── backup.sh                # Day 1 - Backup script
├── system_update.sh         # Day 2 - Update & cleanup script
├── log_monitor.sh           # Day 3 - Log monitoring script
├── maintenance_suite.sh     # Day 4 - Combined menu script
├── README.md                # Project documentation
└── logs/                    # Log files generated during execution
<br>

🧑‍💻 Author

AMAN KUMAR
Assignment 5 – LinuxOS and LSP
