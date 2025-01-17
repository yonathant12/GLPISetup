<h1>GLPI Setup</h1>

<h2>Overview</h2>

<br />


<h2>Application Used</h2>

- <b>VMware Workstation 17 Pro</b>
- <b>Windows Server 2019</b>
- <b>Wampserver</b>


<h2>Lab walk-through:</h2>

<p align="center">
Download WampServer<br/>
<img src="https://i.imgur.com/rph9Qit.png" height="60%" width="60%"/>
<br />
<br />
Complete the installation wizard.<br/>
<img src="https://i.imgur.com/X9WVGC1.png" height="60%" width="60%"/>
<br />
<br />
If this message error appears. Head to Microsoft Visual C++ Redistributable and download the version listed.<br/>
<img src="https://i.imgur.com/1Jud0HB.png" height="60%" width="60%"/>
<br />
<br />
Install all the Microsoft Visual C++ Redistributable.<br/>
<img src="https://i.imgur.com/IOsf3Rm.png" height="60%" width="60%"/>
<br />
<br />
Once all the Microsoft Visual C++ Redistributable have been installed. Install the WampServer.<br/>
<img src="https://i.imgur.com/mEWKVNs.png" height="60%" width="60%"/>
<br />
<br />
Start the WampServer app.<br/>
<img src="https://i.imgur.com/pEXAuXd.png" height="60%" width="60%"/>
<br />
<br />
Download GLPI and extract the zip file.<br/>
Once extracted, move the glpi file to “C:\wamp64\www”.<br/>
<img src="https://i.imgur.com/1LHtOqj.png" height="60%" width="60%"/>
<br />
<br />
Open Microsoft Edge and search “localhost/glpi/”. Select your language and click ok.<br/>
<img src="https://i.imgur.com/aXINiNC.png" height="60%" width="60%"/>
<br />
<br />
Click continue on the “Licenses” page.<br/>
Click install on the “Beginning of the installation” page.<br/>
We need to create these directories to move forward.<br/>
<img src="https://i.imgur.com/tDtLRHf.png" height="60%" width="60%"/>
<br />
<br />
Head over to C:\wamp64\www\glpi\files and create the following folders.<br/>
<img src="https://i.imgur.com/Ke2ZYYg.png" height="60%" width="60%"/>
<br />
<br />
Head over to the GLPI installation, click try again and go through the previous steps again.<br/>
On the database connection setup page open a new tab and search http://localhost/phpmyadmin/<br/>
Enter “root” as the username and click log in. Leave teh password blank.<br/>
<img src="https://i.imgur.com/gf3NTFU.png" height="60%" width="60%"/>
<br />
<br />
Head back to the GLPI installation tab and enter “localhost” as the SQL Server and “root” as the SQL User then click continue. Leave the password blank.<br/>
<img src="https://i.imgur.com/H6vCdgt.png" height="60%" width="60%"/>
<br />
<br />
We are going to create a new database, and we are naming it glpi.<br/>
<img src="https://i.imgur.com/urPZ4lp.png" height="60%" width="60%"/>
<br />
<br />
Click continue when the database has initialized.<br/>
Click continue on the “Collect Data” page.<br/>
Click continue on the services page.<br/>
Once the installation is finished, click “Use GLPI” to log into GLPI.<br/>
Enter “glpi” as the username and password to log in as the administrator.<br/>
<img src="https://i.imgur.com/9NzTTZq.png" height="60%" width="60%"/>
<br />
<br />
GLPI setup is complete<br/>
<img src="https://i.imgur.com/HV28Fqk.png" height="60%" width="60%"/>
<br />
<br />
</p>
