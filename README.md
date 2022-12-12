<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This section outlines the prerequisites and installation of the open-source Help Desk Ticketing System osTicket.<br />






<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)
- Mac OSX High Sierra

<h2>List of Prerequisites</h2>

- Enable Internet Information Services (IIS)
- Web Platform Installer: C++ Redistributable and PHP Manager Installation, and MySQL
- Permissions Configurement

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
On Microsoft Azure, I needed a secure Resource Group in order to create a Virtual Machine (VM); which will give me access to remotetley compute on Windows 10 using the IP address provided on my Macbook Pro. After sucesfully logging on Windows 10 virtually, in order to use osTicket, I needed to install a few programs such as Internet Information Services (IIS) that will essentially give me access to osTicket. IIS was succesfully installed from the Control Panel. IIS is needed to create a web server that will allow me to communicate with the osTicket system. After enabling IIS on Windows 10, the second process is downloading the Web Platform Installer.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The Web Platform Installer is used to download multple files needd for a server to work properlly. In this case, I need to add and download PHP Manager, specific versions of PHP files, C++ Redistributable, and MySQL. This is required for osTicket to function properly on Windows 10. For security, a username (root) and password is required to download files. Once all three are downloaded sucessfully, the next step is to download osTicket on Windows 10. Once download, the osTicket files on Folder must be coppied to Files Explorer: thispc\windowsc\inetpub\wwwroot. After pasted, I open ISS application to start a live server. On the sites tab on IIS, I will find the link that will sucessfully open a web browser of the osTicket which is named as: localhost/osTicket/Setup/
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Mannaging permissions as a Help Desk Admin allows me to create folders or programs that are either visible to a public network or private network using a program called Active Directory (AD). AD is a programs used to systematicallyy manage thousands of groups from computing source. As an admin, I can use the proties tab in every user I emplot ro read/write files, read only, or visible to specific users. This option provides security and convenicne to manange a business of multiple departments level of networking access. 
</p>
<br />
