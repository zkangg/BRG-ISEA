# Lab 2b
### Cloud Web Server Deployment with Amazon EC2  
### Introduction to Bash Scripting & System Automation

## 🔍 Objective
Deploy a cloud‑based web server using Amazon EC2 and practice Bash scripting for automation of system tasks.

## 🛠 Steps Taken
- Launched an Ubuntu EC2 instance on AWS
- Configured security groups to allow SSH (22) and HTTP (80)
- Connected to the instance via SSH using key pair
- Installed Apache web server (`sudo apt install apache2 -y`)
- Verified deployment by accessing the public IP in a browser
- Wrote and executed Bash scripts to:
  - Create backup archives using `tar`
- Tested automation by running scripts and checking logs

## 📸 Screenshots
### EC2 dashboard
<img width="1920" height="1032" alt="1 EC2+2 SecurityGroupConfigured" src="https://github.com/user-attachments/assets/180de22e-255e-4782-aaa1-38aad4326a8e" />

*AWS EC2 instance running Ubuntu*

### Apache default page
<img width="918" height="992" alt="4  Apache_Install_Test" src="https://github.com/user-attachments/assets/5a4537d1-e058-4d78-a218-409e3595bb87" />

*Apache web server accessible via public IP*

### Bash script
<img width="722" height="521" alt="3  Basic Bash Script Created and Run " src="https://github.com/user-attachments/assets/b0c17867-999b-477a-83a4-7bec1b9ed441" />

*Example Bash script created and run*

### System Monitoring
<img width="820" height="238" alt="7  system monitor script" src="https://github.com/user-attachments/assets/eec430ae-d6b5-40fd-ac0c-16ea09a71926" />

<img width="730" height="429" alt="7  System Monitoring Script" src="https://github.com/user-attachments/assets/30e737a2-cbc6-45e6-93a3-b5d21faba2a8" />

*Automating System Monitoring Tasks*

## 💡 Reflection
System command:
- Command to create directory → mkdir
- View file content without GUI → cat, less, or more
- Difference between cp and mv → cp duplicates a file; mv moves or renames it.

Scripts Basic:
- chmod +x → makes a script executable so you can run it directly like ./myscript.sh.
- #!/bin/bash → the shebang line; tells the system to use Bash to interpret the script.
- Personalize output → edit echo lines to show your name, greetings, or custom text.

Loops and Conditionals:
- For loop → Repeats commands for a fixed range (e.g., 1–5).
- Number > 10 → Script prints “Number greater than 10.”
- Graceful invalid input → Add input validation with [[ $num =~ ^[0-9]+$ ]] or prompt again until valid.

Monitoring Automation:
- free -h → Displays memory usage in human-readable format (MB/GB).
- Modify for network usage → Add ifconfig or netstat -tulnp commands.
- Importance of automation → Saves time, ensures consistency, and allows admins to monitor systems without manual repetition.
