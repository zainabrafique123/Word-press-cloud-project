# 🌐 Huawei Cloud WordPress Mini Project

## 🧑‍💻 Project Overview

This cloud mini project demonstrates hosting a **WordPress** website using **Huawei Cloud** services, as part of my NAVTTC Web Hosting course.  
The website is deployed using **ECS** (Elastic Cloud Server), **RDS** (MySQL database), and made public with Elastic IP (EIP).

🎯 Project Objective

✅ Host a WordPress site using cloud infrastructure  
✅ Use external RDS MySQL for database  
✅ Connect ECS and RDS securely  
✅ Configure floating IP for public access  
✅ Document all steps with screenshots

🔧 Cloud Services Used

| Component | Purpose |
| ECS (Ubuntu) | WordPress hosting with Apache & PHP |
| RDS (MySQL) | Remote database for WordPress |
| Elastic IP | Public access to ECS/WordPress |
| Security Group | Allowed ports: 22 (SSH), 80 (HTTP), 3306 (MySQL) |

⚙️ Configuration Summary

- ECS OS: Ubuntu Server
- Software: Apache, PHP, WordPress
- RDS DB Name: wordpress_db
- RDS User: root
- RDS Host IP: `192.168.0.32 (Private IP)
- Floating IP: 192.168.0.129(to access site)
- wp-config.php updated with RDS IP

 🖼️ Deployment Proof

✅ 1. ECS Instance Page (Huawei Console)
_Showing ECS instance running Ubuntu, with EIP_

 ✅ 2. RDS MySQL Instance Page
_MySQL DB instance status: available_

 ✅ 3. Security Group Rules
_Ports 22, 80, 3306,443,ALL opened_

 ✅ 4. WordPress Front Page (Live Site)
_Site running with 159.138.83.242

 ✅ 5. WordPress Admin Dashboard
_Login panel or dashboard view_

 ✅ 6. SSH Terminal (Optional)
_ECS connected and running Apache_

 ✅ 7. wp-config.php File
_Configuring database with RDS IP_(192.168.0.129)

 🔗 Live Website (Optional)

🌐 http://192.168.0.129(ip of rds)
   http://159.138.83.242/wordpress
---

 👤 Project by

- Name: Zainab Rafique  
- Course: NAVTTC Web Hosting  
- Date:13- July 2025  


