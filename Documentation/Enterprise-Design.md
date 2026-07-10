# Enterprise Design Document

# Project

Lukvic Technologies Enterprise Infrastructure

---

# Project Goal

The purpose of this project is to design, build, administer, troubleshoot, and document a Windows enterprise environment.

This project is intended to simulate a real company while developing the technical skills required for IT Support, Systems Administration, Endpoint Administration, and future Cybersecurity roles.

---

# Objectives

- Learn enterprise networking fundamentals
- Deploy Windows Server
- Install Active Directory
- Configure DNS
- Configure DHCP
- Configure Group Policy
- Manage users and computers
- Automate administrative tasks using PowerShell
- Document every stage of the project
- Build a professional GitHub portfolio

---

# Project Status

🟨 Planning Phase

# Company

Company Name

Lukvic Technologies

Industry

Technology Services

Departments

- Executive
- Information Technology (IT)
- Human Resources (HR)
- Finance
- Sales

Estimated Employees

25 

# Physical Infrastructure

## IT-ADMIN-01

Device

HP Laptop

Operating System

Windows 11 Home

Purpose

Primary administrator workstation and virtualization host.

---

## CLIENT-01

Device

Secondary Laptop

Operating System

To be installed

Purpose

Employee workstation used for testing authentication, Group Policy, and domain operations.

---

## LAB-HOST-01

Device

Desktop Computer

Operating System

Windows 10 Pro

Purpose

Expansion platform for advanced labs such as SIEM, additional servers, Linux, and future cybersecurity projects.

# Success Criteria

This project will be considered successful when I can:

- Deploy Windows Server.
- Install Active Directory.
- Configure DNS.
- Configure DHCP.
- Join a Windows client to the domain.

- # Virtual Infrastructure

| Hostname | Operating System | Role | Status |
|----------|------------------|------|--------|
| DC-01 | Windows Server 2022 | Domain Controller | Planned |
| CLIENT-VM-01 | Windows 11 Enterprise | Enterprise Client | Planned |

---

## DC-01 Responsibilities

- Active Directory Domain Services
- DNS
- User Authentication
- Group Policy
- Centralized Administration

---

## CLIENT-VM-01 Responsibilities

- Join the Active Directory domain
- Authenticate users
- Test Group Policy
- Test administrative tasks
- Create users and groups.
- Apply Group Policies.
- Troubleshoot common issues.
- Explain every technology used.
- Demonstrate the environment during an interview.
