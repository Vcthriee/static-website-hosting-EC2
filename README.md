# 🌐 Static Website Hosting on EC2 with Apache

This project demonstrates how to host a simple static website using an **Amazon EC2** instance running **Apache HTTP Server**. The goal is to understand how cloud infrastructure can be used to manually deploy websites, and to get hands-on with networking, security, and server configuration.

---

## 📦 Tech Stack

- **Amazon EC2 (Ubuntu)**
- **Apache HTTP Server**
- **HTML/CSS Website**
- **Security Groups**
- **SSH (Terminal)**

---

## 🧠 What I Learned

- How to launch and configure EC2 instances
- Setting up and securing Apache web servers
- Basic cloud networking (ports, public IP, inbound rules)
- Manual deployment of static files via SSH
- Real-world understanding of how cloud infrastructure works

---

## 🛠️ Deployment Steps

1. **Launched EC2** instance (Ubuntu) from AWS Console
2. Created and used a `.pem` SSH key to connect
3. SSH'd into the server:
   ```bash
   ssh -i ~/Downloads/my-key.pem ubuntu@<EC2_PUBLIC_IP>
   
INSTALLED APACHE
sudo apt update
sudo apt install apache2 -y

Screanshots 
[landing page](https://github.com/Vcthriee/static-website-hosting-EC2/blob/main/Screenshot%202025-03-13%20235351.png)
