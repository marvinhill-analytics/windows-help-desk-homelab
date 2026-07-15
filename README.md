# Windows Help Desk Homelab

This project documents eight simulated Windows 11 help desk tickets completed in a VirtualBox homelab environment. The project focuses on user support, Windows administration, troubleshooting, access control, and technical documentation.

## Lab Environment

- Oracle VirtualBox
- Windows 11 virtual machine
- HTSAdmin administrator account
- Standard local user accounts
- Windows Settings
- Computer Management
- Command Prompt
- Task Manager
- Services
- Event Viewer
- Microsoft Print to PDF

## Skills Practiced

- Creating and managing local user accounts
- Password configuration and account verification
- Standard-user and administrator access
- NTFS folder permissions
- Least-privilege access
- Approved software installation
- Windows IP configuration
- Network connectivity testing
- Printer and Print Spooler troubleshooting
- Event Viewer log analysis
- Kernel-Power Event ID 41 investigation
- New employee workstation setup
- Technical ticket documentation
- Root-cause and verification reporting

## Completed Tickets

### Ticket 001 — Local User Account Creation
Created a new Windows local user account, maintained standard-user privileges, and verified successful sign-in.

### Ticket 002 — Password Configuration
Configured and tested a user password while maintaining the account as a standard user.

### Ticket 003 — Shared-Folder Access
Reviewed and modified NTFS permissions to provide approved access and verify that unauthorized users were denied.

### Ticket 004 — Approved Software Installation
Installed approved software using administrator credentials and confirmed that it worked under a standard-user account.

### Ticket 005 — Unable to Access the Internet
Used `ipconfig`, loopback testing, external IP testing, DNS testing, and network-adapter review to identify and resolve a connectivity issue.

### Ticket 006 — Unable to Print
Investigated Windows printing, reviewed the Print Spooler service, restored the service, and verified successful printing with Microsoft Print to PDF.

### Ticket 007 — Unexpected System Restart Investigation
Used Event Viewer to filter System logs, identified Kernel-Power Event ID 41, reviewed detailed event data, and documented what the evidence confirmed and what remained inconclusive.

### Ticket 008 — New Employee Workstation Setup
Prepared a workstation for a new employee, configured the account, applied least-privilege folder access, and verified approved workstation functions.

## Documentation Format

Each ticket includes:

- Problem reported
- Business impact
- Manager approval
- Requested service
- Security requirements
- Steps performed
- Root cause or investigation conclusion
- Verification
- Resolution
- Final status
- Supporting screenshots

## Disclaimer

This is a simulated educational homelab project. All usernames, employees, departments, and business scenarios are fictional. No real organizational systems or confidential data are included.
