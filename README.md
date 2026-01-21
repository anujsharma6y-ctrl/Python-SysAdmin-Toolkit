#  Python System Administration & Automation Toolkit

A collection of professional Python-based automation tools designed for System Administrators and DevOps Engineers. This toolkit automates daily tasks like system health monitoring, security auditing, data protection, and maintenance.

##  Projects Overview

This repository contains 7 specialized automation tools:

### 1.  System Report Generator
- **Description:** Generates a comprehensive hardware and OS health report.
- **Key Features:** Fetches Hostname, OS details, and Disk health. Exports data to JSON.

### 2.  User & Group Manager
- **Description:** Automates the creation of system users and groups.
- **Key Features:** Includes root/admin privilege checks and error handling for existing users.

### 3.  Disk Space Alert System
- **Description:** Real-time disk monitoring tool.
- **Key Features:** Sends automated email notifications via SMTP when disk usage crosses 80%.

### 4.  Automated Backup Tool
- **Description:** Professional backup solution for critical directories.
- **Key Features:** Creates date-stamped, compressed ZIP archives using `shutil`.

### 5. 🏥 Service Health Checker
- **Description:** A self-healing monitoring script for system services.
- **Key Features:** Monitors services like Nginx/Apache and automatically attempts a restart if they crash.

### 6.  Smart Log Cleaner
- **Description:** Automated disk space optimizer.
- **Key Features:** Identifies and deletes logs/files older than a specific retention period (e.g., 30 days).

### 7.  Security Permission Auditor
- **Description:** A security compliance tool to audit file access.
- **Key Features:** Detects "World Writable" files and alerts on potential security vulnerabilities.

---

##  Tech Stack & Requirements
- **Language:** Python 3.x
- **Libraries Used:** `os`, `sys`, `psutil`, `shutil`, `smtplib`, `subprocess`, `stat`, `datetime`
- **Platform:** Linux (Tested on Ubuntu/CentOS) & Windows

##  Project Structure
Each project is organized into its own directory:
/Python-SysAdmin-Toolkit ├── 01_System_Report/ ├── 02_User_Manager/ ├── 03_Disk_Space_Alert/├── 04_Backup_Automation/ ├── 05_Service_Checker/ ├── 06_Log_Cleaner/ └── 07_Permission_Auditor/


##  Author
**Anuj Sharma**
*System Automation Enthusiast | IT Automation Enthusiast | Python for SysAdmin*

---
