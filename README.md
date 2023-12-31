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



<h2>Installation Steps</h2>

![image](https://github.com/AdamDCollins7/osticket-prereqs/assets/99514625/45445101-e875-4789-89fe-98f58614db9b)




<p>
Starting with creating a resource group so that all of my resources will be placed together in the same group.
</p>
<br />

![image](https://github.com/AdamDCollins7/osticket-prereqs/assets/99514625/cefbe533-146e-4368-a08c-b0106f7e0a76)



<p>
Next I created a virtual machine and used it's public address to login to remote desktop.
</p>
<br />


![image](https://github.com/AdamDCollins7/osticket-prereqs/assets/99514625/07a72ed8-757b-47a9-b1e7-823e020add9a)


<p>
I then installed and enabled IIS(Internet Information Services) and configured the appropriate settings
</p>
<br />

![image](https://github.com/AdamDCollins7/osticket-prereqs/assets/99514625/7062cda3-afd9-44a1-87ee-ac989d8f7968)


<p>
I installed PHP Manager for IIS and also in stalled Rewrite Module as well.
</p>
<br />


![image](https://github.com/AdamDCollins7/osticket-prereqs/assets/99514625/ddbebb31-9d7b-4237-946b-db73a10e5f8f)


<p>
Then installed PHP 7.3.8
</p>
<br />

![image](https://github.com/AdamDCollins7/osticket-prereqs/assets/99514625/c6fd2822-5b02-4c6f-9fb5-618f6d8a157b)



<p>
Then needed a database to hold the information on osTicket, and so I downloaded MY SQL
</p>
<br />

![image](https://github.com/AdamDCollins7/osticket-prereqs/assets/99514625/51461e21-846d-44ee-98a9-ad8922221c21)


<p>

</p>
<br />


![image](https://github.com/AdamDCollins7/osticket-prereqs/assets/99514625/8e7729b6-da06-4cdc-96ae-0ee1b1113ba4)


<p>
Downloaded and installed osTicket and then enabled php_imap.dll, php_intl.dll, php_opcache.dll
</p>
<br />
<p>
Installation complete!
</p>
<br />








