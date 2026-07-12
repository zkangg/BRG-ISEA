# Lab 3b
### Additional Server Setup (MariaDB)

## 🔍 Objective
Install and configure MariaDB on a cloud server to provide database services, test connectivity, and practice basic SQL operations.

## 🛠 Steps Taken
- Installed MariaDB:
  ```bash
  sudo apt install mariadb-server -y
- Checked service status:
  ```bash
  sudo systemctl status mariadb
→ Output showed Active: active (running)
- Secured installation:
  ```bash
  sudo mariadb-secure-installation
  1.Current Root Password
  2.Unix Socket Authentication
  3.Set root password
  4.Removed anonymous users
  5.Disabled remote root login
  6.Removed test database
  7.Reload Privilege Tables
- Tested login:
  ```bash
  sudo mysql -u root -p

## 📸 Screenshots
### Install MariaDB
<img width="720" height="482" alt="1 Install MariaDB" src="https://github.com/user-attachments/assets/5b57f1c6-56e0-4a08-8a55-77b628e93122" />

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
