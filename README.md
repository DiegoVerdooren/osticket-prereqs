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

- php-7.3.8-nts-Win32-VC15-x86
- HeidiSQL_12.3.0.6589_Setup.exe
- mysql-5.5.62-win32.msi
- osTicket-v1.15.8.zip
- PHPManagerForIIS_V1.5.0.msi
- rewrite_amd64_en-US.msi
- VC_redist.x86.exe

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/88rQraA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After creating the virtual machine through Azure, log into the vm and begin installing all the software for osTicket.  
</p>
<br />

<p>
<img src="https://i.imgur.com/efit8wn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Make sure to enable IIS as well as CGI, without IIS you cannot run osTicket and CGI allows for the installation of php manager. 
</p>
<br />

<p>
<img src="https://i.imgur.com/yrhP7EG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once able to access osTicket you must create the database for osTicket through HeidiSQL after isntalling the software. 
</p>
<br />

<p>
<img src="https://i.imgur.com/WmvefH6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Congrats the inital installation of osTicket has been completed and you may now log into the system. :)
</p>
<br />
