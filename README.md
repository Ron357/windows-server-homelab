# Windows Server 2025 Home Lab

## Overview
Built a Windows Server 2025 domain controller from scratch in VirtualBox 
as part of an IAM and Security Operations learning curriculum.

## Environment
- Host: Lenovo Yoga Pro 9i
- Hypervisor: Oracle VirtualBox 7.2.6
- Guest OS: Windows Server 2025 Standard Evaluation (Desktop Experience)
- RAM allocated: 4GB
- Storage: 60GB virtual disk

## What Was Built
- Installed Windows Server 2025 in VirtualBox
- Configured static IP address (192.168.1.10)
- Renamed server to DC01
- Installed Active Directory Domain Services (AD DS) role
- Promoted server to Domain Controller
- Created domain: theronlab.local
- Configured DNS pointing to 127.0.0.1

## Key Commands Used
```powershell
Get-ADDomain
Get-ADDomainController
```

## Screenshots
See /screenshots folder

## Skills Demonstrated
- Windows Server administration
- Active Directory setup and promotion
- DNS configuration
- PowerShell verification commands
- VirtualBox virtualization
