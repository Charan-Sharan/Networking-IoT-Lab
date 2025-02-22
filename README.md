# IoT Lab Networking Setup:

## Overview

This document provides a summary of the tasks completed for Networking setup at CoE-IOT lab at R.V. College of Engineering, focusing on configuring network devices and creating a safe and secure interconnection between various devices such as IOT devices, servers, our devices(personal/work laptops), guest devices,etc.

---
## Navigation

1. [Flashing OpenWRT OS on Netgear Nighthawk 6800 Router](#1-flashing-openwrt-os-on-netgear-nighthawk-6800-router)
2. [Setting Up Internet for the Lab with Static IP](#2-setting-up-internet-for-the-lab-with-static-ip)
3. [Guest Network Setup](#3-guest-network-setup)  
4. [VPN Server Setup](#4-vpn-server-setup)  

### 1. Flashing OpenWRT firmware on Netgear Nighthawk 6800 Router

The first task involved flashing the **OpenWRT** operating system onto the **Netgear Nighthawk 7800** router. OpenWRT is an open-source router firmware that provides extensive customization and management features for networking setups. This step was necessary for enhancing the router's capabilities and enabling advanced networking configurations such as VLANS, iptables,etc for the lab.  
For detailed steps, see [flashing_openwrt.md](./src/01_flashing_openwrt.md).

### 2. Setting Up Internet for the Lab with Static IP

The second task involved setting up the **internet connection** for the lab using a **static IP** provided by the ISP. This ensures that the lab's network devices have a consistent and reliable IP address, which is essential for setting up servers, IoT devices, and network services.  
For detailed steps, see [internet_setup.md](./src/02_internet_setup.md).

---

### 3. Guest Network Setup

The third task involved setting up a **guest network** to isolate guest devices from the main network. This ensures security and prevents unauthorized access to lab devices and services.  
For more details, see [guest_network_setup.md](./src/03_guest_network_setup.md).


### 4. VPN Server Setup

The next task was to setup up a VPN Server on the Openwrt and the need to do it was, we had to access all the locally connected devices and remotely and securely.
For more details, see [vpn_server_setup.md](./src/04_vpn_server_setup.md).
## Current status 

With these tasks completed, the basic network infrastructure for the IoT lab is now in place. The lab is ready for further development, device integration, and experimentation in network management, IoT, and cloud-based systems.