# 2.	Introduction
## 2.1	Overview
The Digital Business Council (Council) provides a framework for interoperability in digital business, expressed as a set of technical specifications (Profiles) and usage guidelines (Implementation Guides). Profiles and Implementation Guides are designed to facilitate effective business based on a modular approach for implementation, with a focus on global interoperability.
Council Profiles can be seen as agreements on message contents and business processes. The profile descriptions focus on the core information elements that typically cater to the majority of user requirements applicable across Australia and lower the need for detailed bilateral agreements between the trading partners.

The Digital Capability Locator (DCL) is used by Access Points to enable the eInvoicing process.  Figure 1 highlights the role of the DCL within the standard four-corner model.
 


*Figure 1 Four-corner model*


The Digital Capability Locator and Digital Capability Publisher are needed for an Access Point to determine the destination of a message in a dynamic environment. The Digital Capability Locator is a mapping of participant identifiers to the digital address of the participant’s Digital Capability Publisher. 


The Digital Capability Locator Implementation Guide (Digital Business Council, 2016b) incorporates the Council's Metadata Service Location Profile which describes a technical specification for the automated lookup of digital address information for a participant's capability metadata. The profile is based on the OASIS Business Document Metadata Service Location Committee Specification Version 01 (OASIS, 2014) which standardises retrieval of information about a participant's digital address.  The specification is based on the successful implementation within the PEPPOL program.


The Digital Capability Locator Implementation Guide provides further guidance for service consumers, specifically in relation to the management of participant and Digital Capability Publisher information stored in the Digital Capability Locator.
A single, centralised Digital Capability Locator will exist in a four-corner model and MUST implement the Council’s profile.

This document provides the high-level business requirements for the Digital Capability Locator in the format of Agile Epics.   Most Epics have a direct reference back to the Council’s interoperability Framework and specifically the Digital Capability Locator Implementation Guide.


## 2.2	Description of Actors
The following table contains descriptions of the key actors (natural persons, organisations and systems) referenced in this document.


ID | Actor/Role	| Category | Description
---|---|---|---
R001 | Australian Business | Organisation | Synonyms - Participant
R002 | Accredited Access Point (AP) | System | A software system offering Access Point Services that has been tested and accredited in accordance with the Council’s Interoperability Framework. Synonyms – Access Point
R003 | Accredited Digital Capability Publisher (DCP) | System | A software system offering DCP services that has been tested and accredited in accordance with the Council’s Interoperability Framework. Synonyms – Digital Capability Publisher
R004 | Digital Capability Locator (DCL) | System | Described by this document.
R005 | DCL Operations Support Staff | Natural Person | Staff who support the day to day operations of the DCL.  This includes responding to queries and operational issues.
R006 | DCL Maintenance Staff | Natural Person | Staff who maintain (build, test and deploy) changes and enhancements to the DCL.
R007 | DBC Technical Working Group | Forum | The Council’s Working Group responsible for the creation of the framework’s technical design and supporting Implementation Guides.
R008 | Accreditation Authority | Natural Person | An individual with the delegation to issue, suspend or revoke an organisation’s accreditation.
R009 | Accreditation Support Staff | Natural Person | A staff member who supports the Accreditation Authority to fulfil its duties,
R010 | Accredited Access Point Provider | Organisation | The organisation/legal entity which operates an Accredited Access Point – R002. Synonyms – Accredited Service Provider
R011 | Accredited Digital Capability Publisher Provider | Organisation | The organisation/legal entity which operates an Accredited Digital Capability Publisher – R003. Synonyms – Accredited Service Provider
R012 | Assigned Testing Partner Organisation  | Organisation | Any Accredited Service Provider (R010 & R011) assigned to support interoperability testing.
R013 | DBC Secretariat | Organisation | Provides a mechanism to clarify testing problems and facilitates dispute resolution.
R014 | Identifier Issuing Authority | Organisation | ABR, GS1, Dun and Bradstreet
R015 | DCL Operator | Organisation | The organisation that runs, operates and maintains the DCL.

Figure 2 shows the relationship between the key actors and the Digital Capability Locator:
 
*Figure 2. DCL Key Actors and Relationships*
 
## 2.3	Key Definitions
The following table contains a definition of key terms used throughout this document.

Term | Definition
---|---
Accreditation | Accreditation is a process by which an Access Point Provider or a Digital Capability Publisher Service Provider is recognised by the Digital Business Council (Council) as having met certain technical criteria. It should be noted that accreditation is mandatory for a Service Provider (Access Point or Digital Capability Publisher) if it intends to provide services under the Council’s Framework.
Accredited Service Provider | An organisation who has been accredited to operate in accordance with the eInvoicing Interoperability Framework.  (Refer section 2.2 R010 or R011)
Anonymous | Anonymous, in a general computing context, means keeping a user's name and identity concealed through various applications.
Application Programming Interface (API) | Just as a graphical user interface makes it easier for people to use programs, application programming interfaces make it easier for developers to use certain technologies in building applications through abstraction  of the underlying implementation and exposure of only the objects or actions the developer needs.
Business | An enterprise conducting economic activity.
Conformance | Compliance with standards, rules, or laws.
Digital Capability Address | The address of a participant’s Digital Capability Publisher
Epic | A common term used in Agile software development techniques.  Epics are feature-level work that encompasses many user stories.
Participant | The generic term to represent a consumer of eInvoicing or eDelivery services offered by Accredited Service Providers (R002 & R003). In the context of eInvoicing the participant would be a Business.  For eBilling the participant may be either a business or an individual.
User Story | A user story is a tool used in Agile software development to capture a description of a software feature from an end-user perspective. The user story describes the type of user, what they want and why. A user story helps to create a simplified description of a requirement.

