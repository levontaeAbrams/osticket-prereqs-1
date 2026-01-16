<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Item 1
- Item 2
- Item 3
- Item 4
- Item 5

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 1: Create and Access the Virtual Machine
A Windows 10 virtual machine is created in Microsoft Azure with sufficient resources (4 vCPUs). The VM is placed in a dedicated resource group and accessed using Remote Desktop. This virtual machine serves as the environment where osTicket and all required services will be installed and configured.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 2: Configure the Web Server and Dependencies
Internet Information Services (IIS) is installed and configured with CGI enabled to support PHP applications. Required components such as PHP, PHP Manager for IIS, the IIS Rewrite Module, Visual C++ Redistributable, and MySQL are installed. PHP is registered within IIS, and necessary PHP extensions are enabled to ensure osTicket can run properly.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 3: Install, Configure, and Secure osTicket
The osTicket application files are deployed to the IIS web root directory and configured for use. File permissions are set, configuration files are renamed, and the web-based installer is completed to define the help desk name, database connection, and administrative settings. Once installation is complete, the setup directory is removed, configuration files are locked down, and both the admin and end-user portals are tested to confirm the system is fully operational and secure.
</p>
<br />
