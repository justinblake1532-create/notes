# Access Control Best Practices

### Principle of Least Privilege
 : Restricts users and systems to the minimum level of access needed to perform their specific tasks


### Need to Know
 : Restriction of the information <ins>unless</ins> the user needs to know


### Seperation of Duties
 : Have multiple people complete a task


### Job Rotation
 : Making sure one group/entity doesn't have full control over a system


### Defense-In-Depth
 : Applying multiple layers of security


### Mutual Authentication
 : Two-way authentication exchange


### Time of Day Restrications
 : Only allowed to access certain entities/systems during a specific timeframe# Access Control Models


### Discretionary Access Control(DAC)
 : Each resource has an owner
- Weak Implementaion


### Mandatory Access Control(MAC)
 : Subjects/Objects need a <u>clearance<u> to access resources
- Security goes both ways


### Role-Based Access Control(RBAC)
 : Controls based on the users job functions


### Attribute-Based Access Control(ABAC)
 : Evaluates suject specific details


### Rule-Based Access Control(RuBAC)
 : Policies are enforced on users/systems
- Conditional Access# Access Controls


### Access Controls
 : Ensures the CIA triad is met; governs how subjects interact with objects
# Active Directory


## Assets

- PCs(Client Systems)
- Servers
- SSO -> Authentication
- Users
- Networks

## Directory Service
 : A netowrking architecture that stores information on all IT assets for an organization

## Lightweight Directory Access Protocol(LDAP)
 : A netowrking protocol used to access netowrking/directory services

## Active Directory(AD)
 : A proprietary service owned by microsoft that serves as a centralized database containing all information for an organizations IT assets
* <ins>Domain Controllers</ins> -> The devices that centralize all IT assets
* AD allows for easier security configurations; easy to organzie resources in general
* Easily copy the AD database/domain controller
* Able to assign user specific rights/privileges
* Scaling resources more efficiently # Additional Policies


### Location-Based
 : Physical or system location

### Time-Based
 : How long a user can access a system/entity# Authorization Permissions


### Authorization Permissions
 : The process of granting or denying a user, program, or process the permission to access a specific resource, based on their authenticated identity


## Authorization Permission Rules


1. ### Deny Permissions
2. ### Allow Permissions
    - ### Deny > Allow
        * ### Deny permissions always override allow permissions
3. ### Explicit Allow
4. ### Inherited Deny
    - ### Explict Allow > Inherited Deny
        * ### Explicit permissions always override inherited deny permissions
# Components of Active Directory


## Domain
 : A collection of network resources that share a common directory database and policies; basic administrative unit of Active Directory structure


## Tree
 : A group of related domains that share the same contiguous DNS namespaces


## Forest 
 : The highest level of organization hiearchy in AD
* Collections of related domain trees


## Organizational Units(OUs)
 : A folder that subdivides IT resources and organizes them within a domain


## Generic Containers
 : A networking resource that are initially created when a domain is created
* Can't be adjusted, deleted, renamed at all


## Objects 
 : Resources in Active Directory(users, computers, shared folders)
* Objects contain attributes unique to them


## Groups
 : A collection of objects that have similar attributes to each other

# Data Governance Roles


## Owner
 : High-ranking employees, CEOs, ultimately resposible for securing and classifying data


## Controller
 : Public authority/agency, identifying how data should be processed, makes sure data handling meets <ins>legal</ins> requirements


## Processor 
 : Third-party vendor, processes data, maintains a public record of data transactions, ensure data is handled in a secure method


## Custodian
 : IT department, implements and enforces security policies, resports on security incidents, ensures data is sotred in a secure manner

# Deprovisioning Assets


### Deprovisioning Assets
 : Removing access to an asset
 * When employee leaves, access to company resources are revoked
# Federation


### Federation
 : Allowing <ins>shared</ins> login options for multiple trusted resources


### Open Authentication(OAuth)
 : A networking protocol that provides federation to occur. Provides third-party applications access to specific user resurces
 * ### Example: Login with Google/Facebook
# GPO Application Order


1. ## The local Group Policy on the computer
2. ## GPOs linked to the sire
3. ## GPOs linked to the domain containing the computer
4. ## GPOs linked to the organizational unit(Highest OU to Lowest OU)
# GPO Structure


## Computer Configuration
 : Enforced when the system initially boots


## User Configuration
 : Enforced when a user logs in
* (BOTH) Software installed on the system
* Running scripts


## Remote Desktop Protocol(RDP)
 : A networking protocol to operate a computer using a graphical interface# Group Account


### Group Account
 : Account where everyone has the <u>same<u> permissions and access
# Group Policy


## Group Policy(GP)
 : A windows service for managing and configuring resources throughout a centralized database/AD
* Linked to an OU or a group


## Group Policy Objects(GPOs)
 : A collection of policy setting configured for each object each time it accesses network resources
* Passworkd policies, Account restrictions# Hardening Authentication


### Account Lockout
 : Access to a user account is temporarily blocked, usually due to too many failed password attempts


### Concurrent Sessions
 : Practice of restricting the number of simultaneous active login sessions a single user account can have


### Impossible Travel
 : Detect account compromise by identifying login attempts from geographically diestant locations within a timeframe that defies physical possibility


### Password Policies
 : A set of rules that define and enforce requirements for creating and managing passwords to enhance security and prevent unauthorized access


### MultiFactor Authentication(MFA)
 : A security measure that requires users to provide two or more verification factors to prove their identity before gaining access to account or system


### Account Restrictions
 : Limit how user accounts can be used to authenticate and access a system/network


### Account Maintenance
 : Process of continually managing and applying security controls to user and service accounts to minimize the risk of compromise


### Limiting Remote Access
 : Restricting who, where, and how users can connect to a network/system


### Password Managers
 : Generating, storing, and managing strong, unique passwords in an encrypted vault, while also often supporting MFA


### Passwordless
 : Replacing traditional passwords with more secure methods like biometrics or possession factors


### Remote Access
 : A form of networking where a user's system does not make direct wired/wireless connection to a network


### Virtual Private Network(VPN)
 : Creates a secure <ins>tunnel</ins> between two systems over an unsecure network
 * Client-To-Client
 * Site-To-Site
 * Host-To-Host# Identity and Access Management


### Identity and Access Management
 : Providing a secure process to interact with specifi resources
- Identification(ID)
- Authorization(what?)
- Authentication(who?)
- Accounting(Activity)



1. Identify
2. Protect
3. Detect
4. Respond 
5. Recover


### Gap Analysis
 : A process where an organization examines thier current security posture and comparing to a known framework
# Implementing Governance


- ## Keep in mind the organizations objectives
- ## Leverage expertise for better descision making
- ## Establishing a comprehensive list of policies, procedures, and guidelines
- ## Improving consistency, reducing respose times, and supporting compliance mechanisms


## Governance Board
 : A group of senior executives and stakeholders with the resposibility for setting up strategies and ensuring compliance


# Laws for Safeguarding Data


## Healthcare
* HIPPA
* GDRP

## Financial
* GLBA
* PCI DSS

## Telecommunications
* CALEA

## Energy
* NERC

## Education and Children
* FERPA
* CIPA
* COPPA

## Government
* FISMA
* CJIS
* GSC 


## Governance Community
 : Leaders and subject matter experts with the responsibilities for defining policies, procedures, and standards within a particular domain

# MultiFactor Authentication



### MultiFactor Authentication (MFA)
 : A security measure that requires users to provide two or more verification factors to prove their identity before gaining access to account or system


## Types of MutiFactor Authentication


* ### Something You Know -----> Password
* ### Something You Are ------> Biometrics
* ### Somewhere You Are ------> Physical/Digital Location
* ### Something You Can Do ---> Writing Sample
* ### Something You Exhibit --> Personality Traits
* ### Someone You Know -------> Trusted Individual
* ### Something You Have -----> ID Badge
# Network Directories


## Network Directories
 : A compiled list of assets on a network and shows the asset's permissions


## Securing Directories

* No Authentication
* <ins>Simple Bind</ins> -> using a username and password
* <ins>Simple Authentication and Security Layer(SASL)</ins> -> clients and servers negotiate using a supported authentication method
* <ins>LDAP Secure(LDAPS)</ins> -> servers are installed with digital certificate to set up a secure tunnel for exchanging credentials # Provisioning Assets


### Provisioning Assets
 : Initially deploying an asset
 * User Account
 * Web Server

# Remote Access Administration Services


## AAA Server
 : Handles user requests for IT resources; Any policies defined on AAA server applies to all connected clients
* RADIUS
* TACACS+


## RADIUS
 : A microsoft service for centralized remote access administration; Combines AAA policies for users to access resources, all A's must be present in RADIUS; Encrypts passwords usign MD5; UDP ports 1812 and 1813


## TACACS+
 : Developed by Cisco for centralized remote access administration; Used different protocols for each of the A's; Encrypts the entire contents of network packets sent and received on the network; TCP Port 49
# Security Governance


## Objective
 : Develop, implement, and maintain policies, procedures, standards, guidelines to protect assets and IT infrastructure
* Governance Frameworks must be compliant with laws, regulations, and contractual obligations


## Governance
 : Creating and maintaining policies and procedures to manage assets
* Ensure compliance with regulations at the local, state, and gobal level
* Manages legal risk
# Single Sign On


### Single-Sign On(SSO)
 : Authenticating subjects to access resources <u>without<u> entering credentials again


### Kerberos
 : An implementation of SSO; SSO network authentication and authorization protocol that is <u>time-sensitive<u> and uses a ticket-generating system
# Types of Governance


## Centralized Governance
 : Top-down approach where a single, central authority defines and enforces security policies acorss and an entire organization


## Decentralized Governance
 : A system where power and decision-making are distributed amoung many participants, rather than concentrated in a single central authority


## Hybrid Governance
 : Combines the centralized control of a top-down model with the decentralized felxibility of a bottom-up approach

 # VPN Networking Protocols


### Point-To-Point Tunneling(PPT)
 : Dial-up protocol to remotely connect devices; not secure


- ### Transport Layer Security(TLS)

- ### Internet Protocol Security(IPSec)
# Windows User Accounts


### Windows User Accounts
 : An identity that a person or system uses to sign in to a computer, controlling what they can access and what they can do on it
 * Security Identifier(SID) -> A value the windows operating system gives to user account
 * Name
 * Credentials
# Zero Trust Security


### Zero Trust Security(ZTS)
 : Assumes all the assets are <u>not<u> inherently trusted; regardless if it's internal/external
- ### Reauthenticating each time a subject access resources
- ### Reduce the threat scope and increase the trust of know subjects


## Zero Trust Security Concepts


### Adaptive Identity
 : Subjects are not static


### Policy Driven Controls
 : Enforcing restrictions on users based on their attributes


### Device Posture
 : Current security status of a computing device


### Control Plane
 : Dictates how the data should be transported on a network


### Data Plane
 : Parts of the network that <ins>transfer data</ins>
 - ### Establis/Deny any data transfers