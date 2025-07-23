<h1>Campus Network Design</h1>

 

<h2>Description</h2>
Project consists of a simple PowerShell script that walks the user through "zeroing out" (wiping) any drives that are connected to the system. The utility allows you to select the target disk and choose the number of passes that are performed. The PowerShell script will configure a diskpart script file based on the user's selections and then launch Diskpart to perform the disk sanitization.
<br />


<h2>Environments and Utilities Used</h2>

- <b>Cisco Packet Tracer 


<h2>Design walk-through:</h2>

<p align="center">
Setting up connections and deisgn: <br/>
<img width="1500" height="500" alt="Campus Network Design PNG 1" src="https://github.com/user-attachments/assets/c622571a-f281-4bd3-89f2-6642357c01c7" />

<br />
<br />
Configuring initial routers:  <br/>
<img width="1568" height="897" alt="image" src="https://github.com/user-attachments/assets/7f3cd08d-388b-4634-b313-e3c34e22f88d" />

<br />
<br />
Configuring VLANs (Layer 2 Switches): <br/>
<img width="1662" height="787" alt="image" src="https://github.com/user-attachments/assets/3449bf7b-149f-4f96-bf7c-7effccdb861f" />

<br />
<br />
DHCP Configuration of Main Campus:  <br/>
<img width="1862" height="864" alt="image" src="https://github.com/user-attachments/assets/3a5f1327-675f-4428-9e80-700b1313a1ea" />

<br />
<br />
Pinging different VLANs for confirmation:  <br/>
<img width="1367" height="811" alt="image" src="https://github.com/user-attachments/assets/0d5f5728-fa07-49cf-a75a-0d0e26ac6df4" />

<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
