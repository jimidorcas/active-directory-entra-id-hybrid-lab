# Active Directory and Microsoft Entra ID Hybrid Identity Lab

## Project Overview

This project demonstrates a hands-on lab for connecting an on-premises Active Directory environment running on Windows Server with Microsoft Entra ID using **Microsoft Entra Cloud Sync**.

The lab focused on configuring the directory environment, setting up synchronisation, and verifying that a user created in the on-premises environment appeared in Microsoft Entra ID.

## Objectives

- Set up a Windows Server virtual machine for an Active Directory lab.
- Configure an on-premises Active Directory environment.
- Create and configure a Microsoft Entra ID environment.
- Configure directory synchronisation using Microsoft Entra Cloud Sync.
- Verify that a synchronised user appeared in Microsoft Entra ID.
- Document the configuration and verification process.

## Lab Environment

| Component | Configuration |
|---|---|
| Virtualisation platform | [Fusion] |
| Server operating system | Windows Server [2025] |
| On-premises directory | Active Directory Domain Services |
| Cloud identity platform | Microsoft Entra ID |
| Synchronisation method | Microsoft Entra Cloud Sync |
| Verification | Confirmed a synchronised user appeared in Microsoft Entra ID |

## Implementation

### 1. Windows Server and Active Directory

Set up a Windows Server virtual machine and configured the on-premises Active Directory environment.

*See the screenshots in the `screenshots/` directory.

### 2. Microsoft Entra ID

Created a Microsoft Entra ID environment to serve as the cloud directory for the hybrid identity lab.

### 3. Microsoft Entra Cloud Sync

Configured Microsoft Entra Cloud Sync to connect the on-premises directory with Microsoft Entra ID.

### 4. Synchronisation Verification

Verified that a user from the on-premises directory appeared in Microsoft Entra ID after synchronisation.

This provided evidence that the configured synchronisation process was working for the tested user.

## Skills Demonstrated

- Windows Server fundamentals
- Active Directory Domain Services
- Microsoft Entra ID fundamentals
- Microsoft Entra Cloud Sync
- Hybrid identity concepts
- User and directory management
- Configuration troubleshooting and technical documentation

## Evidence

The `screenshots/` directory contains supporting evidence of the lab setup, configuration and synchronisation verification.


## Learning Outcomes

This lab provided practical exposure to the relationship between an on-premises directory and a cloud identity platform. It also reinforced the importance of verifying synchronisation rather than assuming that a configuration has succeeded.
