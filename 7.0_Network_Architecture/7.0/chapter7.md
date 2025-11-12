
# Common Types of Security Zones


## Screened Subnet
 : A public-facing network that acts as a barrier between the public and private network resources


## Intranet
 : An internal private network only accessible to specific users


## Extranet
 : An internal private network that grants access to their resources to trusted third-party entities
* Wireless


# Deceptive Technologies


## Honeyfiles/Honeynets
 : Decoy files/networks to entice threat actors to target those fake resources


## DNS Sinkhole
 : A temporary DNS record that redirects malicious traffic to a controlled IP address; helps in preventing DoS/DDoS actors


## Fake Telemetry
 : A method of intentionally providing fake information to device threat actors



# MAC Filtering


## MAC Filtering
 : Identifying and categorizing systems by their hardware address
 * Allow/Deny devices based on their MAC address


## Port Authentication(802.1x)
 : Allows authenticated devices to connect to the network through the switch; must have authentication to access ports on a switch


## Spanning Tree Protocol(STP)
 : A networking protocol designed to prevent interconnected switches from forming broadcast loops



# Methods of Filtering


## Web Filtering
 : Blocks users on a network from accessing specific websites; agent-based and centralized filtering are two common examples


## Agent-Based Filtering
 : Software installed on systems that enforce web filtering policies on the system


## Centralized Web Filtering
 : A proxy server performs the web filtering for devices on the network


## DNS Filtering
 : Blocking/Allowing access to specific websites through controlling the translation of domain names into IP addresses



# Methods of Securing a Router

## - Change Factory Settings
## - Implement Secure Versions of Protocols(SSH > Telnet)
## - Secure Routers Physically 
## - Secure The Configuration File
## - Update the Router's Firmware
## - Implement Anti-Spoofing Rules
## - Implement ACLs


# Network Access Control


## Network Access Control(NAC)
 : A method of access control that authenticate users and ensures their corresponding information is compliant with established security policies
* Can be agent-based or agentless


# Network Applications


## Vulnerability Scanning
 : A method of combining through a network to located and identify misconfigurations and exploits; common tools include openVAs and Nessus


## Application Vulnerability Scanning
 : A specialized method of scanning for misconfigurations and exploits found in software


## Packet Monitoring
 : The process of tracking accessing the security of thrid-party services to ensure their compliance with an organizations standards



# Network Architecture


## Network Architecture
 : The selection and placement of media, devices, protocols/services, and data assets to support basic network connectivity


## Host Node
 : The computing device that initiates data transfers
* Servers
* Clients


## Intermediary Node
 : The computing devices that forwards network traffic around the network
* Switch 
* Router


## Switch
 : Forwards the network traffic based on the destination MAC address; used for local networkds


## Router
 : Forwards network traffic based on IP addresses; routes traffic to outside networks



# Networks Found in a Security Zone


## Wireless
 : Netowrks that don't require a physical connection to connect to the network


## Guest
 : A organization network type that allows temporary internet access to users


## Honeynet
 : A unique network to entice and trap threat actors; used by security analysts to extract data from


## Ad Hoc
 : A decentralized netowrk for direct network connections between two or more devices



# OSI Model Layers


## Physical Layer
 : the physical networking equipment involved with the data transfers; data is converted into <ins>bits</ins> (0's and 1's)


## Data Link Layer
 : Fascilitates data transfers between <ins>two</ins> devices into smaller pieces called frames


## Network Layer
 : Decides the path that the data will take when transporting data


## Transport Layer
 : Ensures data is being sent to other systems, the actual communication itself using protocols; breaks up data into segments to send to layer 3 (TCP,UDP)


## Session Layer
 : Responsible for maintaining a network session between two or more systems (data transmission)


## Application Layer
 : Reposible for protocols and data manipulation that software uses to present data to the user; web browsers, email clients; only layer that interacts with input data from user (SMTP,FTP)



# Open Systems Interconnection (OSI) Model


## OSI Model
 : One of the most widely used models to show how systems interact with each other on the network


# Security Controls


## Passive Security Controls
 : Methods to secure assets/resources that does not take any direct action to stop monitored threats


## Active Security Controls
 : Methods to secure assets/resources that does prevent and stop threats once they're monitored


## Inline Device
 : A computing device/service that is placed on a network path to monitor and filter the traffic in real-time


## Test Access Point
 : A computing device/service that copies network traffic from one network port and send traffic to another computing device


## Fail-Open
 : When a network/host fails, the network access to that device or service is preserved


## Fail-Closed
 : Whne a network/host fails, the network access to that device or service remains blocked



# Security Zone


## Security Zone
 : Portions of the network or system that have specific security concerns or requirements



# Segmentation


## Segmentation
 : Dividing a network into smaller networks/subnets
 * Each subnet has its own security configurations/policies
 * Allows more granular control over assets/resources at the individual/local layer



# Types of Security Appliances


## Proxy Server
 : A netowrking device that acts on behalf of the client when accessing resources from another computing device; serves as the "middle-man" in network transfers


## Jump Server
 : A type of hardened server that provides access to toher assets/resources on a network; acts as a gateway for accessing important data


## Load Balancer
 : A networking device that distributes netowrk traffic across multiple servers for optimal performance and ensures fault tolerance


## Sensor(Packet Sniffer)
 : A network device/service that captures traffic from a nearby device to monitor its traffic


## Universal Threat Management(UTM)
 : A piece of hardware that combines multiple security functions into one hardware



# Types of Firewalls


## Host-Based Firewall
 : Inspects network traffic received by an individual system; generally seen as software implementation


## Network-Based Firewall
 : Inspects incoming and outgoing network traffic on a network; generally seen as a hardware implementation


## Web Application Firewall
 : Helps to protect application/services running on web servers and databases; enforces rules to filter and inspect traffic


## Next Generation Firewall
 : A more advanced firewall with more features(intrusion prevention, malware detection) for more in-depth network analysis


## UTM


## Stateless Firewall
 : A firewall that doesn't preserve information about network sessions; packets are analyzed individually


## Layer 4 Firewall
 : A firewall that examlines the TCP-handshake to distinguish new connections from established ones; block specific IP addresses


## Layer 7 Firewall
 : A firewall that inspects packet headers and their payload in full; reassembles entire messages and stops each packet for inspection



# Types of Network Vulnerabilities 


## - Default Account/Passwords
## - Weak Passwords
## - Privilege Escalation
## - Backdoors
## - Zero-Day Attacks


# Types of Screened Subnets


## Bastion
 : A device that has been repeatedly exposed to cyberattacks to further secure the device


## Screening Router
 : A router most external to the network(closest to the internet); uses ACLs to filter network packets


## Dual-Homed Gateway
 : A type of firewall that has three different interfaces(internet, public subnet, private network); must log into gateway to forward traffic


## Screened-Host Gateway
 : A type of firewall that resides ina a screened-subnet; users must authenticate themselves to access netowrk resources


## Two-Firewall Screened Subnet
 : A screened subnet implementation that has one firewall protecting public resources and another firewall protecting private resources



# Virtual Local Area Network (VLAN)


## Virtual Local Area Network(VLAN)
 : A networking implementation where a single physical network is divided into multiple virtual networks
 * VLANs are assigned by a single port on a switch; one VLAN per port
 * A router is needed to communicate with other workstations on other VLANs


