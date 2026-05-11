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

![Static IP Configuration](https://github.com/JamesStahler/active-directory-homelab/blob/main/screenshots/03-dc-networking/02-dc01-static-ip-dns-configuration.png)

![IP Configuration Verification](https://github.com/JamesStahler/active-directory-homelab/blob/main/screenshots/03-dc-networking/04-dc01-ipv4-properties.png)

---

### Active Directory Installation

Installed Active Directory Domain Services and promoted the server to a Domain Controller.

![AD DS Installation](https://github.com/JamesStahler/active-directory-homelab/blob/main/screenshots/04-active-directory-install/02-ad-ds-role-installation-progress.png)

![Domain Controller Promotion](https://github.com/JamesStahler/active-directory-homelab/blob/main/screenshots/04-active-directory-install/03-create-new-forest-homelab-local.png)

---

### Active Directory Management

Created and managed domain users, Organizational Units, and security-related administrative configurations.

![Active Directory Users and Computers](https://github.com/JamesStahler/active-directory-homelab/blob/main/screenshots/05-ad-management/03-creating-it-ou-users.png)

![Organizational Unit Management](https://github.com/JamesStahler/active-directory-homelab/blob/main/screenshots/05-ad-management/07-aduc-users-and-groups-view.png)

---

### Domain Join and Authentication

Joined the Windows client workstation to the domain and validated domain authentication functionality.

![Domain Join](https://github.com/JamesStahler/active-directory-homelab/blob/main/screenshots/08-domain-join-authentication/04-welcome-to-domain-confirmation.png)
![Whoami Verification](https://github.com/JamesStahler/active-directory-homelab/blob/main/screenshots/08-domain-join-authentication/06-whoami-domain-user-verification.png)
---

## Future Improvements

- Group Policy configuration
- Shared folder permissions
- PowerShell automation
- Security group management
- Additional client workstations
- Network segmentation
