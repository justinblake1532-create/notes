
# Bluetooth Attacks


## Bluejacking
 : Looks for nearby devices and sends unwanted messages; <ins>unable</ins> to steal my data


## Bluesnarfing
 : Exploits a vulnerability in a bluetooth protocol to pair with the target device



# Hardware Used in Wireless Networks


## Wireless Access Point(WAP)
 : A device that broadcasts data over radio waves; use a Set Service Identifier(SSID) to allow easier connection


## Wireless Interface
 : A piece of hardware ingrained in a computing device that allows for connections to a wireless access point


## Wireless Bridge
 : A device that connects two wireless networks together


## Wireless LAN Controller(WLCs)
 : A device used in enterprise environments to manage multiple access points; able to communicate and manage other WAPs


## Lightweight Access Point(LWAP)
 : A device that forwards frames to WLCs to decide to forward/drop the frames


## Site Survey
 : Documentation about a location for the purposes of building an ideal wireless infrastructure; contains information about the best locations for wireless access point locations


## Heat Map
 : A diagram showing signal strength and channel utilization at different locations



# Internet Key Exchange


## Internet Key Exchange(IKE)
 : A framework for creating a security association with IPSec
* Security associations establish that two hosts trust one another (authenticate) and agree on secure protocols and cipher suites to used to exhange data
# Modes Of IPSec


## Transport Mode
 : Secures the communication between hosts on a private network; only the payload data is encrypted


## Tunnel Mode
 : Secures the communication between VPN sites acress an unsecure network; the entire packet header is encrypted and encapsulated



# RFID Tag Attacks


## RFID Tags
 : Small circuit boards that use radio waves to transmit data


## - Types of RFID Tags


### * Active RFID Tag
 : Use onboard batteries and can send signals over a long distance (ex: road toll pass)
### * Passive RFID Tags
 : Are not powered and relies on the energy of the scanner to transmit data (ex: ID badges, credit cards, etc.)
### * Near Field Communication(NFC)
 : A more secure version of RFID; allows for two way commmunication between devices within a few centimeters of each other



# RFID/NFC Attacks


## Eavesdropping
 : A threat actor uses an RFID reader to listen to conversations between a tag and the intended reader


## Man-In-The-Middle(MITM)
 : An attack where a threat actor intercepts a connection from a RFID tag and manipulates the signal


## DoS
 : Denying service to the RFID tag


## Cloining/Spoofing
 : A threat actor creates a fake copy of a badge to gain access to a system/resources



# Types of Wireless Attacks


## Wireless DoS
 : Prevents access to a legitimate WAP


## Wireless Replay and Key Recovery
 : An attack aimed to capture the hashes used when a wireless device authenticates itself with an access point


## Evil Twin
 : A malicious rogue access point that poses as a legitimate device on a network


## Initialized Vector(IV) Attack
 : An attack where threat actors target the encryption algorithm for how it generates keys


## Jamming Attack
 : A malicious form of interferance created by a threat actor to disrupt network services


## Disassociation Attacks
 : An attack that aims to disconnect or deauthenticate users/systems on a network


## Bluetooth
 : A network type that allows for devices to communicate with each other withing <ins>close</ins> proximity



# Web Application Attacks


## - Types of Web Application Attacks


### * Privilege Escalation
### * Dereferencing
 : Retrieving a value stored in a systems memory
### * Buffer Overflow
 : An attack where a threat actor sends high-volume of data to a system causing it to crash
### * Resource Exhaustion
 : An attack that focuses on depleting resources of the target system



# Wireless Access Protocols


## Wireless Equivalent Privacy(WEP)
 : A legacy protocol for encrpyting data sent over a wireless connection; not secure anymore


## WiFi Protected Access(WPA)
 : a legacy protocol used for secure data transfers over a wireless network; incorporated TKIP; not secure anymore


## WPA2
 : A more secure version of the WPA protocol; implements AES encryption over TKIP


## WPA3
 : A more secure version of WPA2 protocol; implements Simultaneous Authentication of Equals(SAE)


## Pre-Shared Key(PSK)
 : A wireless netowrk authenticaiton mode where a passphrase-based mechanism is used to allow group authentication to a wireless network



# Wireless Defenses


## - Methods of Securing WiFi Configurations


### * Changing Default Credentials
### * Enable MAC Filtering
### * Update the Firmware
### * Enable Firewalls
### * Adjusting the WiFi Signal Strength


## - Securing Netowrk Protocols


### * Remote Desktop Protocol
### * Secure Shell (SSH)
### * HTTPS
### * IPSec


