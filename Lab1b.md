# Lab 1b
### Linux Services, SSH, Firewalls & Compression  
### Linux File Permissions and Group Access Control

## 🔍 Objective
Learn how to manage Linux services, secure remote access with SSH, configure firewalls, compress and archive files, control permissions and groups, and perform file search and analysis.

## 🛠 Steps Taken
- Enabled and tested SSH service (`systemctl status ssh`)
- Connected to a partner VM using `ssh user@IP`
- Configured firewall rules with `ufw allow 22/tcp` and `ufw allow 80/tcp`
- Compressed and decompressed files using `tar`, `gzip`, and `bzip2`
- Practiced file permission changes with `chmod` and ownership changes with `chown`
- Created groups and tested access control with `usermod -aG`
- Used `find` and `grep` to locate files and analyze content
- Archived logs and datasets for efficient storage and transfer

## 📸 Screenshots

### SSH connection
<img width="569" height="132" alt="6 Explicit username" src="https://github.com/user-attachments/assets/c7c93b68-a5f1-4319-8628-e00470ca9429" />

*Successful SSH login to partner VM*

### Firewall rules
<img width="701" height="510" alt="5 Firewall (UFW)" src="https://github.com/user-attachments/assets/f138cc0d-5683-46c5-b8d2-0cc405890708" />

*UFW showing allowed ports for SSH and HTTP*

### File compression
<img width="582" height="591" alt="8 Compression   Decompression" src="https://github.com/user-attachments/assets/991c8cd3-f0bd-49ce-a127-18d8b9b15092" />

*Archive created and compressed with tar/gzip*

### Permissions demo
<img width="654" height="451" alt="5 Permissions" src="https://github.com/user-attachments/assets/909eec1d-f179-43f0-8f71-daa3d8a9c26f" />

*Using chmod to restrict access to a file*

### File search
<img width="1113" height="628" alt="3 find_txt" src="https://github.com/user-attachments/assets/e3aa68bf-3322-425a-8f8f-96d82f0a9f15" />

*Using find and grep to locate files with specific content*

## 💡 Reflection
- What’s the role of a firewall in managing services? 

Firewall helps block unwanted traffic and only allows needed services.

- How did SSH access deepen your understanding of Linux as a server? 

SSH showed me how to manage Linux servers remotely and securely.

- Why is file compression important in server contexts? 

Compression saves space and speeds up file transfers, which is vital on servers.

- How does user privilege management help secure systems?

User privileges keep systems safe by limiting access and preventing mistakes.

