---
layout: default
title: Logical Access to Interfaces
navOrder: 4
navTitle: Logical
permalink: /technical/logical/
---

# Logical Access to Interfaces

_See also the [non-technical counterpart to this section](../_Nontechnical/logical.md)_
{:latex-ignore="true"}

## Authentication and Identity Management

Ability to require authentication to the IoT device and to establish authentication and identification configuration and display requirements. Elements that may be necessary:

- Ability for the IoT device to support and require appropriate authentication.
  - Ability for the IoT device to require authentication prior to connecting to the device.
  - Ability for the IoT device to support a second, or more, authentication method(s) through an out of band path such as:
    - Temporary passwords or other one-use logon credentials
    - Third-party credential checks
    - Biometrics
    - Text messages
    - Hard Tokens
    - Manufacturer proprietary method
  - Ability for the IoT device to hide or mask authentication information during authentication process.
- Ability to set and change authentication configurations, policies and limitations settings for the IoT device.
  - Ability to set the time period for how long the device will remain locked after an established configurable limit of unsuccessful login attempts has been met.
  - Ability to disable or lock access to the device after an established pre-defined or user-configurable number of unsuccessful login authentication attempts.
  - Ability to display and/or report the previous date and time of the last successful login following successful login authentication.
  - Ability to automatically disable accounts for the IoT device after an establish period of inactivity.
    - Ability to support automatic logout of inactive accounts for the IoT device after a configurable established time period.
    - Ability to support automatic removal of temporary, emergency and other special use accounts from the IoT device after an established time period.
- Ability to display to IoT device users an organizationally-defined system use notification message or banner prior to successful IoT device authentication. (e.g., the message or banner would provide privacy and security notices consistent with applicable federal laws, Executive Orders, directives, policies, regulations, standards, and guidance).
  - Ability to create an organizationally-defined system use notification message or banner to be displayed on the IoT device.
    - Ability to edit an existing IoT device display.
    - Ability to establish the maximum size (in characters, bytes, etc.) of the available device display.
  - Ability to keep the notification message or banner on the device screen until the device user actively acknowledges and agrees to the usage conditions.
- Ability to restrict all unauthorized interactions.
  - Ability to identify authorized users and processes.
  - Ability to differentiate between authorized and unauthorized users (physical and remote).
- Ability to establish access to the IoT device to perform organizationally-defined user actions without identification or authentication.

## Role Support and Management

Ability to establish unique, privileged, organization-wide, and other types of IoT device user accounts. Elements that may be necessary:

- Ability to create unique IoT device user accounts.
- Ability to assign roles to IoT device user accounts.
- Ability to identify unique IoT device user accounts.
- Ability to support a hierarchy of logical access privileges for the IoT device based on roles (e.g., admin, emergency, user, local, temporary, etc.).
  - Ability to establish user accounts to support role-based logical access privileges.
  - Ability to administer user accounts to support role-based logical access privileges.
  - Ability to use organizationally-defined roles to define each user account's access and permitted device actions.
  - Ability to support multiple levels of user/process account functionality and roles for the IoT device.
- Ability to apply least privilege to user accounts (i.e., to ensure that the processes operate at privilege levels no higher than necessary to accomplish required functions).
  - Ability to create additional processes, roles (e.g., admin, emergency, temporary, etc.) and accounts as necessary to achieve least privilege.
  - Ability to apply least privilege settings within the device (i.e., to ensure that the processes operate at privilege levels no higher than necessary to accomplish required functions).
  - Ability to limit access to privileged device settings that are used to establish and administer authorization requirements.
  - Ability for authorized users to access privileged settings.
- Ability to support organizationally-defined actions for the IoT device.
  - Ability to create organizationally-defined accounts that support privileged roles with automated expiration conditions.
  - Ability to establish organizationally-defined user actions for accessing the IoT device and/or device interface.
  - Ability to enable automation and reporting of account management activities.
    - Ability to assign access to IoT device audit controls to specific roles or organizationally-defined personnel.
    - Ability to control access to IoT device audit data.
    - Ability to identify the user, process or device requesting access to the audit/accountability information (i.e., to ensure only authorized users and/or devices have access).
   - Ability to establish conditions for shared/group accounts on the IoT device.
   - Ability to administer conditions for shared/group accounts on the IoT device.
  - Ability to restrict the use of shared/group accounts on the IoT device according to organizationally-defined conditions.
- Ability to implement dynamic access control approaches (e.g., service-oriented architectures) that rely on:
  - run-time access control decisions facilitated by dynamic privilege management.
  - organizationally-defined actions to access/use device.
- Ability to allow information sharing capabilities based upon the type and/or role of user attempting to share the information.
- Ability to restrict access to IoT device software, hardware, and data based on user account roles, used with proper authentication of the identity of the user to determine type of authorization.

## Limitations on Device Usage

Ability to establish restrictions for how the device can be used. Elements that may be necessary:

- Ability to establish pre-defined restrictions for information searches within the device.
- Ability to establish limits on authorized concurrent device sessions for:
  - User accounts
  - Roles
  - Groups
  - Dates
  - Times
  - Locations
  - Manufacturer established parameters

## External Connections

Ability to support external connections. Elements that may be necessary:

- Ability to securely interact with authorized external, third-party systems.
- Ability to allow for the user/organization to establish the circumstances for when information sharing from the device and/or through the device interface will be allowed and prohibited.
- Ability to establish automated information sharing to approved identified parties/entities.
- Ability to identify when the external user's system meets the required security requirements for a connection.

## Interface Control

Ability to establish controls for the connections made to the IoT device. Elements that may be necessary:

- Ability to establish requirements for remote access to the IoT device and/or IoT device interface including:
  - Usage restrictions
  - Configuration requirements
  - Connection requirements
  - Manufacturer established requirement
- Ability to restrict use of IoT device components (e.g., ports, functions, protocols, services, microphones, video, etc.).
- Ability to restrict use of IoT device services.
- Ability to enforce the established local and remote access requirements.
- Ability to prevent external access to the IoT device management interface.
- Ability to control the IoT device's logical interface (e.g., locally or remotely).
- Ability to change IoT device logical interface(s).
- Ability to control device responses to device input.
- Ability to control output from the device.
- Ability to support communications technologies (including but not limited to):
  - 802.11x
  - Bluetooth
  - Ethernet
  - Manufacturer defined
- Ability to establish and configure IoT device settings for communications technologies including authentication protocols (e.g., EAP/TLS, PEAP).
