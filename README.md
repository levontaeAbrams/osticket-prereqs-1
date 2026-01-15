![osTicket logo](https://camo.githubusercontent.com/db7fb97a55f1d97b5a55b10b56016a185b1e1d57e4bd799d0e862c79b8ace91a/68747470733a2f2f692e696d6775722e636f6d2f436c7a6a3758732e706e67)

# osTicket - Prerequisites and Installation

This project is a **hands-on tutorial and walkthrough** that demonstrates the prerequisites, installation, and basic configuration of **osTicket**, an open-source help desk ticketing system commonly used in IT support environments.

The goal of this project is to simulate a real-world IT help desk setup using a cloud-hosted Windows machine and to demonstrate practical system administration skills relevant to entry-level IT and Help Desk roles.

---

## 📌 Project Summary

### 🔹 Project Type
This project is a **technology implementation and walkthrough** that documents the full installation process of osTicket, from environment setup to verification and testing.

### 🔹 Languages Used
- PowerShell (basic system checks and administration)
- HTML / PHP (osTicket backend – configuration only, no custom coding)

### 🔹 Environments Used
- Microsoft Azure
- Windows 10 (21H2)
- Internet Information Services (IIS)

### 🔹 Technologies / Applications / Services Used
- osTicket
- Microsoft Azure Virtual Machines
- Internet Information Services (IIS)
- PHP Manager for IIS
- MySQL Database
- Remote Desktop Protocol (RDP)

---

## 🎥 Video Demonstration
-  
### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com/)
*(Optional – screenshots provided below for demonstration)*

---

## 🌐 Environments and Technologies Used
- Microsoft Azure (Virtual Machines / Compute)
- Remote Desktop
- Internet Information Services (IIS)

---

## 💻 Operating Systems Used
- Windows 10 (21H2)

---

## 📋 List of Prerequisites
- Microsoft Azure subscription
- Windows 10 Virtual Machine
- Internet Information Services (IIS)
- PHP 7.4
- PHP Manager for IIS
- MySQL Server
- osTicket installation files

---

## ⚙ Installation Steps

### Step 1: Azure Virtual Machine Creation
A Windows 10 virtual machine was created in Microsoft Azure and accessed using Remote Desktop Protocol (RDP).

![Azure VM](https://camo.githubusercontent.com/9e90bac6a4fc4b0aaca74c7fd8d8f0fb13d9dbe648eebad81265de9136132376/68747470733a2f2f692e696d6775722e636f6d2f444a6d455845422e706e67)

---

### Step 2: Enable Internet Information Services (IIS)
Internet Information Services (IIS) was enabled along with required features such as CGI and Common HTTP Features to support PHP-based applications.

![IIS Installation](https://camo.githubusercontent.com/5b8b3f8c5f7fa7a72df2b31e7a44b0fcb3b3cfc07c8a8a7b5f2f6cb8a9e92f61/68747470733a2f2f692e696d6775722e636f6d2f69544f39506c372e706e67)

---

### Step 3: PHP and PHP Manager Configuration
PHP Manager for IIS was installed and configured. Required PHP extensions were enabled to ensure osTicket compatibility.

![PHP Manager](https://camo.githubusercontent.com/87f58b8c1bb50bde7f9db84fbeafdd6c11a6f5c54c8b20fd1b9c46e0d8bfb38f/68747470733a2f2f692e696d6775722e636f6d2f73424b7a61524b2e706e67)

---

### Step 4: MySQL Database Setup
A MySQL database was installed and configured to store osTicket data. A dedicated database and user account were created for the application.

![MySQL Setup](https://camo.githubusercontent.com/6d3b10e91b7f4cfb5f8b99f0a7fdc9b45f57f5eec3a4bce81baf43a3e6cb8c8d/68747470733a2f2f692e696d6775722e636f6d2f63514b507a63562e706e67)

---

### Step 5: osTicket Installation and Configuration
The osTicket files were downloaded, extracted to the IIS web directory, and configured. The web installer was completed successfully.

![osTicket Installer](https://camo.githubusercontent.com/1e7f7b1bff30d5d8cb35e19bbf3d54a1b76a4030ad4b92c5b7cb4a38a4f693cc/68747470733a2f2f692e696d6775722e636f6d2f6d70394f6a546a2e706e67)

---

### Step 6: Verification and Testing
After installation, the osTicket admin dashboard was accessed. A test user was created, and a support ticket was successfully submitted and resolved.

![osTicket Dashboard](https://camo.githubusercontent.com/cae4b26fbcfdabec4cb9fa38e01d0c7bbcfad9f17cf2d8d3bbf52d7b4d3c53fd/68747470733a2f2f692e696d6775722e636f6d2f6f6a4d4b4d70702e706e67)

---

## ✅ Conclusion
This project demonstrates the successful deployment of a fully functional help desk ticketing system in a cloud-based Windows environment. It highlights practical skills in system administration, web server configuration, database setup, and IT documentation—skills that directly align with real-world Help Desk and IT Support roles.
