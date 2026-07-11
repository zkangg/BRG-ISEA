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

## 📸 Screenshots
### Free Domain
<img width="1244" height="379" alt="1 Domain Name Registered" src="https://github.com/user-attachments/assets/eb48297a-4819-48f9-9034-6c73b0223acf" />

*Domin name registered*

### DNS
<img width="720" height="237" alt="6 DNS Test Output" src="https://github.com/user-attachments/assets/acc25ff9-dc6c-4e13-8d93-a965c9348f37" />

*Test Output*

### Certbot
<img width="724" height="335" alt="1 Certbot Installed" src="https://github.com/user-attachments/assets/f7b3a227-0e01-4fc5-b41a-da27a5e70134" />

*Certbot Installing*

### Domain → Server
<img width="974" height="671" alt="1 Domain → Server" src="https://github.com/user-attachments/assets/3ab56063-08d6-4821-87a1-2772e59d321e" />

*duckdns*

## 💡 Reflection
What is the role of DNS in Internet presence?  
It translates domain names into IP addresses so users can reach servers.

Why does DNS propagation take time?  
Changes must update across many global DNS servers, which can take hours.

How does Let’s Encrypt validate domain ownership?  
It connects to your domain on port 80 or 443 to confirm you control it.

What are the risks if TLS is not configured on a public-facing site?  
Data can be intercepted, users see “Not Secure,” and trust is lost.

What could happen if you leave your cloud VM running for months?
Leaving a cloud VM running for months can cause high costs, wasted resources, and security risks.
