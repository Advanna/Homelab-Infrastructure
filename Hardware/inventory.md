# Home Lab Hardware Inventory

## Overview

This document tracks the hardware used in my home lab, including system specifications, intended uses, and deployment status. I'll update it as I configure, upgrade, and add equipment.

**Project Status:** In Progress  
**Last Updated:** October 16, 2026

---

## 1. Hardware Inventory

| Asset ID | Device | Manufacturer / Model | Intended Role | Status |
|---|---|---|---|---|
| HL-001 | Mini PC | Lenovo ThinkCentre M700 | Network Firewall | OS Installed |
| HL-002 | Server 01 | Supermicro X7SPE-HF-D525 | TBD | Hardware Inspected |
| HL-003 | Server 02 | Supermicro X7SPE-HF-D525 | TBD | Hardware Inspected |
| HL-004 | Server 03 | Supermicro — Model TBD | Storage / Media Server (Proposed) | Hardware Inspected |
| HL-005 | Network Switch | Cisco SG300-52P | Network Switching / VLANs | Configuration Pending |

---

## 2. Hardware Specifications

### HL-001 — Lenovo ThinkCentre M700

**Intended Role:** Network Firewall

| Component | Specification |
|---|---|
| Manufacturer | Lenovo |
| Model | ThinkCentre M700 |
| Form Factor | TBD |
| Processor | Intel Core i5-6500 |
| Memory | 8 GB RAM |
| Storage | 256 GB |
| Integrated Network Interface | 1 × Ethernet |
| Additional Network Interface | USB Ethernet Adapter |
| Operating System | OPNsense |
| Previous Operating System | Windows 7 |
| Status | OS Installed; Configuration Pending |

**Notes:**

The Lenovo ThinkCentre M700 will serve as the dedicated firewall for the home network. OPNsense has been installed, and final network configuration is pending.

---

### HL-002 — Supermicro Server 01

**Intended Role:** TBD

| Component | Specification |
|---|---|
| Manufacturer | Supermicro |
| Motherboard | X7SPE-HF-D525 Rev 1.00 |
| Processor | Intel Atom D525 @ 1.8 GHz |
| CPU Cores / Threads | 2 cores / 4 threads |
| Memory | 4 GB DDR3 |
| Memory Type | DDR3 SO-DIMM |
| Maximum Supported RAM | 4 GB |
| SATA Connections | 6 × SATA II |
| Remote Management | IPMI 2.0 |
| Chassis | Supermicro SC502L-200B |
| Drive Capacity | 1 × 3.5-inch or 2 × 2.5-inch drives |
| Operating System | TBD |
| Status | Hardware Inspected |

**Notes:**

This server uses an Intel Atom D525 processor and has 4 GB of RAM. Its intended role will be determined after hardware testing.

---

### HL-003 — Supermicro Server 02

**Intended Role:** TBD

| Component | Specification |
|---|---|
| Manufacturer | Supermicro |
| Motherboard | X7SPE-HF-D525 (Pending Verification) |
| Processor | Intel Atom D525 @ 1.8 GHz (Pending Verification) |
| CPU Cores / Threads | 2 cores / 4 threads (Pending Verification) |
| Memory Module Identified | G.SKILL DDR3 4 GB |
| Memory Part Number | F3-10666CL9D-8GBSQ |
| Storage | Western Digital HDD, approximately 80 GB |
| Power Supply | Solid Gear 300 W |
| Chassis | Compact Rackmount |
| Operating System | TBD |
| Status | Hardware Inspected |

**Notes:**

The motherboard and processor were identified during the initial inspection but still require verification. Additional testing will help determine a suitable workload for this server.

---

### HL-004 — Supermicro Server 03

**Intended Role:** Storage / Media Server (Proposed)

| Component | Specification |
|---|---|
| Manufacturer | Supermicro |
| Motherboard | TBD |
| Processor | TBD |
| Memory | 32 GB DDR4 ECC RDIMM |
| Memory Configuration | 2 × 16 GB |
| Memory Speed | DDR4-2666 |
| Drive Bays | 4 |
| Drive Form Factor | 2.5-inch |
| Cooling | 3 fans observed |
| Expansion | PCIe slots present |
| Power Supply | Internal Supermicro PSU |
| Operating System | TBD |
| Status | Hardware Inspected |

**Notes:**

This server is being considered for centralized file storage, device backups, and media streaming. The final storage configuration will depend on drive compatibility and hardware testing.

---

### HL-005 — Cisco SG300-52P

**Intended Role:** Network Switching and VLAN Segmentation

| Component | Specification |
|---|---|
| Manufacturer | Cisco |
| Model | SG300-52P |
| Switch Type | Managed Gigabit Ethernet |
| Ethernet Ports | 50 × Gigabit RJ-45 + 2 × Gigabit Combo Ports |
| Power over Ethernet | PoE+ |
| PoE Power Budget | 375 W |
| VLAN Support | IEEE 802.1Q |
| Routing Capabilities | Layer 2 / Layer 3 Lite |
| Management | Web Interface / CLI |
| Status | Configuration Pending |

**Notes:**

The Cisco switch will provide wired connectivity and VLAN segmentation for servers, personal devices, gaming consoles, and other equipment.

---

## 3. Planned Hardware and Upgrades

| Component | Purpose | Status |
|---|---|---|
| USB Ethernet Adapter | Additional firewall network interface | Configuration / Testing Pending |
| Storage Drives | Centralized storage and backups | Selection Pending |
| Equipment Shelving | Equipment organization and support | Planned |
| Cooling Fans | Improve cabinet airflow | Planned |
| Cable Management | Organize and label connections | Planned |
| UPS | Backup power and safe shutdowns | Future Upgrade |

---

## 4. Hardware Checklist

### Inventory

- [x] Identify available servers
- [x] Record Lenovo ThinkCentre M700 specifications
- [x] Identify Cisco switch model
- [x] Perform initial server inspections
- [x] Identify motherboard and processor in Server 01
- [x] Identify memory configuration in Server 03
- [ ] Verify Server 02 motherboard and processor
- [ ] Identify Server 03 motherboard and processor
- [ ] Verify remaining hardware specifications

### Testing

- [ ] Verify server POST and BIOS/UEFI access
- [ ] Test installed memory
- [ ] Check storage drive health
- [ ] Test network interfaces
- [ ] Check cooling and operating temperatures
- [ ] Measure power consumption

### Deployment

- [x] Install OPNsense firewall operating system
- [ ] Configure and test firewall network interfaces
- [ ] Assign server roles
- [ ] Install and configure storage drives
- [ ] Prepare equipment cabinet
- [ ] Organize and label cables
- [ ] Configure VLANs
- [ ] Configure hardware monitoring

---

## 5. Documentation Notes

Hardware specifications will be updated as equipment is inspected, configured, and upgraded.

Unconfirmed information is marked **TBD**.

Serial numbers, passwords, private keys, and sensitive network information are excluded from this public repository.

---

**Document Status:** In Progress
