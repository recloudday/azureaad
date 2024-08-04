<h1>Azure/Entra and Active Directory - Create New Users and Groups</h1>

<h2>Description</h2>
Project consists of a simple PowerShell script that walks the user through "zeroing out" (wiping) any drives that are connected to the system. The utility allows you to select the target disk and choose the number of passes that are performed. The PowerShell script will configure a diskpart script file based on the user's selections and then launch Diskpart to perform the disk sanitization.
<br />


<h2>Concepts and Utilities Used</h2>

- <b>Azure Active Directory (Now Entra)</b>
- <b>Managing User Groups</b>

<h2>Environments Used </h2>

- <b>Microsoft Azure</b>
- <b>Entra</b>

<h2>Environment walk-through:</h2>

<p align="center">
Confirm Users are created: <br/>
<img src="https://imgur.com/xTrxC10.png" height="80%" width="80%" alt="Entra Steps"/>
<br />
<br />
Create Group:  <br/>
<img src="https://imgur.com/UOIOSjY.png" height="80%" width="80%" alt="Entra Steps"/>
<br />
<br />
Select Members -> Add Members: <br/>
<img src="https://imgur.com/hyuGcHN.png" height="80%" width="80%" alt="Entra Steps"/>
<br />
<br />
Select members to add:  <br/>
<img src="https://imgur.com/U2O67sE.png" height="80%" width="80%" alt="Entra Steps"/>
<br />
<br />
Create a new user:  <br/>
<img src="https://imgur.com/VGoFeI7.png" height="80%" width="80%" alt="Entra Steps"/>
<br />
<br />
Make the new user the owner:  <br/>
<img src="https://imgur.com/bpAqzX8.png" height="80%" width="80%" alt="Entra Steps"/>
<br />
<br />
We now have a Cloud Intern Mentor as an owner of the Group:  <br/>
<img src="https://imgur.com/j0wqNMU.png" height="80%" width="80%" alt="Entra Steps"/>
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
