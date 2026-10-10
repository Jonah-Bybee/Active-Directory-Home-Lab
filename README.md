# Active Directory Home Lab

## Overview

This is my ongoing lab for practicing Windows administration and cybersecurity in an Active Directory environment. I’m using it to work with user accounts, groups, permissions, networking, and policies, and to understand how these configurations affect access and security.

The initial setup is complete. As I expand the lab, I’ll document individual exercises with configuration details, screenshots, and testing results.

## Lab Environment

- **Virtualization:** Oracle VirtualBox
- **Domain controller:** Windows Server 2022
- **Client:** Domain-joined Windows 10 Pro endpoint
- **Domain:** `mydomain.com`
- **Services:** Active Directory Domain Services, DNS, DHCP, and Routing and Remote Access
- **Tools:** PowerShell and Windows administration consoles

## Project Sections

| Folder | Description | Status |
| --- | --- | --- |
| [Active Directory Setup](./Active%20Directory%20Setup/) | Building the domain, configuring networking and server roles, creating users, and validating client connectivity and domain sign-in | Complete |
| Active Directory Exercises | Administration and cybersecurity exercises, with a separate folder and README for each exercise | Planned |

## Planned Exercises

- **User and group management:** Create accounts, organize organizational units, manage group membership, reset passwords, unlock accounts, and practice offboarding.
- **Permissions and access control:** Configure shared folders and NTFS permissions, assign access through groups, and test allowed and denied access.
- **Group Policy:** Apply user and computer settings, explore policy scope and inheritance, and verify the results on the client.
- **Delegated administration:** Assign specific administrative permissions and test what delegated accounts can and cannot do.
- **Security configuration:** Practice password policies, account lockout settings, and Windows audit policies.
- **Windows event logs:** Review failed sign-ins, account lockouts, and account or group changes using activity generated in the lab.
- **PowerShell automation:** Automate account and group management tasks and verify the changes.
- **Troubleshooting:** Investigate sign-in, DNS, connectivity, permissions, and policy application issues.

## Documentation Approach

Each exercise will explain what I configured, why I made the change, and how I tested it. I’ll include relevant screenshots or command output and document problems and fixes when they add useful context.

For access control exercises, I’ll test both successful access and expected restrictions using different accounts.

## Current Progress

**Completed:** Initial domain setup, networking, DHCP, bulk user provisioning, client domain join, and domain-account sign-in validation.

**Next:** User and group management, followed by shared-folder permissions and access testing.
