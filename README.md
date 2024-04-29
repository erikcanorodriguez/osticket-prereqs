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

- Firstly, we must install and enable IIS in windows with CGI and Common HTTP features checked. From here we must also install the IIS management console.
- Install PHP Managher for IIS
- Install Rewrite Module
- Install VC Redistrubite
- Install HeidiSQL

<h2>Installation Steps</h2>

<p>
<img src="https://github.com/erikcanorodriguez/osticket-prereqs/assets/168192619/375e24fb-6df8-481e-9832-ba4afccbaff7" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Before begining to install any programs the first step is enabling some common features on our own computer through the control panel. Here is where we activate the IIS management console which is where the bulk of setting up osTicket occurs.
</p>
<br />

<p>
<img src="https://github.com/erikcanorodriguez/osticket-prereqs/assets/168192619/84e1c3ca-94b8-440f-955b-5404a16201a3" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
HeidiSQL is a pivotal component when trying to install the osTicket server as it provides the IIS system with the database required to run osTicket, so in other words from the IIS we connect to the database we connected in HeidiSQL.
</p>
<br />

<p>
<img src="https://github.com/erikcanorodriguez/osticket-prereqs/assets/168192619/fd4782f8-7cd8-4066-9526-aa2dd37af418" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Upon opening IIS(Internet Information Services Manager) we are able to enable or disable extensions that were prviously missing from osTicket. It is also dirrectly from here that we are able to open osTicket and run the server.
</p>
</p>
<br />
<img src="https://github.com/erikcanorodriguez/osticket-prereqs/assets/168192619/3e6157c2-c47b-4553-ae51-2b27eadf5d88" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
Finally, after all the prerequisites are done we should have a successful launch!
