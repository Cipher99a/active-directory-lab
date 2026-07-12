# Module 03 – Windows Server Installation
## Server Role

Definition:

A server role is a primary function assigned to a Windows Server. Installing a role enables the server to provide specific services, such as Active Directory Domain Services (AD DS), DNS, DHCP, or File Services.

My own explanation:

A Windows Server is just an operating system after installation. A role gives the server a specific purpose within an enterprise environment.

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

My explanation: Adeskstop Experience is a Windows Setup that comes with a GUI, which makes the user experience much easier and more comfortable.

---

## Why Custom Installation?

My explanation: Custom Installation allows a clean installation. This means it allows the file system of our Windows Server to be downloaded to the empty VDI (virtual hard disk) of our virtual machine. On the other hand, an upgrade installation only updates the operating system already installed in a VDI.

---

## Why 4 GB RAM?

My explanation: The host computer has a total of 8GB of RAN, and we allocated 4GB to our Virtual Machine to prevent the host from running out of resources and becoming unresponsive. 

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


# Module Checklist

- [ ] Install Windows Server
- [ ] Log in as Administrator
- [ ] Understand Server Manager
- [ ] Update GitHub
- [ ] Pass Module Review
- [ ] 
