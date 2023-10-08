# Router-On-A-Stick
Elaborates how resources can be used on a Small Enterprise scale to give a big out put especially using a single Switch and Virtual Router Interfaces to restrict and enhance communication between various Vlans in a LAN Network.
![image](https://github.com/RoggersAnguzu/Router-On-A-Stick/assets/141458053/fb12af50-b12a-44e8-80cf-51c92e80a42c)

# Cisco Router-on-a-Stick Configuration with Multiple VLANs

This repository contains a Cisco router-on-a-stick configuration example that demonstrates how to set up a router to route traffic between different VLANs using a single physical interface.

## Overview

In a network with multiple VLANs, a router-on-a-stick configuration allows you to route traffic between VLANs using subinterfaces on a router's single physical interface that is sub divided into Virtual interfaces. This configuration is useful for segmenting and isolating network traffic in different VLANs while enabling inter-VLAN communication.

## Repository Contents

- `router-config.txt`: This file contains the sample Cisco router configuration for this project.

## Configuration Details

### Router Configuration

The `router-config.txt` file provides a sample router configuration using Cisco IOS commands. It includes:

- Configuration of VLANs on the switch.
- Configuration of subinterfaces on the router.
- Assigning IP addresses to subinterfaces.
- Enabling routing (inter-VLAN routing) on the router.
- Setting up DHCP pools for each VLAN (if required).

Please note that this is a basic example, and you should adapt the configuration to your specific network requirements.

## Usage

To use this router-on-a-stick configuration:

1. Apply the configuration to your Cisco router by pasting the commands from `router-config.txt` into the router's command-line interface.

2. Adjust the VLAN IDs, IP addresses, and DHCP settings according to your network design.

3. Verify connectivity and routing between VLANs.

## Contributions

Contributions to improve this example or provide additional insights are welcome. Feel free to submit pull requests or open issues if you encounter problems.

## Acknowledgments

- Cisco Networking Academy for providing educational resources.
- JRS UGANDA for Providing me with the Necessary Knowledge

