# AWS EC2 DEVOPS  

This is a static website on an AWS EC2 instance using Nginx as a web server.

---

## Project Overview

A simple `index.html` file is hosted on an EC2 instance and served using Nginx. The project includes a deployment script to automate updates to the web server.

---
 **Set up the EC2 instance:**
   - Launch an EC2 instance (Amazon Linux 2).
   - Install Nginx:
     ```bash
     sudo yum install nginx -y
     sudo systemctl start nginx
     sudo systemctl enable nginx
---
2. **NECESSARY PERMISSIONS**
   ```bash
   sudo chown -R ubuntu:ubuntu /var/www/html/
---
