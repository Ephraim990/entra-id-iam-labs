# Entra ID IAM Lab — Cook Technologies

## Overview
This project simulates core identity and access management (IAM) operations for a fictional organization, **Cook Technologies**, using Microsoft Entra ID (formerly Azure Active Directory). It was built as a hands-on portfolio piece to demonstrate practical skills in user lifecycle management, group-based access control, and role assignment using the principle of least privilege.

**Goal:** Demonstrate working knowledge of fundamental identity administration tasks that align with entry-level IAM Analyst and Microsoft identity roles.

## Environment
- **Platform:** Microsoft Entra ID (Microsoft 365 Developer Program tenant)
- **Organization:** Cook Technologies (fictional sandbox tenant — no real company data)
- **Reference:** Andy Malone MVP — "Learn Microsoft Azure Active Directory in Just 30 Mins"

## What I Did

### 1. Tenant Setup
Created a Microsoft 365 Developer tenant to serve as an isolated sandbox for Cook Technologies, ensuring all work remained separate from any production or real organizational environment.

![Tenant Overview](screenshots/01-tenant-overview.png)

### 2. Navigating the Entra Admin Center
Explored the Entra admin center structure (Users, Groups, Roles, and Identity Protection) to build familiarity with where core identity functions are managed.

![Admin Center Overview](screenshots/02-admin-center-overview.png)

### 3. User Account Creation & Management
Created multiple test user accounts representing different departments (e.g., Sales, Finance, IT) to simulate a realistic onboarding process.

![Create User Form](screenshots/03-create-user-form.png)
![User List](screenshots/04-user-list.png)

### 4. Group-Based Access Control
Created security groups (e.g., "Finance-Team") and added users to them, applying group-based access rather than individual permission assignments — the scalable approach used in most enterprise environments.

![Security Group](screenshots/05-security-group.png)

### 5. Role Assignment (Least Privilege)
Assigned administrative roles (such as User Administrator) to a designated test account, deliberately avoiding broad Global Administrator rights in order to follow least-privilege principles.

![Assigned Roles](screenshots/06-assigned-roles.png)

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
