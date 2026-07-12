# Module 03 – Windows Server Installation

## Status

🟨 In Progress

---

# Objective

Install Windows Server 2022 on DC-01 and understand every step of the installation process.

---

# Learning Outcomes

By the end of this module, I should be able to:

- Explain what an ISO image is.
- Explain the purpose of a virtual hard disk (VDI).
- Explain the difference between Upgrade and Custom installation.
- Explain why Windows boots from the VDI after installation.
- Explain the purpose of the Administrator account.
- Explain why Server Manager opens automatically.

---

# Engineering Decisions

## Why Desktop Experience?

My explanation:

---

## Why Custom Installation?

My explanation:

---

## Why 4 GB RAM?

My explanation:

---

## Why 2 vCPUs?

My explanation:

---

## Why Dynamic Disk?

My explanation:

---

# Concepts Learned

## ISO Image

Definition:

My own explanation:

---

## Virtual Hard Disk (VDI)

Definition:

My own explanation:

---

## Windows Setup

Definition:

My own explanation:

---

## Administrator Account

Definition:

My own explanation:

---

## Server Manager

Definition:

My own explanation:

---

# Questions I Answered

- Why doesn't deleting the ISO break Windows?
- Why would deleting the VDI destroy the server?
- Why does Windows Server require a strong Administrator password?
- Why does Server Manager open automatically?

---

# Lessons Learned

(To complete after finishing the module.)

---

# Commands Learned

(None yet)

---
## Installation Type

### Role-based or feature-based installation

Definition:

Allows administrators to install Windows Server roles and features, such as Active Directory Domain Services (AD DS), DNS, DHCP, File Services, and Hyper-V.

My own explanation:

This option is used when we want to assign a specific job to a Windows Server. In our lab, we selected it because DC-01 will become the Domain Controller for Lukvic Technologies.

---

### Remote Desktop Services Installation

Definition:

Installs the services required to provide centralized remote desktops and applications to users.

My own explanation:

This option is used when the server's main purpose is to host remote desktop sessions for users rather than providing infrastructure services like Active Directory.

# Module Checklist

- [ ] Install Windows Server
- [ ] Log in as Administrator
- [ ] Understand Server Manager
- [ ] Update GitHub
- [ ] Pass Module Review
