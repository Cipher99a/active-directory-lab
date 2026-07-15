# Lab 01 - Deploying the First Active Directory Domain Controller

## Objective

Deploy Windows Server 2022 in Oracle VirtualBox and promote it to the first Domain Controller of a new Active Directory forest.

---

## Environment

- Hypervisor: Oracle VirtualBox
- Guest OS: Windows Server 2022 Standard Evaluation
- Host RAM: 8 GB
- VM RAM: 4 GB
- CPU: 2 vCPUs
- Virtual Disk: 81.5 GB (VDI)

---

## Architecture

Host Computer

↓

Oracle VirtualBox

↓

Windows Server 2022

↓

Active Directory Domain Services

↓

Domain Controller

↓

lukvic.local

---

## Concepts Learned

- Hypervisor
- Virtual Machine
- ISO Image
- Virtual Disk Image (VDI)
- Active Directory Domain Services (AD DS)
- Domain Controller
- Forest
- Domain
- NetBIOS
- DNS
- NTDS Database
- SYSVOL
- DSRM
- Forest Functional Level
- Domain Functional Level
- Global Catalog

---

## Key Takeaways

### Hypervisor

A hypervisor enables virtualization by allowing multiple virtual machines to share the physical resources of the host computer.

### ISO Image

The ISO file is installation media containing the operating system files. After installation, the virtual machine boots from its virtual hard disk (VDI), not from the ISO.

### NTDS

The `ntds.dit` database stores:

- Users
- Groups
- Computer Accounts
- Organizational Units
- Password Hashes

### SYSVOL

SYSVOL stores shared domain files such as:

- Group Policies
- Logon Scripts
- Startup Scripts

### DNS

Active Directory depends on DNS because clients must locate a Domain Controller before authentication can occur.

DNS resolves the Domain Controller's hostname into an IP address.

---

## Lessons Learned

- A Domain Controller is different from an Active Directory domain.
- NetBIOS is the short name of the domain.
- DNS is essential for Active Directory.
- NTDS stores directory information.
- SYSVOL stores shared files and Group Policy data.
- Domain Controllers should use static IP addresses in production environments.

---

## Result

Successfully promoted Windows Server 2022 into the first Domain Controller of the `lukvic.local` Active Directory forest.
