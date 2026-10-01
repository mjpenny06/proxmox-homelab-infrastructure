This A 4-node ProxmoxVE virtualization cluster built for enterprise infrastructure, virtualization, networking, storage, and cybersecurity laboratory environments.

## Project Overview ##

This project demonstrates the design, deployment, and operation of a multi-node Proxmox VE cluster with distributed storage using Ceph.

### Infrastructure ###

| Component      | Specification 
|----------------|---------------------
| Hypervisor     | Type 1:ProxmoxVE 
| Nodes          | 4 
| CPU            | Intel Core i7-4790 
| Memory         | 32 GB DDR3 per node 
| Storage        | 1TB Ceph 
| Cluster        | ProxmoxVE Cluster 
| Virtualization | KVM / LXC 
| Monitoring     | Prometheus / Grafana 
| Networking     | Unmanaged SW / Linux Bridge 

###  Architecture ###

<img width="1206" height="1305" alt="image" src="https://github.com/user-attachments/assets/bd19c75d-ea0f-4c53-b12b-e6b951a83dc8" />

### Key Technologies ###
- Proxmox VE
- Ceph
- KVM
- LXC
- Linux
- Linux Bridge
- Distributed Storage
- Prometheus
- Grafana
- High Availability concepts

### What I Built ###
- Designed a 4-node Proxmox VE cluster
- Configured clustered virtualization
- Implemented Ceph distributed storage
- Created VM and container workloads
- Configured networking and VLAN connectivity
- Implemented infrastructure monitoring
- Troubleshot Ceph OSD and cluster health issues
- Documented recovery procedures

### Skills Demonstrated ###
- Virtualization & Infrastructure
- Linux Administration
- Storage & Ceph
- Networking
- Monitoring & Observability
- Infrastructure Troubleshooting
- Security
- Cloud & Hybrid Infrastructure
- Documentation

### Troubleshooting ###

See the troubleshooting documentation: 
- [Ceph Recovery]( To be created)
- [OSD Rebuild]( To be created)
- [Common Issues]( To be created)

### Project Goals ###
- To learn and gain hands-on experience with different server operating systems, including Windows Server and Linux distributions.
- To build practical experience in virtualization using Proxmox VE, including virtual machines, LXC containers, resource allocation, and cluster management.
- To understand and implement distributed storage using Ceph, including OSD management, storage pools, data availability, and storage troubleshooting.
- To develop practical Linux system administration and troubleshooting skills.
- To strengthen networking skills by implementing IP addressing, VLANs, virtual networking, DNS, DHCP, and network segmentation.
- To gain experience with infrastructure monitoring using Prometheus and Grafana.
- To practice infrastructure security concepts, including secure remote administration, access control, network segmentation, and system hardening.
- To create a realistic enterprise-style home lab environment for testing servers, applications, networking technologies, and security tools.
- To develop troubleshooting and root-cause analysis skills by intentionallyinvestigating and resolving infrastructure failures.
- The long-term goal is to integrate this Proxmox environment with AWS to create a hybrid infrastructure laboratory.
- To demonstrate practical infrastructure engineering skills through a documented, reproducible, and continuously improving homelab project.


## Future Improvements
- AWS hybrid connectivity via VPN using Tailscale
- Centralized logging
- Automated VM deployment
- Infrastructure as Code
- Security monitoring using Security Onion
- Fortigate/Pfsense (Load Balancing & Failover)
- Use Docker/Containers for PiHole, 
