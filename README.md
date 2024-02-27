# Linux


<h1>Linux Privilege Escalation</h1>

<img src="https://imgur.com/EyI5SYi.png" height="80%" width="80%" alt="diagram"/>

<h2>Objective<h2>
<b>Linux Privilege Escalation skills on an intentionally misconfigured Debian VM with multiple ways to get root! SSH is available. </b>

<h2>Description</h2>
In the Simulation below, We will Perform  : <br>
    <b> 1. Misconfigured File Permission Exploits</b><br>
    <b> 2. Exploit Path and Environment Variables</b><br>
    <b> 3. Network and Service Exploits</b><br>
    <b> 4. CRON exploits</b><br>
    <b> 5. SUID/SGID exploits</b><br>

    
<br />


<h2>Languages and Utilities Used</h2>

- <b>hashcat</b> 
- <b>nmap</b>
- <b>SSH</b>

<h2>Environments and OS </h2>

- <b>Kali </b>
- <b>Debian VM</b>

<h2>Program walk-through:</h2>

<p align="center">
Here is the exploit walkthroughs: Login as user with SSH. <br/>

<img src="https://imgur.com/TFGzxYG.png" height="80%" width="80%" alt="diagram"/>
<br />
<img src="https://imgur.com/a3UbAKA.png" height="80%" width="80%" alt="diagram"/>
<br /><br />

1. Exploiting Common Linux Services: <br/>
<img src="https://imgur.com/vsJRKCP.png" height="80%" width="80%" alt="set up"/>
<br />
<br />


2. Weak File Permissions (Readable /etc/shadow) : <br/>
<img src="https://imgur.com/R6IfbVh.png" height="80%" width="80%" alt="set up"/>
<img src="https://imgur.com/ylnpCrh.png" height="80%" width="80%" alt="set up"/>
<br />
<br />


3. Exploiting Writable File Permissions (Writable /etc/shadow  /etc/passwd) <br/>
<img src="https://imgur.com/6movUhL.png" height="80%" width="80%" alt="set up"/>
<img src="https://imgur.com/Lm3r4MQ.png" height="80%" width="80%" alt="set up"/>
<img src="https://imgur.com/7kYWsXu.png" height="80%" width="80%" alt="set up"/>
<br />
<br />

4. Cron Job File Permission Exploits :   <br/>
<img src="https://imgur.com/m8MxvBy.png" height="80%" width="80%" alt="set up"/>
<br />
<br />

6. Path Variable Exploits <br/>
<img src="https://imgur.com/AF3ASY1.png" height="80%" width="80%" alt="set up"/>
<img src="https://imgur.com/CFeTXbC.png" height="80%" width="80%" alt="set up"/>
<img src="https://imgur.com/AxxWUEK.png" height="80%" width="80%" alt="set up"/>
<br />
<br />

7. CRON WildCards <br/>
<img src="https://imgur.com/9zTH8WY.png" height="80%" width="80%" alt="set up"/>
<img src="https://imgur.com/LlemMQG.png" height="80%" width="80%" alt="set up"/>
<img src="https://imgur.com/eNVyF4U.png" height="80%" width="80%" alt="set up"/>

<br />
<br />

8. SUID/SGID Shared Object Injection<br/>
<img src="https://imgur.com/3MEWd9A.png" height="80%" width="80%" alt="set up"/>
<br />
<br />

9. Environement Variable Exploit and Abusing Shell Features  <br/>
<img src="https://imgur.com/MXdTT1x.png" height="80%" width="80%" alt="set up"/>
<img src="https://imgur.com/sIBy9sq.png" height="80%" width="80%" alt="set up"/>
<img src="https://imgur.com/kVMYf5z.png" height="80%" width="80%" alt="set up"/>
<br />
<br />

10. Lab Conclusion. Several tools have been written which help find potential privilege escalations on Linux.  <br/>
<img src=".png" height="80%" width="80%" alt="set up"/>
<br />
<br />





<br />
This Concludes This Active Directory Exploit Project!
NOTE: You can add onto this and make it more complex, or use these methonds to automate other tasks!  <br/>
<br />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@

<br />
This Concludes This Active Directory Exploit Project!
NOTE: You can add onto this and make it more complex, or use these methonds to automate other tasks!  <br/>
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



