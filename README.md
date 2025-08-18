# Network Boot (PXE) Deployment

## Project Overview
Designed and implemented a Preboot Execution Environment (PXE) solution to facilitate diskless, automated operating system deployments across a network. This project demonstrates practical expertise in configuring DHCP, TFTP, and NFS services to enable client systems to boot and install various operating systems (including Windows and Linux distributions) without requiring physical installation media.

## Technical Implementation
- **Solution Selection**: Implemented iVentoy (version 1.0.21) as the PXE boot solution, selected for its efficient deployment capabilities and modern approach to network installations.
- **Deployment Configuration**: Installed the application on the primary system drive (C:) for optimal accessibility and performance.
- **Testing Environment**: Validated the solution using VirtualBox virtual machines with Host-Only Adapter network configuration to prevent DHCP conflicts with the mobile hotspot connection.
- **Verification**: Documented successful network boot process through system screenshots (see Figure 1 and 2).

![PXE Boot Process](/images/iventoy_0.png)  
*Figure 1: Keeping iso files in iVEntoy iso directory*

![PXE deployed](/images/iventoy_1.png)  
*Figure 2: PXE deployed*

## Value Proposition
The implemented solution demonstrates:
- Efficient network-based OS deployment capabilities
- Practical understanding of critical network boot protocols
- Comprehensive documentation of the implementation process