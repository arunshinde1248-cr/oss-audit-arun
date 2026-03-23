# OSS Audit Project

## Student Details
Name: Arun Shinde  
Course: Open Source Software  
Project: Open Source Audit  

---

## Chosen Software
Git (Version Control System)

---

## Project Description
This project focuses on studying an open-source software (Git) and creating five basic shell scripts to demonstrate Linux and Bash scripting concepts. The scripts show how open-source tools work in a Linux environment.

---

## Scripts Description

### Script 1: System Identity Report
Displays basic system information such as Linux distribution, kernel version, current user, home directory, uptime, and date.

---

### Script 2: FOSS Package Inspector
Checks whether Git is installed on the system. If installed, it shows details like version and description.

---

### Script 3: Disk and Permission Auditor
Checks important system directories and displays their size and permissions. Also verifies the Git configuration file.

---

### Script 4: Log File Analyzer
Reads a log file and counts how many times a specific keyword (like "error") appears. It also shows the last few matching lines.

---

### Script 5: Open Source Manifesto Generator
Takes user input and generates a short open-source philosophy statement, which is saved in a text file.

---

## How to Run

### Step 1: Give execute permission
chmod +x script1.sh script2.sh script3.sh script4.sh script5.sh

### Step 2: Run scripts
./script1.sh  
./script2.sh  
./script3.sh  
./script5.sh  

### For Script 4
./script4.sh /var/log/syslog error

---

## Requirements
- Linux system (Ubuntu or any distribution)
- Git installed
- Basic knowledge of terminal commands

---

## Conclusion
This project helped in understanding open-source software, Linux system basics, and shell scripting concepts in a simple and practical way.