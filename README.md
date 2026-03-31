# Open Source Audit Project

## Student: Jiya Arora  
## Roll No: 24BAI10034

## Open Source Software Audit Project Project Overview

This repository contains my Open Source Software audit project completed as part of the Open Source Software course at VIT Bhopal. The objective of this project is to explore how open-source software works within a Linux environment and to understand the philosophy, ecosystem, and technical structure behind widely used FOSS tools.

For this audit, I selected Python as the primary open-source software. Python is one of the most widely used programming languages in the world and is known for its readability, simplicity, and strong open-source community support.

Through this project, I examined Python's presence in a Linux system and implemented a set of shell scripts to analyze system information, software installation, file permissions, log files, and open-source philosophy. Selected Open Source Software

## Software Name: Python
## Category: Programming Language 
## License: Python Software Foundation License (Open Source)

Python was created by Guido van Rossum and first released in 1991. It was designed to emphasize code readability and developer productivity. Over the years, Python has become an essential tool in fields such as:

-Software development 
-Data science
-Artificial intelligence
-Web development 
-Automation and scripting

Because Python is open-source, developers around the world can contribute to its development and improve its ecosystem.

## Project Objectives
The main objectives of this project were: 
-To understand the philosophy behind open-source software. 
-To analyze how an open-source tool exists and operates inside a Linux environment. 
-To gain hands-on experience with Linux shell scripting. 
-To inspect system information, packages, logs, and directories using automation scripts. 
-To document observations and learn how open-source ecosystems function

## Repository Structure

This repository contains several shell scripts that perform different auditing and analysis tasks. 
-README.md 
-script1_system_identity.sh 
-script2_package_inspector.sh 
-script3_disk_auditor.sh 
-script4_log_analyzer.sh 
-script5_manifesto_generator.sh

## Script Descriptions 
### Script 1 – System Identity Report

This script gathers basic information about the Linux system and displays it in a structured format.

It collects details such as:

-Current user
-Linux distribution 
-Kernel version 
-System uptime 
-Current date and time

This script demonstrates how simple shell commands can be combined to generate a quick system overview.

### Script 2 – FOSS Package Inspector

The second script checks whether Python is installed on the system.

It performs tasks such as:

-Detecting the Python installation 
-Displaying the installed version 
-Printing a short description of Python

This helps confirm the presence of the selected open-source software in the Linux environment.

### Script 3 – Disk and Permission Auditor

This script inspects several important Linux directories and reports information such as:

-Directory permissions 
-Owner and group 
-Directory size

Directories examined include: /etc /var/log /home /usr/bin /tmp

### Script 4 – Log File Analyzer

The log analyzer script scans Linux log files and searches for specific keywords such as "error".

The script:

-Reads a log file line by line 
-Counts occurrences of the keyword 
-Displays the most recent matching log entries

This demonstrates basic log monitoring techniques used in system administration.

### Script 5 – Open Source Manifesto Generator

The final script is an interactive script that generates a small open-source philosophy statement.
The script asks the user three questions:

-An open-source tool they use daily 
-What "freedom" means to them 
-Something they would build for the community

Based on the answers, the script generates a short Open Source Manifesto and saves it as a text file.
This script highlights the collaborative and philosophical aspect of open-source software.

To Run the Scripts- First make the scripts executable: chmod +x *.sh

Then run any script using: ./script_name.sh

## Technologies Used: 
-Linux (Ubuntu / WSL)
-Bash Shell Scripting
-Python (audited software)
-Git & GitHub for version control

## Key Learnings

Working on this project helped me understand several important concepts, including:

-The structure of Linux file systems 
-How open-source software is installed and maintained 
-The importance of automation through shell scripting 
-Basic system auditing techniques 
-The collaborative nature of open-source communities

It also improved my familiarity with GitHub and version control, which are essential tools in modern software development.

## Conclusion

Open-source software plays a vital role in today's technology ecosystem. Projects like Python demonstrate how collaborative development can produce powerful tools used across industries.
This audit project provided practical experience with Linux systems, scripting, and open-source principles. It also highlighted the transparency and flexibility that make open-source software so valuable.
