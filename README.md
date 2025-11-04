<h1>Virtual Machine</h1>



<h2>Description</h2>

<br />


<h2>Languages and Utilities Used</h2>
- <b>Oracle VM VirtualBox</b> 

-<b> PowerShell</b>


<h2>Environments Used </h2>

 -<b>Windows 11</b> (24H2)

<h2>Program walk-through:</h2>

<p align="center">
1.	First go to the VirtualBox website: <br/>
<img src="https://i.imgur.com/pJDMeoW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
2.	Click the blue download button:  <br/>
<img src="https://imgur.com/qAKeAG2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
3.	Choose what operating system you use: <br/>
<img src="https://imgur.com/FfOTzf9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
4.	Download VirtualBox  :  <br/>
<img src="https://imgur.com/w76J3zU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
5.	Optional: Check hashes of the file. The integrity of it:  <br/>
 a.	Scroll down on the download VirtualBox page until you see “File Checksums” <br/>
 b.	Click on the SHA256 checksums
<img src="https://imgur.com/ygs5wjH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://imgur.com/vElUWkD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 
 c.	At the right hand side, find the one you downloaded earlier based on the OS of the system. 
 I downloaded windows. 
 <br />
 
 d.	Next hit the windows button on your keyboard and type PowerShell, open it.
<br />
<br />
<img src="https://imgur.com/JOXB9jw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

e. Next type certutil -hashfile  (the downloaded file location) sha256 <br/>
<img src="https://imgur.com/RBfCVim.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
     i.	Compare the hashes with the one on step 5C and if the values are the same then you know the file wasn’t tampered with. <br/>
     ii.	It’s important to check the integrity of the files you download.

6.	Click the VirtualBox installer and follow instructions.
7. After installing and following all the instructions. Open VirtualBox and click the blue spikey box.
<img src="https://imgur.com/ICulKSr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

8.This will open up a window in how to create a new VM. 
<img src="https://imgur.com/xnr3EAN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

9. Name your VM machine, pick where its installed, and choose any ISO images for the operating system. For example, windows 10/11, Ubuntu, Linux Mint, etc. Moreover, to find an ISO image. Go to a vendors website: Ubuntu, Linux Mint, or Microsoft to name a few. For your information, the ISO image will be free and not cost anything and we can check the  integrity of these images by using step:5.
    
10. Now we can specify virtual hardware. Depending on the specs of your physical machine will determine performance in a virtual one.
 <img src="https://imgur.com/MIsU1eW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

 11. Specify virtual hard disk.  Choose the disk size of the machine. I recommend 25-50GB for a test machine. 
  <img src="https://imgur.com/COv65Du.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

  12. Click the finish button.
  13. Double click your virtual machine to power it on or click the green arrow.
  <img src="https://imgur.com/VYaXqaa.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

  14.Done: you created your first virtual machine!
  
  <img src="https://imgur.com/mq6Eujk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


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
