# Active Directory User Management Lab

## Overview

This project demonstrates common Tier 1 Help Desk and IT Support tasks performed in an enterprise Windows Server environment. The purpose of this lab was to practice Active Directory user account management, security group assignment, password policy configuration, and applying the principle of least privilege.

This lab was completed as part of my CompTIA A+ practical learning activities.

---

## Objectives

The objectives of this lab were:

- Create and configure new Active Directory user accounts
- Modify existing user account information
- Assign users to the correct security groups
- Manage department-based access permissions
- Apply password security policies
- Verify users do not have unnecessary administrative privileges

---

## Environment & Tools Used

**Operating System:**
- Windows Server Active Directory Environment

**Tools:**
- Server Manager
- Active Directory Users and Computers
- osTicket Help Desk Ticketing System

---

## Tasks Completed

### User Account Creation - Ash

- Created a new Active Directory user account for Ash
- Assigned the user to the Engineering department security group
- Added the account to:
  - `sec-glo-engineering`
- Placed the user in the NonAdmins Organizational Unit (OU)
- Enabled "User must change password at next logon"
- Verified the account did not have administrative privileges

---

### User Account Modification - Hunter

- Accessed Hunter's existing Active Directory account
- Reviewed current group memberships
- Removed the user from the Sales department group
- Added Hunter to:
  - `sec-glo-engineering`
- Updated account security settings
- Enabled password change requirement at next login
- Confirmed "Password never expires" was disabled
- Verified the account followed least-privilege principles

---

## Security Practices Applied

During this lab, the following security practices were implemented:

- **Least Privilege Access:** Users were only assigned permissions required for their department role.
- **Security Group Management:** Access was controlled through Active Directory security groups instead of individual permissions.
- **Password Policy Enforcement:** Users were required to create their own passwords after the initial account setup.
- **Account Organization:** Users were placed in the correct Organizational Unit for easier administration and management.

---

## Skills Demonstrated

This project demonstrates experience with:

- Active Directory administration
- Windows Server user management
- User onboarding and account changes
- Security group management
- Password policy configuration
- Help Desk ticket procedures
- Enterprise access control concepts

---

## Screenshots

Screenshots documenting the completed tasks are available in the `/Screenshots` folder.

---

## Author

**Italo Martins**

Aspiring IT Support / Cybersecurity Professional
