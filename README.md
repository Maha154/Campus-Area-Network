# Campus-Area-Network
📡 Campus Area Network (CAN)
📝 Project Overview

The Campus Area Network (CAN) project demonstrates the design and implementation of a high-speed network that interconnects multiple Local Area Networks (LANs) within a university or corporate campus.
Using Cisco Packet Tracer, this project simulates communication between different departments through routers, switches, and servers, ensuring efficient data transfer and centralized management.

🎯 Objective

To design a Campus Area Network topology connecting multiple buildings (e.g., Admin, Academic, Library, and Hostel blocks).

To simulate inter-departmental communication through routers and switches.

To demonstrate VLAN segmentation, IP addressing, and routing between subnets.

To ensure scalability, reliability, and centralized resource sharing.

🧩 Tools & Technologies

Cisco Packet Tracer

Networking Devices:

Routers

Switches

PCs and Servers

Wireless Access Points (if included)

Protocols Used:

Static Routing / RIP / OSPF (depending on configuration)

VLAN (for segmentation)

DHCP (for dynamic IP allocation)

DNS / HTTP / FTP (for network services)

🏗️ Network Design
Topology Structure

The network consists of multiple LANs connected via a central backbone router.

Each department (LAN) is assigned a unique subnet.

Communication between departments is enabled through routing protocols.

Optional servers are added for DNS, DHCP, or Web hosting.

Example Layout
Building / Department	Network (Subnet)	Devices	Services
Admin Block	192.168.1.0/24	PCs, Switch	DHCP
Academic Block	192.168.2.0/24	PCs, Switch	HTTP
Library	192.168.3.0/24	PCs, Switch	DNS
Hostel Block	192.168.4.0/24	PCs, Switch	FTP

(You can modify according to your .pkt design.)

⚙️ Configuration Steps

Create LANs for each department using switches and PCs.

Assign IP addresses to all end devices.

Connect LANs to routers and configure routing (Static / RIP / OSPF).

Configure VLANs if departmental separation is implemented.

Add Servers (DNS, DHCP, HTTP, FTP) and assign IPs.

Verify Connectivity using the ping command across departments.

Save and export the final topology as Campus Area Network.pkt.

✅ Expected Output

Successful end-to-end communication between all LANs.

Each department has distinct subnet addressing.

Network services (HTTP, DNS, DHCP, FTP) are accessible campus-wide.

Demonstrates centralized and scalable network design for a medium-sized campus.

📊 Features

Centralized router backbone

VLAN-based departmental segmentation

Server-based IP and DNS management

Layer-2 and Layer-3 connectivity

Easy scalability for new buildings or networks

📂 Project Files
File Name	Description
Campus Area Network.pkt	Cisco Packet Tracer simulation file containing the full network design
README.md	Project documentation (this file)
🧠 Learning Outcomes

Understanding of Campus Area Network architecture

Experience with subnetting and routing

Familiarity with Cisco Packet Tracer simulation

Ability to design a scalable and secure campus network
