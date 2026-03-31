# OSS Capstone Project: The Open Source Audit
**Course:** Open Source Software (CSE0002)  
**Student Name:** Udit choudhary  
**Registration Number:** 24BCE10594  
**Slot:** B21  
**Date:** 31 March 2026  

## Project Overview
This repository contains the practical component of the "Open Source Audit" capstone project[cite: 4, 12]. [cite_start]The project involves a structured audit of a major open-source software project, focusing on its history, licensing, and technical footprint on a Linux system[cite: 13, 29].

Chosen Software for Audit: Git

## Repository Contents
This repository includes five shell scripts designed to demonstrate practical Linux administration and automation skills[cite: 14, 89].

| File | Script Name | Description |
| :--- | :--- | :--- |
| `script1.sh` | System Identity Report | [cite_start]Displays OS distribution, kernel version, and system uptime[cite: 93]. |
| `script2.sh` | FOSS Package Inspector | [cite_start]Checks if Git is installed and provides a brief philosophy note[cite: 125]. |
| `script3.sh` | Disk & Permission Auditor | [cite_start]Loops through system directories to report size and ownership[cite: 145]. |
| `script4.sh` | Log File Analyzer | [cite_start]Analyzes system logs to count specific keywords like "ERROR"[cite: 163]. |
| `script5.sh` | OSS Manifesto Generator | [cite_start]An interactive script that generates a personalized philosophy statement[cite: 185]. |

## How to Run
[cite_start]To execute these scripts on a Linux environment (such as Webminal, WSL, or a VM), follow these steps[cite: 92]:

1. **Clone the repository:**
   ```bash
   git clone <your-repo-link>
   cd <repo-name>
   ```

2. **Grant execution permissions:**
   ```bash
   chmod +x *.sh
   ```

3. **Run a script:**
   ```bash
   bash script1.sh
   ```

## License
[cite_start]The scripts in this repository are created for educational purposes as part of the VIT Bhopal OSS Capstone Project[cite: 1, 5]. [cite_start]Git itself is licensed under the **GNU General Public License v2.0**[cite: 24].

***

### Step-by-Step to Push to GitHub:
1. **Create the file:** In your project folder, create a new file named `README.md`.
2. **Paste the content:** Paste the text above into that file and save it.
3. **Commands to Push:**
   ```bash
   git add README.md
   git commit -m "Add professional README for Capstone Project"
   git push origin main
   ```
