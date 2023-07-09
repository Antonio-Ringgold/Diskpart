<h1>Disk Wipe using Powershell Command JWipe</h1>

<h2>Description</h2>
Project consists of a simple PowerShell script that walks the user through wiping any drives that are connected to the system. The utility allows you to select the target disk and choose the number of passes that are performed. The PowerShell script will configure a diskpart script file based on the user's selections and then launch Diskpart to perform the disk sanitization.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Diskpart</b>

<h2>Environments Used </h2>

- <b>Windows 10</b>

<h2>Lab Walkthrough:</h2>

Launch the utility: <br/>
<img src="https://i.imgur.com/jHaQCJy.png" height="80%" width="80%" alt="DiskPart"/>
<br />
<br />
Select the disk:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="700%" width="80%" alt="DiskPart"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="700%" width="80%" alt="DiskPart"/>
<br />
<br />
Confirm what you selected:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="DiskPart"/>
<br />
<br />
Wait for the sanitation to complete (It can take a while):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="DiskPart"/>
<br />
<br />
Sanitization complete!
Check the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="650%" width="70%" alt="DiskPart"/>
</p>


