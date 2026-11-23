
# Cybersecurity Home Lab Progress Log

## Milestone 1: Lab Setup & Documentation

### Lab Environment
- Attacker: Kali Linux
- Target: Metasploitable 2
- Virtualization: VirtualBox
- Network: Host-only

### Network Configuration
- Kali NAT interface (eth0): 10.0.2.15/24
- Kali host-only interface (eth1): 192.168.56.102/24
- Metasploitable 2: 192.168.56.101

### Connectivity Verification
Command executed from Kali:

`ping -c 4 192.168.56.101`

Result: Successful communication between Kali and Metasploitable 2.

### Completed Tasks
- Created GitHub repository.
- Configured Git and development branch.
- Created project directory structure.
- Created documentation files.
- Updated main README.
- Identified VM network interfaces and IP addresses.
- Verified connectivity between the two VMs.

### Next Steps
- Create .gitignore.
- Commit and push Milestone 1 documentation.
- Begin network reconnaissance using Nmap.
