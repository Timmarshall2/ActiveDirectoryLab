<h1>Active Directory Home Lab</h1>

 ### [YouTube Demonstration](https://youtu.)

<h2>Description</h2>
In this lab I’m going to walk through how to create an Active Directory home lab environment via Oracle Virtual Box. Many organizations utilize active directory, so I highly encourage running through it a couple of times. Practicing this lab will help you develop a deeper understanding of how active directory and windows networking work.  
Don’t forget that Windows home edition does not have the ability to join a domain! 
<br />

<h2>Environments Used </h2>

- <b>Windows 10</b> 

<h2>Program walk-through:</h2>

<p align="center">
Before we get started, we will first need to Download Virtual Box. At the time of this posting [Virtual Box] ( https://www.virtualbox.org/) 7.0 is the latest version.: <br/>
<img src="https://i.imgur.com/nMR3CF2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Open Virtual Box and click Machine drop down and select New.:  <br/>
<img src="https://i.imgur.com/te3OSOu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Name Server and select the correct version (Windows 2016 64-bit): <br/>
<img src="https://i.imgur.com/K12ckNF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Allocate Memory:  <br/>
<img src="https://i.imgur.com/MLVkABn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select Create virtual hard disk now:  <br/>
<img src="https://i.imgur.com/qfgfdhq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select VDI:  <br/>
<img src="https://i.imgur.com/AU0vJT7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select Dynamic Allocated:  <br/>
<img src="https://i.imgur.com/EXW0fvX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select Hard drive space in regards to how much your machine can handle:  <br/>
<img src="https://i.imgur.com/yLR5Bu2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Open Browser and Download the ISO:  <br/>
<img src="https://i.imgur.com/15ljebd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Type in your information and Download ISO:  <br/>
<img src="https://i.imgur.com/9K6lADj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select 64-bit download:  <br/>
<img src="https://i.imgur.com/CSZ2Lbf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Save .ISO file to Desktop or Downloads file :  <br/>
<img src="https://i.imgur.com/vb9BNoC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Open Virtual Box and select your server and Click Start:  <br/>
<img src="https://i.imgur.com/SV4OLLt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Click on the Folder and press add at the top:  <br/>
<img src="https://i.imgur.com/jGWwkjJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
  <br/>
<img src="https://i.imgur.com/RKui1Ed.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Go to the file where you put the ISO file and select it, then select Open:  <br/>
<img src="https://i.imgur.com/tM7gMGN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select CHOOSE :  <br/>
<img src="https://i.imgur.com/bPjVWx1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Selct Start:  <br/>
<img src="https://i.imgur.com/Jr30c1P.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Click Next:  <br/>
<img src="https://i.imgur.com/jftyjrx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Install Now:  <br/>
<img src="https://i.imgur.com/JdP2s27.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Choose Windows Server Standard Eval Desktop Experience and Click Next:  <br/>
<img src="https://i.imgur.com/XRBCzCW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Accept the Terms :  <br/>
<img src="https://i.imgur.com/YLwnoVc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select Install Windows Only :  <br/>
<img src="https://i.imgur.com/3jnZKkL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Click Next:  <br/>
<img src="https://i.imgur.com/IOi71fN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
System will restart. Enter Password for Admin. :  <br/>
<img src="https://i.imgur.com/pecVQ7r.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Login as Administrator:  <br/>
<img src="https://i.imgur.com/DPDbWo2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Once you Login, your Server Management Dashboard will appear. Open up File Explorer on the Task bar.:  <br/>
<img src="https://i.imgur.com/ZWW7Onu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Right click on This PC and open Properties:  <br/>
<img src="https://i.imgur.com/znnJYk0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Go to Change Settings under Computer Name, domain, and workgroup settings.:  <br/>
<img src="https://i.imgur.com/axHYIjq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Click Change..:  <br/>
<img src="https://i.imgur.com/InMCET0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Rename To whatever you wish and press OK:  <br/>
<img src="https://i.imgur.com/SKtI3hy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Press OK:  <br/>
<img src="https://i.imgur.com/xWG8b10.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Restart:  <br/>
<img src="https://i.imgur.com/A4hczk7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 Log into the Machine and you will return to the Server Dashboard. At the Top Right corner, Click “Manage” and Click on “Add Roles and features”:  <br/>
<img src="https://i.imgur.com/AeVoQG9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Click Next:  <br/>
<img src="https://i.imgur.com/c2gROjL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Click Next with “Role based installation” selected :  <br/>
<img src="https://i.imgur.com/5uMMqFb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Click Next:  <br/>
<img src="https://i.imgur.com/Hrd9W6z.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select “Active Directory Domain Services”:  <br/>
<img src="https://i.imgur.com/Tykx4z3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Click “Add features” and Select “Next”:  <br/>
<img src="https://i.imgur.com/5uW2fw5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select Next :  <br/>
<img src="https://i.imgur.com/DxvCBQs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select Next:  <br/>
<img src="https://i.imgur.com/f9LxjsG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Click “Install” :  <br/>
<img src="https://i.imgur.com/n0jarDD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Once prompted click “Promote this server to a domain controller”:  <br/>
<img src="https://i.imgur.com/jwaxXFC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select “Add a new forest” and input your domain name Ex. Makeitup.com. Then select "Next”:  <br/>
<img src="https://i.imgur.com/AZBvcSv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter a password and Select “Next”:  <br/>
<img src="https://i.imgur.com/zYyhYTC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
<br />
Click “Next”:  <br/>
<img src="https://i.imgur.com/AAU0HHP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
NetBIOS Domain name will automatically populate. Click “Next”:  <br/>
<img src="https://i.imgur.com/OKYBfyO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Click “Next”:  <br/>
<img src="https://i.imgur.com/X3kU418.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Click “Next”:  <br/>
<img src="https://i.imgur.com/ls4etE2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Click “View Script” :  <br/>
<img src="https://i.imgur.com/EHfsJbw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Copy All:  <br/>
<img src="https://i.imgur.com/jvcRXZl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Exit the Wizard:  <br/>
<img src="https://i.imgur.com/ielq6ME.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Run PowerShell and Right Click to Paste Script. Add Password.:  <br/>
<img src="https://i.imgur.com/Sn0FsXu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
System will automatically restart.:  <br/>
<img src="https://i.imgur.com/V3qbOzE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Log in and Active Directory is now Setup.:  <br/>
<img src="https://i.imgur.com/2CXJYKy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
