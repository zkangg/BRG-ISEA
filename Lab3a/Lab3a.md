# Lab 3a – Domain, DNS and TLS Certificates with Let's Encrypt  
### Enabling HTTPS with Let's Encrypt & Certbot

## 🔍 Objective
Configure a custom domain name, set up DNS records, and secure a web server with HTTPS using Let’s Encrypt and Certbot.

## 🛠 Steps Taken
- Registered a free domain using DuckDNS
- Created a DNS A record pointing the domain to the EC2 public IP
- Verified domain resolution with `nslookup` and browser test
- Installed Certbot via Snap:
  ```bash
  sudo snap install --classic certbot
