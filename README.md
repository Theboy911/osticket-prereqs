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
Open IIS (Internet INformation Services) Manager. Navigate to PHP manager then click Register new PHP version. A file explorer tab should open, then a navigate to tje PHP folder that we copied. Then click php-cgi application in the screenshot and click open. Once complete close IIS and then reopen it and stop and start the server with IIS.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Open IIS (Internet INformation Services) Manager. Navigate to PHP manager then click Register new PHP version. A file explorer tab should open, then a navigate to tje PHP folder that we copied. Then click php-cgi application in the screenshot and click open. 
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
