
# 2.	General quality of service requirements

## 2.1	Business data

The following quality of service requirements relates to the business data that are stored, extracted and transmitted to and from the DCL and DNS:

ID|Relates to|Requirement|Reference|Mandatory/Optional/Desirable
---|---|---|---|---
NFR-01	Data format	The lookup service in the DCL shall conform to the standard web Uniform Resource Locators (URLs) to resolve Business Identifiers. 	Rf07
M

2.2	Digital Capability Locator (DCL)
The following quality of service requirements relates to Digital Capability Locator (DCL):
ID	Relates to	Requirement	Reference	Mandatory
Optional
Desirable
NFR-02	Infrastructure / Hardware	The DCL must operate on distributed and highly-redundant infrastructure that is based in Australia.  
This will prevent the service from a single point of failure and will ensure that sensitive information about Australian businesses is maintained onshore. 	Rf07
Rf02
M
NFR-03	Infrastructure / Hardware	The equipment that supports the DCL must be capable of segregating from the network and have the network connectivity and access controls removed or disabled.  
This will isolate affected systems that contain sensitive information from harm during a data spill. 	Rf01
M
NFR-04	Availability		The DCL must be capable of providing 100% service uptime.	Rf07
M
NFR-05	Encryption	Communication to and from the DCL must be encrypted over the public network. 	Rf01
M
NFR-06	Authentication	The DCL must only accept authenticated clients with valid certificates issued for use in the infrastructure by a trusted third-party.	Rf07
M
NFR-07	Authentication	Client authentication information shall be stored separately to the DCL.	Rf01
M
NFR-08	Monitoring	Availability monitoring, with real-time alerts, shall be used to detect denial of service with the ability to measure its impact. 	Rf01
D
NFR-09	Event logging	All transactions to and from the DCL shall be logged, including successful and failed transactions. 	Rf01
M

2.3	Domain Name Server (DNS)
The following quality of service requirements relates to Domain Name Server (DNS):	
ID	Relates to	Requirement	Reference	Mandatory
Optional
Desirable
NFR-10	Availability		The DNS must be capable of providing 100% service uptime.	Rf07
M
NFR-11	Backup strategy	The DNS facility must be capable of backing up digital addresses for recovery purposes. 	Rf01
M
NFR-12	Storage of data	The DNS facility must comply with Section 187BA of Part 5-1A of the Telecommunications (Interception and Access) Amendment (Data Retention) Act 2015 to ensure the confidentiality of digital addresses that may lead to sensitive information about businesses are stored securely and prevents unauthorised access. 	Rf02
M
NFR-13	Storage of data	The DNS facility must comply with Section 187C(1)(a) of the Telecommunications (Interception and Access) Amendment (Data Retention) Act 2015 to ensure digital addresses that may lead to sensitive information about businesses are retained as historical data for a period of two (2) years after the cessation of the information. 	Rf02
M
NFR-14	Collection of digital addresses	The DNS facility must comply with Part 2 of the Australian Privacy Principles when collecting digital addresses that may lead to sensitive information about businesses. 	Rf05
M
NFR-15	Maintaining digital addresses	The DNS facility must comply with Parts 4 and 5 of the Australian Privacy Principles to ensure the integrity of digital addresses that may lead to sensitive information about businesses is maintained. 	Rf05
M
NFR-16	Use or disclosure of digital addresses	The DNS facility must comply with Part 2 of the Australian Privacy Principles when using or disclosing digital addresses that may lead to sensitive information about businesses. 	Rf05
M

 
2.4	Vendor Services
The following quality of service requirements relates to the engagement of service providers to provide the design, implementation, and/or the support of the DCL: 
ID	Relates to	Requirement	Reference	Mandatory
Optional
Desirable
NFR-17	Outsourcing IT services	Service providers’ shall provide documented strategies to prevent and mitigate denial of service.  	Rf01
M

