# networkwalks-B082-week1-Cybersecurity-lab-setup
Cybersecurity Lab Setup
# Cybersecurity Lab Setup

## Project Overview

This project focuses on setting up a basic cybersecurity laboratory environment using Kali Linux and Oracle VM VirtualBox.

The purpose of this lab is to create a controlled virtual environment where cybersecurity concepts, networking activities, security tools, and practical exercises can be performed safely.

## Objectives

The main objectives of this lab are:

* Install and configure Kali Linux in a virtual machine.
* Configure the virtual machine's hardware resources.
* Configure the network adapter in VirtualBox.
* Verify network connectivity.
* Confirm that the Kali Linux environment is functioning correctly.
* Prepare the environment for future cybersecurity practical exercises.

## Tools and Technologies Used

| Tool                 | Purpose                                |
| -------------------- | -------------------------------------- |
| Oracle VM VirtualBox | Virtualization platform                |
| Kali Linux           | Cybersecurity-focused operating system |
| Windows              | Host operating system                  |
| Terminal             | Network and system verification        |

## Lab Environment

The cybersecurity laboratory consists of a Kali Linux virtual machine running inside Oracle VM VirtualBox.

The virtual machine provides an isolated environment for performing cybersecurity exercises without directly affecting the host system.

### Lab Architecture

```text
Host Computer
     |
     | Oracle VM VirtualBox
     |
     v
Kali Linux Virtual Machine
     |
     | Network Adapter
     |
     v
Network / Internet
```

## System Configuration

The Kali Linux virtual machine was configured through Oracle VM VirtualBox before starting the practical activities.

### Virtual Machine Configuration

The virtual machine settings were reviewed to ensure that the required resources were available for Kali Linux.

**Screenshot: Virtual Machine Configuration**

Place your VirtualBox configuration screenshot here:

```markdown
![Virtual Machine Configuration](images/virtual-machine-configuration.png)
```

## Network Configuration

The network adapter was configured through the VirtualBox network settings.

The network configuration allows the Kali Linux virtual machine to establish network connectivity while operating inside the virtualized environment.

**Screenshot: VirtualBox Network Settings**

Place your network settings screenshot here:

```markdown
![VirtualBox Network Settings](images/virtualbox-network-settings.png)
```

## Kali Linux Environment

After configuring the virtual machine, Kali Linux was started successfully.

**Screenshot: Kali Linux Desktop**

Place your Kali Linux desktop screenshot here:

```markdown
![Kali Linux Desktop](images/kali-linux-desktop.png)
```

## Network Verification

The network configuration was verified from within Kali Linux.

The IP configuration can be checked using:

```bash
ip addr
```

This command displays the available network interfaces and their assigned IP addresses.

**Screenshot: IP Address Configuration**

Place your terminal screenshot showing the IP configuration here:

```markdown
![IP Address Configuration](images/ip-address-configuration.png)
```

## Connectivity Testing

Network connectivity can be tested using the `ping` command.

For example:

```bash
ping 8.8.8.8
```

A successful response indicates that the virtual machine is able to communicate over the network.

**Screenshot: Connectivity Test**

Place your connectivity test screenshot here:

```markdown
![Connectivity Test](images/connectivity-test.png)
```

## Verification

The following checks were performed as part of the laboratory setup:

* Kali Linux successfully started inside VirtualBox.
* The virtual machine network adapter was configured.
* The network interface was identified.
* An IP address was assigned.
* Network connectivity was tested.

These checks confirm that the basic cybersecurity laboratory environment is ready for further practical exercises.

## Challenges and Troubleshooting

During the setup process, network configuration and VirtualBox settings may require troubleshooting.

Common issues include:

* Network adapter options not appearing as expected.
* Kali Linux not receiving an IP address.
* Network connectivity not working.
* Incorrect VirtualBox network mode.
* Insufficient virtual machine resources.

Checking the VirtualBox network configuration and verifying the network interface from Kali Linux can help identify and resolve these issues.

## What I Learned

Through this laboratory setup, I gained practical experience with:

* Creating and configuring virtual machines.
* Using Oracle VM VirtualBox.
* Installing and working with Kali Linux.
* Understanding virtual network adapters.
* Checking IP addresses and network interfaces.
* Testing network connectivity.
* Preparing a controlled environment for cybersecurity activities.

## Security and Ethical Considerations

This laboratory environment is intended for educational and authorized cybersecurity activities.

Any security testing, scanning, exploitation, or penetration-testing activity should only be performed against systems where explicit permission has been provided.

Using cybersecurity tools against unauthorized systems may cause disruption and can have legal consequences.

## Repository Structure

The project can be organized as follows:

```text
Cybersecurity-Lab-Setup/
│
├── README.md
│
└── images/
    ├── virtual-machine-configuration.png
    ├── virtualbox-network-settings.png
    ├── kali-linux-desktop.png
    ├── ip-address-configuration.png
    └── connectivity-test.png
```

## Future Improvements

The laboratory can be expanded by adding additional virtual machines and cybersecurity tools.

Possible future activities include:

* Network traffic analysis using Wireshark.
* Vulnerability scanning in an authorized lab.
* Network enumeration.
* Security monitoring.
* Digital forensics exercises.
* Penetration-testing practice in intentionally vulnerable environments.

## Conclusion

The cybersecurity laboratory environment was successfully prepared using Kali Linux and Oracle VM VirtualBox.

The virtual machine was configured, network settings were reviewed, and connectivity was verified. This environment provides a foundation for continuing with practical cybersecurity and networking exercises.

## Author

Anaam Umar

B.Sc. Cyber Security
