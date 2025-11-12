
# Backup and Restore


## Data Duplication
 : a data compresssion technique that optimize storage space by indetifying and eliminating redundant data

## Back Up Frequency
 : How often an organization conducts back ups on their data
 * Depends on the organizations regulatory requirements, unique needs, resk tolerance, and resources

## Snapshot
 : An instant copy of a system that can be saved and accessed if that same system were to be corrupted

## Replication and Journaling
 : Methods to ensure data availability and integrity through maintaining multiple copies and tracking changes to data
 * Replication
  : Creating and maintaining exact copies of data on different storage systems or locations
* Journaling
 : Records changes to data in a seperate, dedicated log known as a journal



# Digital Forensics


## Digital Forensice
 : The practice of collecting evidence from computer systems to a standard that will be accepted in a court of law

## Due Process
 : A low to require people only be convicted of crimes following the fair applications of the laws of the land
 * A set of procedural standards to enure fairness

## Legal Hold
 : Information that can be relevant to a cour case must be preserved
 * Systems will be taken as evidence
 * Companies will suspend deletion process during the legal hold process

## Chain of Custody
 : A document that records where, when, and who collected the evidence, who subsequently handled it, and where it was stored

## - <ins>Common Data Sources for Forensic Investigations</ins>
### * Logs
### * Files
### * Web Applications
### * Email Client

## System Memory Dump
 : A process where specialized software creates an image file that can be analyzed to identify if running processes, temporary file systems, and other important data while the system is accessing data held in RAM

## Disk Image Acquisition
 : Acquiring a device's nonvolatile storage unit(HHDs, SSDs, Optical Drives, etc.)


# Handling Data


## Isolation
 : Creating seperate zones from one larger zone for the purpose of creating a more secure environment

## Containment
 : A reactive process to stop and mitigate an attack from spreading to other resources

## Segmentation
 : Seperating a network into smaller sections

## SOAR
 : A platform that compiles security data received generated from multiple end-points on a network
 * Helps fascilitate integrating applications and services as well as focused analysis


# Incident Plans


## Runbooks
: A conditioned-based series of protocols used to establish automated processes for incident response; used with assessments, investigations, and mitigation strategies


## Playbooks
 : A document specifying how to respond to a threat or an incident



# Incident Response Process


## 1. Preparation
 : Making the system resilient to an attack in the first place

## 2. Detection
 : Discovering indicators of threat actor activity

## 3. Analysis
 : Security analysts determine if a security incident has occurred or not and assess the severity of the incident

## 4. Containment
 : Limiting the scope and magnitude of the incident

## 5. Eradication
 : Removing the cause of the incident and restoring any affected systems to a secure state

## 6. Recovery
 : Reintergrating the affected systems into the organizations and restoring any data that was lost

## 7. Lessons Learned
 : Security analysts conduct and assessment detailing the entire incident for the purpose of improving what could have been done and what can be done moving forward


# Log Data Attributes


## 1. The resources being logged(hardware, software, networks, etc.)

## 2. Where the logs are stored

## 3. Time/Data Information


## Metadata 
 : Data that is found inside of files(file creation date, last time modified, location, etc.)
 * Common types of metadata include email, mobile, and web metadata


## - Data Anlayzer Tools

### * NetFlow
 : A tool that examines the flow of the network data throughout the a network

### * sFlow
 : A tool that performs datat analysis quickly and efficiently in a small network range

### * IPfix
 : A tool that help centralize data collection from various devices on the network 


# Redundancy


## Redundancy
 : A method for providing fault tolerance by using duplicate or multiple components that perform the same function

## Fault Tolerance
 : The ability to respond to an unexpected hardware or software failure without loss of data or loss of operation


## - <ins>Methods for Implementing Secure Networks</ins>

### * Load Balancing
 : A process that distributes processing amoung multiple nodes

### * Active/active
 : Two load balancers working in tandum to distribute network traffic

### * Active/passive
 : Two load balancers with one actively working and the second one listening mode to take over if the first becomes unavailable

### * Power Scheduling
 : Used to configure an active redundancy by sending power to networks when a power fascility goes down; helps prevent total power loss

### * Virtual IP(VIP)
: An IP addresss that isnt't assigned to a signle system; can be assigned to multiple systems

### * Geographical Dispersal
 : The use of multiple locations to store data to mitigate downtime due to location

### * Multipath
 : A fault-tolerance technique that gives multiple physical paths between a CPU and a mass-storage appliance

### * Uninterrupted Power Supply(UPS)
 : A stand-alone bank of batteries that allows for the gracedful shutdown of network appliances when the power goes out

### * Generator
 : A large scale device that provides power for an extended period of time

### * Dual Supply
 : A power device that allows for one power unit to fail and for the other power supply to replace it; able to hot-swap power supplies

### * Managed Power Distribution Unit(PDU)
 : A rack-mounted unit that ditributes power on a large scale as a data center


# Security Information and Event Management


## Security Information and Event Management(SIEM)
 : A tool that collects and correlates data from network sensors and system logs


## - Components of SIEM


### * Vulnerability Scan Output
 : Vulnerability scans generated by specific scanning tools will be forwarded to the SIEM tool for security analysts to view

### * SIEM Dashboards
 : The centralized component of SIEM which displays all the ongoing processes

### * Sensors
 : Collects data traffic from nearby devices

### * Trends
 : Patterns discovered by SIEM tools 

### * Alerts
 : Informs security analysts of any suspicious activity on the network

### * Correlation
 : The process of aggregating data and compares it with known malicious behaviors


# Types of Security Incidents


## - Employee Errors
## - An Unauthorized Act by an Employee
## - External Intrusion Attempts
## - Viruses and/or Harfmful Code
## - Coprorate Espionage
 : Unethical gathering of information from another oranization

