# Networking
This repository contains the network configuration and design created using Cisco Packet Tracer.


# Network_DesignV1
  Topology
      -The router connects to two switches.
      -Switch1 hosts the DHCP server, which assigns IP addresses to all devices within the network.
      -Switch0 connects additional devices and communicates through Switch1.
  Features
      -DHCP Server: Devices on the network receive dynamic IP addresses from the DHCP server located on Switch1.
      -IP Helper Address: The router is configured with the IP helper address to forward DHCP requests from Switch0 to the DHCP server on Switch1, enabling devices on both switches to receive IP addresses.
      -SSH Access: Secure SSH protocol has been enabled to allow remote login and management of network devices.
      -Password Protection: Console access to network devices is secured with a password for enhanced security.
Getting Started
      -Open the .pkt file in Cisco Packet Tracer.
      -Explore the network configuration, which includes IP addressing, DHCP settings, and SSH configuration.
      -Modify and test network configurations as needed.
