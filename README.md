# NTI-CCNA-Graduation-Project

# Multi-Building Enterprise Network — CCNA Capstone Project

**Project type:** Cisco Packet Tracer network simulation  
**Author:** Belal Ebrahim  
**Status:** Completed (CCNA capstone)

## Project Summary
Designed and implemented a scalable multi-building enterprise network using Cisco Packet Tracer. The network includes inter-site OSPF routing, VLAN segmentation across floors, inter-VLAN routing on multilayer switches, and a dedicated services building hosting DHCP, DNS, web, and email services with NAT/PAT for internet access. Security controls implemented include port security and ACLs.

## Key Features
- OSPF dynamic routing between sites (area 0 backbone)
- VLAN design per floor / per department and inter-VLAN routing via multilayer switches
- DHCP pools for client subnets and helper-address configuration on L3 switches
- NAT/PAT for internet access on edge router
- Access Control Lists (ACLs) and port-security for basic security enforcement
- Core services hosted in a central building (DHCP, DNS, Web, Email)

## Files in this repository
- `pkt/` – Packet Tracer project files (`*.pkt`)  
- `configs/final_project_config.txt` – Exported CLI configuration snippets (routers & switches). :contentReference[oaicite:1]{index=1}  
- `images/` – Topology screenshots and diagrams  
- `docs/` – Report and IP addressing plan (optional)

## How to run / open
1. Install Cisco Packet Tracer (the same version used to create the `.pkt` file is recommended).  
2. Open `pkt/final_project.pkt` in Packet Tracer.  
3. To review device CLI configs, open `configs/final_project_config.txt` or inspect each device inside Packet Tracer.

## Notes & tips
- If `.pkt` file(s) are large (>100 MB), consider using Git LFS (see `.gitattributes`).  
- Keep a separate `docs/` folder for your lab report and IP addressing table to make the repo portfolio-friendly.

## Future improvements
- Add authentication & role-based access simulation (RADIUS/AAA)  
- Implement redundancy (HSRP/VRRP) and link aggregation for high availability  
- Add automated topology diagram generation and step-by-step lab exercises

## License
Educational use — created as a CCNA capstone project.

