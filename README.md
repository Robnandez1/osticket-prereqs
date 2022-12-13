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
<img src="https://imgur.com/HANbNid.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
On Microsoft Azure, I needed a secure Resource Group in order to create a Virtual Machine (VM); which will give me access to remotely compute on Windows 10 using the IP address provided from Azure on my Macbook Pro. After sucesfully logging in Windows 10 virtually, in order to affectively use osTicket, I needed to install a few programs such as Internet Information Services (IIS) that will essentially give me access to osTicket, C++, and PHP Manager. IIS can be installed from the Control Panel. IIS is needed to create a web server that will allow me to create the osTicket system. After enabling IIS on Windows 10, the second process is downloading the Web Platform Installer.
</p>
<br />

<p>
<img src="https://imgur.com/vBAckSa.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The Web Platform Installer is used to download multple files needed for a server to work properlly. In this case, I need to add and download PHP Manager, specific versions of PHP files, C++ Redistributable, and MySQL. This is required for osTicket to function properly on Windows 10. For security, a username (root) and password is required to complete the download process. Once all three are downloaded sucessfully, the next step is to download osTicket on Windows 10. Once downloaded, the files on the osTicket Folder must be copied to Files Explorer: thispc\windowsc\inetpub\wwwroot. After pasted, I can open the ISS application to program a live server. On the "sites" tab on IIS, I will find the link that will sucessfully open a web browser of the osTicket application which is named as: localhost/osTicket/Setup/
</p>
<br />

<p>
<img src="https://imgur.com/Z6gvNfX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Mannaging permissions as a Help Desk Admin allows me to create folders or programs that are either visible to a public network or private network using a program called Active Directory (AD). AD is a program used to systematicallyy manage thousands of groups from one computer source. As an admin, I can use the properties tab in every user's folder I employ or manage to read/write files, view only, or make files exclusively visible to specific users. This option provides security and convenience to manange a company of multiple departments regarding networking access. To use AD properly, I need to create another VM on Azure as a Windows Server in order to access Server Manager on Windows virtually. This will allow me access to install Active Directory and manage files and storages as an admin to control from one to thousands of users.
</p>
<br />
