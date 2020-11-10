---
layout: default
title: Cybersecurity Event Awareness
navOrder: 6
navTitle: Event
permalink: /technical/event/
---

# Cybersecurity Event Awareness

_See also the [non-technical counterpart to this section](../_Nontechnical/event.md)_
{:latex-ignore="true"}

## Access to Event Information

Ability to access IoT device state information. Elements that may be necessary:

- Ability to access information about the IoT device&#39;s cybersecurity state and other necessary data (e.g., trustworthy time).
- Ability to preserve system state information.

## Event Identification and Monitoring

Ability to provide event identification and monitoring capabilities and/or support event identification and monitoring tools interfacing with the device. Elements that may be necessary:

- Ability to identify organizationally-defined cybersecurity events (e.g., expected state change) that may occur on or involving the IoT device.
- Ability to monitor for organizationally-defined cybersecurity events (e.g., expected state change) that may occur on or involving the IoT device.
- Ability to support a list of events that are necessary for auditing purposes (to support the organizational auditing policy).
- Ability to identify unique users interacting with the device (to allow for user session monitoring).
- Ability to support a monitoring process to check for disclosure of organizational information to unauthorized entities. (The device may be able to perform this check itself or provide the information necessary for an external process to check).
- Ability to monitor communications traffic.
- Ability to detect remote activation attempts.
- Ability to detect remote activation of a collaborative computing device/component (e.g., microphone, camera, etc.).
- Ability to detect remote activation of sensors.
- Ability to define the characteristics of unapproved content.
- Ability to scan files for unapproved content.

## Event Response

The device can respond to organizationally-defined cybersecurity events in an organizationally-defined way. Elements that may be necessary:

  - Ability to generate alerts for specific events (e.g., capacity thresholds).
  - Ability to respond to alerts according to predefined responses (e.g., such as those dictated by the auditing policies of the organization).
  - Ability to alert connected information systems of potential issues found during the auditing process.
  - Ability to provide information to an external process that will issue auditing process alerts.
  - Ability to notify users of activation of a collaborative computing device.
  - Ability to provide a physical indicator of sensor use.
  - Ability to respond following an auditing failure (either by the device or an external auditing process that interacts with the device).
  - Ability to prevent download of unapproved content.
  - Ability to delete unapproved content.
  - Ability to support alternative security mechanisms when primary mechanisms (e.g., login protocol, encryption, etc.) are compromised.

## Audit Support

Ability for the device, or an interfaced system, to generate, store, retain, delete, and report on specific device audit events, to run specific audit checks, and report findings in a variety of ways. Elements that may be necessary:

- The device can generate audit logs for defined events
  - Ability to identify and capture organizationally-defined events using a persistent method.
  - Ability to capture information related to organizationally-specified cybersecurity events (e.g., cybersecurity state, timestamp) through organizationally-defined means (e.g., logs).
  - Ability to create audit logs within the device for organizationally-defined and auditable events (e.g. account creation, modification, enabling, disabling, removal actions and notifications).
- The device can capture required information in audit logs
  - Ability to track users interacting with the device, the time they interacted with the device, the time the user logged out of the device, and to list this information in an audit log.
   - Ability to log information pertaining to:
      - The type of event that occurred
      - The time that the event occurred
      - Where the event occurred
      - The source of the event
      - The outcome of the event
      - Identity of users/processes associated with the event
  - Ability to support auditing of configuration actions.
  - Ability to provide information as to why the device captured a particular event or set of events.
  - Ability to capture organizationally-defined information to support examination of security incidents.
  - Ability to record stored data access and usage.
- Ability to maintain audit logs in accordance with organizational policy.
  - Ability to comply with organizational policy for storing persistent audit logs up to a predefined size.
  - Ability to comply with organizational policy for audit log retention period (i.e., the required time to keep the audit logs).
  - Ability to delete audit logs in accordance with organizational policy.
  - Ability to send alerts that the logs are too big for the device to continue to store (if the predefined amount of time has not yet passed to delete them).
- Ability to use timestamps to record the time an auditing event occurred.
  - Ability to support organizationally-defined granularity in device timing measurements.
  - Ability to use synchronization with a verified time source to determine the validity of a timestamp.
  - Ability to record timestamps that can be translated to Coordinated Universal Time (UTC) or Greenwich Mean Time (GMT) to support a standardized representation of timing.
  - Ability to log timing measurements that stray beyond a set threshold value (e.g., enabling alerts if the device's system time is too far out of sync to be reliable).
- Ability to report on its cybersecurity state.
- Ability to support a self-audit generation process.
- Ability to run audit scans (automated or otherwise) to provide specific information (e.g., such as that requested for an external process to audit the device).
- Ability to send requested audit logs to an external audit process or information system (e.g., where its auditing information can be checked to allow for review, analysis, and reporting.).
- Ability to support an alternate auditing process in the event that the primary auditing process fails.
- Ability to protect the audit information through the use of:
  - Encryption
  - Digitally signing audit files
  - Securely sending audit files to another device
  - Other protections created by the device manufacturer
