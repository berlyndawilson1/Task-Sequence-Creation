# Task-Sequence-Creation

<h2>Description</h2>
Project consists of a simple PowerShell script that walks the user through "zeroing out" (wiping) any drives that are connected to the system. The utility allows you to select the target disk and choose the number of passes that are performed. The PowerShell script will configure a diskpart script file based on the user's selections and then launch Diskpart to perform the disk sanitization.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Diskpart</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
Create New Task Sequence: <br/>
<img src="https://imgur.com/MneAJ2e.png" height="80%" width="80%" alt="Task Sequence Steps"/>
<br />
<br />
Used Default Template:  <br/>
<img src="https://imgur.com/t5380ps.png" height="80%" width="80%" alt="Task Sequence Steps"/>
<br />
<br />
OS Selected: <br/>
<img src="https://imgur.com/YBRiWWI.png" height="80%" width="80%" alt="Task Sequence Steps"/>
<br />
<br />
Product Key Not Specified:  <br/>
<img src="https://imgur.com/zs7vfhL.png" height="80%" width="80%" alt="Task Sequence Steps"/>
<br />
<br />
OS Settings:  <br/>
<img src="https://imgur.com/SuA9mQt.png" height="80%" width="80%" alt="Task Sequence Steps"/>
<br />
<br />
Created Administrative Password:  <br/>
<img src="https://imgur.com/QlI5iU6.png" height="80%" width="80%" alt="Task Sequence Steps"/>
<br />
<br />
Summary of Details:  <br/>
<img src="https://imgur.com/C7oV7vE.png" height="80%" width="80%" alt="Task Sequence Steps"/>
Process Completed:  <br/>
<img src="https://imgur.com/cGaOVQQ.png" height="80%" width="80%" alt="Task Sequence Steps"/>
<br />
<br />
General Properties of Task Sequence:  <br/>
<img src="https://imgur.com/mvjL15L.png" height="80%" width="80%" alt="Task Sequence Steps"/>
<br />
<br />
Updated Deployment Share to x64:  <br/>
<img src="https://imgur.com/XQmwefw.png" height="80%" width="80%" alt="Task Sequence Steps"/>
<br />
<br />

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
