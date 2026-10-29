Home Lab Setup
Overview
This project documents the creation of a cybersecurity home lab using VirtualBox. The purpose of the lab is to provide a safe environment for learning networking, system administration, vulnerability assessment, and security monitoring.

Objectives
Learn virtualization technologies
Practice Windows and Linux administration
Create an isolated testing network
Prepare an environment for future cybersecurity projects
Lab Environment
Host Machine
Windows 11
16 GB RAM
Intel Core i7
Virtual Machines
Ubuntu Linux
OS: Ubuntu 24.04 LTS
RAM: 4 GB
Storage: 25 GB
Windows 11
OS: Windows 11
RAM: 6 GB
Storage: 50 GB
Tools Used
VirtualBox
Ubuntu
Windows 11
GitHub
Installation Steps
1. Install VirtualBox
Downloaded and installed VirtualBox on the host machine.

2. Create Ubuntu VM
Allocated 4 GB RAM
Assigned 25 GB virtual disk
Installed Ubuntu using ISO image
3. Create Windows VM
Allocated 6 GB RAM
Assigned 50 GB virtual disk
Installed Windows 11 evaluation copy
4. Configure Networking
Configured VMs to communicate on an isolated virtual network
Verified connectivity using ping
Screenshots
Ubuntu VM
screenshots/ubuntu-install.png

Windows VM
screenshots/windows-vm.png

Skills Learned
Virtual machine creation
Operating system installation
Network configuration
Basic Linux administration
Environment documentation
Future Improvements
Install Wireshark
Install Nmap
Deploy a SIEM solution using Wazuh
Conduct vulnerability scans
References
https://www.virtualbox.org/
https://ubuntu.com/

