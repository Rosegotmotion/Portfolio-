# Portfolio-
my course career GitHub portfolio  
# Active Directory Home Lab – Windows Server 2022

**Author:** Jasiahs Herrera  
**Project Type:** Windows Server Administration / IT Infrastructure  
**Difficulty:** Intermediate

---

## 1. Project Summary

### Project Description

This project demonstrates the implementation of a small enterprise-style Active Directory environment using Windows Server 2022.

The objective was to build a centralized Windows domain environment where an administrator can manage user accounts, security groups, organizational units, authentication, and computer policies.

The lab simulates a business network in which employees log into company computers using centralized domain credentials rather than individual local accounts.

The project covers the installation and configuration of Active Directory Domain Services (AD DS), deployment of a domain controller, creation of organizational units and user accounts, implementation of Group Policy Objects (GPOs), and joining a Windows client to the domain.

### Technologies Used

| Category | Technology |
|---|---|
| Operating System | Windows Server 2022 |
| Client OS | Windows 10/11 Pro |
| Virtualization | Oracle VirtualBox or VMware |
| Directory Services | Active Directory Domain Services |
| Administration | Active Directory Users and Computers |
| Network Configuration | TCP/IP, DNS |
| Policy Management | Group Policy Management |
| Command Line | PowerShell, Command Prompt |

### Lab Environment

The project uses two virtual machines connected through an isolated virtual network.

| Machine | Configuration |
|---|---|
| Domain Controller | Windows Server 2022 |
| Client Computer | Windows 10/11 Pro |
| Domain Name | corp.example.test |
| Server IP | 192.168.10.10 |
| Client IP | 192.168.10.20 |
| DNS Server | 192.168.10.10 |

---

## 2. Project Objectives

The primary objectives of this project were:

1. Install and configure Windows Server 2022.
2. Configure a static IP address for the domain controller.
3. Install Active Directory Domain Services.
4. Promote the server to a domain controller.
5. Create organizational units for different departments.
6. Create and manage domain user accounts.
7. Configure security groups and group membership.
8. Implement Group Policy security settings.
9. Join a Windows client machine to the domain.
10. Verify domain authentication and policy application.

---

## 3. Implementation Walkthrough

### Step 1: Set Up the Virtual Machines

**Objective:** Create the virtual infrastructure required for the Active Directory environment.

1. Open Oracle VirtualBox or VMware.
2. Create a new virtual machine.
3. Name the first machine `DC01`.
4. Select Windows Server 2022 as the operating system.
5. Allocate at least 2 CPU cores and 4 GB of RAM.
6. Create a virtual hard drive with at least 60 GB of storage.
7. Attach the Windows Server 2022 installation ISO.
8. Start the virtual machine and complete the Windows Server installation.
9. Create a second virtual machine named `CLIENT01`.
10. Install Windows 10/11 Pro on the client machine.

Configure both machines to use the same isolated virtual network.

**Expected
