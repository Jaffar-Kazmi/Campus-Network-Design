# University Campus Network Project

This repository contains a Cisco Packet Tracer implementation of a university campus network project with segmented departments, core routing, centralized services, and basic security controls based on the project requirements in the provided semester brief.

## Included Work
- Packet Tracer topology for the campus network.
- Project report documenting topology, IP addressing, routing, services, testing, and results.
- Supporting screenshots used for verification and submission.

## Network Scope
The design targets a medium-sized university campus with academic blocks, an administration block, a library, and a data center connected through a hierarchical network structure. Departmental VLANs are used to separate traffic, while inter-network communication is handled through a routed backbone using OSPF as the dynamic routing protocol.

## Configured Services
The project includes DHCP for automatic IP assignment, DNS for name resolution, HTTP for web access, and FTP for file transfer between departments as required by the project brief. Basic access control and port security are also included to enforce segmentation and protect access-layer ports.

## Testing
Validation covers IP allocation, inter-VLAN communication, OSPF route learning, DNS lookups, web access, FTP transfer, ACL-based restriction, and switch port-security verification in line with the stated testing requirements.

## Files
- `campus.pkt` - Cisco Packet Tracer project file
- `Report.pdf` / report document - final project report
- `README.md` - repository overview
