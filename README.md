# Entra ID IAM Lab — Cook Technologies

## Overview
This project simulates core identity and access management (IAM) operations for a fictional organization, **Cook Technologies**, using Microsoft Entra ID (formerly Azure Active Directory). It was built as a hands-on portfolio piece to demonstrate practical skills in user lifecycle management, group-based access control, and role assignment using the principle of least privilege.

**Goal:** Demonstrate working knowledge of fundamental identity administration tasks that align with entry-level IAM Analyst and Microsoft identity roles.

## Environment
- **Platform:** Microsoft Entra ID (Microsoft 365 Developer Program tenant)
- **Organization:** Cook Technologies (fictional sandbox tenant no real company data)
- **Reference:** Andy Malone MVP "Learn Microsoft Azure Active Directory in Just 30 Mins"

## What I Did

### 1. Tenant Setup
Created a Microsoft 365 Developer tenant to serve as an isolated sandbox for Cook Technologies, ensuring all work remained separate from any production or real organizational environment.

<img width="2560" height="1321" alt="Screenshot 2026-09-07 072440" src="https://github.com/user-attachments/assets/36fa1b7c-613d-49d3-9f92-6753d4a6c318" />


### 2. Navigating the Entra Admin Center
Explored the Entra admin center structure (Users, Groups, Roles, and Identity Protection) to build familiarity with where core identity functions are managed.

![Admin Center Overview] <img width="2560" height="1320" alt="Screenshot 2026-09-07 082128" src="https://github.com/user-attachments/assets/8cbe48ef-8d87-41d0-bca0-6d48b751c18d" />

### 3. User Account Creation & Management
Created multiple test user accounts representing different departments (e.g., Sales, Finance, IT) to simulate a realistic onboarding process.

<img width="2560" height="1321" alt="Screenshot 2026-09-07 092453" src="https://github.com/user-attachments/assets/2e9bde5b-bb90-45df-88ab-8003c0b2caf8" />

<img width="2560" height="1316" alt="Screenshot 2026-09-07 092402" src="https://github.com/user-attachments/assets/e7e27dc0-8825-467a-b8d0-8b001d4c5024" />

<img width="2560" height="1324" alt="Screenshot 2026-09-07 082313" src="https://github.com/user-attachments/assets/1fe49944-fedc-4de3-9bbf-ad43856dad81" />



### 4. Group-Based Access Control
Created security groups (e.g., "Finance-Team") and added users to them, applying group-based access rather than individual permission assignments — the scalable approach used in most enterprise environments.

<img width="2560" height="1320" alt="Screenshot 2026-09-07 085031" src="https://github.com/user-attachments/assets/7ccaf3f0-6a47-4749-b69e-6d7d5a156bea" />



### 5. Role Assignment (Least Privilege)
Assigned administrative roles (such as User Administrator) to a designated test account, deliberately avoiding broad Global Administrator rights in order to follow least-privilege principles.

<img width="2560" height="1316" alt="Screenshot 2026-09-07 090650" src="https://github.com/user-attachments/assets/325d0f71-6679-478b-9c4e-1efd3f6f5259" />

## Key Takeaways
- Practiced core identity lifecycle tasks: user creation, group management, and RBAC role assignment
- Applied the principle of least privilege when granting administrative access
- Built practical familiarity with the Entra admin center layout and navigation
- Documented the work in a structured format that mirrors real-world IAM change and audit documentation

## Next Steps
- Implement Conditional Access policies
- Configure Privileged Identity Management (PIM) for just-in-time admin access
- Explore hybrid identity by integrating an on-premises Active Directory lab via Entra Connect

---
*This is a personal training lab built for skill development. All users, groups, and data shown are fictional.*
