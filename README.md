# osticket-prereqs
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


- Install PHP Manager for IIS v1.5.0
- Install Rewrite Module
- Create a directory in the C:\ drive called PHP
- Install and Download PHP 7.3.8 then unzip contents into C:\PHP
- Download and install VC_redist.x86.exe which is a visual C++ redistributable that osticket requires
- Install and download MySQL 5.5.62

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/tXUZATD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once all dependancies from prerequisites list are installed you then must install osticket. Once osticket is installed navigate to osticket directory and copy the "upload" folder FROM osticket directory TO C:\inetpub\wwwroot. After upload folder is in wwwroot directory rename the upload folder to "osticket"
</p>
<br />

<p>
<img src="https://i.imgur.com/ThwciRR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Open control panel from start menu. Navigate to "programs" on the left panel. Click turn windows features on or off. Scroll to Internet Information Services--> World Wide Web Services--> Application Development Features then scroll and ENABLE CGI.
</p>
<br />

<p>
<img src="https://i.imgur.com/84wRmnb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Open IIS (Internet INformation Services) Manager. Navigate to PHP manager then click Register new PHP version. A file explorer tab should open, then a navigate to tje PHP folder that we copied. Then click php-cgi application in the screenshot and click open. Once complete close IIS and then reopen it and stop and start the server within IIS. Once done navigate back to PHP Manager and this time click enable or disable an extenesion and enable the following extensions
  
  - php_imap.dll
  - php_intl.dll
  - php_opcache.dll
</p>
<br />

<p>
<img src="https://i.imgur.com/YlN0CqJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Navigate to the file location in the screenshot and rename the file ost-sampleconfig.php to ost-config.php. Essentially just deleting the word sample from the file name. 
</p>
<br />

<p>
<img src="https://i.imgur.com/y1hHSIN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Change Permissions of ost-config.php file to everyone has full read write accesss. 
</p>
<br />

<p>
<img src="https://i.imgur.com/0q4zetB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Change Permissions of ost-config.php file to everyone has full read write accesss. 
</p>
<br />

<p>
<img src="https://i.imgur.com/dK5BEk3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Change Permissions of ost-config.php file to everyone has full read write accesss. 
</p>
<br />

<p>
<img src="https://i.imgur.com/bJQQoJd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Change Permissions of ost-config.php file to everyone has full read write accesss. 
</p>
<br />
