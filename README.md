# Linux & VMware Lab

## Overview
Hands-on infrastructure lab deploying and configuring Ubuntu Server VMs 
in VMware Workstation Pro to practice Linux administration and 
virtualization skills relevant to DoD IT environments.

## Environment
- Host: Windows 11 Pro (Ryzen 7 9800X3D, 32GB RAM)
- Hypervisor: VMware Workstation Pro 25H2
- Guest OS: Ubuntu Server 26.04 LTS x2

## What I Did
- Deployed two Ubuntu Server VMs in VMware from scratch
- Verified OS identity, network configuration, and system resources (Screenshot 1)
<img width="1170" height="915" alt="1" src="https://github.com/user-attachments/assets/f7157a67-6463-4f7f-8c60-33218d3ba7cd" />

- Created users and managed sudo privileges (Screenshot 2)
<img width="649" height="101" alt="2" src="https://github.com/user-attachments/assets/2e4cdf90-67a3-4713-b2bb-97f0dcd9cd40" />

- Created directories, files, and applied file permissions with chmod (Screenshot 3)

<img width="485" height="263" alt="3" src="https://github.com/user-attachments/assets/3b75a6a8-6e64-482b-b8ca-5a7d04fe8b4e" />

- Confirmed internet connectivity, routing table, hosts file, and open ports (Screenshot 4)
<img width="1207" height="597" alt="4" src="https://github.com/user-attachments/assets/115019e3-d12b-4ac9-ab24-14398b01b5d4" />

- Validated VM-to-VM communication via ping with 0% packet loss (Screenshot 5)
<img width="590" height="203" alt="5" src="https://github.com/user-attachments/assets/216d4943-d72c-42f2-a973-ca0682dfe835" />

- Installed Docker and ran first container
- <img width="691" height="500" alt="6" src="https://github.com/user-attachments/assets/2a8691c7-c4bf-4a67-8aac-3f2253f000b7" />

- Deployed nginx web server in a Docker container, confirmed serving pages via curl (Screenshot 7)

<img width="629" height="482" alt="7" src="https://github.com/user-attachments/assets/4a5aebd0-b551-46ee-9006-5186ab14ca31" />

- Installed and configured OpenSSH for remote access
- Patched both servers using apt package manager

## Skills Practiced
- Linux CLI navigation and administration
- User and permission management
- Network configuration and auditing
- Server patching and maintenance
- VMware virtualization
- SSH configuration

## Screenshots
See screenshots above for evidence.
