\# Smart Transit Network System



\*\*CSE421 Project\*\*



\## Overview



This project implements a VLSM-based Smart Transit Network using Cisco Packet Tracer. The network connects six operational centres (CCH, DPC, PSC, FDU, DAU, and RSP).



The project includes static routing, dynamic routing (RIPv2), route redistribution, DHCP, DNS, web and email services, and failover scenarios using floating static routes.



\## Group Members



| Name | Primary Responsibility |

|---|---|

| Alma Usha | Static Routing |

| Maisha Jahan Fatima | Email Services |

| Abu Bakar Siddique | Dynamic Routing (RIPv2) |

| Samiul Mahmud | DHCP |



\## Base Network



`20.20.0.0/16`



The base network is derived from the sum of the last three digits of the fourth member's student ID.



\## Technologies Used



\- Cisco Packet Tracer

\- VLSM (Variable Length Subnet Masking)

\- Static Routing

\- RIPv2 Dynamic Routing

\- Route Redistribution

\- DHCP

\- DNS

\- Web Server

\- Email Server

\- Floating Static Routes



\## Network Centres



\- CCH

\- DPC

\- PSC

\- FDU

\- DAU

\- RSP



\## Key Design Notes



\- Static routes include next-hop, exit-interface, recursive, floating, and default routes.

\- RIPv2 runs on CCH, DPC, FDU, and PSC.

\- DAU and RSP remain static-only.

\- CCH redistributes static routes into RIP.

\- Floating static routes provide backup paths for selected link-failure scenarios.

\- VLSM is used for efficient IP address allocation.



\## Repository Contents



\- Cisco Packet Tracer topology file (.pkt)

\- Technical Report (.pdf / .docx)

\- Work Distribution Report

\- Full Verification Report

\- VLSM Tree Diagram

\- Network Topology Diagram



\## Verification



The project includes verification of:



\- Inter-centre connectivity

\- Static and dynamic routing

\- RIP convergence

\- DHCP allocation

\- DNS resolution

\- Web server access

\- Email communication

\- Failover scenarios



\## How to Open



1\. Install Cisco Packet Tracer (version 8.x or later recommended).

2\. Open the `.pkt` file.

3\. Review the network topology and IP addressing.

4\. Test connectivity using `ping` and `tracert`.

5\. Verify routing using Cisco IOS commands.



\## CSE421 Project



\*\*Smart Transit Network System \*\*

