# Lab 3b
### Additional Server Setup (MariaDB)

## 🔍 Objective
Install and configure MariaDB on a cloud server to provide database services, test connectivity, and practice basic SQL operations.

## 🛠 Steps Taken
- Installed MariaDB:
  ```bash
  sudo apt install mariadb-server -y
Checked service status:
  sudo systemctl status mariadb
→ Output showed Active: active (running)
Secured installation:
sudo mariadb-secure-installation
- Current Root Password
- Unix Socket Authentication
- Set root password
- Removed anonymous users
- Disabled remote root login
- Removed test database
- Reload Privilege Tables

## 📸 Screenshots
### Install MariaDB
<img width="720" height="482" alt="1 Install MariaDB" src="https://github.com/user-attachments/assets/df78952c-834f-4363-ae32-71bbe7515f5b" />

### Check status
<img width="725" height="488" alt="2 Check status" src="https://github.com/user-attachments/assets/981550a6-1437-436a-acc0-dd32eede5055" />

### Secure installation
<img width="686" height="765" alt="3 Secure installation" src="https://github.com/user-attachments/assets/454288ba-55d5-4a13-bd1f-649bfe3415a5" />

### Test login
<img width="715" height="337" alt="4 Test login" src="https://github.com/user-attachments/assets/2833cad0-1ff5-48f2-9804-9c555196eb60" />

## 💡 Reflection
This lab taught me how to install and secure a database server.
I learned that the mariadb-secure-installation script is essential for removing default vulnerabilities.
Testing login confirmed that the root account was protected with a password.
This exercise reinforced the importance of securing database services before exposing them to the network.
