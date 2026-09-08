# Linux-Virtual-Machine

I built my homelab concentrating on Linux.

# Description

Linux is the kernel, or core of an operating system. It is a free and open-source family of operating system. It was founded by Linus Torvalds in 1991. A distribution can have extensive GUI, such as Ubuntu, or better suited for high-performance server tasks like Red Hat.

# Requirements of a Virtual Machine

The requirements of a virtual machine are:
* maximum CPU cores
* motherboard Hardware Assisted Virtualization (HAV) must be enables in the BIOS/UEFI setup
* maximum RAM
* lots of storage space
* Network Requirements- Network Interface Card (NIC) supports Gigabit Ethernet

# Step 1: Installing VirtualBox

I installed VirtualBox, which I will use to host my virtual machines.

# Step 2: Downloading Ubuntu

I downloaded Ubuntu from an official website at ubuntu.com. In addition, I had to attach ISO of Ubuntu to optical drive.

# Step 3: Creating a Linux Virtual Machine

I created a virtual machine for Linux. I gave the following

* 5145 MB of Memory
* 10 CPU core
* Disk Size: 200 GB
* Hard Disk Size: 1 TB

# Step 4: Initial Configuration

After installation, updated and upgraded all system packages and files. They are
* $ sudo apt update
* $ sudo apt upgrade -y

# Applications to Install

I installed the following applications for Ubuntu.
* Visual Studio Code
* File Tools
* VLC Media Player
* Git
* Terminal Terminator

# Conclusion

The Linux Ubuntu virtual machine is on a cross-platform virtualization. I learned that virtual machines run multiple operating systems on a single device and can be used to protect the host system by separating it from one another.



