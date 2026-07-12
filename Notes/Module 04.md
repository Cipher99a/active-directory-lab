## Active Directory Family

### Active Directory Domain Services (AD DS)

Purpose:

Provides centralized authentication, authorization, and identity management for users, computers, and groups within a Windows domain.

---

### Active Directory Certificate Services (AD CS)

Purpose:

Provides digital certificates and public key infrastructure (PKI).

---

### Active Directory Federation Services (AD FS)

Purpose:

Provides Single Sign-On (SSO) for applications and external services.

---

### Active Directory Lightweight Directory Services (AD LDS)

Purpose:

Provides directory services without requiring a Windows domain.
## Dependencies

### Definition

A dependency is a software component or feature that another application or server role requires to function correctly.

### My Own Explanation

When installing a server role, Windows may automatically require additional features or management tools. These dependencies ensure the role can be configured, managed, and maintained properly after installation.

---

## Management Tools

### Definition

Administrative tools that allow administrators to configure, monitor, and troubleshoot Windows Server roles.

### Examples

- Active Directory Administrative Center
- AD DS Snap-ins
- Active Directory Module for Windows PowerShell
## Why Active Directory Requires DNS

### Definition

Active Directory depends on DNS to locate Domain Controllers and other domain services.

### My Own Explanation

When a client computer wants to authenticate to the domain, it first uses DNS to locate a Domain Controller. Without DNS, clients would not know where to send authentication requests, so Active Directory would not function correctly.

---

## High Availability

### Definition

High availability is the practice of deploying multiple servers that provide the same service so that if one server fails, another can continue operating.

### My Own Explanation

Organizations usually deploy at least two Domain Controllers so users can continue logging in even if one Domain Controller fails.
  
