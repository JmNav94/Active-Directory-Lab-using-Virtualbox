<h1>Active Directory Lab</h1>



<h2>Description</h2>
Project consists of an exploration of Active Directory via JobSkillsShare virtual Sandbox. 
<br />


<h2>Languages and Utilities Used</h2>

- <b>JobsShareSkill virtual sandbox</b> 


<h2>Environments Used </h2>

- <b>Windows 11</b>
- <b>Windows Server 2022</b>

<h2>Program walk-through:</h2>

<p align="center">
Access Server Manager: <br/>
<img src="https://i.imgur.com/nfTE5cc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select Active Directory Users and Computers in Tools Menu to view connected Devices:  <br/>
<img src="https://i.imgur.com/b83pRc8.png)" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create Demo Account in Users section: <br/>
<img src="https://i.imgur.com/lsXskKt.png)" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create Password for Demo Account:  <br/>
<img src="https://i.imgur.com/fx7B6zu.png)" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Log onto Demo account on Connected Device:  <br/>
<img src="https://i.imgur.com/ANQ5KEp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Verify connection to Domain through System settings > About > System Properties:  <br/>
<img src="https://i.imgur.com/7IJninD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
2. Create Local User: Right click Start button to access Computer Management:  <br/>
<img src="https://i.imgur.com/vOZqBJ1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
In Computer Management expand Local Users and Groups > Users then right click to create a new local user:  <br/>
<img src="https://i.imgur.com/YAHPGCU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Login to local user account will fail since the device is connected to the domain: <br/>
<img src="https://i.imgur.com/P1QiKul.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Log into local user by adding ".\" to the account name:  <br/>
<img src="https://i.imgur.com/MHw53jI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
3. Connect a new Device to the Domain (ACIWINSS01): Access System > About > System Properties to view domain status:  <br/>
<img src="https://i.imgur.com/d7PAjvR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Change device from Workgroup to Domain: ACILABS.COM:  <br/>
<img src="https://i.imgur.com/5RlPaOs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Connect to Domain with Administrator account login:  <br/>
<img src="https://i.imgur.com/TkhqjPF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Connection Confirmed:  <br/>
<img src="https://i.imgur.com/UBS9yRS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Finalize connection by restarting device: <br/>
<img src="https://i.imgur.com/MZHlD2O.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm new computer name added into the Domain Controllers Active Directory :  <br/>
<img src="https://i.imgur.com/kf97lJk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
:  <br/>
<img src="https://i.imgur.com/d7PAjvR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
:  <br/>
<img src="https://i.imgur.com/5RlPaOs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
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
