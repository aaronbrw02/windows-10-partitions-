<h1>Creating Partitions in Windows 10</h1>

<h2>Description</h2>
Project consists of using Dispart within PowerShell to create partitions.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Diskpart</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
Launch poweshell from the start menu<br/>
<img src="https://i.imgur.com/Ct3MZBT.png"/>
<br />
<br />
Enter the diskpart command  <br/>
<img src="hhttps://i.imgur.com/WYVHlWI.png"/>
<br />
<br />
Enter the list disk command <br/>
<img src="https://i.imgur.com/ZQ6o7mZ.png"/>
<br />
<br />
Select a disk using the select disk x command  <br/>
<img src="https://i.imgur.com/Jy9Llks.png"/>
<br />
<br />
Type the command create partition primary size=x to initialize a new partition with a size  <br/>
<img src="https://i.imgur.com/2FEMSZg.png"/>
<br />
<br />
Type exit to close Diskpart when the process completes  <br/>
<img src="https://i.imgur.com/TTicPjt.png"/>
<br />
<br />
