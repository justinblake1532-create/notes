
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

