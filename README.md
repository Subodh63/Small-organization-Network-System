Secure Campus Network (SCN) Simulation using Cisco Packet Tracer


📘 Overview
This project simulates a Secure Campus Network (SCN) for a university environment using Cisco Packet Tracer. It includes topology design, VLAN configuration, IP addressing, protocol implementation (RIPv2, DHCP, Static Routing), and secure interdepartmental communication. The aim is to enhance network performance, ensure reliable communication, and provide a scalable infrastructure for educational institutions.

🎯 Objectives
Design and simulate a realistic campus network architecture.

Implement VLANs for departmental segmentation.

Configure routing protocols (RIPv2, static routes).

Enable DHCP services for dynamic IP allocation.

Ensure secure and efficient data transmission between departments.

🏛️ Network Structure
🏢 Departments
Building A: Electrical & Computer Engineering (with VLANs)

Building B: Mathematics

Building C: Admission Office

Building D: Computer Science (treated as a branch campus)

🌐 Servers
External Cloud-Based Email Server

Internal Web Server (for IT/CS department)

🧰 Tools & Technologies

Tool	Description
Cisco Packet Tracer 7.3	Network simulation tool
RIPv2	Routing between internal routers
DHCP	Dynamic IP allocation in Building A & B
VLANs	Network segmentation for security and efficiency
Static Routing	Communication with external cloud email server
🔧 Features
Layer-2 VLAN segmentation for isolation and security.

End-to-end packet flow with successful ICMP echo responses.

Frame Relay switching between campuses for WAN simulation.

Efficient redistribution between multiple routing protocols.

Scalability and flexibility with modular network design.

📊 Simulation Results
✅ Successful ping between all departments.

🖥️ Simulated real-time ICMP packet flow.

⏱️ Measured latency and packet success rates using Command Prompt inside Packet Tracer.

🚀 How to Use
Install Cisco Packet Tracer v7.3 or later.

Open campus-network.pkt from the Simulation_Files folder.

View network traffic via Simulation Mode.

Use Command Prompt in end devices (PCs) to test connectivity.

Refer to the Documentation/Network_Project_Report.pdf for detailed configurations and topology explanations.

📌 Future Improvements
Integration with SDN controllers for dynamic network control.

Implementation of firewall configurations for added security.

Deployment of wireless controllers and access points for WiFi access.

Upgrade to IPv6 for broader scalability.

📚 References
Tanenbaum, A. S., & Wetherall, D. J. (2011). Computer Networks.

Cisco Networking Academy. (n.d.). Packet Tracer Resources.

Jiang, H. (2021). A Review of Network Topologies. Journal of Network Systems.

Kartik Pandya et al. (2020). Star Topology Network Design.

📜 License
This project is for educational and academic use only. Please credit the authors when reusing or modifying any part of the project.

