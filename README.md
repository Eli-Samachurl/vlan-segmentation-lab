# VLAN Segmentation and Layer 2 Isolation Lab

## Overview

This project demonstrates VLAN segmentation and Layer 2 isolation using Cisco Packet Tracer.

Two switches were connected using a trunk link, and devices were assigned to separate VLANs to restrict communication between departments.

## Objectives

- Create VLAN 10 (HR)
- Create VLAN 20 (IT)
- Configure access ports
- Configure trunk links
- Verify VLAN isolation

## VLAN Assignment

| Device   | VLAN    |
|----------|---------|
| PC0      | VLAN 10 |
| PC1      | VLAN 10 |
| PC2      | VLAN 20 |
| PC3      | VLAN 20 |

## Tools Used

- Cisco Packet Tracer

## Results

Devices within the same VLAN communicated successfully.

Devices in different VLANs were unable to communicate, confirming Layer 2 isolation.

## Key Concepts Learned

- VLAN Segmentation
- Layer 2 Isolation
- Trunking
- Broadcast Domain Separation

## Screenshots

Network Topology

![Network Topology](https://github.com/Eli-Samachurl/vlan-segmentation-lab/blob/main/topology.png?raw=true)

VLAN Configuration

![VLAN Configuration](https://github.com/Eli-Samachurl/vlan-segmentation-lab/blob/main/show_vlan_brief.png?raw=true)

Successful Ping Test

![Successful Ping Test](https://github.com/Eli-Samachurl/vlan-segmentation-lab/blob/main/ping_success.png?raw=true)

Failed Ping Test

![Failed Ping Test](https://github.com/Eli-Samachurl/vlan-segmentation-lab/blob/main/ping_fail.png?raw=true)
