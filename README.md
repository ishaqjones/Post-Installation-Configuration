# Post-Installation-Configuration
Tutorial outlines the post-install configuration of the open source help desk ticketing system osTicket

<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)





<h2>Configuration Steps</h2>

  Post configuration: Delete the setup folder in our system. 
  -Delete: C:\inetpub\wwwroot\osTicket\setup
  Only delete the setup folder and nothing else.
  
  We then will want to set the permissions back to "Read" only in the ost-config.php file.
  
<p>
  
![alt-text](https://github.com/ishaqjones/Post-Installation-Configuration/assets/156931487/fe322dc3-0fed-4ce7-955d-e9dce69714d9)

</p>
<p>
  
<p>
  
![alt-text](https://github.com/ishaqjones/Post-Installation-Configuration/assets/156931487/c23af8c6-a370-415c-a880-bdf37e12498f)

</p>
<p>
  
  The last step after that is to log in to osTicket on the browser.
  
<p>
  
![alt-text](https://github.com/ishaqjones/Post-Installation-Configuration/assets/156931487/501fe6d5-23e9-41f7-8e63-a819c82ba56c)

</p>
<p>
  
  Congrats! You have now successfully installed and setup osTicket!


