# osTicket - Prerequisites and Installation

This tutorial provides a step-by-step walkthrough of the prerequisites and installation process for **osTicket**, an open-source help desk ticketing system commonly used in IT support environments. This project demonstrates hands-on experience with system administration, web server configuration, and help desk software deployment in a cloud environment.


## Environments and Technologies Used
- Microsoft Azure (Virtual Machines / Compute)
- Remote Desktop Protocol (RDP)
- Internet Information Services (IIS)
- PHP Manager for IIS
- MySQL
- osTicket

---

## Operating Systems Used
- Windows 10 (21H2)

---

## List of Prerequisites
- Microsoft Azure subscription
- Windows 10 Virtual Machine
- Internet Information Services (IIS) enabled
- PHP (v7.4 or compatible)
- MySQL Database Server
- PHP Manager for IIS
- osTicket installation files

---

## Installation Steps

### Step 1: Create and Access Azure Virtual Machine
- Created a Windows 10 Virtual Machine in Microsoft Azure
- Connected to the VM using Remote Desktop (RDP)
- Verified internet connectivity and system updates

![Azure VM Setup](images/azure-vm-setup.png)

---

### Step 2: Enable IIS and Required Features
- Enabled **Internet Information Services (IIS)** through Windows Features
- Installed required IIS components:
  - CGI
  - Common HTTP Features
  - Application Development Features

![IIS Installation](images/iis-installation.png)

---

### Step 3: Install PHP and PHP Manager
- Installed PHP Manager for IIS
- Installed PHP 7.4
- Configured PHP within IIS Manager
- Enabled required PHP extensions:
  - php_imap.dll
  - php_intl.dll
  - php_opcache.dll

![PHP Configuration](images/php-config.png)

---

### Step 4: Install and Configure MySQL
- Installed MySQL Server
- Created a database for osTicket
- Created a database user with appropriate permissions

![MySQL Setup](images/mysql-setup.png)

---

### Step 5: Download and Configure osTicket
- Downloaded osTicket from the official website
- Extracted files to:
