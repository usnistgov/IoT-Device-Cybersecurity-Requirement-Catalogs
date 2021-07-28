---
layout: default
title: "Device Security"
category: "Technical"
tags: device security execution communication secure resource integrity memory process system utilize environment
navOrder: 7
navTitle: Device Security
permalink: /technical/security/
---

# Device Security
 
The capability to secure the IoT device to meet organizational requirements.
 
## Secure Execution
 
Ability to protect the execution of code on the device. Elements that may be necessary:

- Ability to enforce organizationally-defined execution policies.
  - Ability to execute code in confined virtual environments.
  - Ability to separate IoT device processes into separate execution domains.
- Ability to separate the levels of IoT device user functionality.
- Ability to authorize various levels of IoT device functionality.
 
## Secure Communication
 
Ability to securely initiate and terminate communications with other devices. Elements that may be necessary:

- Ability to enforce traffic flow policies.
- Ability to utilize standardized protocols.
- Ability to establish network connections.
- Ability to terminate network connections (e.g., automatically based on organizationally-defined parameters).
- Ability to de-allocate TCP/IP address/port pairings.
- Ability to establish communications channels.
- Ability to secure the communications channels.
- Ability to interface with DNS/DNSSEC.
- Ability to store and process session identifiers.
- Ability to identify and track sessions with identifiers.
 
## Secure Resource Usage
 
Ability to securely utilize system resources and memory. Elements that may be necessary:

- Ability to support shared system resources.
  - Ability to release resources back to the system.
  - Ability to separate user and process resources use.
- Ability to manage memory address space assigned to processes.
- Ability to enforce access to memory space through the kernel.
- Ability to prevent a process from accessing memory space of another process.
- Ability to enforce configured disk quotas.
- Ability to continue operation when associated networks are unavailable (e.g., a smart smoke detector must still go off when a fire occurs even if it is not attached to the associated network).
- Ability to provide sufficient resources to store and run the operating environment (e.g., operating systems, firmware, applications).
- Ability to utilize file compression technologies (e.g., to provide denial of service protection).
 
## Device Integrity
 
Ability to protect against unauthorized changes to hardware and software. Elements that may be necessary:

- Ability to perform security compliance checks on system components.
- Ability to detect unauthorized hardware and software components.
- Ability to take organizationally-defined actions when unauthorized hardware and software components are detected (e.g., disallow a flash drive to be connected even if a USB port is present).
- Ability to store the operating environment (e.g., firmware image, software, applications) in read-only media (e.g., Read Only Memory).
 
## Secure Device Operation
 
Ability to operate securely and safely. Elements that may be necessary:

- Ability to keep an accurate internal system time.
- Ability to define various operational states.
- Ability to support various modes of IoT device operation with more restrictive operational states.
  - "travel mode" for transit.
  - "safe mode" for operation when some or all network security is unavailable.
  - Others as determined necessary based on the purpose and goals for the IoT device.
- Ability to define differing failure types.
- Ability to fail in a secure state.
- Ability to disable operations and/or functionality in the event of security violations.
- Ability to restrict components/features of the IoT device (e.g., ports, functions, protocols, services, etc.) in accordance with organizationally-defined policies.
- Ability to sense the environment and securely (i.e., preserving confidentiality, integrity, and availability of the device and its data) interface with the environment, either directly or through the IoT system. Examples include:
  - Emergency shutoff mechanism
  - Emergency lighting mechanism
  - Fire protection mechanism
  - Temperature and humidity mechanism
  - Water damage protection mechanism
  - Manufacturer defined capability

