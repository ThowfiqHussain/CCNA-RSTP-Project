# CCNA RSTP Project

This repository contains resources related to the Rapid Spanning Tree Protocol (RSTP), a key topic in the CCNA (Cisco Certified Network Associate) curriculum. RSTP is defined by IEEE 802.1w and is an enhancement of the original Spanning Tree Protocol (STP), offering significantly faster convergence and improved network efficiency.

## Overview

Rapid Spanning Tree Protocol (RSTP) is designed to prevent Layer 2 switching loops while ensuring fast network topology convergence. Unlike traditional STP, which can take up to 50 seconds to respond to topology changes, RSTP typically converges in less than 10 seconds.

## Key Concepts

- **Faster Convergence**: RSTP reduces the time required for a network to reconfigure itself following a change in topology.
- **Port Roles**: RSTP defines new port roles such as Root Port, Designated Port, Alternate Port, and Backup Port.
- **Port States**: Only three port states are used – Discarding, Learning, and Forwarding.
- **Edge Ports**: These are ports that are not connected to any other switches, allowing for immediate transition to the forwarding state.

## Files Included

- **RSTP Diagrams**: Visual representations of network topologies implementing RSTP.
- **Configuration Examples**: Sample switch configurations for enabling RSTP on Cisco devices.

