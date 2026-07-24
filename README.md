# ☁️ CloudSphere Solutions – AWS Cloud & DevOps Company Website

A professional responsive business website developed for **CloudSphere Solutions**, a fictional cloud consulting company specializing in **Amazon Web Services (AWS)** and **DevOps** solutions.

This project demonstrates how a modern business website can be hosted on a **Windows Server EC2 instance using IIS (Internet Information Services)** on Amazon Web Services.

---

## 📌 Project Overview

CloudSphere Solutions is a responsive corporate website designed to showcase cloud consulting services, AWS expertise, DevOps solutions, pricing plans, technologies, and company information.

The website was developed using only front-end technologies and deployed on an AWS Windows Server using IIS.

---

## 🎯 Project Objectives

- Design a modern cloud consulting website.
- Develop a fully responsive user interface.
- Host the website on AWS EC2 Windows Server.
- Configure IIS for website deployment.
- Demonstrate practical cloud hosting skills.
- Publish the project on GitHub.

---

# 🛠 Technologies Used

- HTML5
- CSS3
- JavaScript (ES6)
- Font Awesome Icons
- Google Fonts
- Microsoft IIS
- AWS EC2 (Windows Server)

---

# ☁ AWS Services Used

- Amazon EC2 (Windows Server)
- Security Groups
- Elastic IP (Optional)
- Remote Desktop Protocol (RDP)
- Internet Information Services (IIS)

---

# ✨ Features

- Responsive Design
- Fixed Navigation Bar
- Hero Section
- About Section
- Company Statistics
- Cloud Services
- Why Choose Us
- Technologies Section
- Team Section
- Testimonials
- Pricing Plans
- Contact Form
- Footer with Social Icons
- Smooth Scrolling Navigation
- Active Navigation Highlight
- Responsive Layout

---

# 📂 Project Structure

```
CloudSphere-Solutions/
│
├── index.html
├── style.css
├── script.js
│
├── images/
│   ├── hero.png
│   ├── about.png
│   ├── team1.jpg
│   ├── team2.jpg
│   └── team3.jpg
│
└── README.md
```

---

# 🚀 Deployment Steps

## 1. Launch Windows Server EC2

- Login to AWS Console
- Launch Windows Server Instance
- Configure Security Groups
- Allow:
  - HTTP (80)
  - HTTPS (443)
  - RDP (3389)

---

## 2. Connect to EC2

- Download RDP File
- Decrypt Administrator Password
- Connect using Remote Desktop

---

## 3. Install IIS

Open PowerShell as Administrator.

```powershell
Install-WindowsFeature -name Web-Server -IncludeManagementTools
```

---

## 4. Copy Website Files

Copy the project files into:

```
C:\inetpub\wwwroot
```

---

## 5. Start IIS

Open:

```
Internet Information Services (IIS) Manager
```

Ensure the **Default Web Site** is running.

---

## 6. Access the Website

Open your browser:

```
http://YOUR_PUBLIC_IP
```

---

# 📷 Project Screenshots

## Home Page

(Add Screenshot)

---

## About Section

(Add Screenshot)

---

## Services Section

(Add Screenshot)

---

## Technologies Section

(Add Screenshot)

---

## Team Section

(Add Screenshot)

---

## Pricing Section

(Add Screenshot)

---

## Contact Section

(Add Screenshot)

---

## IIS Hosting

(Add Screenshot)

---

## AWS EC2 Dashboard

(Add Screenshot)

---

# 💡 JavaScript Features

- Smooth scrolling navigation
- Active navigation highlighting
- Contact form submission alert
- Automatic form reset

---

# 📱 Responsive Design

The website is optimized for:

- Desktop
- Laptop
- Tablet
- Mobile Devices

---

# 📖 Learning Outcomes

Through this project, I learned:

- AWS EC2 deployment
- Windows Server administration
- IIS website hosting
- Front-end web development
- Responsive web design
- Git & GitHub workflow
- Cloud deployment fundamentals

---

# 🔮 Future Improvements

- Backend Integration
- Database Connectivity
- Contact Form API
- Live Chat Support
- Authentication System
- SSL Certificate
- Domain Configuration

---

# 👩‍💻 Author

**Ajwa Farooq**

BS Software Engineering Student

National Textile University

---

# 📄 License

This project is developed for educational and portfolio purposes.

---

# ⭐ If you like this project

Please give this repository a ⭐ on GitHub.