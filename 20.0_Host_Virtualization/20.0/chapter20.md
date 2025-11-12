
# Attributes of Virutal Networking


## - VMs can suppoert an unlimited number of virtual networks

## - A virtual network's configuration is dependent on the configuration of the physical hardware that its installed on

## - The resources on a virtual network are split up, which turns available bandwidth into channels

## - A virtual DHCP server leases out IP information only to VMs n the virtual network


# SDN Layers


## Application Layer
 : Houses all of the networks applications and services; communicates with the control layer through the Northbound interface/API

## Control Layer
 : Receives requests from the application layer and provides the physical layer with configurations and instructions

## Physical Layer
 : Houses all of the networking hardware and performs instructions provided by the control layer; communicates with the control layer through Southbound interface/API


# Securing Virtual Machines


## - Reduce the number of services running

## - Apply patches and updates regularly

## - Install Anti-Virus and other security software

## - Implement backups, operating system snapshots, and other solutions for data protection


# Software Defined Networks


## Software Defined Networking(SDN)
 : A network implementation that enables software to configure and intelligently control the network over static configuration files

## SDM Controller
 : A software implmentation that gathers data from all computing systems on the network and makes decesions based on the data that was gathered


# Virtual Network Terms


## VLAN
 : A netowrk configuration that splits up a physical LAN into multiple logical LANs

## Virtual Area Network(VAN)
 : A network configuration that enables VMs on seperate physical systems to communicate with each other

## VPN
 : A secure method of communication for connecting endpoints over a remote connection

## Virtual Machine(VM)


# Virtual Networking


## Virtual Networking
 : A type of network that is made up of one or more VMs configured to access local or external network resources


# Virtual Networking Devices


## Virtual Switch(vSwitch)
 : Software that fascilitates communication between VMs and physical networks

## Virtual Router(vRouter)
 : A software function that replicates the funcationality of a physical router

## Virtual Firewall Appliance(VFA)
 : Software that functions as a network firewall device that provides the usual packet filtering and monitoring

## Hypervisor


# Virtualization Advantages

## * Flexibility
 : Able to be easily moved from one host system to another

## * Able to create Honeypots/Honeynets

## * Serves as a great sandbox environment for testing applications/code

## * Server Consolidation
 : Moving multiple servers onto a few physical servers with multiple VM implementations
 
## * Very easy to isolate resources/assets inside a VM


# Virtualization Components


## Physical Machine
 : The hardware component of the system(HDD/SSD, RAM, motherboard, CPU, etc.)

## Virtual Machine(VM)
 : A software implementation of a computer

## Virtual Hard Disk(VHD)
 : A file created within the host OS and simulates a HDD for the VM

## Hypervisor
 : A layer of software that resides between the VM and the hardware; allows VMs to interact with the hardware
 * TYPE 1 Hypervisor
  : A dedicated appliance that directly interfaces with the hardware(Bare Metal)
 * TYPE 2 Hypervison
  : Run as a application within an OS(VirtualBox)

## Containerization
 : Packaging software and all its configuration files into an isolated unit; able to run applications without the need for a host OS(Docker)


# Virtualization Disadvantages


## * Attacks targeting the host physical system could compromise all of the VMs on that host machine

## * Any failures on the host system could also affect the VMs running on the host system

## * Implementing multiple VMs can be a complex process

## * VM Escape
 : An attack where a threat actor gains access to a VM and is able to break out of that environment and into the host system

