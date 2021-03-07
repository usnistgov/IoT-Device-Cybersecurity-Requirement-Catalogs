**Updated IoT Cybersecurity**

**Manufacturers and Supporting Entities**

**Non-Technical Supporting Capabilities**

**Introduction**

Non-technical supporting capabilities include the actions manufacturers
or their supporting entities take in support of initial and on-going
security of IoT devices. Such actions make it easier for customers to
understand and identify how IoT devices are built to meet their
cybersecurity needs, as well as the manufacturers' goals for how the IoT
device should be securely used. The non-technical cybersecurity
capabilities described can support cybersecurity-related customer
efforts. By making customers more knowledgeable about how to secure the
IoT devices, and how to most effectively use the device's cybersecurity
capabilities, manufacturers can help reduce the number of occurrences
and related severity of IoT device compromises, thwart attacks against
the devices, and reduce the number of vulnerabilities that are exploited
and lead to compromised devices.

The purpose of this catalog is to help IoT device manufacturers and
their supporting entities (contractors, supply chain vendors, etc.) to
identify non-technical IoT cybersecurity capability actions they can use
to better support their customers' cybersecurity needs and goals for
understanding, identifying and managing cybersecurity and privacy risks
associated with the use of the manufacturer's IoT device. Such actions
can include using communications, documentation, training and other
activities throughout the full lifecycle of an individual IoT device.

The actions found within this catalog provides a wide range of
non-technical cybersecurity actions that can be used to support a
manufacturer's goals and intended uses of each of IoT device, and to
meet the expectations and needs of the IoT device customers, to help
them to use the device in a way that supports their risk management
requirements. Because this is a catalog of actions, it is not expected
that a manufacturer would use all the actions within this catalog.

Manufacturers, and their supporting entities, can determine which of the
non-technical actions are applicable to each IoT device. This can be
accomplished by taking into consideration:

1)  the goal of the IoT device;

2)  the technical capabilities of the IoT device;

3)  the expectations for the intended uses of the IoT device;

4)  the types of uses for the IoT device that are not intended;

5)  the IoT device customer's purpose for using the IoT device;

6)  the expected context within which the IoT device is meant to be
    > used;

7)  the data that is generated, derived, collected, generated, stored,
    > disseminated and otherwise used;

8)  the expected security actions that the IoT device customer will be
    > responsible for performing;

9)  the actions the manufacturer will commit to performing; and

10) the associated risks that the IoT device brings into the system
    > where it will be used by each IoT device customer.

Manufacturers can then provide the most useful communications and
education to their customers for each associated device. Manufacturers
should consider that risks may vary greatly from one IoT customer to the
next, so the non-technical communications and actions they take and
provide to IoT device customers will be an important aspect of security
for each IoT device.

Cybersecurity and privacy risks for an IoT device cannot all be
addressed within the IoT device itself. Every IoT device operates within
a broader IoT environment where it interacts with other IoT and non-IoT
devices, cloud-based services, people, and other components. IoT device
customers need to understand the assumptions and expectations under
which the manufacturer created the IoT device that they are considering
purchasing. Then after purchase, IoT device customers need to be
provided with communications, education and actions that will help them
to understand how to securely use and maintain the IoT device. Such
understanding will allow the IoT customer to more knowledgeably
determine the risks of using the IoT device within their system (risks
that the manufacturer may not have even thought about when engineering
the device) and establish the associated technical abilities and
non-technical actions.

NIST created the NISTIR 8259 series of IoT cybersecurity guidance
documents, and the associated SP 800-213 document, to meet the needs of
the federal agencies, and to provide the manufacturers creating the IoT
devices with guidance and information describing the cybersecurity
requirements that need to be established and maintained for IoT devices
used within federal agencies.

For assistance in determining risks created by IoT devices,
manufacturers and their supporting entities can use the following NIST
resources. These are also some of the documents which federal agencies
use for determining risks within their systems and can inform
manufacturers' actions for identifying the general kinds of risks the
IoT device customers consider:

-   FIPS 200: Minimum Security Requirements for Federal Information and
    Information Systems

-   NIST Special Publication 800-53 Revision 5: Security and Privacy
    Controls for Information Systems and Organizations

-   Framework for Improving Critical Infrastructure Cybersecurity (often
    referenced as the Cybersecurity Framework, or CSF)

-   Draft NISTIR 8286A: Identifying and Estimating Cybersecurity Risk
    for Enterprise Risk Management (ERM)

-   NIST SP 800-161: Supply Chain Risk Management

The IoT Cybersecurity Manufacturer Non-Technical Supporting Capabilities
catalog is structured as follows:

> **A. Documentation from the Manufacturer**
>
> **1.** **Document assumptions made during the development process and
> other expectations related to the IoT device.**
>
> **2. Document the cybersecurity capabilities, such as those detailed
> within NISTIR 8259A and within the full IoT cybersecurity technical
> catalog, that are implemented within the IoT device, and how to
> configure and use them.**
>
> **3.Document design and support considerations related to the IoT
> device.**
>
> **4.Document maintenance requirements for the IoT device**.
>
> **B.** **Manufacturer Information and Query Reception**
>
> **1.The ability for the manufacturer and/or supporting entity to
> receive maintenance and vulnerability information (e.g., bug reporting
> capabilities, bug bounty programs) from their customers and other
> types of entities.**
>
> **2.The ability for the manufacturer and/or supporting entity to
> respond to customer and third-party queries about cybersecurity of the
> IoT device (e.g., customer support).**
>
> **C. Information Dissemination -- From the Manufacturer and/or
> Supporting Entity**
>
> **1.The procedures to support the ability for the manufacturer and/or
> supporting entity to alert customers of the IoT device about
> cybersecurity relevant information.**
>
> **2.The procedures to support the ability for the manufacturer and/or
> supporting entity to notify customers of cybersecurity related events
> and information related to an IoT device throughout the support
> lifecycle.**
>
> **D. Education and Awareness from Manufacturers/Supporting Entities**
>
> **1.Educate customers of the IoT device about the presence and use of
> device cybersecurity capabilities.**
>
> **2.Make customers aware of their cybersecurity responsibilities
> related to the IoT device and how responsibilities may be shared
> between them and others, such as the IoT device manufacturer.**
>
> **3.Make customers aware of key assumptions and expectations related
> to the cybersecurity of the IoT device.**
>
> **4.Educate customers about how to back-up the data collected from or
> derived by the IoT device, and how to access such data that is stored
> in cloud storage, or other repositories.**
>
> **5.Educate customers about vulnerability management options for the
> IoT device or associated system available to be used by customers.**
>
> **6.Educate customers about how an IoT device can be securely
> reprovisioned or disposed of.**

**\
**

A.  **Documentation from the Manufacturer**

> **The ability for the manufacturer and/or the manufacturer's
> supporting entity, to create, gather, disseminate, and store
> information relevant to cybersecurity of the IoT device prior to
> customer purchase, and throughout the development of a device and its
> subsequent lifecycle.**
>
> Documentation of cybersecurity information helps potential IoT device
> customers to make informed purchase decisions that support their
> organization's cybersecurity requirements for IoT devices and/or
> systems where they are used. Documentation of important cybersecurity
> information also then helps enable secure use of the IoT device by
> customers after the purchase since it serves as the source of
> information for customers.
>
> Documentation is also important to support legal requirements
> (regulatory, contractual, web site security and privacy policies,
> etc.), for audits or other certifications that some customers may
> require for the IoT devices they use, and/or to support due diligence
> activities. Documentation about maintenance requirements, especially
> regarding the supporting entities contracted by the manufacturer to
> perform maintenance, device changes, and other activities, also
> supports the customer's need to adequately plan for maintenance
> activities.
>
> This section of capabilities includes non-technical communications and
> actions that manufacturers can provide to support potential and
> existing IoT device customers' needs related to

1)  complying with their own organizational policies and applicable
    > legal requirements for determining the risks created by IoT
    > devices,

2)  understanding how implementing the IoT device will possibly
    > introduce risks into their processing system(s), and

3)  describing the supporting actions and information the IoT device
    > manufacturer will provide.

> The term "establish communications" is used throughout this section to
> mean developing, documenting, implementing, distributing/providing,
> and maintaining the documentation and performing the actions involved
> with the non-technical capabilities.

1.  **Document assumptions made during the development process and other
    expectations related to the IoT device.**

> This section of capabilities includes non-technical communications and
> actions that manufacturers can provide IoT device customers to help
> them understand the manufacturer's assumptions made during development
> about how their customers would use the device, and the expectations
> for the security controls the customers would implement for the
> device, both technical and the non-technical controls beyond the
> technical device capabilities. This documentation will provide
> important information to the IoT device customer describing the
> additional actions the customer needs to take related to implementing
> the IoT device based upon the assumptions and expectations the
> manufacturer has for their customers.

a.  **Expected customers and use cases**

```{=html}
<!-- -->
```
1.  **Device acquisition and maintenance: Establish communications
    > describing the IoT device security, authorization, and supporting
    > maintenance requirements.**

> Manufacturers may need to provide information to customers to support
> the customers' intended goals and purposes for using the device, as
> determined by each customer's assessment of cybersecurity risk created
> by the IoT device within the associated customer system, and to meet
> each customer's organizational and legal requirements. To support
> these needs, manufacturers are encouraged to include details and
> actions such as:

-   Providing details for the device security capabilities, along with
    how to implement the security management and operational controls,
    and supporting maintenance activities, for the IoT device.

    -   *Examples:*

        -   *This type of information is often necessary to support the
            > IoT device customer's organizational mission/business
            > process planning requirements, acquisition policies, legal
            > compliance, and other possible reasons.*

        -   *Providing details about the frequency, authorization
            > requirements, and source of maintenance activities, for
            > updates to the IoT device software, firmware and hardware.
            > This information can then support the IoT device
            > integration within each customer's own internal security
            > management and maintenance policies and procedures.*

        -   *Providing details for the operating systems compatible with
            > the security software used by the IoT device enables
            > customers to determine if the IoT device is even feasible
            > for implementation within their system, and if so, to help
            > identify any additional security controls that must be
            > related in the system around the use of the IoT device.*

        -   *Providing instructions for establishing and changing
            > security settings within the IoT device allows customers
            > to incorporate this information within their own
            > procedures, and supports consistent and accurate use of
            > those controls, to mitigate risks of not using the
            > security settings appropriately.*

-   Providing details about the types of, and situations that trigger,
    local and/or remote maintenance activities required once the device
    is purchased and deployed in the organization's digital ecosystem or
    within an individual consumer's home.

-   Describing the ability to establish management roles to perform
    specified information security activities, and to establish security
    requirements, for the IoT device.

    -   *Example: Organizational mission/business process planning, and
        > information security policies, often require management roles
        > to be established for computing devices, such as IoT devices.
        > This type of documentation supports customers in their need to
        > meet requirements for assigning roles to support the IoT
        > device, and to ensure IoT device security requirements are
        > comprehensively managed by those roles.*

-   Establishing and providing communications that describe the
    suggested types of resources necessary to protect the associated
    information system(s) within which the IoT device will be deployed.

    -   *Example: When making purchase decisions for computing devices,
        > such as IoT devices, that will be implemented within the
        > corporate system, organizations often require information
        > about the related resources (e.g., storage capacities, network
        > bandwidth, operating systems) required to support the device,
        > as well as the resources necessary to secure the IoT device
        > within the system. Such resources may be provided from the IoT
        > device itself, or the manufacturer may recommend additional or
        > primary security protections from outside the IoT device, in
        > which case details for those external resources' protections
        > will also be needed. Such information is typically required to
        > support the organization\'s capital planning and investment
        > control (CPIC) process.*

-   Providing details about the IoT device data security and privacy
    capabilities and limitations, and the types of risks mitigated by
    the capabilities.

    -   *Examples:*

        -   *Describing the security risks of integrating the IoT device
            > within a system (access to data in transit, creating a
            > pathway to other network components, etc.).*

        -   *Describing suggested risk reduction actions using IoT
            > device capabilities (encrypting data in transit, requiring
            > authorization for specific roles' access to go beyond the
            > IoT device).*

-   Providing instructions and documentation describing the physical and
    logical access capabilities necessary to the IoT device to perform
    each type of maintenance activity.

    -   *Example: Organizations need to determine the access
        > authorizations and roles for personnel to perform logical and
        > physical access maintenance on the IoT device. To make the
        > determinations, the organizations need to understand the
        > activities required for each of the IoT device maintenance
        > activities.*

-   Providing other information and actions as necessary for physically
    securing, and securely using, the IoT device based upon the IoT
    device use, purpose, and other contextual factors related to the
    digital ecosystem(s) within which they are intended to be used.

    -   *Examples:*

        -   *Providing information about how individuals or roles
            > authorized to use drones can physically and logically
            > secure a drone when it is used in areas where public
            > access could occur.*

        -   *Using wi-fi security to protect logical access to the
            > drone.*

        -   *Using two-factor authentication to logically access the
            > drone.*

        -   *Using geo-fencing capabilities to disable drone usage
            > capabilities when the device is stolen.*

    a.  **Physical use and characteristics**

    ```{=html}
    <!-- -->
    ```
    1.  **Device Security:** **Establish communications describing
        options for implementing security oversight of IoT device users
        connected to the network.**

> Information that may be necessary to provide, to support the IoT
> device customers requiring organizational oversight for using the IoT
> device, when the IoT device users are also connected to the system
> networks, and as determined by the customer's and/or manufacturer's
> assessment of cybersecurity risk created by the IoT device. To support
> these needs, include details and actions such as:

-   Providing descriptions of the types of physical access practices,
    > and manufacturer suggested hardware or other types of devices,
    > that can be used to prevent unauthorized physical access to the
    > IoT device based upon the determined risk level that the device
    > brings to the IoT customer's system.

    -   *Examples:*

        -   *Keeping the IoT device within a secured room, locker, or
            > some other type of container to keep unauthorized users
            > from physically using the IoT device controls, exploiting
            > device vulnerabilities or capabilities to access other
            > system components through the IoT device interface.*

        -   *Configuring the device to keep cybersecurity status and
            > associated information, such as the associated network
            > details, from being displayed when the IoT device will be
            > located within an area where unauthorized users are or may
            > be present.*

        -   *Using keys, locks, combinations, and card readers to create
            > a physical barrier to IoT device when it is connected to
            > the network.*

-   Providing descriptions of the physical access security procedures
    > the manufacturer recommends to limit physical access to the
    > device, and to associated device controls.

    -   *Example: Providing such information will support the IoT device
        customer's needs to comply with their internal security
        policies, applicable laws, executive orders, directives,
        policies, regulations, standards, and guidelines for limiting
        access, through use of the IoT device connection to the
        network.*

-   Providing details of indications, and recommendations for how to
    > determine, when unauthorized physical access to the IoT device was
    > or is attempted, or is occurring.

    -   *Examples:*

        -   *Providing information about the types of physical access
            > monitoring that can be done will support many IoT device
            > customers' needs to identify suspicious activity,
            > anomalous events, or potential threats.*

        -   *Using CCTV or similar types of visual monitoring devices.*

        -   *Using device movement detection tools.*

        -   *Setting audible alarms on the IoT device.*

    a.  **Network access and requirements**

1.  **Device Security:** **Establish communications explaining how to
    accomplish logical organizational oversight for using the IoT
    device.**

> Information that may be necessary to provide to explain how to
> accomplish logical oversight of the IoT device include details and
> actions such as:

-   Providing information to IoT device customers with recommendations
    or suggestions for implementing management and operational controls.

    -   *Example: Federal agencies, and other types of organizations,
        > require establishing IoT device oversight and user roles and
        > responsibilities. The IoT device manufacturer's documentation
        > and other types of communications can help the customer to
        > determine if, and how, to establish and maintain such
        > oversight.*

-   Providing IoT device customers the tools, assistance, instructions,
    and other types of information to support establishing a hierarchy
    of role-based privileges within the IoT device.

    -   *Examples:*

        -   *Organizations that establish distinct roles to perform
            > different types of activities with computing devices,
            > including IoT devices.*

        -   *Instructions for how to use the IoT device technical
            > ability to assign read-only access to device data for
            > auditors.*

        -   *Instructions for how to use the IoT device technical
            > ability to assign full access to the device for IoT device
            > admins.*

-   Providing recommendations to IoT device customers for using the
    technical IoT device security controls, or external devices or
    applications communicating with the IoT, to establish a variety of
    oversight capabilities for the IoT device users.

2.  **Logical Access to Interfaces: Establish communications that
    describe the ways in which the IoT device can logically access
    devices on the NIST-approved products list.**

> Information that may be necessary to provide include details and
> actions such as:

-   Providing information and details to the IoT device customers
    indicating if and when the IoT device was placed on the Federal
    Information Processing Standards (FIPS) 201 approved products list
    for Personal Identity Verification (PIV) capability, as applicable
    to the use and purpose of the IoT device.

    -   *Example: Federal agencies need to obtain such information prior
        > to making a purchase of any type of computing device that is
        > incorporated within their system. When an IoT device is not on
        > the FIPS 201 approved list of products, then the IoT device
        > will not be allowed unless the agency's security policy allows
        > for such exceptions, or if the IoT device can be allowed with
        > appropriate management approval.*

-   Providing documentation describing how the IoT device can
    technically support PIV card implementation, accessibility and
    interfaces.

    -   *Example: Such information is necessary for making purchases of
        > IoT devices that require implementation of only products
        > listed in the NIST-approved products list.*

-   Providing documentation with suggested ways in which customers can
    implement compensating controls around the IoT device if the IoT
    device cannot support PIV cards.

-   Providing documentation explaining how to configure the IoT device
    to technically support PIV implementation, accessibility and
    interfaces.

-   Providing detailed instructions for how to integrate the IoT device
    within a PIV system.

-   Providing an attestation, from an authoritative source, that the IoT
    device can be used in compliance with Federal agency requirements,
    with associated descriptions for how the agency can accomplish this,
    if the IoT device cannot be integrated within a PIV system.

3.  **Logical Access to Interfaces:** **Establish communications
    detailing the IoT device interface and access controls
    capabilities.**

> Information that may be necessary to provide include details and
> actions such as:

-   Providing details for how to implement IoT device logical and remote
    > access controls through device interfaces for data transmission
    > between devices and subjects, objects, systems and components
    > within the system.

-   Providing documentation describing all the IoT device logical and
    > remote interface access controls.

-   Providing detailed instructions for how to restrict access to the
    > IoT device interface for both users of the interface, and for the
    > data that can be transmitted through that interface, and
    > describing if and how interface restrictions can be defined.

-   Providing copies of the manufacturer\'s policies and practices that
    > govern how and with whom the manufacturer shares the data obtained
    > from the manufacturer\'s IoT device.

-   Providing the details and instructions to establish management and
    > operational controls on and/or to the IoT device.

    -   *Example: Obtaining such instructions are often necessary to
        > support IoT device customers' implementation of management and
        > operational controls to support the organizational access
        > control requirements on IoT devices.*

-   Providing details and descriptions about the specific types of
    > manufacturer's needs to access the IoT device interfaces; such as
    > for specific support, updates, ongoing maintenance, and other
    > types of purposes.

-   Providing documentation describing the manufacturer requirements for
    > collecting data from the IoT device, including the specific types
    > of data being collected.

-   Providing documentation with instructions for the IoT device
    > customer to follow for how to restrict interface connections that
    > enable specific activities.

-   Providing descriptions of the types of access to the IoT device the
    > manufacturer will require on an ongoing or regular basis.

    -   *Examples:*

        -   *Remote logical access to medical device data and firmware*

        -   *Physical access to smart refrigerators and smart TVs
            > hardware*

        -   *Physical access to HVAC device hardware*

        -   *Remote logical access IoT device maintenance data*

-   Providing detailed instructions for how to implement management and
    > operational controls based on the role of the IoT device user, and
    > not on an individual basis.

```{=html}
<!-- -->
```
-   *Examples:*

```{=html}
<!-- -->
```
-   *In situations where anyone within the office can use the smart
    > coffee maker as part of a \"general use\" type of role, but only
    > those within the \"admin\" type of role can modify the smart
    > coffee maker settings.*

-   *For when a device can be configured to allow anyone with access to
    > the device to view information in a public space, e.g., a public
    > kiosk. However, the device has an \"admin\" type of role that
    > allows only those within that role to make changes to the device.*

-   Providing information and detailed instructions for how to
    > establish, change and technically enforce role-based access
    > settings and capabilities built within the IoT device, such as
    > admin, general user, and other types of roles.

-   Providing information and instructions describing how role-based
    > access settings and capabilities for the IoT device can be
    > established, changed and technically enforced using hardware,
    > software and/or firmware that is outside of the IoT device.

    -   *Example: Instead of using controls within a smart coffee maker
        > device, using a cloud-based platform, an application installed
        > within the system where the IoT device is implemented, and/or
        > a mobile app to establish and manage the roles used within the
        > smart coffee maker; such as defining the individuals within an
        > "admin" type of role, or a "general use" role.*

4.  **Logical Access to Interfaces: Establish communications describing
    situations where identification and authentication are not**
    **needed for the IoT device.**

> Information that may be necessary to provide include details and
> actions such as:

-   Providing detailed instructions and guidance for establishing
    > activities performed by the IoT device that do not require
    > identification or authentication.

    -   *Examples:*

        -   *To support IoT device customers that must allow
            > organizationally specified uses of the IoT device without
            > requiring identification or authorization, while requiring
            > authentication and access controls for other types of uses
            > of the IoT device, to fulfill security policies and/or
            > purchasing requirements.*

        -   *When a smart TV must be enabled to be turned on/off and
            > channels changed by all individuals in the vicinity of the
            > TV, while other roles must to be required to perform other
            > capabilities for the TV, such as requiring "admin" roles
            > to establish the channels that can be viewed, to turn
            > viewing logs off/on, and perform other setting changes.*

-   Providing a description of the privacy protection capabilities built
    > within the IoT device that do not require authentication.

    -   *Example: The ability to turn off the audio recording capability
        > for an intelligent digital assistant without requiring
        > authentication.*

-   Providing a description for how to access the IoT device through the
    > logical access interface without authentication, as applicable to
    > the purpose of the device.

    -   *Example: When visitors need to be able to access certain IoT
        > devices without needing to authenticate, such as when asking
        > the IoT device for the location of a doctor\'s office within a
        > health clinic.*

5.  **Cybersecurity State Awareness: Establish communications explaining
    how to provide monitoring information to authorized personnel or
    roles.**

> Information that may be necessary to provide to support customer's
> needs to provide monitoring reports to specific roles within their
> organization include details and actions such as:

-   Providing information that describes the types of system monitoring
    > information generated from, or associated with, the IoT device and
    > instructions for obtaining that information.

    -   *Example: This information is useful for helping IoT device
        > customers to determine the roles within their organization
        > that need to have access to the IoT device systems monitoring
        > information based upon the organization's authorized personnel
        > or roles, and according to their organizationally-defined
        > frequencies for providing such reports to the designated
        > roles.*

-   Providing documentation describing the types of monitoring tools
    > with which the IoT device is compatible, and recommendations for
    > how to configure the IoT device to best work with such monitoring
    > tools.

    a.  **Data created and handled by the device**

        1.  **Cybersecurity State Awareness: Establish communications**
            > **describing how the IoT device cybersecurity event data
            > is protected from unauthorized access, modification, and
            > deletion.**

> Information that may be necessary to provide include details and
> actions such as:

-   Providing documentation and/or other communications describing how
    > to implement management and operational controls to protect data,
    > obtained from IoT devices, and associated systems and
    > intrusion-monitoring tools, from unauthorized access,
    > modification, and deletion.

    -   *Example: Describing how to encrypt smart security camera video
        to prevent others that may access the video in transit through
        the internet from being able to view the video.*

-   Providing documentation describing the types of usage and
    > environmental systems data that can be collected from the IoT
    > device.

    -   *Example: Times and dates a smart coffee maker was used, and the
        temperature settings for the coffee for each use.*

        1.  **Data Protection: Establish communications** **describing
            > capabilities supporting IoT device data integrity, secure
            > data handling and data retention.**

> Information that may be necessary to provide include details and
> actions such as:

-   Providing communications to IoT device customers describing how to
    > implement management and operational controls to protect IoT
    > device data integrity and associated systems data integrity.

    -   *Examples:*

        -   *To ensure data is accurate, organizations often require
            > data integrity controls to be established within computing
            > devices to ensure that the data is accurate.*

        -   *IoT device integrity controls also support organizational
            > security policies requiring specific roles to be
            > responsible for validating data integrity, such as
            > internal auditors and systems administrators, to meet
            > compliance with policies, standards, and/or legal
            > requirements.*

-   Providing detailed information listing capabilities that are
    > required by data protection regulations.

    -   *Example: This type of information is often required by the role
        or position within the organization that is responsible for
        determining the security and privacy regulatory requirements
        with which the IoT device capabilities must comply.*

```{=html}
<!-- -->
```
-   Providing detailed instructions for how to implement management and
    > operational controls for securely handling and retaining IoT
    > device data, associated systems data, and data output from the IoT
    > device.

    -   *Example: This type of information is often required by the role
        or position within the organization that is responsible for
        ensuring the IoT device capabilities comply with the
        organization's applicable Federal laws, Executive Orders,
        directives, policies, regulations, standards, and operational
        requirements.*

-   Providing documentation describing how to irreversibly delete data
    > from the IoT device.

```{=html}
<!-- -->
```
-   Providing detailed instructions for how to protect device data from
    > being accidentally modified.

    a.  **Assumed cybersecurity requirements for the IoT device**

        1.  **Device Acquisition and Maintenance: Establish
            > documentation describing IoT device security requirements
            > that can be used to support customers' organizational
            > mission, business process planning, and IoT device
            > acquisitions requirements.**

> Documentation of basic IoT device cybersecurity requirements, for the
> device capabilities, as well as for device development and supply
> chain entities with access to the device, information helps potential
> IoT device customers to make purchase decisions that support their
> organization's requirements for these issues. To support these needs,
> include details within documentation and associated actions such as:

-   Providing detailed information describing the resources necessary
    > for each type of security capability used with the IoT device.

    -   *Example: This type of information is often required as part of
        the organizational mission/business process planning, and for
        determining, documenting, and allocating the resources necessary
        to protect the associated information system to support the
        organization\'s capital planning and investment control (CPIC)
        process.*

-   Providing instructions and/or information describing the recommended
    > methods and tools for protecting the IoT device hardware, software
    > and data, and the associated resources necessary to support them.

    -   *Example: Providing documentation with the recommended number of
        personnel needed to secure the IoT device and related
        components, the amount of data storage within the system the
        device will or could use, and estimated costs for using the
        methods and tools.*

-   Providing detailed instructions for how to establish restrictions
    > for the acquisition of IoT devices, systems and services to only
    > assigned organizationally-defined personnel or roles.

    -   *Example: Organizations often assign individuals or roles
        responsible for ensuring the required device capabilities
        (compliance and implementation controls, etc.) exist for devices
        being considered for purchase. The manufacturer can provide
        documentation explaining how to designate specific individuals
        within the IoT customer organization to be the only ones allowed
        to order IoT device related systems, part, services, etc.*

-   Providing documentation that clearly details the IoT device security
    > and privacy capabilities and limitations, the specific types of
    > manufacturer support that will be provided throughout the life of
    > the device, supported operating systems compatible with the IoT
    > device, and other information pertinent to the use and security of
    > the device.

    a.  **Laws and regulations the IoT device and related support
        > activities comply with.**

        1.  **Device Security: Establish documentation and
            > communications describing the types of legal compliance
            > the IoT device supports.**

> Information that may be necessary to provide to support customer legal
> compliance needs, include details and actions such as:

-   Providing documentation describing the legal (Federal regulations,
    > state and local laws) requirements for security and privacy
    > controls that the IoT device supports.

    -   *Examples: Federal Information Security Modernization Act
        (FISMA), Health Insurance Portability and Accountability Act
        (HIPAA), California Consumer Privacy Act (CCPA), EU General Data
        Protection Regulation (GDPR).*

-   Providing information describing how the manufacturer stays
    > up-to-date with regulations, laws, and other legal requirements
    > and standards that apply to IoT devices.

-   Providing white papers and use cases of existing IoT device
    > customers describing how they used the IoT device in ways that
    > supported their legal compliance requirements needs.

    a.  **Expected lifespan, anticipated cybersecurity costs related to
        > the IoT device (e.g., price of maintenance), and term of
        > support**

        1.  **Device Acquisition and Maintenance: Establish
            > communications and documentation that detail the expected
            > lifespan of the device, the expected time for supporting
            > the device, the costs for maintaining the device, the
            > costs for device parts replacements, costs for device
            > repairs, and other costs related to using the IoT
            > device.**

> Information that may be necessary to provide include details and
> actions such as:

-   Providing detailed information about the anticipated costs
    > associated with the IoT device purchase, usage activities,
    > repairs, maintenance, parts, operations, security, and disposal
    > costs throughout the potential lifetime of the IoT device.

    -   *Example: Most organizations must establish a discrete line item
        for IoT device information security costs within the
        organizational programming and budgeting documentation.*

    a.  **Obligations for manufacturer oversight of their IoT device
        > supporting entities (third-parties, contractors, vendors,
        > resellers, supply chain entities)**

        1.  **Device Security: Establish communications that describes
            > the manufacturer's third party, contractor, and vendor IoT
            > device security oversight, and for including security and
            > privacy requirements within contractual agreements.**

> Information that may be necessary to provide to explain supply chain
> risk management include details and actions such as:

-   Communications, detailed descriptions, methods, techniques, and/or
    > policies the manufacturer uses to monitor IoT device activities
    > and associated systems security control compliance by external
    > service providers on an ongoing basis.

    -   *Example: Organizations often must meet their organizational
        requirements and policies for consistently using methods and
        techniques to monitor IoT device and associated systems security
        control compliance by external service providers on an ongoing
        basis, which would require them to obtain these types of
        communications and details.*

-   Providing detailed information describing how the IoT device
    > manufacturer performs oversight activities for their supporting
    > entities, including such information as:

    -   How the manufacturer meets legal and/or regulatory safeguard
        requirements related to supply chain risk management.

    -   Details about the activities performed by each of the supporting
        entities to whom the manufacturer outsources IoT device support
        activities, and how such activities are monitored.

    -   The ways in which security and oversight requirements are
        included within contracts with entities throughout the supply
        chain for the IoT device.

    -   Remote monitoring activities the manufacturer performs for each
        of the supporting entities' activities.

    -   Description of the other access and data collection, use and
        sharing activities the supporting entities perform in support of
        the IoT devices, and how the manufacturer provides monitoring
        for these activities.

    -   *Examples:*

        -   *For a situation where maintenance on a smart coffee maker
            is performed by the manufacturer's contracted supporting
            entity, an organization's security policies may require that
            the manufacturer's supporting entity personnel each 1) use
            two-factor authentication to access the device, 2) have
            limitations for the times when access can occur, 3) have
            their access activities logged, 4) and be restricted from
            accessing the logs.*

        -   *The manufacturer should then establish a way to make the
            logs available to the IoT device customer.*

-   Communications and documentation detailing how the IoT device
    > supports regulatory requirements for auditing and monitoring
    > capabilities. Such information should list the external supporting
    > entities throughout the supply chain that are involved with these
    > activities, the specific activities and data that the supporting
    > entities access while providing these activities, and the
    > oversight that the manufacturer provides for the supporting
    > entities.

    -   *Examples:*

        -   *Many organizations need to verify that a computing device
            > meets their organization's security, purchasing and/or
            > legal requirements, including requirements for supply
            > chain entities, prior to being approved to purchase the
            > device.*

        -   *Many organizations need to verify that supporting entities
            > throughout the supply chain have their security practices
            > audited and/or assessed, and have security oversight of
            > their activities, particularly for entities with access to
            > the IoT device, data, or other related systems.*

        -   *For a smart security camera, which stores the recorded
            > video within a manufacturer's supporting entity, an
            > organization will typically need to obtain from the
            > manufacturer details such as the name of the supporting
            > entity, location for the servers where the video data will
            > be stored, how access to the video data will be
            > restricted, and other information as required by the IoT
            > device customer's security policies and/or purchasing
            > requirements.*

-   Providing the detailed instructions for how IoT customers can
    > implement and consistently use methods and techniques to monitor
    > the IoT device and associated systems security control compliance
    > of the manufacturer's supporting entities on an ongoing basis.

-   Providing appropriate tools, assistance, instructions, or other
    > details describing the capabilities for monitoring the IoT device
    > and/or for the IoT device customer to report actions to the
    > manufacturer's supporting entity's monitoring service.

    -   *Example: IoT device customers will often need to include this
        type of information within their organization's system devices
        logging and auditing procedures.*

-   Communicating the manufacturer's procedure for how customers can
    > provide feedback when the manufacturer's supply chain security
    > management and logging practices do not meet established
    > compliance requirements of IoT device customers' external service
    > providers.

    1.  **Device Security: Establish communications detailing the
        > security and privacy requirements the manufacturer includes
        > within their supporting entity contractual agreements that
        > cover access to, and/or use of, the IoT device by third
        > parties.**

> Information that may be necessary to provide include details and
> actions such as:

-   Providing within the IoT device customer contracts a description and
    > listing of the third parties used by the manufacturers that will
    > have access to the IoT device and/or the data collected,
    > generated, accessed, processed, or shared through the device, and
    > a description of the associated security and privacy controls
    > established for such third parties.

-   Providing documentation detailing all the cloud services used to
    > support the IoT device.

-   Providing a detailed description of all logical interfaces to the
    > IoT device and documenting the interfaces used by the
    > manufacturer\'s third parties, and the purposes for such uses.

-   Providing the IoT device customers with a list of the third parties
    > to whom the manufacturer provides the IoT device data and/or
    > customer information.

-   Providing the IoT device customers with a list of the types of data
    > provided to the third parties directly form and/or by the device
    > (e.g., device usage, entities using the device, device location,
    > personal data, etc.).

    -   Providing the IoT device customers a detailed description of the
        > other types of devices, systems, etc., that will be accessing
        > the IoT device during customer use of the device, and how they
        > will be accessing it.

        -   *Example: Supporting entities using static IP addresses
            and/or using device identifiers to access the IoT device.*

    -   Providing within the IoT device customer contracts, disclosures
        > and/or similar types of documents, describing the actions the
        > manufacturer will take for requested modification of interface
        > capabilities, the supporting entities involved, and
        > descriptions for how device customers should make such
        > requests.

    ```{=html}
    <!-- -->
    ```
    -   Providing a detailed description for how the IoT device customer
        > will be notified of changes in the activities of the
        > manufacturer\'s contractors and third parties that have access
        > to the IoT devices, such as when the origination or locations
        > (e.g., city, state, country) of the contractors or third
        > parties change, and other related types of contractor and
        > third-party changes.

    -   Providing a detailed description of the methods by which the
        > manufacturer prevents unauthorized access to the customer\'s
        > IoT device by third parties not listed on the provided
        > documentation.

    -   Providing a detailed description for how third parties are, or
        > can be, prohibited by the IoT device customers from accessing
        > the IoT device and/or restricted in their access to the
        > device.

    -   Providing a detailed description for the ways in which the
        > manufacturer and/or the manufacturer's listed supporting
        > entities, will be accessing and making modifications to the
        > IoT device throughout the expected or typical lifespan of the
        > IoT device.

    -   Providing a description to Federal agencies for how the IoT
        > device supports the Federal Risk and Authorization Management
        > Program (FedRAMP) requirements.

2.  **Document the technical cybersecurity capabilities, such as those
    > detailed within NISTIR 8259A** **and within the full IoT
    > cybersecurity technical catalog, that are implemented within the
    > IoT device and how to configure and use them.**

> NISTIR 8259A discusses technical device cybersecurity capabilities,
> which are cybersecurity features or functions that computing devices
> provide through their own technical means (i.e., device hardware and
> software), and establishes a core baseline of device cybersecurity
> capabilities needed by many IoT device customers. This section of
> capabilities includes non-technical communications and actions to
> explain how to most effectively use the technical abilities of an IoT
> device. Such information will help IoT device customers understand how
> to configure and implement the technical IoT device cybersecurity
> capabilities to limit the risks the IoT device brings to their
> systems. It will also help IoT device customers to comply with their
> associated legal requirements, and support their organizational
> purchasing requirements.

a.  **Monitoring, diagnostics and legal requirements**

```{=html}
<!-- -->
```
1.  **Device Acquisition and Maintenance: Establish communications**
    > **detailing the ways in which the IoT device capabilities connect
    > to and communicate with diagnostic tools used by the manufacturer
    > and/or supporting entities to support customers' legal
    > requirements.**

> Information and documentation that may be necessary to provide about
> the IoT device technical capabilities include details and actions such
> as:

-   Providing the details necessary for IoT device customers to
    > implement only organizationally-approved IoT device diagnostic
    > tools within their system.

    -   *Example: IoT device customers need this information to support
        > their internal security policies and legal requirements for
        > using only approved IoT device diagnostic tools.*

```{=html}
<!-- -->
```
-   Providing detailed documentation describing the tools manufacturers
    > require for IoT device diagnostics activities.

1.  **Cybersecurity State Awareness:** **Establish communications
    > explaining how to use monitoring systems, possible monitoring
    > activities, the use of devices and tools, and descriptions of
    > security level changes.**

> Information that may be necessary to provide include details and
> actions such as:

-   Providing the details necessary for IoT device customers to monitor
    IoT devices and associated systems.

-   Providing documentation to IoT device customers describing how to
    perform monitoring activities.

> *Examples:*

-   *Describing all the ways in which the IoT device can be monitored,
    > and the recommended associated tools to perform monitoring.*

-   *Describing the indicators of attacks on the IoT device.*

-   *Describing how to identify local, network and remote IoT device
    > access attempts and connections.*

-   *Describing expected behavior of the normal operation of the IoT
    > device.*

```{=html}
<!-- -->
```
-   Providing documentation describing IoT device behavior indicators
    > that could occur when an attack is being launched.

-   Providing documentation describing details necessary to identify
    > unauthorized use of IoT devices and their associated systems.

    -   *Example: Many organizations require this type of information to
        comply with the IoT device customer's organizationally-defined
        security policies governing techniques and methods for
        identifying unauthorized devices implemented within the
        systems.*

-   Providing documentation to the IoT device customers that describes
    > indicators of unauthorized use of the IoT device.

-   Providing documentation to IoT device customers describing how to
    > implement and securely deploy monitoring devices and tools for IoT
    > devices and associated systems.

-   Providing documentation to IoT device customers describing how and
    > when to heighten the level of security for an IoT device and
    > associated systems.

-   Providing documentation to IoT device customers describing how to
    > use the security controls and monitoring capabilities built within
    > the IoT device, and how to configure the device to best fit the
    > risk levels within the systems where they are used.

    -   Providing the details necessary to implement management and
        operational controls for when and how to generate internal
        security alerts, advisories, and directives about the IoT
        devices.

        1.  **Data Protection: Establish communications** **to provide
            > the IoT device customers with the details necessary to
            > establish and modify IoT device data integrity controls.**

> Information that may be necessary to provide include details and
> actions such as:

-   Providing IoT device customers with the details necessary to support
    > secure implementation of the IoT device and associated systems
    > data integrity controls.

-   Providing IoT device customers with documentation describing the
    > data integrity controls built into the IoT device and how to use
    > them. If there are no data integrity controls built into the IoT
    > device, include documentation explaining to IoT device customers
    > the ways to achieve IoT device data integrity.

    1.  **Device Identity: Establish communications describing how to
        > establish unique identification for the IoT device.**

> Information that may be necessary to provide, as determined by the
> manufacturer's assessment of cybersecurity risk created by the IoT
> device, include details and actions such as:

-   Providing details for how to establish unique identification for
    each IoT device associated with the system and critical system
    components within which it is used.

    -   *Example: IoT device customers must often comply with their
        applicable organizational security policies and legal
        requirements for using unique identification for each IoT device
        associated with the system and critical system components within
        which it is used.*

3.  **Document device design and support considerations related to the
    IoT device.**

> This section of capabilities includes documentation describing the
> design of the device and associated cybersecurity capabilities, such
> as how IoT platforms were used in the development of the device. This
> section also provides details about the support for secure use of the
> IoT device by customers that will be necessary, including
> documentation for the supporting entities involved with support
> activities throughout the manufacturer's supply chain. Such
> documentation may also be important to meet the organization's
> purchasing requirements, to support audits, or to qualify for specific
> certifications that some customers may require for IoT devices they
> use.

a.  **IoT platform used in the development of the IoT device, and
    > related documentation**

    1.  **Logical Access to Interfaces: Establish communications with
        > detailed instructions for using authentication techniques
        > supported by IoT platforms.**

> An IoT platform is typically a third-party vendor provided/hosted
> SaaS-based tool that is used to support IoT device and endpoint
> management, connectivity and network
>
> management, data management, processing and analysis, application
> development, security, access control, monitoring, event processing
> and interfacing/integration.
>
> Documentation about such a third-party can provide important
> information about supply chain security practices and vulnerabilities
> to allow for the IoT user to more accurately determine risks related
> to the use of an IoT platform. Information that may be necessary to
> provide include details and actions such as:

-   Providing documentation describing the specific IoT platforms used
    > with the device to support required IoT authentication control
    > techniques.

    -   *Examples:*

        -   *For federal agencies this would be the IoT platforms that
            > support how the IoT device can use PIV authentication.*

        -   *For some organizations this may be information about the
            > IoT platforms using biometric capabilities.*

-   Providing documentation with details about the capabilities of the
    > IoT platform used to support device interface controls, and
    > descriptions for if and how a second factor for authentication can
    > be implemented.

-   Providing documentation with details describing external
    > authentication IoT platforms, and associated authentication
    > methods, that can be used with the IoT device.

    -   *Examples:*

        -   *Using a third-party IoT platform, vetted and authorized by
            > the manufacturer, to distribute and manage the
            > authentication certificates used within the IoT device.*

        -   *An IoT device that is configured to access a cloud service
            > (provided by the manufacturer, or a supporting entity of
            > the manufacturer; such as an infrastructure as a service
            > (IaaS), platform as a service (PaaS), or software as a
            > service (SaaS) from the IoT device or the IoT device
            > customers' information systems.*

    a.  **Protection of software and hardware components of the IoT
        > device**

        1.  **Device Security: Establish communications that provide
            > details about the security capabilities of the IoT device
            > software components.**

> Information that may be necessary to provide describing the technical
> security capabilities include details and actions such as:

-   Providing details about how the security capabilities of the IoT
    > device software components meet regulatory and other legal and
    > policy requirements.

    -   *Examples:*

        -   *Federal agencies need such information to meet their
            organizational security policies and legal requirements for
            IoT device software security functional requirements,
            security strength requirements, security assurance
            requirements, security-related documentation requirements,
            requirements for protecting security-related documentation,
            descriptions of the information system development
            environment and environment in which the IoT device and
            associated system is intended to operate, and acceptance
            criteria in the acquisition contracts for every IoT device
            system, system component, or information system service in
            accordance with applicable Federal laws, Executive Orders,
            directives, policies, regulations, standards, guidelines,
            and organizational mission/business needs.*

        -   *Organizations outside the federal government have their own
            corporate security policies, and legal requirements, for
            which they must comply that require they meet IoT device
            software security functional requirements, security strength
            requirements, security assurance requirements,
            security-related documentation requirements, requirements
            for protecting security-related documentation, descriptions
            of the information system development environment and
            environment in which the IoT device and associated system is
            intended to operate, and acceptance criteria in the
            acquisition contracts for every IoT device system, system
            component, or information system service in accordance with
            applicable Federal and international laws, directives,
            policies, regulations, standards, guidelines, and
            organizational mission/business needs.*

        -   *Organizations must often provide information to their
            internal and external auditors and regulatory assessors that
            provide this kind of information. Because of this,
            organizations often require such information to be obtained
            and reviewed before approving acquisition for all types of
            computing devices, including IoT devices.*

            1.  **Device Security: Establish communications for the IoT
                > device customers with details for the security
                > capabilities of the hardware components.**

-   Providing the IoT device customers with details about the security
    > capabilities of the IoT device hardware components.

    -   *Examples:*

        -   *Federal agencies must meet their applicable policies and
            legal requirements for IoT device hardware security
            functional requirements, security strength requirements,
            security assurance requirements, descriptions of the
            information system development environment and environment
            in which the IoT device and associated system is intended to
            operate, and acceptance criteria in the acquisition
            contracts for every IoT device system, system component, or
            information system service in accordance with applicable
            Federal laws, Executive Orders, directives, policies,
            regulations, standards, guidelines, and organizational
            mission/business needs.*

        -   *Organizations outside the federal government have their own
            corporate security policies, and legal requirements, for
            which they must comply that require they meet IoT device
            hardware security functional requirements, security strength
            requirements, security assurance requirements,
            security-related documentation requirements, requirements
            for protecting security-related documentation, descriptions
            of the information system development environment and
            environment in which the IoT device and associated system is
            intended to operate, and acceptance criteria in the
            acquisition contracts for every IoT device system, system
            component, or information system service in accordance with
            applicable Federal laws, Executive Orders, directives,
            policies, regulations, standards, guidelines, and
            organizational mission/business needs.*

        -   *Some organizations require a hardware-validated boot
            process that ensures the first executable code starts from
            an immutable source. For example, through the establishment
            of a Root of Trust. Information related to this is often
            requested from organizations for their computing devices.*

    a.  **Secure software development and supply chain practices used**

        1.  **Device Security:** **Establish communications providing
            > IoT device management details** **that can be incorporated
            > within the IoT device customer's system development life
            > cycle.**

> Information that may be necessary to provide about IoT device security
> management include details and actions such as:

-   Providing the details necessary for customers to 1) manage the IoT
    > device within their system using their organizationally-defined
    > system development life cycle\'s associated information security
    > considerations, 2) assign individuals with IoT device information
    > security roles and responsibilities, and 3) integrate the IoT
    > device within the organizational information security risk
    > management process.

-   Providing communications and the detailed instructions for
    > implementing a hierarchy of privilege levels to use with the IoT
    > device and/or necessary associated information systems.

    -   *Example: Throughout the system development lifecycle, roles
        > that are responsible for testing and determining necessary
        > security capabilities to use will typically be provided with
        > the highest, full set of security privileges in order to
        > perform such testing. However, when the IoT device is moved to
        > production, those roles performing testing will typically be
        > moved to a much more restricted privilege level, and those
        > responsible for security in the production system will be
        > given highest security privileges instead.*

-   Providing communications with instructions and recommendations for
    > how to incorporate IoT device management and associated security
    > management, within the system development life cycle.

    a.  **Accreditation, certification and/or evaluation results for
        > cybersecurity-related practices**

        1.  **Device Security:** **Establish communications that provide
            > details about the manufacturer's supply chain risk
            > management process and the controls used within ongoing
            > supply chain security assessment and authorization
            > activities.**

> Information that may be necessary to provide about supply chain risk
> management include details and actions such as:

-   Providing documentation explaining how the manufacturer provides
    security oversight of their supporting entities, and how they assess
    the cybersecurity risks that those supporting entities present to
    the IoT devices and the systems within which they are implemented.

-   Providing documentation and information describing the security
    requirements included within the contractual requirements for the
    supporting entities. Such requirements may include implementing
    security practices, safeguards, access controls and assessments to
    provide oversight of the supporting entities' activities.

    -   *Examples:*

        -   *Federal government agencies using the supply chain risk
            > management practices described within SP 800-161 to
            > determine the controls for manufacturers to use for
            > overseeing supporting entities involved with maintaining
            > the IoT device.*

        -   *Manufacturers providing a copy of their supply chain and/or
            > third-party security assessment and oversight management
            > policies, authorization policies and procedures for supply
            > chain entities, and other similar types of policies and
            > procedures.*

-   Providing documentation describing the types of security and/or
    privacy certifications the manufacturer requires of their supporting
    entities.

4.  **Document maintenance requirements for the IoT device.**

> Documentation about maintenance requirements, especially involving
> supporting entities the manufacturer contracted to perform
> maintenance, device changes, etc., supports the customer's need to
> adequately plan for maintenance activities. This section of
> capabilities includes non-technical communications and actions that
> manufacturers provide to support the need for IoT customers to perform
> common and minimum necessary technical maintenance activities
> consistently, accurately, and most securely. Such documentation may
> also be necessary to meet the organization's purchasing requirements,
> security policies, to support audits, or to qualify for specific
> certifications that some customers may require for IoT devices they
> use.

a.  **Cybersecurity maintenance expectations and associated instructions
    > or procedures for the customer**

    1.  **Device Acquisition and Maintenance: Establish communications
        > describing the specifications and providing instructions for
        > performing IoT device maintenance and repairs, for IoT device
        > systems review, and for maintenance activities following
        > trigger events.**

> Information that may be necessary to provide for device maintenance
> and repairs include details and actions such as:

-   Providing the details and instructions necessary to perform
    > necessary IoT device maintenance activities and repairs.

    -   *Examples:*

        -   *Organizations may need such information to perform
            organizationally-defined required maintenance to comply with
            their security policies.*

        -   *Organizations may need such information to perform repairs
            following specified trigger events in accordance with the
            documentation from the IoT device manufacturer, and/or in
            compliance with their organization's security policies and
            procedures.*

-   Providing communications and comprehensive documentation describing
    > the IoT device maintenance operations performed by the
    > manufacturer and the manufacturer's supporting entities.

-   Providing communications and comprehensive documentation describing
    > maintenance operations that the IoT device customer is required to
    > perform. If such comprehensive IoT device maintenance operations
    > documentation does not exist, the manufacturer should clearly
    > communicate to IoT device customers that the user must perform
    > these operations themselves.

-   Providing the details necessary for IoT device customers to perform
    > required IoT device systems reviews.

    -   *Example: Organizations often have IT and/or security policies
        and procedures requiring audits or other types of reviews of
        computing devices within the system, according to
        organizationally-defined frequencies and/or established trigger
        events. The details provided by the manufacturers will support
        these customer needs.*

-   Providing documentation that includes the suggested frequency of
    > system review and maintenance activities for the IoT device.

-   Providing communications that include details for the recommended
    > events that will trigger IoT device system reviews and/or
    > maintenance by the manufacturer.

-   Providing communications and documentation detailing how to perform
    > account management activities, using the technical IoT device
    > capabilities, or through supporting systems and/or tools.

-   Providing communications and documentation detailing how to perform
    > recommended local and/or remote maintenance activities.

-   Providing communications and documentation detailing the
    > manufacturer's recommended vulnerability and patch management
    > plan.

    1.  **Data Protection: Establish communications** **with
        > instructions for removing all data from IoT devices prior to
        > maintenance and repairs.**

> Information that may be necessary to provide include details and
> actions such as**:**

-   Providing IoT device customers the details necessary for them to
    know when and how to remove all data from IoT devices prior to
    removing the devices from facilities for offsite maintenance or
    repairs.

-   Providing information describing how to use the IoT device
    capabilities to remove all data from the device.

    a.  **When maintenance will be performed by supporting entities that
        > will need access (remote or onsite) to customer's IoT devices,
        > and their information security contract requirements**

        1.  **Device Acquisition and Maintenance: Establish
            > communications** **to provide the IoT device customers
            > with the details necessary to support IoT device
            > maintenance and diagnostic activities and documentation.**

> Information that may be necessary to provide include details and
> actions such as

-   Providing the details necessary to enable IoT device customers to
    > monitor onsite and offsite IoT device maintenance activities.

    -   *Examples:*

```{=html}
<!-- -->
```
-   *Clearly indicating to customers the type and nature of the local
    > and/or remote maintenance activities required once the device is
    > purchased and deployed in the organization.*

-   *Communicating the physical and technical capabilities required for
    > these maintenance activities to occur.*

    -   Providing the details necessary for maintaining records for
        > nonlocal IoT device maintenance and diagnostic activities.

        -   *Examples:*

            -   *Clearly indicating through direct communications to IoT
                > device customers the type and nature of the remote
                > maintenance and diagnostic activities required once
                > the device is purchased and deployed in the
                > organization.*

            -   *Communicating to IoT device customers the physical and
                > technical capabilities required for the IoT device
                > maintenance and diagnostic activities.*

    -   Providing the details necessary to implement management and
        > operational controls for IoT device maintenance personnel and
        > associated authorizations, and record-keeping of maintenance
        > organizations and personnel.

    -   Providing communications describing the type and nature of the
        > local and/or remote maintenance activities that will involve
        > and require manufacturer personnel, or their contractors, once
        > the device is purchased and deployed in the IoT device
        > customer's organization.

    -   Providing IoT device customers with the details necessary to
        > implement management and operational controls in support of
        > their security policies and legal requirements for IoT device
        > maintenance for assigned organizationally-defined personnel or
        > roles to follow.

> *Example: Clearly indicate through documented statements to IoT device
> customers the type and nature of the local and/or remote maintenance
> activities required once the device is purchased and deployed in the
> organization.*

-   Providing documented descriptions of the specific maintenance
    procedures for defined maintenance tasks.

B.  **Manufacturer Information and Query Reception**

> **The ability for the manufacturer and/or supporting entity to receive
> from the customer information and queries related to cybersecurity of
> the IoT device.**
>
> This capability provides an input for the manufacturer to use to
> gather cybersecurity related information about their IoT devices as
> they are being used by customers, revealing topics where there may be
> a need to provide additional customer training, along with tracking
> information provided to customers to answer their questions about
> securing the device. Such ongoing interactions have an important role
> in securing the IoT device and meeting customers' cybersecurity needs
> and goals after purchase. These actions can also support a number of
> other cybersecurity supporting activities, including those within the
> Information Dissemination and Education and Awareness non-technical
> supporting sections of capabilities.
>
> Customer organizations may also need to have such capabilities to meet
> organizational requirements related to conditions for making
> technology purchases, to support updates to management about how
> discovered problems or flaws within the IoT device are being
> addressed, and to maintain a history of documentation for specific IoT
> devices that could be considered when situations arise where other
> types of IoT devices are proposed to replace the existing IoT device.
>
> Customer organizations and their third-parties may want, or be
> required by contract, law and/or policy, to report vulnerabilities to
> manufacturers that they identify in an IoT device, or the systems that
> interface with or are incompatible with the device. Manufacturers can
> use such reports of common queries and vulnerabilities to identify
> ways to improve the cybersecurity of the IoT device (e.g., development
> of software updates to patch reported vulnerabilities). For broadly
> used IoT devices, some customers may need additional support from the
> manufacturer to securely provision and use an IoT device.

1.  **The ability for the manufacturer and/or supporting entity to
    receive maintenance and vulnerability information from their
    customers and other types of entities.**

This section of capabilities includes non-technical communications and
actions that manufacturers provide to support the need for IoT customers
to report discovered maintenance problems, security incidents,
vulnerabilities, bugs, and other types of suspected security weaknesses
or abnormalities. Customer organizations and third-parties may want, or
be required, to report vulnerabilities they identify within or related
to an IoT device. These communications and actions also allow IoT device
customers to ask questions related to the security of the IoT device, as
well as provide input for the manufacturer to then use in the
Information Dissemination and Education and Awareness non-technical
supporting capability.

a.  **Software flaws**

1.  **Software Update: Establish methods for the customer to report
    > software flaws to the manufacturer with the details necessary for
    > the manufacturer to fix the software flaws.**

> Information that may be necessary to provide to support efficient
> software flaw reporting include details and actions such as**:**

-   Providing the details necessary to identify the type of software
    > flaw, describe the characteristics of the flaw, and provide any
    > suggestions for the manufacturer to consider when determining how
    > to fix the software flaw.

-   Providing instructions for the IoT device customer to use to send
    > the manufacturer software flaw reports.

-   Providing a description of the procedures the manufacturer follows
    > for processing the software flaw reports, determining which flaws
    > need to be fixed, for scheduling corrections to identified flaws,
    > and for how the manufacturer will notify the IoT customer of the
    > status of the software flaw fix.

-   Communicating device remediation efforts with stakeholders and IoT
    > device customers.

-   Providing instructions for the IoT device customer to use to send
    > other types of IoT device bug reports to the manufacturer.

2.  **The ability for the manufacturer and/or supporting entity to
    respond to customer and third-party queries about cybersecurity of
    the IoT device (e.g., customer support)**

> This section of capabilities includes non-technical communications and
> actions that manufacturers provide to receive and answer questions
> about the IoT device security, privacy and compliance issues from IoT
> device customers. Manufacturers and/or their supporting entities can
> provide trained personnel to respond to customer questions, or other
> methods as described in the examples. Manufacturers can use reports of
> common queries and vulnerabilities to identify ways to improve the
> cybersecurity of the IoT device. For broadly used IoT devices, some
> customers may need additional support to securely provision and use an
> IoT device.

a.  **Customer Queries**

    1.  **Cybersecurity State Awareness: Establish communications**
        > **with the details necessary for answering customer questions
        > about implementing cybersecurity event awareness and control
        > directives.**

> Information that may be necessary to provide to answer questions about
> how to implement technical cybersecurity event awareness capabilities
> include details and actions such as:

-   Providing customers with answers that include the details necessary
    > to implement IoT device and associated systems security directives
    > for cybersecurity events in accordance with established time
    > frames.

-   Providing customers with a method of contacting the manufacturer to
    > obtain answers to questions about cybersecurity events related to
    > the IoT device, and related cybersecurity requirements
    > noncompliance.

    -   *Examples:*

```{=html}
<!-- -->
```
-   *Providing directions and procedures to IoT device customers
    > detailing how to submit questions and requests for information to
    > manufacturers about their IoT device related to security and
    > privacy compliance requirements.*

-   *Some examples of regulatory compliance requirements information
    > that may be needed include for the: Federal Information Security
    > Modernization Act (FISMA), Health Insurance Portability and
    > Accountability Act (HIPAA), California Consumer Privacy Act
    > (CCPA), EU General Data Protection Regulation (GDPR).*

-   *Including within the reporting instruction to the IoT device
    > customer a timeframe within which such IoT device compliance
    > questions and requests will be answered.*

    1.  **Device Acquisition and Maintenance: Establish ways for IoT
        > device customers to document attempts to obtain the IoT device
        > components or information.**

> Information that may be necessary to provide include details and
> actions such as:

-   Providing the details necessary for IoT device customers to document
    > attempts to obtain IoT device components, or IoT device
    > information system service documentation when such documentation
    > is either unavailable or nonexistent, and documenting the
    > appropriate response for manufacturer employees, or supporting
    > entities, to follow.

-   Following procedures to obtain input from IoT device customers about
    > the breadth and depth of the technical documentation provided with
    > the IoT device to determine if it is acceptable to support
    > customer needs.

    1.  **Device Acquisition and Maintenance: Establish customer
        > communications methods to the manufacturer to allow for
        > questions about the security of the IoT device, ask for help
        > with securing the IoT device, or related questions.**

> Information and actions that may be necessary to provide to IoT device
> customers include:

-   Providing a process to IoT device customers to follow to contact the
    > manufacturer to ask questions or obtain help related to the
    > minimum requirements they need to implement for the IoT device
    > configuration settings.

    1.  **Establish a customer services support communications
        > capability to respond to customer calls and queries.**

> Manufacturers may need to create, or add responsibilities to, their
> service support / call center teams to answer questions from IoT
> device customers. Information that may be necessary to provide to IoT
> customers, as well as the manufacturer's' internal or external
> supporting call center staff, include details and actions such as:

-   Providing the details necessary for IoT device customers to contact
    > the manufacturer's call center with questions, concerns, or to
    > report potential security or privacy problems with their IoT
    > device.

-   Establishing policies and procedures for call center staff to follow
    > to verify the identity of customers.

-   Establishing policies and procedures for call center staff to follow
    > to document IoT device customer calls.

-   Providing an online communications portal for IoT device customers
    > to use to receive and respond to security questions, report areas
    > of concern, and other IoT device related communications.

C.  **Information Dissemination -- From the Manufacturer and/or
    Supporting Entity**

> **The ability for the manufacturer and/or supporting entity to
> broadcast and distribute information related to cybersecurity of the
> IoT device.**
>
> This capability supports on-going cybersecurity of the device by
> keeping customers informed of developments and new information after
> the initial documentation was developed and provided.
>
> Customer organizations may need to be informed about
> cybersecurity-related activities on the IoT device, especially if the
> IoT device is critical to their operations. Customer organizations
> will want to stay informed about the cybersecurity of IoT devices to
> allow them to fine tune their mitigations and maintain an adequate
> level of risk assurance.
>
> Customer organizations may need to know the security practices of the
> manufacturer and/or supporting entities that have made or will have
> occasional or ongoing access to the IoT devices to enable them to
> ensure the other parties do not unacceptably add to the customer's
> cybersecurity risk. Customer organizations may need to maintain a
> history of such documentation that may then be considered when
> situations arise where other types of IoT devices are proposed to
> replace the existing IoT device. Customer organizations may also want
> to view security certifications, accreditations and evaluations for
> what is typically third-party assurance of acceptable information
> describing cyber, networking, applications, and related security
> practices.
>
> Customer organizations can use the associated documentation to support
> their evaluation of the adequacy of the security provided by the
> manufacturer and/or supporting entities and related IoT device.
> Customer organizations who must ensure IoT devices comply with the
> associated laws and regulations for which they are covered can use the
> documentation to support their IoT purchase decisions and risk
> assessments.

1.  **The procedures to support the ability for the manufacturer and/or
    > supporting entity to alert customers of the IoT device about
    > cybersecurity relevant information.**

> This section of capabilities includes non-technical communications and
> actions that manufacturers can provide to alert IoT device customers
> about cybersecurity information relevant to the IoT device. These
> capabilities support on-going cybersecurity of the device by keeping
> customers informed of developments and new information after the
> initial documentation was developed and provided. Customer
> organizations may need to be informed about cybersecurity-related
> activities on the IoT device, especially if the IoT device is critical
> to their operations.
>
> Manufacturers and/or their supporting entities can provide security
> alerts, advisories and other types of information, such as those
> provided as examples in the section, to IoT device customers to
> maintain situational awareness throughout the IoT device customer\'s
> system.

a.  **Software update availability or application**

```{=html}
<!-- -->
```
1.  **Data Protection: Establish communications with the details
    necessary for maintaining IoT device data integrity during software
    modifications.**

> Information that may be necessary to provide about maintaining data
> integrity during software modifications include details and actions
> such as:

-   Providing details for how to review and update the IoT device and
    associated systems while preserving data integrity.

```{=html}
<!-- -->
```
-   *Examples:*

    -   *IoT device customers often need details from IoT device
        > manufacturers to comply with their applicable security
        > policies and legal requirements for reviewing and updating the
        > current IoT device and associated systems to preserve data
        > integrity.*

        -   *The manufacturer can provide instructions for how to create
            > backups of the data prior to performing updates, and then
            > how to do a comparison of the data in the device after the
            > update with the backup data to ensure data integrity.*

```{=html}
<!-- -->
```
-   Providing information detailing the trigger events that will result
    > in automated updates to the IoT devices, or will indicate the need
    > for a manual update.

-   Providing communications with details about updates and possible
    > impacts to IoT device data integrity (e.g., alerting users if an
    > update will delete data).

    1.  **Software Update: Establish communications with the details
        necessary to meet customer requirements for software updates for
        flaw remediation and security-relevant reasons.**

> Information that may be necessary to provide include details and
> actions such as:

-   Providing details for performing the tests necessary for IoT device
    > and related system software updates related to flaw remediation,
    > for effectiveness and to identify potential side effects before
    > installation.

-   Providing communications describing the types of security and
    > privacy tests necessary for the IoT device and software before
    > installation.

-   Providing the details necessary for the installation of IoT devices
    > and associated systems security-relevant software updates within
    > an organizationally-defined time period from the vendor release of
    > the updates.

    -   *Examples:*

```{=html}
<!-- -->
```
-   *Providing information to IoT device customers and stakeholders
    > regarding the criticality of IoT device software and hardware
    > updates, and the recommended time period within which the update
    > should be installed.*

-   *Communicating to IoT device customers and other stakeholders the
    > IoT device system environment dependencies and/or potential
    > impacts for the updates.*

    a.  **End of term of support or functionality for the IoT device**

    ```{=html}
    <!-- -->
    ```
    1.  **Unsupported IoT Device: Establish communications describing
        > the security impacts of using the IoT device when the
        > manufacturer no longer supports or provides functionality for
        > the IoT device.**

> Such information is important for security risk mitigations since when
> manufacturers and/or their supporting entities no longer provide
> critical software patches, this provides a substantial opportunity for
> adversaries to exploit new weaknesses discovered in the currently
> installed IoT devices. Information that may be necessary to provide
> include details and actions such as:

-   Providing information with the details necessary to determine
    > exceptions and/or alternatives to replacing unsupported IoT
    > devices.

    -   *Example: Possible exceptions may include IoT devices that
        > provide critical mission/business capability where newer IoT
        > devices are not available or where the IoT devices are so
        > isolated that installing a replacement IoT device is not an
        > option.*

-   Providing information to allow for in-house support from within the
    > IoT device customer organization.

    -   *Example: IoT device customers can establish in-house support by
        > developing customized patches for critical software components
        > or securing the services of external providers who, through
        > contractual relationships, provide ongoing support for the
        > designated unsupported IoT devices. Such contractual
        > relationships can include, for example, those supporting
        > entities that were used by the IoT device manufacturer.*

-   Providing information with the details describing service contract
    > completion and the situations that define the end of the system
    > integrator or external service provider relationship. This is
    > important to know for re-compete, potential changes in providers,
    > and also to manage system end-of-device-life processes.

    a.  **Needed maintenance operations**

        1.  **Cybersecurity State Awareness: Establish communications
            > with the details for responding to privacy and security
            > and maintenance alerts, advisories, and directives from
            > outside of their organization.**

> Information that may be necessary to provide include details and
> actions such as:

-   Providing information with the details necessary to disseminate
    privacy and security alerts, advisories, and directives about the
    IoT devices, and associated systems and then take the necessary
    actions.

-   Providing information to IoT device customers necessary to inform
    the review and update of the IoT device systems and services
    practices.

    a.  **Cybersecurity and vulnerabilities alerts**

    ```{=html}
    <!-- -->
    ```
    1.  **Cybersecurity State Awareness: Establish communications with
        > information necessary for IoT device customers to receive the
        > manufacturer's external and internal security alerts,
        > advisories, and directives.**

> Information that may be necessary to support alerts, advisories and
> directives include details and actions such as:

-   Providing information with the details necessary to implement
    > management and operational controls for how and when IoT device
    > customers will receive up-to-date security and privacy information
    > from the manufacturer, or supporting entity.

    -   *Example: Information may be provided to the IoT device customer
        on an ongoing basis about IoT devices and associated systems,
        such as information system security alerts, advisories. There
        may also be directives to take actions for the device issued
        from IoT device manufacturers, information security researchers,
        and other sources the organization determines to be valuable to
        receive from the manufacturer.*

-   Providing information with the details and instructions necessary to
    > receive the manufacturer's security and privacy updates, such as
    > IoT device information system security and privacy alerts,
    > advisories, directives, security and/or privacy research, and
    > other information that would be valuable for IoT device customers
    > to help ensure security and privacy of the IoT device.

```{=html}
<!-- -->
```
-   Providing information to IoT device customers to inform them when to
    > review and update the IoT device systems, based upon specific
    > device states, and to provide a description of the services
    > practices.

    1.  **Device Acquisition and Maintenance:** **Establish
        > communications notifying IoT device customers they should
        > review and update the IoT device, systems and services
        > acquisition practices.**

> Information that may be necessary to provide for such updates and
> services include details and actions such as:

-   Providing the instructions for following the manufacturer's updates
    > to the IoT device, systems and services acquisition practices.

-   Providing the details necessary for IoT device customers to document
    > attempts to obtain IoT device components, or IoT device system
    > service information when such information is either unavailable or
    > nonexistent, and documenting the appropriate response for the
    > manufacturer's employees to follow.

    -   *Examples:*

        -   *Providing IoT device customers with procedures detailing
            > how to submit questions about IoT device parts, use, and
            > other related issues.*

        -   *Describing how to get components for the IoT device, or how
            > to get the IoT device fixed, when necessary.*

    1.  **Device Security: Establish communications with the details
        > necessary for performing periodic IoT device security checks
        > and/or audits.**

> Information that may be necessary to provide about performing security
> checks and audits include details and actions such as:

-   Providing the details requested by IoT device customers to perform
    periodic checks and/or audits to ensure IoT device security controls
    are functioning as intended following maintenance and repairs.

```{=html}
<!-- -->
```
-   Providing IoT device customers, upon their request, with the tools,
    > assistance, instructions, and other support for the IoT device to
    > perform audit and log maintenance and repairs operations.

2.  **The procedures to support the ability for the manufacturer and/or
    > supporting entity to notify customers of cybersecurity related
    > events and information related to an IoT device throughout the
    > support lifecycle.**

> A well-defined manufacturer cybersecurity support life cycle provides
> the foundation for the successful and secure implementation and
> operation of IoT devices within customer systems. Customer
> organizations will want to stay informed about the cybersecurity of
> IoT devices throughout the lifetime of the device to allow them to
> fine tune their mitigations and maintain an adequate level of risk
> assurance. This section of capabilities includes non-technical
> communications and actions that manufacturers can provide to alert IoT
> device customers about cybersecurity information relevant to the IoT
> device to enable IoT device customers to have the most effective
> security controls for the IoT device throughout the entire life of the
> device.

a.  **New IoT device vulnerabilities, associated details and mitigation
    actions**

```{=html}
<!-- -->
```
1.  **Device Security:** **Establish communications to notify customers
    > of cybersecurity related events throughout the full time that the
    > IoT device is in use.**

> Information that may be necessary to provide include details and
> actions such as:

-   Providing communications for cybersecurity related events involving
    > or related to the IoT device.

```{=html}
<!-- -->
```
-   *Examples:*

```{=html}
<!-- -->
```
-   *Compromises of the IoT device, and associated information systems
    > and supply chain entities.*

-   *Changes or updates to IoT device roadmaps, new component
    > development, updates to components, end-of-life decisions.*

-   *The addition, replacement, and removal of IoT device personnel
    > supporting the IoT device and supply chain infrastructure changes
    > related to IoT device support and use.*

-   *Infrastructure changes within the manufacturer's supporting
    > entities, such as any new operating system rollout, hardware
    > upgrades, or replacements due to field failures, or data storage
    > architecture changes.*

    a.  **Breaches in customer IoT devices and instructions for making
        > associated fixes or actions to prevent similar breaches of
        > other devices.**

    ```{=html}
    <!-- -->
    ```
    1.  **Cybersecurity State Awareness: Establish communications for
        > responding to IoT device breaches, associated fixes to
        > vulnerabilities allowing the breaches, and breaches that have
        > occurred for similar types of IoT devices.**

> Information that may be necessary to provide include details and
> actions such as:

-   Providing security incident and breach information in a timely
    manner.

-   Using notification and communications that include incident and
    breach information for the customer's IoT device.

D.  **Education and Awareness from** **Manufacturers/Supporting
    Entities**

> **The ability for the manufacturer and/or supporting entity to create
> awareness of, and educate IoT device customers about,
> cybersecurity-related information, considerations, features, and other
> information related to reducing the risks created by the IoT device
> being implemented within the IoT customer's digital ecosystem.**
>
> This capability supports secure provisioning and on-going
> cybersecurity support for using the IoT device. For IoT devices with a
> wide range of use cases, some customers may need more education than
> others to securely provision and use the device. The complexities of
> IoT systems, devices, and use cases makes it important for
> manufacturers to create awareness and educate customers about
> cybersecurity risks, capabilities, and related issues for their IoT
> devices.
>
> Manufacturers and/or their supporting entities can provide education
> to IoT device customers covering a wide range of topics, and determine
> the content of IoT device customer security training and awareness
> based on such factors as the specific organizational requirements of
> IoT device customers, the purpose of and capabilities within the IoT
> device, and other topics as determined by the results of the
> manufacturer performing an IoT device risk assessment and taking into
> consideration the questions and concerns communicated to them from
> their customers, through the activities in capability B. Manufacturer
> Information and Query Reception. For example, growing numbers of
> regulations and laws also require manufacturers and/or their
> supporting entities to provide customers with access to the data that
> the IoT device manufacturer and/or supporting entities possess about
> them, and also to make such data portable so that customers can take
> that data and use it elsewhere. Knowing how to obtain access to such
> data requires some type of education, including formal training
> possibilities or awareness information and/or activities. Education
> may occur through many forms; in-person, videos, online modules,
> training booklets, or some other form.
>
> The education content should ultimately address the needs for IoT
> device customers to know how to use the IoT device securely and
> include such topics as those described in this capability set of
> actions.

1.  **Educate customers of the IoT device about the presence and use of
    > device cybersecurity capabilities.**

> The complexities of IoT systems, devices, and use cases means it is
> important for manufacturers to create awareness and educate customers
> about the cybersecurity capabilities of their IoT device. This section
> of capabilities includes non-technical communications and actions that
> manufacturers can provide to help ensure IoT device users know and
> understand how to use such technical capabilities. This information
> will help IoT device customers to determine the degree to which the
> manufacturer's non-technical support will help them use the technical
> IoT device cybersecurity capabilities to support their security and
> purchasing policies, and associated legal requirements.

a.  **How to use device identifiers**

1.  **Device Identity: Provide education explaining how to establish and
    > require unique identification for each IoT device.**

> Information that may be necessary to provide within the education
> activities include details and actions such as:

-   Providing IoT device customers with the details necessary to
    establish and implement unique identification for each IoT device
    associated with the system and critical system components within
    which it is used.

    -   *Examples:*

        -   *Providing capabilities within the IoT device to allow for
            > unique identification of each IoT device.*

        -   *Providing instructions for implementing and using the
            > unique IoT identifiers.*

        -   *Providing training videos showing how to implement unique
            > identifiers for the IoT device.*

-   Providing IoT device customers with the details necessary to require
    unique identifiers for each IoT device associated with the system
    and critical system components within which it is used.

    -   *Examples:*

        -   *IoT device customers may need such identifiers to be able
            > to include the devices within their system device
            > inventories.*

        -   *For IoT devices that contain personal data, such device
            > identifiers may be needed to locate personal data in
            > storage.*

    a.  **How to change configuration settings**

        1.  **Device Configuration:** **Provide IoT device customers
            > with the education necessary to** **establish the IoT
            > device configuration settings and requirements.**

> Education topics that may be necessary to provide include details and
> actions such as:

-   Providing IoT device customers with the education necessary to teach
    > them how to establish then implement the minimum required IoT
    > device configuration settings.

```{=html}
<!-- -->
```
-   *Examples:*

```{=html}
<!-- -->
```
-   *Providing training (e.g., in person, online webinar, video, etc.)
    > to the IoT device customers explaining and showing how to
    > configure the devices, and how to perform related actions with the
    > devices.*

```{=html}
<!-- -->
```
-   *Providing awareness communications (e.g., posters, short video
    clips, podcast tutorials) to the IoT device customers providing tips
    related to configuring the security capabilities for the devices,
    and perform related actions.*

```{=html}
<!-- -->
```
-   Providing IoT device customers with education demonstrating how to
    > ensure the configuration changes can be performed only by
    > authorized entities.

```{=html}
<!-- -->
```
-   *Examples:*

```{=html}
<!-- -->
```
-   *Providing training based on the IoT device customers' internal
    > security policies, explaining and showing how to configure the
    > devices to meet the requirements of the policies.*

```{=html}
<!-- -->
```
-   *Providing education to the IoT device customers to demonstrate how
    > to set role-based authorization settings within the device.*

-   Providing education detailing how to set the minimum configuration
    > settings available within the IoT device, and how to change those
    > settings, to meet customers\' needs and requirements.

-   Providing education explaining the process IoT device customers need
    > to follow to contact the manufacturer to ask questions or obtain
    > help related to the minimum requirements for the IoT device
    > configuration settings.

    a.  **How to configure and use access control functionality**

    ```{=html}
    <!-- -->
    ```
    1.  **Device Configuration: Provide education for how to establish
        > the IoT device access controls.**

> Education that may be necessary to provide include details and actions
> covering topics such as:

-   Providing education explaining how to establish and enforce approved
    > authorizations for logical access to IoT device information and
    > system resources.

-   Providing education explaining how to control access to IoT devices
    > implemented within IoT device customer information systems.

-   Providing education explaining how to enforce authorized access at
    > the system level.

    -   *Example: IoT customer policies and/or legal requirements may
        require authorized access to be established at the system level
        when the associated systems host many applications and services
        in support of mission and business functions, and that access
        enforcement mechanisms can also be used at the application and
        service level to provide increased information security and
        privacy.*

    a.  **How to use software update functionality, including aspects
        > such as update validation that may be part of the device
        > cybersecurity capability**

        1.  **Device Configuration: Provide education explaining how to
            > establish software update functionality.**

> Education that may be necessary to provide include details and actions
> such as:

-   Providing education explaining how to inspect IoT device and/or use
    > maintenance tools to ensure the latest software updates and
    > patches are installed.

-   Providing education for how to scan for critical software updates
    > and patches.

2.  **Educate customers about how an IoT device can be securely
    > reprovisioned or disposed of.**

> IoT devices, associated data, documentation, tools, or system
> components can be disposed of at any time during the device life cycle
> (not only at the end of life or service). For example, disposal of an
> IoT device's components and/or data can occur during research and
> development, design, prototyping, or operations and maintenance and
> can be accomplished using a wide range of methods. Opportunities for
> compromise during disposal affect physical and logical data. This
> section of capabilities includes non-technical communications and
> actions that manufacturers can provide to help ensure IoT device
> customers use secure disposal methods based upon the type of IoT
> device, the associated data and supporting documentation and system
> components.

a.  **Device handling, retention, and disposal**

    1.  **Data Protection: Provide education explaining how to implement
        > security safeguards within customers' IoT device data handling
        > and retention practices.**

> Education topics that may be necessary to provide include details and
> actions such as:

-   Providing educations describing how to securely handle and retain
    IoT device data, associated systems data, and data output from the
    IoT device, to meet requirements of the IoT device customers'
    organizational security policies, contractual requirements,
    applicable Federal laws, Executive Orders, directives, policies,
    regulations, standards, and other legal requirements.

```{=html}
<!-- -->
```
-   Providing education that explains and/or demonstrates how to
    securely and irreversibly to delete data from the IoT device and any
    associated data storage locations.

3.  **Make customers aware of their cybersecurity responsibilities
    > related to the IoT device and how responsibilities may be shared
    > between them and others, such as the IoT device manufacturer.**

> Manufacturers and/or their supporting entities can provide basic and
> advanced levels of IoT device security training to IoT device
> customers, using the best training method as it relates to the
> customers, the type of IoT devices, and other related factors,
> describing the customer's responsibilities for IoT device security
> activities, such as those related to maintenance of the IoT device.
> This section of capabilities includes non-technical communications and
> actions that manufacturers can provide to help IoT device customers
> fulfill their responsibilities related to the operation of the IoT
> device within the context of their own systems within which the IoT
> device is implemented, and in accordance with their own security and
> privacy programs.

a.  **Device maintenance**

    1.  **Device Acquisition and Maintenance:** **Provide education
        > explaining in detail how to perform IoT device maintenance.**

> Education that may be necessary to provide include covering details
> and actions such as:

-   Providing education that explains the legal requirements governing
    IoT device maintenance responsibilities, or how to meet specific
    types of legal requirements when using the IoT device.

    -   *Examples:*

        -   *IoT device customers often require their personnel with
            roles and responsibilities for ensuring compliance with
            legal requirements applicable for their organization to take
            training to understand how to use computing devices in ways
            that meet those legal requirements. They often will then in
            turn provide training within their organization to those who
            will be using the IoT devices.*

        -   *IoT device customers subject to healthcare regulations
            (such as HIPAA), financial regulations (such as GLBA),
            and/or US federal regulations (such as FISMA) will need to
            know the specific existing IoT device capabilities that fall
            under those regulations.*

-   Providing education and supporting materials to ensure the
    individuals filling the established IoT device customer roles
    understand the requirements for specified maintenance procedures.

-   Providing education and supporting materials to support the
    responsibilities for IoT device customer's data security roles.

-   Providing education and supporting materials to IoT device customers
    explaining how to establish roles and responsibilities for IoT
    device data security, using the device capabilities and/or other
    services that communicate or interface with the device.

```{=html}
<!-- -->
```
-   Providing education and supporting materials describing the IoT
    device capabilities for role-based controls, and how to establish
    different roles within the IoT device.

-   Providing education and supporting materials for how to establish
    roles to support IoT device policies, procedures and associated
    documentation.

-   Providing education and supporting materials to be used by IoT
    device customer personnel with information security
    responsibilities, and others as determined appropriate.

-   Providing education and supporting materials explaining recommended
    IoT device roles and responsibilities to support the ability for IoT
    device customers to determine the appropriate level within their
    organizational hierarchy of privileges to establish those roles.

4.  **Provide training to IoT customers that explains the manufacturer's
    > key assumptions and expectations related to the cybersecurity of
    > the IoT device.**

> Manufacturers and/or their supporting entities can provide education
> and associated supporting materials to IoT device customers describing
> the key assumptions for how the IoT device will be used, the needed
> types of physical, administrative and systems security controls that
> are expected to be implemented to support the strongest security for
> the IoT device, and the expectations the manufacturer has related to
> the use of the IoT device, and related impacts to security risks for
> which the IoT customer needs to be aware. This section of capabilities
> includes examples of such non-technical education that manufacturers
> can provide to make the IoT customer aware of expectations and
> assumptions for how the customer will use the device.

a.  **Device Assumptions and Expectations**

    1.  **Device Security:** **Provide education** **that clearly
        > describes the assumptions and expectations for how the IoT
        > device customers will manage risk for the IoT device.**

> Information that may be necessary to provide include details and
> actions such as:

-   Providing education explaining the responsibilities of IoT device
    > customers to perform their own risk assessments using the
    > information provided by the manufacturer, to determine the risks
    > the IoT device will bring into the IoT device customer's systems.

5.  **Provide training for how to back-up the data collected from or
    > derived by the IoT device, and how to access such data that is
    > stored in cloud storage, or other repositories.**

> Data backups must be made to support IoT device customers'
> organizational requirements and as required by each organization's
> applicable laws, executive orders, directives, regulations, or other
> legal requirements regarding specific categories of information (e.g.,
> personal health information). Manufacturers can provide education to
> IoT device customers explaining and/or demonstrating how to back-up
> the data collected, derived from, stored, transmitted and/or processed
> by the IoT device, in addition to the IoT device system-level
> information including, if applicable, system state information,
> operating system software, middleware, application software, and
> licenses. This section of capabilities includes non-technical
> educational activities that manufacturers can provide to IoT device
> customers to teach them how to backup, access and restore IoT device
> related data.

a.  **Creating Backups**

    1.  **Data Protection: Provide training explaining how to create and
        > restore from IoT device data backups.**

> Education and supporting materials that may be necessary to provide
> include details and actions such as:

-   Providing education to IoT device customers covering the
    > instructions and details necessary for them to create accurate
    > backups, and to recover the backups when necessary.

    -   *Example: IoT device customers often need this information to be
        > able to create, update, or meet compliance with their own
        > organizational backup and recovery policies and procedures
        > that detail how to make backups of IoT device data and
        > software as applicable.*

-   Providing education to IoT device customers that includes
    > instructions describing how to back up data from systems where IoT
    > device data is stored.

-   Providing awareness reminders and tips to IoT device customers
    > (e.g., directly in person, in videos, in an online webinar) for
    > various aspects involved with backing up the IoT device data.

6.  **Educate customers about threat and vulnerability management
    > options available for the IoT device or associated system that
    > could be used by customers.**

> This section of capabilities includes education activities that
> manufacturers can provide to IoT device customers to make them aware
> of the full range of cybersecurity threats and vulnerabilities
> associated with the IoT device, and their options for managing them.
> Manufacturers and/or their supporting entities can provide education
> to IoT device customers describing the IoT device and/or
> manufacturer's threat and vulnerability monitoring for IoT device
> components, ensuring that potential threats are not overlooked.
> Providing education to IoT device customers about vulnerability
> management options will provide them with the knowledge necessary for
> them to most effectively manage risk within the systems where the IoT
> device is implemented.

a.  **State Awareness**

    1.  **Cybersecurity State Awareness: Provide education that
        > describes the details necessary for malicious code protection,
        > detection and eradication.**

> Information that may be necessary to provide, as determined by the
> manufacturer's assessment of cybersecurity risk created by the IoT
> device, include details and actions such as:

-   Providing education to IoT device customers for how to implement
    > malicious code protection in the IoT device and associated
    > systems, as well as within related systems entry and exit points,
    > and how to detect and eradicate malicious code.

```{=html}
<!-- -->
```
-   *Examples:*

```{=html}
<!-- -->
```
-   *Providing information to the IoT device customers that describe the
    > vulnerabilities to malware for the associated IoT devices, and
    > advice for the best types of anti-malware to use. If no
    > anti-malware is needed for the IoT device, explain why.*

> *Providing information about the IoT device resource restraints
> related to malicious code protection and possible compensating
> controls that IoT device customers can use for such restraints.*

-   Providing education to IoT device customers for how to update the
    > IoT device and related systems malicious code protection
    > mechanisms when new releases are available, in accordance with
    > organizational configuration management policy and procedures.

-   Providing training and awareness information to IoT device customers
    > that describe newly identified vulnerabilities and threats (such
    > as zero-day malware) for the associated IoT device.

-   If the IoT device manufacturer provides anti-malware for the
    > associated IoT device, or if the IoT device has built-in
    > anti-malware capabilities, the manufacturer should provide
    > education to the IoT device customers describing how to use and/or
    > configure malicious code protection mechanisms in IoT devices,
    > supporting anti-malware tools, and related systems.

```{=html}
<!-- -->
```
-   *Examples:*

    -   *How to schedule automatic scanning on the IoT device.*

    -   *How to perform real-time scanning for new files introduced
        > through the IoT device interfaces.*

    -   *How to block and/or quarantine malicious code to allow for
        > inspection of that code by customer organizational roles with
        > those responsibilities.*

    -   *How to configure the IoT device to shut-down upon detecting
        > malicious code, as appropriate to the purpose of the IoT
        > device.*

    -   *How the IoT device user should address false positives and how
        > to report the false positives to the manufacturer.*

    -   *Explanations and examples of the possible availability and
        > functioning impacts on the associated IoT device and the
        > system within which it is implemented*

```{=html}
<!-- -->
```
-   Providing education describing the operational impacts of the
    > anti-malware activities on mission critical processes in the
    > system where the IoT device is used.

```{=html}
<!-- -->
```
-   Providing education describing the options and recommended responses
    > to malicious code identification within the IoT device.

```{=html}
<!-- -->
```
-   *Examples: shutting down the device; redirecting the network
    > traffic; sending alerts; logging the events; etc.*

```{=html}
<!-- -->
```
-   Providing education that include the details necessary to implement
    > management and operational controls for malicious code detection
    > and eradication.

    1.  **Software Update: Provide education explaining and/or showing
        > how to incorporate IoT device flaw remediation into the
        > customer's configuration management process.**

> Education and supporting materials that may be necessary to provide
> include details and actions such as:

-   Providing the education explaining how to incorporate IoT device
    flaw remediation into the IoT device customer's
    organizationally-defined configuration management process.

-   Providing the education explaining the processes that the
    manufacturer, or supporting entities, will follow to communicate the
    IoT device remediation efforts with stakeholders (IoT device
    customers, users, etc.).
