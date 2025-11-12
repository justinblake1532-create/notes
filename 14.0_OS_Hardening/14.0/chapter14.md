
# Basic File Permissions


## Read(r)
 : being able to read/access files


## Write(w)
 : Being able to edit a file and save changes to that same file


## Execute(e)
 : Being able to run a file, app or script on a system


## chmod
 : a <ins>linux</ins> command for managing file permissions



# File Server Security


## File Server
 : A dedicated piece of hardware/software on an organizations network that is responsible for storing and securing data


## Shared Folder
 : A type of folder whose contents are available across a network; multiple users can access the contents of this folder


## Securing File Servers
### * Limit Physical Access to the Server
### * Backup Data on External Devices
### * Encrypt Important Data
### * Implement strong Authentication Methods
### * Proper Usage of Access Control Lists
### * Removing and Uninstalling unecessary Software
### * Limit Access to Shared Folders


## Least Privilege
 : A pricipal is granted the minimum possible sufficient rights to complete a task they are authorized to perform


## Authorization Creep
 : A scenario where a user acquires more rights over time directly or by being added to security groups or roles


## Provisioning
 : The process of setting up a service according to a standard procedure or best practice checklist



# File System Permissions


## Share Permissions
 : A type of permissions architecture that controls access through a network connection with the file server
 * Have 3 levels of Permissions
 * Share Permissions can only be set to a folder
 * If files are accessed on a local device, the share permissions don't take effect


## New Technolody File System(NTFS)
### * Can be set to drives, folders, and files
### * Able to control access to resources on local and network resources
### * Multiple Permissions to Assign
### * Can only be set on colunmns formatted with NTFS


# Hardening


## Hardening
 : The ongoing process of changing an asset/resource for it to operate in a more secure manner than before


## Simple Methods for Hardening a Workstation
* Automatice Updates
* Removing Unecessary Software
* Limiting Privileges in User Accounts
* Strong Authentication Features


## Path Management
 : Idnetifying, testing, and deploying OS and application updated
 * Cruscial to test patches before deploying them throughtout the network



# Network Protocols for Data Transfers


## FTP
 : Sending and receiveing files over a network transmission; not a secure method of sending data


## Trivial File Transfer Protocol(TFTP)
 : A type of FTP protocol that provides no security implementations; uses UDP over TCP; faster than TCP


## Secure Copy Protocol(SCP)
 : Uses vefrsion one of SSH to secure file transfers and login credentials


## Secure Shell File Transfer Protocol(SFTP)
 : A file transfer protocol that uses secure shell version 2(SSH2) to secure data transfers; <ins>NOT</ins> a vairant of FTP protocol


## Secure FTP
: A network protocol that funnels FTP traffic through an SSH tunnel


## FTP Secure
 : A network protocol that adds either SSL or TLS to an FTP transmission to secure logon credentials and encrypt data transfers; requries a server certificate to operate



# OS Hardening Best Practices


## - Implementing Access Controls
## - Incorporate Priciple of Least Privilege for User Accounts
## - Allow/Block Lists
## - Monitoring Device Activity
## - Enforcing Policies
## - Decommissioning
## - Changing/Removing Defaults and Unnecessary Software
## - Implementing different forms of encryption helps to maintain the confidentiality of the data on the client system. Some encryption methods that meet this goal include:
### * Full Disk Encryption(FDE)
### * Removeable Media Encryption
### * Virtual Private Networks(VPN)
### * Email Encryption



# Provisioning Checklist


## Identity Proofing
 : Ensuring the individual says who they say they are


## Issuing Credentials
 : The individual is provided credentials to gain authorzied access to resources


## Issuing Hardware/Software Assets
 : The individual is provided necessary assets to perform their day-to-day tasks


## Teaching Policy Awareness
 : Training and providing resources to the individual so they can perform their tasks as intended


## Creating Permission Assignment
 : Identifying the roles and permissions the individual needs to have access to


## Deprovisioning
 : The process of removing the access rights and permissions allocated to an employee when they leave the company or from a contractor when a project finishes

