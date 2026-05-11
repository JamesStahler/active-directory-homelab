# Active Directory Homelab

## Project Overview

This project documents the deployment of a Windows Server Active Directory homelab using VirtualBox.

The environment demonstrates enterprise IT administration concepts including:

- Active Directory Domain Services (AD DS)
- DNS configuration
- Domain controller deployment
- Domain user management
- Organizational Unit (OU) management
- Workstation domain joining
- Authentication testing
- Basic Windows administration

---

## Technologies Used

- Windows Server 2022
- Windows 10 Client VM
- Active Directory Domain Services
- DNS
- VirtualBox
- PowerShell
- Command Prompt

---

## Lab Objectives

- Configure static IP addressing
- Install and configure Active Directory
- Promote server to Domain Controller
- Create and manage domain users
- Configure Organizational Units
- Join workstation to domain
- Validate authentication using command-line tools
- Practice enterprise identity management concepts

---

## Skills Demonstrated

- Windows Server Administration
- Active Directory Management
- DNS Configuration
- Identity and Access Management (IAM)
- Troubleshooting
- Virtualization
- Windows Networking
- Domain Authentication

---

## Screenshots

---

### VM Setup

Configured the Windows Server virtual machine hardware, networking adapters, and ISO installation media within VirtualBox.

![VM Setup](screenshots/01-vm-setup/01-server-vm-memory-and-boot.png)

![VM CPU Configuration](screenshots/01-vm-setup/02-server-vm-cpu-hardware.png)

![VirtualBox Network Adapters](screenshots/01-vm-setup/04-server-vm-network-adapters.png)

---

### Windows Server Installation

Installed Windows Server and prepared the environment for Active Directory deployment.

![Windows Server Installation](https://github.com/JamesStahler/active-directory-homelab/blob/main/screenshots/02-server-installation/01-windows-server-installation-progress.png)

![Server Manager Dashboard](https://github.com/JamesStahler/active-directory-homelab/blob/main/screenshots/02-server-installation/02-server-manager-dashboard-initial.png)

---

### Domain Controller Networking

Configured static IP addressing, DNS settings, and validated network connectivity for the domain controller.

![Static IP Configuration](screenshots/03-dc-networking/01-static-ip-configuration.png)

![IP Configuration Verification](screenshots/03-dc-networking/03-ipconfig-verification.png)

---

### Active Directory Installation

Installed Active Directory Domain Services and promoted the server to a Domain Controller.

![AD DS Installation](screenshots/04-active-directory-install/01-ad-ds-installation.png)

![Domain Controller Promotion](screenshots/04-active-directory-install/03-domain-controller-promotion.png)

---

### Active Directory Management

Created and managed domain users, Organizational Units, and security-related administrative configurations.

![Active Directory Users and Computers](screenshots/05-ad-management/01-active-directory-users-and-computers.png)

![Organizational Unit Management](screenshots/05-ad-management/02-organizational-units-created.png)

---

### Domain Join and Authentication

Joined the Windows client workstation to the domain and validated domain authentication functionality.

![Domain Join](screenshots/08-domain-join-authentication/01-domain-join-success.png)

![Whoami Verification](screenshots/08-domain-join-authentication/03-whoami-domain-verification.png)
---

## Future Improvements

- Group Policy configuration
- Shared folder permissions
- PowerShell automation
- Security group management
- Additional client workstations
- Network segmentation
