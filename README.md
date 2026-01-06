# Computer Networks Lab Project - Cisco Packet Tracer Implementation

![Cisco Packet Tracer](https://www.startertutorials.com/blog/wp-content/uploads/2024/08/Cisco-Packet-Tracer-CPT.png)

This repository contains a sample implementation of a **Computer Networks Lab Project** using **Cisco Packet Tracer**. The project simulates a realistic organizational network topology, demonstrating key networking concepts such as subnetting, IP addressing, device interconnection, and static routing.

## Project Objective

Design and implement a logical network topology using Cisco Packet Tracer that represents a realistic organizational network. The simulation integrates core concepts from lab sessions, including:

- Successful interconnection of end devices (PCs) and network infrastructure (routers, switches).
- Logical traffic separation through proper subnetting and department segregation.

## Customization Requirements Implemented

To ensure uniqueness, the following variations were applied as per project guidelines:

- **Subnetting Scheme**: Custom Class C subnetting with non-standard masks for variable host requirements per department.
- **IP Addressing**: Unique private IP ranges (e.g., from 192.168.x.0/24 series) and distinct network IDs for each subnet.
- **Servers**: Multiple server types including HTTP (Web), Email, DNS, and FTP servers.
- **End Devices**: Varying number of PCs across departments.
- **Infrastructure**: Customized quantity and hierarchical arrangement of routers and switches.
- **Routing**: **Static routing** configured on all routers for inter-network communication.


## Repository Contents

- `project.pkt` – Main Cisco Packet Tracer simulation file.
- `Screenshots/` – Folder containing topology overview, configuration screenshots, and ping test results.
- `--.pdf` – Detailed project report (including IP addressing table, subnet calculations, and static route configurations).
- `README.md` – This file.

## How to Use

1. Download and install [Cisco Packet Tracer](https://www.netacad.com/portal/resources/packet-tracer) (free for Networking Academy users).
2. Open the `NetworkTopology.pkt` file in Packet Tracer.
3. Explore the topology:
   - Test connectivity using ping between departments.
   - Access services (HTTP, Email, DNS) from client PCs.
   - View router configurations for static routes.

## Features Demonstrated

- Hierarchical network design (Core, Distribution, Access layers where applicable).
- VLAN configuration for traffic separation (optional extension).
- Server services configuration and client access.
- Full end-to-end connectivity verification.

This project serves as a reference for students learning computer networking fundamentals, subnetting, and router/switch configuration.

**Note**: This is a sample implementation. Customize further to meet specific group requirements.

---

*Submitted as part of Computer Networks Laboratory Course*
