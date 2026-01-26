🛠️ Python-SysAdmin-Toolkit
A modular suite of Python scripts to automate system administration, monitoring, and maintenance tasks.

🚀 Projects Overview (Alphabetical Order)
Each tool is designed to solve a specific administrative challenge, organized for quick access:

1. Advanced File Organizer
Description: A smart script to clean up cluttered directories (like Downloads).

Key Features: Automatically sorts files into categorized folders (Images, Docs, Media, etc.) based on extensions.

2. Automated Backup Tool
Description: Professional backup solution for critical directories.

Key Features: Creates date-stamped, compressed ZIP archives using shutil.

3. Disk Space Alert System
Description: Real-time disk monitoring tool.

Key Features: Sends automated email notifications via SMTP when disk usage crosses 80%.

4. Security Permission Auditor
Description: A security compliance tool to audit file access.

Key Features: Detects "World Writable" files and alerts on potential security vulnerabilities.

5. Service Health Checker
Description: A self-healing monitoring script for system services.

Key Features: Monitors services like Nginx/Apache and automatically attempts a restart if they crash.

6. Smart Log Cleaner
Description: Automated disk space optimizer.

Key Features: Identifies and deletes logs/files older than a specific retention period (e.g., 30 days).

7. System Report Generator
Description: Generates a comprehensive hardware and OS health report.

Key Features: Fetches Hostname, OS details, and Disk health. Exports data to JSON.

8. User & Group Manager
Description: Automates the creation of system users and groups.

Key Features: Includes root/admin privilege checks and error handling for existing users.

🛠️ Tech Stack & Requirements
Language: Python 3.x

Libraries: os, sys, psutil, shutil, smtplib, subprocess, stat, datetime

Platform: Linux (Tested on Ubuntu/CentOS) & Windows

📂 Project Structure
Project directories are numbered according to the alphabetical order:

Plaintext
/Python-SysAdmin-Toolkit
├── 01_Advanced_File_Organizer/
├── 02_Automated_Backup/
├── 03_Disk_Space_Alert/
├── 04_Permission_Auditor/
├── 05_Service_Checker/
├── 06_Log_Cleaner/
├── 07_System_Report/
└── 08_User_Manager/
👨‍💻 Author
Anuj Sharma System Automation Enthusiast | IT Automation Enthusiast | Python for SysAdmin
