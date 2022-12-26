<p align="center">
<img src="https://imgur.com/vxny63o.png" height="50%" width="50%" alt="Microsoft Active Directory Logo"/>
</p>

<h1>Azure Basics</h1>
This tutorial outlines how to create Resource Groups and Storage Accounts in Azure.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Resource groups and Storage accounts)

<h2>Overview</h2>

- Step 1:	Within the Azure Portal, Create a Resource Group
- Step 2: Create a Storage Account within the Resource Group created in Step 1
- Step 3: Create a file on your local desktop and upload it into the Storage Account
- Step 4: Edit the file within the Storage Account (within the Azure Portal) Download the file and observe the changes
- Step 5: Delete the Resource Group created in step 1 (in order to ensure you don’t incur “cost”)



<h2>Steps</h2>

<p>
<img src="https://imgur.com/zRiUU7x.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/Pw66yE1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
- Step 1: In the Azure Portal home page, look up Resource groups in search. Next, in Resource groups, click Create Resource groups. Then,  in Basics, make sure you are on correct subscription, Name the Resource group RG-Lab-1, then in region, pick West US 3. After that click Review+Create, then Create.
</p>
<br />

<p>
<img src="https://imgur.com/JRKJcLd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
- Step 2: In the Azure Portal home page, look up Storage accounts in search, then click Create Storage accounts. Make sure to select RG-Lab-1 for resource group, then, name storage account testedcclab, select West US 3, select standard performance and select the box in redundancy, then Review, then Create.
</p>
<br />

<p>
<img src="https://imgur.com/mAS4a8c.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/YjC22i1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/wMXxKDh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
- Step 3: In testedcclab, go to containers, and click + Container. Name New container cclab and click create. Then create a text file and save it. Then, in cclab, click upload, in upload blob, click the blue upload button, select text file and upload to cclab.
</p>
<br />

<p>
<img src="https://imgur.com/xKwyxeG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/Ge9V8De.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
- Step 4: Edit text file, maybe add "!!!", click save. Download the text file. After opening the file, notice the "!!!" are here now.
</p>
<br />

<p>
<img src="https://imgur.com/K25bMr8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
- Step 5: To delete everything, go to resource group, then click Delete resource group. Type the group name, and click Delete
</p>
<br />
