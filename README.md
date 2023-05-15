# osTicket
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Enable Internet Information Services (IIS)
- Install web platform installer
- Install mySQL and setup username and password
- Install C++ redistributable
- Install osTicket and configure permission 

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/QoE5Rcn.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Install/Enable IIS in Windows with CGI
- World Wide Web Services -> Application Develop Features -> [X].
</p>
<br />

<p>
<img src="https://i.imgur.com/ftk2FAd.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Download and install PHP Manager for IIS (PHPManagerForIIS_V1.5.0.msi).
</p>
<br />

<p>
<img src="https://i.imgur.com/zUCYlQh.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Download and install the Rewrite Module (rewrite_amd64_en-US.msi).
</p>
<br />

<p>
<img src="https://i.imgur.com/0hW80Fl.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create a folder in the C drive called “PHP”.
</p>
<br />

<p>
<img src="https://i.imgur.com/CqCabIy.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Download and install PHP 7.3.8 (php-7.3.8-nts-win32-VC15-x86.zip) and unzip the contents into the PHP folder you created in the C drive.
</p>
<br />

<p>
<img src="https://i.imgur.com/QgVTtJz.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Download and install VC_redist.x86.exe.
</p>
<br />

<p>
<img src="https://i.imgur.com/CLgMA7Z.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Download and install MySQL 5.5.62
- Typical Setup ->
- Launch Configuration Wizard (after install)
- Standard Configuration ->
- (Password of your choice).
</p>
<br />

<p>
<img src="https://i.imgur.com/iaZ9nLl.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Install osTicket v1.15.8
- Download osTicket from the Installation Files Folder
- Extract and copy “upload” folder to c:\inetpub\wwwroot
- Within c:\inetpub\wwwroot, Rename “upload” to “osTicket” 
- Reload IIS (Open IIS, Stop and Start the server)
</p>
<br />

<p>
<img src="https://i.imgur.com/ivG9dRq.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Download and install HeidiSQL
- Open Heidi SQL
- Create a new session, (use the username: “root” and a password of your choice)
- Connect to the session
- Create a database called “osTicket”
</p>
<br />

<p>
<img src="https://i.imgur.com/yGiojKY.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Continue Setting up osTicket in the browser
- MySQL Database: osTicket
- MySQL Username: (the username you chose)
- MySQL Password: (the password you chose)
- Click “Install Now!”
</p>
<br />

<p>
<img src="https://i.imgur.com/VD9zXGJ.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Congratulations hopefully, it is installed with no errors!
Browse to your help desk login page: http://localhost/osTicket/scp/login.php
End Users osTicket URL: http://localhost/osTicket/ 

</p>
<br />

