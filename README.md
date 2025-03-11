# Two_Site_Routing
Title: Implementation of a Two-Site Network with OSPF Routing
Project Goal:
The objective of this project was to design and configure a network connecting two hypothetical offices (Tehran and Shiraz) using OSPF routing protocol to enable communication between the sites.
Network Topology: 
• Devices: 
• 2 Routers (Cisco 2911) 
• 2 Switches (2950-24) 
• 4 PCs 
• Connections: 
• Routers are connected via Serial link (10.0.0.0/30). 
• Each router connects to its respective switch and PCs. 
Configurations Performed: 
1. IP Addressing:
  • Tehran LAN: 192.168.1.0/24 • Shiraz LAN: 192.168.2.0/24 • Serial Link: 10.0.0.0/30
2. OSPF Configuration:
  • OSPF was enabled on both routers with Area 0 to advertise the networks.
3. Device Setup:
  • PCs were assigned static IPs with their respective gateways.
 Results:
• Successful ping tests confirmed connectivity between Tehran (192.168.1.x) and Shiraz (192.168.2.x).
• Routing tables showed OSPF-learned routes.
 Conclusion:
This project showcases my skills in configuring multi-site networks, IP subnetting, and dynamic routing using OSPF.
![Two_Site_Routing](https://github.com/user-attachments/assets/df20cb43-932e-4a22-9d61-8eb5650c5fa1)
