# Lab 07 — Privileged Identity Management (PIM) Overview  
**Tenant:** Willowmora  
**Service:** Microsoft Entra ID  
**Focus:** Identity Governance / Least Privilege  

---

## Objective
Explore Microsoft Entra Privileged Identity Management (PIM) to understand how organizations manage **just-in-time (JIT)** privileged access to sensitive administrative roles.

This lab demonstrates where PIM is configured, how it is intended to be used in enterprise environments, and how it enforces the principle of least privilege.

---

## Overview
Microsoft Entra Privileged Identity Management (PIM) is an advanced identity governance feature designed to reduce risk from standing administrative privileges.

Instead of permanent admin access, PIM requires administrators to:
- Activate roles only when needed
- Use time-bound access
- Complete approval and MFA workflows
- Maintain detailed audit logs

This approach minimizes insider risk and strengthens security posture.

---

## Steps Performed

### Step 1: Accessed Privileged Identity Management
- Logged into the **Microsoft Entra Admin Center**
- Navigated to **Identity Governance → Privileged Identity Management (PIM)**

📸 **Screenshot 1:** PIM landing page in Willowmora tenant

---

### Step 2: Reviewed the PIM Quick Start Dashboard
- Opened the **Quick Start** section
- Reviewed core PIM capabilities:
  - **Assign** – Manage eligible role assignments
  - **Activate** – Just-in-time role activation
  - **Approve** – Approval workflows for elevation
  - **Audit** – Visibility into role usage and history

📸 **Screenshot 2:** PIM Quick Start dashboard showing Assign, Activate, Approve, and Audit

---

### Step 3: Attempted to View Roles and Assignments
- Navigated to **Roles** and **Assignments**
- Received a message indicating that **PIM requires a Premium (P2) license**

📸 **Screenshot 3:** Premium feature notice when accessing PIM role assignments

---

### Step 4: Supplemental Learning (Theory Validation)
Since role activation requires Entra ID P2 licensing, I reviewed:
- Microsoft Learn documentation
- Coursera identity governance modules

Key concepts reviewed:
- Eligible vs. permanent role assignments
- Time-bound activation windows
- MFA and approval requirements for elevation
- PIM audit logs and compliance tracking

---

## Learning Outcome
This lab provided hands-on exposure to enterprise identity governance by demonstrating:

- **Just-in-Time (JIT) access** reduces risk from standing admin privileges
- **Role eligibility vs. permanent access** enforces least privilege
- **Approval and MFA workflows** protect sensitive role elevation
- **Auditing and visibility** support compliance and investigations

Although PIM activation requires a Premium license, this exercise clearly demonstrates how large organizations secure privileged access in Microsoft Entra ID.

---

## Security Insight
Privileged Identity Management plays a critical role in:
- Reducing attack surface
- Limiting blast radius of compromised accounts
- Supporting Zero Trust and least privilege strategies

Understanding where PIM lives and how it operates is essential for cloud security and IAM roles.

---

## Portfolio Relevance
This lab complements earlier Willowmora identity labs by showing:
- Role-Based Access Control (RBAC)
- Delegated administration
- Conditional Access enforcement
- **Enterprise-grade privileged access governance with PIM**

Together, these labs demonstrate a full identity security lifecycle in Azure.
