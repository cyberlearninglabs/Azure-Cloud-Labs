# Microsoft Entra ID & Identity Security Lab Portfolio  
**Willowmora Tenant**


## Overview

This repository demonstrates hands-on implementation of **identity and access management (IAM)** controls using **Microsoft Entra ID (Azure AD)** within a simulated enterprise tenant named **Willowmora**.

The labs focus on **least privilege**, **role-based access control (RBAC)**, **Conditional Access enforcement**, **delegated administration**, and **identity governance**—all core competencies for modern cloud security and security engineering roles.

Each lab reflects **real-world enterprise scenarios**, validated through direct testing rather than theory alone.

---

##  Objectives

Through this lab series, I demonstrated the ability to:

- Design and manage users, groups, and administrative roles  
- Enforce least privilege using RBAC and scoped role assignments  
- Validate permissions by testing allowed vs. denied actions  
- Implement self-service and delegated identity controls securely  
- Understand enterprise identity governance features such as Conditional Access and Privileged Identity Management (PIM)

---

##  Lab Modules

### **Lab 01 – Tenant & Identity Foundation**
**Focus:** Tenant setup, baseline identity configuration  

- Established the Willowmora Entra ID tenant  
- Verified identity management capabilities and portal access  
- Prepared the environment for enterprise IAM controls  

---

### **Lab 02 – User Creation & Role Assignment**
**Focus:** Core identity lifecycle management  

- Created users representing different organizational roles  
- Assigned directory roles based on job function  
- Verified role visibility and access boundaries  

---

### **Lab 03 – Conditional Access Enforcement**
**Focus:** Security policy enforcement and validation  

- Applied Conditional Access policies (e.g., MFA enforcement)  
- Tested sign-in behavior from user vs. admin perspectives  
- Verified policy impact through successful and blocked access attempts  

---

### **Lab 06 – Least Privilege Demo (Delegated Administration)**
**Focus:** RBAC validation through real permission testing  

- Created **Jade Windsor** as a User Administrator  
- Confirmed allowed actions (user management, password resets)  
- Attempted restricted actions (Conditional Access management)  
- Validated denial messages to prove enforced least privilege  

This lab demonstrates not just role assignment—but **proof of enforced boundaries**.

---

### **Lab 07 – Privileged Identity Management (PIM) Overview**
**Focus:** Identity governance & just-in-time access  

- Explored Microsoft Entra Privileged Identity Management (PIM)  
- Reviewed role eligibility, activation workflows, and auditing  
- Identified licensing requirements and enterprise governance use cases  

While PIM activation requires a Premium license, this lab demonstrates familiarity with **enterprise-grade identity governance design**.

---

### **Lab 08 – Identity & Access Policy Configuration**
**Focus:** Secure IAM design using groups and scoped administration  

- Created an **Operations Support Group** for delegated access  
- Configured **Self-Service Password Reset (SSPR)** for selected users  
- Assigned **Password Administrator** role using group-based RBAC  
- Demonstrated scoped administration via **Administrative Units (AU)**  
- Validated effective permissions for delegated users  

This module ties together IAM best practices for **secure delegation without Global Admin dependency**.

---

##  Key Skills Demonstrated

- Microsoft Entra ID (Azure AD)  
- Identity & Access Management (IAM)  
- Role-Based Access Control (RBAC)  
- Conditional Access & MFA enforcement  
- Delegated administration & least privilege  
- Identity governance & enterprise security design  

---

##  Why This Matters

Modern cloud environments are **identity-first**.  
These labs demonstrate not only how roles and policies are configured, but **how they behave under real access attempts**—a critical skill for reducing insider risk and enforcing zero-trust principles.

---

##  Next Steps

Future labs may expand into:

- Network security controls  
- Azure Firewall & NSG enforcement  
- End-to-end Zero Trust architecture  

---

##  Portfolio Note

All labs were performed manually in the Azure portal and validated through direct testing. Screenshots and reflections are included within each lab folder to document outcomes and security implications.
