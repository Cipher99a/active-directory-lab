# Module 01 – Enterprise Networking Fundamentals

## Status
🟨 In Progress

---

# Objective

Understand why organizations use Active Directory and centralized identity management.

---

# Learning Outcomes

By the end of this module I should be able to:

- Explain what a server is.
- Explain what a client is.
- Explain what a domain is.
- Explain why organizations use Active Directory.
- Explain the purpose of a Domain Controller.

---

# Concepts Learned

## Server

Definition: A server is a computer or virtual machine that provides resources or services to other computers over a network.

Examples:
1. file server
2. domaine contorler
3. Web sever
4. Print server 

My own explanation: 

---

## Client

Definition: A client is a computer that requests resources or services from a server.

Examples:
1. Printer
2. Computer/Laptop
3. Smartphone

My own explanation:

---

## Domain

Definition: A domain is a logical group of users, devices, servers, and other network resources that are centrally managed by the same security policies and database.
Examples:

My own explanation:

---

## Domain Controller

Definition: Is a windows server that mananges auhentication, authorizatio, users, computers and security policies within active directory domain.

Responsibilities:
- Authenticate users
- Authorize access
- Store user accounts
- Manage computers
- Apply Group Policies

My own explanation:

---

# Enterprise Scenario

Company:

Lukvic Technologies

Departments:

- IT
- HR
- Finance
- Sales

Questions answered during this module:

✔ Why can't every computer manage itself?

✔ How are users managed?

✔ How are employees onboarded?

✔ How are employees offboarded?

---

# Interview Questions

Question 1 Security & Compliance: Without central management, the IT department can't ensure that every computer has the latest security patches, firewalls active, or antivirus software running. One unpatched computer can compromise the entire corporate network.

Consistency: IT needs to push out software updates, configure Wi-Fi profiles, and enforce password policies uniformly across the Finance, Sales, and other departments.

Efficiency: Standardizing configurations means a small IT team can manage hundreds or thousands of devices using centralized tools (like MDM - Mobile Device Management) rather than manually fixing every single machine.

Question 2
Identity as a Key: Every employee gets a single corporate identity (username/password).

Role-Based Access Control (RBAC): Access is granted based on the department. For example, a Finance employee will automatically have access to payroll systems, while a Sales employee will get access to the CRM (Customer Relationship Management) tool, but neither can see internal HR files.

Single Sign-On (SSO): This identity allows employees to log into all their authorized apps securely without needing dozens of different passwords.

Question 3
Onboarding is a cross-departmental choreography that transforms a candidate into a productive employee.

HR finalizes the contract, collects personal details, and triggers the onboarding workflow.

Finance sets up the new hire in the payroll system and establishes their tax and benefit profiles.

IT provisions the user account in the IAM system, assigns them to their departmental groups, and prepares their physical hardware (laptop, phone) shipped out with pre-configured security profiles.

Sales / Department Leads provide the specific training and team-specific tool access on day one.

Question 4
Offboarding is the reverse choreography, with an absolute focus on security and asset recovery.

HR notifies IT and Finance of the employee’s departure date and handles the exit interview.

IT immediately revokes access to the corporate identity/IAM system the moment the offboarding window hits. This instantly cuts off access to email, cloud storage, and SaaS apps to prevent data exfiltration.

Finance processes the final paycheck, calculates remaining PTO, and closes out expense accounts.

IT / Operations manages the return of company property (laptops, keys, security tokens) and securely wipes or reimages the machine for the next user.
---

# Commands Learned

(None yet)

---

# Lessons Learned

(To complete after the module.)

---

# Questions I Still Have

(To complete during the module.)

---

# Module Checklist

- [ ] Understand Server
- [ ] Understand Client
- [ ] Understand Domain
- [ ] Understand Domain Controller
- [ ] Explain Active Directory
- [ ] Complete Lab
- [ ] Update GitHub
- [ ] Pass Module Review

# Virtual Infrastructure

## DC-01

### Operating System
Windows Server 2022

### Role
Primary Domain Controller

### Responsibilities

- Active Directory Domain Services (AD DS)
- DNS Server
- User Authentication
- Group Policy Management
- Centralized Administration

### Status

🟨 Planned

---

## CLIENT-VM-01

### Operating System

Windows 11 Enterprise

### Role

Enterprise Employee Workstation

### Responsibilities

- Join the Active Directory domain
- Authenticate users
- Test Group Policies
- Test administrative tasks

### Status

🟨 Planned

# Naming Standards

## Physical Devices

| Hostname | Purpose |
|----------|---------|
| IT-ADMIN-01 | Primary Administrator Workstation |
| CLIENT-01 | Employee Workstation |
| LAB-HOST-01 | Expansion Host |

---

## Virtual Machines

| Hostname | Role |
|----------|------|
| DC-01 | Domain Controller |
| CLIENT-VM-01 | Enterprise Client |

---

## User Accounts

Format

firstname.lastname

Examples

- alice.johnson
- john.smith
- emily.davis

---

## Security Groups

- IT_Admins
- Finance_Users
- HR_Users
- Sales_Users

---

## Organizational Units (Future)

- IT
- HR
- Finance
- Sales
- Workstations
- Servers
