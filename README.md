<h1>DHCP Network - Cisco - Visual Guide</h1>


<h2>Description</h2>
This project demonstrates how to configure a DHCP (Dynamic Host Configuration Protocol) network using Cisco Packet Tracer. It includes step-by-step visual instructions and screenshots showing how to:

-Set up routers, switches, and end devices
-Configure DHCP on the router
-Assign IP addresses automatically
-Verify network connectivity

Great to learn how to use Cisco Packet Tracer and to understand dynamic IP allocation in LAN environments.
<br />


<h2>Languages and Utilities Used</h2>

- Cisco Packet Tracer – for network simulation
- DHCP (Dynamic Host Configuration Protocol) – for dynamic IP addressing
- Cisco IOS CLI – for router and switch configuration using command-line interface
- Networking Concepts – IP addressing, subnetting, routing, switching

<h2>Environments Used </h2>

- <b>macOS Ventura 13.7.4</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
Launch Cisco Packet Tracer: <br/>
<img src="https://i.imgur.com/ZRUAO4Y.png"/>
<br />
<br />
Select End Devices then drag and drop computers in the netwok:  <br/>
<img src="https://i.imgur.com/VyVdoan.png"/>
<br />
<br />
Select Network Devices then drag and drop a switch in the network: <br/>
<img src="https://i.imgur.com/DVAu33T.png"/>
<br />
<br />
Go on Connections then select the Copper Straight-Through cable, click in one computer and select FastEthernet0 port:  <br/>
<img src="https://i.imgur.com/nXtWe63.png"/>
<br />
<br />
Click on the Switch and select FastEthernet0/1 Port:  <br/>
<img src="https://i.imgur.com/bE44Ynj.png"/>
<br />
<br />
Connect the other computers to the switch using FastEthernet0 and choose different ports on the switch:  <br/>
<img src="https://i.imgur.com/OLQxGBG.png"/>
<br />
<br />
Choose a router, in this case we're using a wireless router, then drag and drop into the network enviroment:  <br/>
<img src="https://i.imgur.com/XhCEejv.png"/>
<br />
<br />
With a Copper Straight-Through cable, click on the router and select GigabitEthernet 1 Port:  <br/>
<img src="https://i.imgur.com/K5QbBvi.png"/>
<br />
<br />
Now click on the Switch and select GigabitEthernet0/1 Port:  <br/>
<img src="https://i.imgur.com/fKdCCz9.png"/> 
<br />
<br />
Choose one computer then double click it, select Desktop then IP Configuration:  <br/>
<img src="https://i.imgur.com/3xV50BV.png"/>
<br />
<br />
Select DHCP, it will automatically allot an IP address to the computer, do the same steps to the other computers in the network:  <br/>
<img src="https://i.imgur.com/xBNJBAk.png"/>
<br />
<br />
Once the IP addresses are assigned, we'll check the connectivity between computers, for that choose 2 computers, double click them, select Desktop then Command Prompt:  <br/>
<img src="https://i.imgur.com/Vl44hEC.png"/>
<br />
<br />
On Command Prompt type the command Ping followed by the IP address of the machine you want to check connectivity with, in this case the connection is successful, do the same steps between the other computers:  <br/>
<img src="https://i.imgur.com/iM9zkVu.png"/>
<br />
<br />
Now that we've checked connectivity double click the Switch and Select CLI:  <br/>
<img src="https://i.imgur.com/UziLISJ.png"/>
<br />
<br />
Tyoe the command en to enter the privilege EXEC mode(without this you can't run advanced commands), and run the code show mac address-table, it'll display the switch's MAC address table with VLAN ID, MAC addresses, type and Ports in the network:  <br/>
<img src="https://i.imgur.com/erxbGTt.png"/>
<br />
<br />
Great! You just configured a DHCP network, congratulations!  <br/>
<img src="https://i.imgur.com/st15fkt.png"/>
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
