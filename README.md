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

- Enable IIS (Internet Information Services)
- Install PHP Manager
- Install Visual C++
- Install MySQL
- Configure IIS
- Installing osTicket
- Install Heidi SQL

<h2>Installation Steps</h2>

<h3>Enabling Internet Information Services</h3>
<p>
<a href="https://imgur.com/wAAWSLs"><img src="https://i.imgur.com/wAAWSLs.png" title="source: imgur.com" /></a>
</p>
<p>
First, we open the Start Menu and open up the Control Panel. From there we select "Programs" then "Turn Windows Features On or Off". In this window we want to tick the box next to Internet Information Services. In the drop down menu, under World Wide Web Services and Application Development Features, make sure CGI is checked.

<a href="https://imgur.com/7H9Wa0s"><img src="https://i.imgur.com/7H9Wa0s.png?1" title="source: imgur.com" /></a>

Also, make sure that Common HTTP Features is selected and, under Web Management Tools, IIS Management console is selected as well.
</p>
<br />

<h3>Install PHP Manager and IIS URL Rewrite Module</h3>
<p>
<a href="https://imgur.com/jnkI7jX"><img src="https://i.imgur.com/jnkI7jX.png" title="source: imgur.com" /></a>
<a href="https://imgur.com/6g9wfXR"><img src="https://i.imgur.com/6g9wfXR.png" title="source: imgur.com" /></a>
</p>
<p>
These two are pretty self explanatory. There is no need for any special configuration or install instructions though, as a precaution, it should be noted that installing these on your default directory (usually the C: drive) is probably best.
</p>
<p>
<a href="https://imgur.com/viZhZYS"><img src="https://i.imgur.com/viZhZYS.png" title="source: imgur.com" /></a>
</p>
<p>
Next we want to download the files for the PHP and extract them from the ZIP file. I would recommend creating a folder on your default directory and extracting the files into that folder. My PHP folder is on my C drive, as seen here.
</p>
<br />

<h3>Install Visual C++ and MySQL</h3>
<p>
<a href="https://imgur.com/RT2fXLc"><img src="https://i.imgur.com/RT2fXLc.png" title="source: imgur.com" /></a>
</p>
<p>
Download and install the Visual C++ Redistributable. Nothing fancy here.
</p>
<p>
<a href="https://imgur.com/yGEAqC5"><img src="https://i.imgur.com/yGEAqC5.png" title="source: imgur.com" /></a>
<a href="https://imgur.com/UOE8RNv"><img src="https://i.imgur.com/UOE8RNv.png" title="source: imgur.com" /></a>
</p>
<p>
Next, we download and install MySQL. Also nothing fancy. Just be sure to check the box to launch the MySQL Instance Configuration Wizard
</p>
<p>
<a href="https://imgur.com/n7He8ft"><img src="https://i.imgur.com/n7He8ft.png" title="source: imgur.com" /></a>
</p>
<p>
In the MySQL Instance Configuration Wizard, we select the Standard Configuration and proceed as normal.
</p>
<br />

<h3>Configure Internet Information Services</h3>
<p>
<a href="https://imgur.com/Py4NdTl"><img src="https://i.imgur.com/Py4NdTl.png" title="source: imgur.com" /></a>
</p>
<p>
From the Start Menu, we open Internet Information Services (IIS) Manager and select PHP Manager
</p>
<p>
<a href="https://imgur.com/0ZNl39N"><img src="https://i.imgur.com/0ZNl39N.png" title="source: imgur.com" /></a>
</p>
<p>
Select "Register New PHP Version" under the PHP Setup section. It will then ask where the new PHP file is. Navigate to the PHP folder we made earlier to locate and select the necessary PHP file to continue.
</p>
<br />

<h3>Installing osTicket</h3>
<p>
<a href="https://imgur.com/mAE4Fjx"><img src="https://i.imgur.com/mAE4Fjx.png" title="source: imgur.com" /></a>
  <a href="https://imgur.com/05BXESk"><img src="https://i.imgur.com/05BXESk.png" title="source: imgur.com" /></a>
</p>
<p>
Now, we download the files for osTicket. From the osTicket folder, copy the "upload" folder to: (default drive)> inetpub> wwwroot.
</p>
<br />

<h3></h3>
<p>
<place image here>
</p>
<p>
Explanation goes here
</p>
<br />
