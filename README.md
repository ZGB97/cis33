<h1> Windows Server (Hyper-V) </h1>


<h2>Description</h2>
To resolve hostnames on a private network, you have to configure your own DNS zones. Resolving IP addresses to hostnames requires the creation of reverse lookup zones. In this Lab, I configured both forward and reverse lookup zones to support the network.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Windows Server 2019</b>
- <b>PowerShell</b>
- <b>Hyper-V Manager</b>

<h2>Program Screenshots:</h2>

<p align="center">
DNS and RSAT-DNS-Server features Installed: <br/>
<img src="https://i.imgur.com/WJbOPgT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Tested the DNS server on Server-02:  <br/>
<img src="https://i.imgur.com/fdyX7Jg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Created A Forward Lookup Zone: <br/>
<img src="https://i.imgur.com/tid2kl0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Verified the zone from the command line AND Records in the Zone: <br/>
<img src="https://i.imgur.com/6SPyAwR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Created a Forward Lookup Zone FROM Powershell:  <br/>
<img src="https://i.imgur.com/98Rh4lR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Created A Primary Reverse Lookup Zone :  <br/>
<img src="https://i.imgur.com/qt2bPC1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Created a Reverse Lookup Zone AND Configured the Zone to allow Dynamic Updates:  <br/>
<img src="https://i.imgur.com/4xFIrVi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
