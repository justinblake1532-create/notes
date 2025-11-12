
# Application Deployment and Update Methods


## App Catalog
 : Allow and organization to define applications a user can and cannot use

## Self-Service Portal
 : A service that makes the distribution of applications easier for employees

## Remote Management
 : Administrators can push updates and other configurations through a remote connection over manually installing updates and configurations
# BYOD Security


## BYOD Security
 : A practice where employees bring in their personal devices for work related tasks


## - <ins>Issues with BYOD</ins>

### * Malware Propagation
 : If a user has malware on their personal device, the same malware can spread on to the organizations network
### * Loss of Data Control
 : When a user moves sensitive data to their personal device, the organization loses control over how the data is handled
### * Insider Threats
### * Managing personal devices with organizations standards
### * End-User support


## - <ins>Alternative Deployment Models to BYOD</ins>

### * Corporate Owned Devices
 : Users have access to their own organization owned device to work on job tasks
### * Corporate Owned, Personally Enabled (COPE)
 : Organizations provide significant control over the device security while allowing the employees to use the devices to access both corporate and personal data
### * Choose Your Own Device (CYOD) 
 : Users are provided a selection of devices to choose from and use
### * Virtual Desktop Infrastructure (VDI)
 : Allows a mobile device to establish a remote connection to a virtualized desktop


# Email


## - Email Threats to Look Out For

### * Viruses
### * Spam
### * Phishing
### * SMTP Relay
 : When a SMTP relay is open, a threat actor can send spam to the targets email for the purpose of blacklisting the same service/data transmission


## - Email Protocols


### * Sender Policy Framework (SPF)
 : An email authentication method that helps detect and prevent sender address forgery commonly used in phishing and spam emails
### * Domain Keys Identified Mail (DKIM)
 : A protocol that leverages encryption features to enable email verification by allowing the sender to sign emails using a digital signature
### * Domain-Based Message Authentication, Reporting, and Conformance (DMARC)
 : A protocol that uses the results of SPF and DKIM checks to define rules for handling messages, such as moving messages to quarantine or spam, rejecting them outright, or tagging the message

## - Methods to Secure Email Transfers

### * S/MIME
### * Pretty Good Privacy (PGP)


# Embedded and Specialized Systems


## - Types of Embedded Devices

### * Smart Appliances
### * Environmental Controls
 : Sending data to devices that control the temperature and humidity of an area
### * Fasicility Automation (lighting controls, door locks, garage doors, etc)
### * Wearable Devices
### * Automobiles
### * Real-Time OS (RTOS)
 : An OS that serves real-time applications without buffer delays, generally used in systems that require a response within a strict time constraint
### * System on a Chip (SoC)
 : An integrated circuit that includes all of the main components of a computer (ex: Rasberry pi)
### * Media Gateway
 : A translation device that converts media streams for use by different telecommunication technologies
### * Multifunction Printers (MFPs)
 : A type of printer that is able to be a translation device that converts media streams for use by different telecommunication technologies
### * Arduino
 : an open-source hardware and software company


# Microsoft Intune Application Life Cycle


## Add
 : Adding an application to manage and assign in Intune

## Deploy
 : Assign the application to users and devices you manage and monitor them on the Azure portal

## Configure
 : Updating the deployed applications with new versions

## Protect
 : Implementing conditional access to safeguard deployed applications

## Retire
 : Removing applications from the application store due to being EOL or outdated


# Mobile Device Management


## - Mobile Device Management (MDM)
 : Security configurations and settings that are applied to all mobile devices associated with an organization
 * Pathces from MDM can be implemented through a network connection
 * Windows Intune is an example of an MDM solution
 * Perform remote wipes
 * Track mobile devices

## - Mobile Application Management (MAM)
 : Focuses on managing the applications on a mobile device, not the mobile device itself
 * Install and Uninstall applications remotely
 * Update applications as needed
 * Limit permissions for using installed applications

## - Enterprise Mobility Management (EMM)
 : Combines the MDM and MAM solutions; allows system admins to remotely manage a mobile devices hardware and applications
 * Being able to manage multiple different types of devices in a single package

## - Unified Endpoint Management (UEM)
 : The joinging together of traditional device management and enterprise mobility management solutions


# Mobile Device Terminology


## App Allow List
 : The process of identifying applications that users are allowed to have on mobile devices

## Geotagging
 : Embedded GPS coordinates within mobile device files

## Jailbreaking
 : Removing inherent protections placed by the device manufacturer

## Sideloading
 : Installing an application on a mobile device via a method other than the manufacturers application repository


# Security Considerations with Mobile Devices


## Geofencing
 : Restricting a device to a particular geographical area

## Geolocation
 : Identifying a devices location using the device specific data(GPS coordinates, network connection, etc.)

## Authorizing techniques implemented on the lock screen

## Encrypting important data


# Types of Connections Used on Mobile Devices


## - Cellular
## - WiFi
## - Bluetooth
## - NFC
## - USB
## - Infrared
## - Satellite