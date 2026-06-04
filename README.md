# Ticketing System Lab

## Overview

This project simulates common IT help desk tasks using Spiceworks Help Desk and Active Directory. The goal was to gain hands-on experience with ticket management, troubleshooting, user administration, and documenting resolutions.

The lab was built to mirror real-world help desk workflows, including ticket creation, investigation, resolution, and closure.

## Technologies Used

- Spiceworks Help Desk
- Windows Server 2025
- Active Directory Domain Services (AD DS)
- Windows 11 Pro
- VMware Workstation

## Skills Demonstrated

- Ticket Lifecycle Management
- Active Directory Administration
- Password Resets
- User Account Creation
- Account Unlocks
- Shared Folder Permission Management
- Software Installation Support
- Troubleshooting and Documentation
- Customer Support Communication

## Objectives

- Simulate common IT support requests
- Practice documenting ticket investigations and resolutions
- Perform Active Directory administrative tasks
- Troubleshoot user access issues
- Follow a complete ticket lifecycle from creation to closure

## Ticket 1 – Password Reset

### Issue

A user reported that they were unable to access their domain account after experiencing login issues. The user requested assistance resetting their password and restoring access.

### Investigation

The ticket was reviewed and the user account was examined in Active Directory to verify account status and determine the appropriate corrective action.

### Resolution

The user's password was reset in Active Directory and the account was reviewed to confirm proper configuration. Access was successfully restored and the user was able to authenticate to the domain.

#### Ticket Creation

![Ticket Creation](screenshots/password-reset/01-ticket-creation-password-reset.png)

#### Open Ticket

![Open Ticket](screenshots/password-reset/02-ticket-open-password-reset.png)

#### Investigation

![Investigation](screenshots/password-reset/03-ticket-investigation-password-reset.png)

#### Password Reset in Active Directory

![Password Reset](screenshots/password-reset/04-ad-user-password-reset.png)

#### User Account Review

![User Account Review](screenshots/password-reset/05-user-account-review.png)

#### Resolution

![Resolution](screenshots/password-reset/06-ticket-resolution-password-reset.png)

#### Ticket Closure

![Ticket Closed](screenshots/password-reset/07-ticket-closed-password-reset.png)

## Ticket 2 – New User Account Creation

### Issue

A request was submitted to create a new domain account for a new employee. The user required access to domain resources and a workstation login account before beginning work.

### Investigation

The request was reviewed and the necessary account information was verified. Active Directory was used to create and configure the new user account.

### Resolution

A new Active Directory user account was created, assigned a temporary password, and enabled for use. The account was verified and made available for the employee's initial login.

#### Ticket Creation

![Ticket Creation](screenshots/new-user-account/01-ticket-creation-new-user-request.png)

#### Open Ticket

![Open Ticket](screenshots/new-user-account/02-ticket-open-new-user-request.png)

#### Investigation

![Investigation](screenshots/new-user-account/03-ticket-investigation-new-user.png)

#### Create User in Active Directory

![Create User](screenshots/new-user-account/04-ad-create-new-user.png)

#### New User Account Created

![New User Created](screenshots/new-user-account/05-ad-new-user-created.png)

#### Resolution

![Resolution](screenshots/new-user-account/06-ticket-resolution-new-user.png)

#### Ticket Closure

![Ticket Closed](screenshots/new-user-account/07-ticket-closed-new-user-request.png)

## Ticket 3 – Account Lockout

### Issue

A user reported that their account was repeatedly becoming locked and they were unable to access domain resources.

### Investigation

The ticket was reviewed and the user account was examined in Active Directory to verify account status and identify the cause of the lockout.

### Resolution

The account was reviewed, unlocked, and validated. The user was able to successfully authenticate after the update.

#### Ticket Creation

![Ticket Creation](screenshots/account-lockout/01-ticket-creation-account-lockout.png)

#### Open Ticket

![Open Ticket](screenshots/account-lockout/02-ticket-open-account-lockout.png)

#### Investigation

![Investigation](screenshots/account-lockout/03-ticket-investigation-account-lockout.png)

#### Active Directory Review

![AD Review](screenshots/account-lockout/04-ad-review-locked-account.png)

#### Resolution

![Resolution](screenshots/account-lockout/05-ticket-resolution-account-unlocked.png)

#### Ticket Closure

![Ticket Closed](screenshots/account-lockout/06-ticket-closed-account-lockout.png)

## Ticket 4 – Shared Folder Access

### Issue

A user reported being unable to access a shared folder used by their team. Other users were able to access the folder, but the affected user was receiving an error when attempting to view its contents.

### Investigation

The ticket was reviewed and the user's access permissions were examined. Shared folder permissions were verified to determine whether the user had the appropriate level of access.

### Resolution

Folder permissions were reviewed and updated as needed. Access was successfully verified, and the user was able to access the shared folder without further issues.

#### Ticket Creation

![Ticket Creation](screenshots/shared-folder-access/01-ticket-creation-shared-folder-access.png)

#### Open Ticket

![Open Ticket](screenshots/shared-folder-access/02-ticket-open-shared-folder-access.png)

#### Investigation

![Investigation](screenshots/shared-folder-access/03-ticket-investigation-shared-folder-access.png)

#### Shared Folder Permissions Review

![Permissions Review](screenshots/shared-folder-access/04-shared-folder-permissions-review.png)

#### Resolution

![Resolution](screenshots/shared-folder-access/05-ticket-resolution-shared-folder-access.png)

#### Ticket Closure

![Ticket Closed](screenshots/shared-folder-access/06-ticket-closed-shared-folder-access.png)

## Ticket 5 – Software Installation

### Issue

A user requested assistance installing software required for daily work tasks. The application was not currently available on the workstation and needed to be installed and verified.

### Investigation

The request was reviewed and the workstation was evaluated to ensure it met the requirements for the requested software. The installation process was then initiated and monitored for any issues.

### Resolution

The requested software was successfully installed and tested. The application launched correctly and was made available for the user to access.

#### Ticket Creation

![Ticket Creation](screenshots/software-installation/01-ticket-creation-software-installation.png)

#### Open Ticket

![Open Ticket](screenshots/software-installation/02-ticket-open-software-installation.png)

#### Investigation

![Investigation](screenshots/software-installation/03-ticket-investigation-software-installation.png)

#### Software Installation Process

![Installation Process](screenshots/software-installation/04-software-installation-process.png)

#### Software Installation Completed

![Installation Completed](screenshots/software-installation/05-software-installation-completed.png)

#### Resolution

![Resolution](screenshots/software-installation/06-ticket-resolution-software-installation.png)

#### Ticket Closure

![Ticket Closed](screenshots/software-installation/07-ticket-closed-software-installation.png)

## Summary / Lessons Learned

This project gave me hands-on experience working through the types of tickets that help desk technicians handle every day. Using Spiceworks and Active Directory, I practiced creating users, resetting passwords, unlocking accounts, reviewing folder permissions, and documenting software installations.

One thing I learned quickly is that solving the technical issue is only part of the job. Clear documentation and good troubleshooting habits are just as important. Working through each ticket helped me get more comfortable following a structured process from the initial request all the way through resolution and closure.

Overall, this lab helped me better understand how help desk teams support users, manage common IT issues, and keep accurate records of the work being performed.
