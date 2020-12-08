---
layout: default
title: Data Protection
navOrder: 3
navTitle: Data Protection
permalink: /technical/protection/
---

# Data Protection

## Cryptography Capabilities and Support

Ability for the IoT device to use cryptography for data protection. Elements that may be necessary:

- Ability to utilize sufficient resources to employ cryptographic mechanisms.
- Ability to obtain and validate certificates.
- Ability to verify digital signatures.
- Ability to run hashing algorithms.
- Ability to compute and compare hashes.
- Ability to change keys securely.
- Ability to manage cryptographic keys securely.
  - Ability to generate key pairs.
  - Ability to store encryption keys securely.
  - Ability to change keys securely.

## Secure Storage

Ability for the IoT device, or tools used through the IoT device interface, to enable secure device storage. Elements that may be necessary:

- Ability to support encryption of data at rest.
  - Ability to cryptographically store passwords at rest, as well as other authentication data.
  - Ability to support data encryption and signing to prevent data from being altered in device storage.
- Ability to secure data in device storage.
  - Ability to secure data stored locally on the device.
  - Ability to secure data stored in remote storage areas (e.g., cloud, server, etc.).
  - Ability to utilize separate storage partitions for system and user data.
- Ability to "sanitize" or "purge" specific or all data within the device.


## Secure Transmission

Ability to secure data transmissions sent to and from the IoT device. Elements that may be necessary:

- Ability to configure the cryptographic algorithm to protect data in transit.
  - Ability to support trusted data exchange with a specified minimum strength cryptography algorithm.
  - Ability to support data encryption and signing to prevent data from being altered in transit.
- Ability to utilize one or more capabilities to protect the data it transmits from unauthorized access and modification.
- Ability to use cryptographic means to validate the integrity of data transmitted.

