# virtualbox-kali-enterprise-lab
Documented Oracle VirtualBox and Kali Linux home lab featuring VM deployment, dual NAT networks, system maintenance, troubleshooting, and operational validation.
# Oracle VirtualBox and Kali Linux Enterprise Lab

## Project Overview

This project documents the deployment, configuration, troubleshooting, and validation of an Oracle VirtualBox home lab running Kali Linux.

The lab was created to develop practical skills in virtualization, Linux administration, network configuration, system maintenance, troubleshooting, and technical documentation.

## Technologies Used

- Oracle VirtualBox 7.2.12
- Oracle VirtualBox Extension Pack
- Kali GNU/Linux Rolling 2026.1
- Windows 11 host system
- NAT Networks
- Linux command-line utilities

## Lab Configuration

The Kali Linux virtual machine was configured with:

- 8 GB RAM
- 4 virtual processors
- 80 GB virtual disk
- VMSVGA graphics controller
- Two virtual network adapters
- NCSA-LABS NAT network
- HOME-LABS NAT network

## Key Tasks Completed

- Installed Oracle VirtualBox and the Extension Pack
- Troubleshot Extension Pack administrative permission errors
- Imported an NGT-provided Kali Linux virtual appliance
- Created and configured isolated NAT networks
- Assigned multiple network adapters to the Kali VM
- Recovered an inaccessible virtual machine configuration
- Verified virtual disk and configuration file locations
- Updated Kali Linux packages and kernel
- Removed obsolete packages and cleaned package caches
- Validated IP addressing, routing, DNS, and internet connectivity
- Verified system resources, operating system, kernel, and virtualization platform

## Network Validation

The Kali VM successfully received addresses on both virtual networks:

- NCSA-LABS: Correct NAT network address ranges
- HOME-LABS: Correct NAT network address ranges

Connectivity testing confirmed:

- Successful gateway communication
- Successful internet connectivity
- Successful DNS resolution
- Zero packet loss during validation testing

## Documentation

- [Oracle VirtualBox Enterprise Lab Setup PDF](Oracle_VirtualBox_Enterprise_Lab_Setup_Final.pdf)
- [Kali Linux Deployment and System Maintenance PDF](Kali_Linux_Deployment_and_System_Maintenance_Final.pdf)

Editable Word versions are also included in this repository.

## Skills Demonstrated

- Virtual machine deployment
- Linux system administration
- Network configuration
- NAT network design
- Troubleshooting
- Package management
- System validation
- Technical documentation
- Operational maintenance

## Author

**Kevin Darger**

U.S. Army Veteran transitioning into information technology and cybersecurity.
