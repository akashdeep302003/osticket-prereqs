<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computer)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)
<h2>List of Prerequisites</h2>

- Microsoft Azure Account
- Azure Virtual Machine
- Remote Desktop Client
- osTicket Installation Files
- Internet Information Services (IIS)
- PHP
- MySQL Database
- HeidiSQL
<h2>Installation Steps</h2>


<p>
  1. Azure Virtual Machine Setup
<img src="https://i.imgur.com/aT7df3o.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>In this step, we create a Virtual Machine in Microsoft Azure. The VM is configured with Windows 10, 2vCPUs, and 8GB of ram to support the osTicket installation and related services.
</p>
  2. Remote Desktp Login 
<br />

<p>
<img src="https://github.com/user-attachments/assets/4fa480b1-5a58-480e-ac43-82e12d373823" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>Using the Remote Desktop Connection (RDP), we log in to the Azure VM with the credentials configured during the setup. This allows us to access the virtual environment to proceed with the installation process.
</p>
3. Enabling IIS with CGI
<br />

<p>
<img src="https://i.imgur.com/r1ol1bD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>We enable Internet Information Services (IIS) on the Azure VM, which acts as the web server for osTicket. The CGI feature under "Application Development" is also enabled to support PHP applications
</p>
4. PHP Folder Setup
<br />

<p>
<img src="https://i.imgur.com/sNDIqhB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>The PHP package is downloaded and extracted to the C:\PHP directory. This step ensures that the required PHP files are available for osTicket to function properly.
</p>
5. MySQL Setup
<br />

<p>
<img src="https://i.imgur.com/gCkpTnC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>The MySQL Community Edition is installed and configured. During the setup, the root username (root) and a secure password are created to manage the osTicket database
</p>
6. osTicket Folder Setup
<br />

<p>
<img src="https://i.imgur.com/OCunqSZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>The osTicket installation files are downloaded, extracted, and placed in the c:\inetpub\wwwroot directory. The folder is renamed to osTicket to prepare for the web server setup
</p>
7.Browser View
<br />

<p>
<img src="https://i.imgur.com/xk3iVcC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>The osTicket setup page is accessed in a web browser via http://localhost/osTicket. This page verifies the required components and allows us to configure the application.
</p>
8. osTicket Login Page
<br />

<p>
<img src="https://i.imgur.com/VgdGo90.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>Once the installation is complete, the osTicket admin login page is accessed at http://localhost/osTicket/scp/login.php. This is where administrators can log in to manage the helpdesk system.
</p>
<br />
