<h1>Setting up pfsense firewall as a Home Lab</h1>


<h2>Description</h2>
pfSense is a free and open-source firewall and router that also features unified threat management, load balancing, multi-WAN, and more. This blog post will guide you through the process of setting up pfSense at home.
<br />



<h2>Environments Used </h2>

- <b>Hardware: </b> Intel(R) Core(TM) i3-3240 CPU @ 3.40GHz 4 CPUs: 1 package(s) x 2 core(s) x 2 hardware threads
- <b>Software: </b> 2.7.0-RELEASE (amd64)

<h2>Program walk-through:</h2>

<p align="center">
Step 1: Download pfSense
First, download the latest version of pfSense from the official website(https://pfsense.org/download).
<img src="https://github.com/PJohnrhoeRepo/Images/blob/main/Pfsense%20download.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> <br/>
<br />
<br />
Step 2: Prepare the Installation Media
Write the downloaded pfSense image to a USB drive using software like Rufus(https://rufus.ie/en/).
<img src="https://github.com/PJohnrhoeRepo/Images/blob/main/Rufus.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> <br/>
<br />
<br />

Step 3: Install pfSense
Insert the USB drive into your hardware and boot from it. Follow the on-screen instructions to install pfSense.
<br />
<br />

Step 4: Initial Configuration
After installation, you’ll be guided through the initial configuration wizard. This includes setting up interfaces, WAN and LAN settings, and general system settings.
<br />
<br />
Step 5: Test Your Setup
Finally, test your setup to ensure everything is working correctly. You can do this by checking internet connectivity and the status of your firewall rules.
<br />
<br />

<h2>Conclusion</h2>
Setting up pfSense at home can greatly enhance your network’s security and control. While the process may seem daunting at first, with careful preparation and patience, you can successfully set up your own home network with pfSense.



</p>


<!--
<p align="center">
Launch the utility: <br/>
<img src="https://github.com/PJohnrhoeRepo/PfSenseLab/blob/main/Pfsense%20download.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select the disk:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

--!>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
