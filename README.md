## Ex. No 1. 	Basic Connectivity between Two PCs Using a Switch
### Date : 22.08.25
### Name: Prithivirajan V
### Reg no: 212223100042

# Objective

          “To configure and test basic LAN connectivity between two PCs using a switch.”
________________________________________
# Apparatus/Tools Required
•	Cisco Packet Tracer Software
•	Devices: PCs, Switch, Router, Cables
•	Optional: Wireless Router, Server, Cloud
________________________________________
# Network Topology Diagram

Insert the network topology from Packet Tracer (Screenshot or drawing)

________________________________________
# IP Addressing Table (if applicable)
Device Name	Interface	IP Address	Subnet Mask
PC0	NIC	192.168.1.2	255.255.255.0
PC1	NIC	192.168.1.3	255.255.255.0
Router0	Fa0/0	192.168.1.1	255.255.255.0
________________________________________
# Procedure
Step-by-step commands/configurations.
Example:
1.	Open Cisco Packet Tracer and add two PCs and one Switch.
2.	Connect the PCs to the switch using straight-through cables.
3.	Assign IP addresses to the PCs.
4.	Use the ping command to verify connectivity.
________________________________________
# Commands Used (if any)

For PC IP assignment:<br>
nginx<br>
CopyEdit<br>
Desktop > IP Configuration > Enter IP: 192.168.1.2 / Subnet: 255.255.255.0<br>
For Router Configuration (CLI):<br>

________________________________________
# Output (Screenshots / Ping Results)
## •	Connectivity between two PCs<br>
<img width="1465" height="800" alt="Screenshot 2025-08-30 140431" src="https://github.com/user-attachments/assets/56a99708-247d-43b1-9750-c696ec87ee9b" />

## •	Successful ping between PC0 and PC1<br>
<img width="867" height="856" alt="Screenshot 2025-08-30 140253" src="https://github.com/user-attachments/assets/40485c74-ec04-42f1-b2b9-15cad34d0b83" />

________________________________________
# Result
“Successfully configured and verified basic LAN communication between two PCs using a switch in Cisco Packet Tracer.”
	
