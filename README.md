# home-networking-experiments
Hands-on networking experiments involving router configuration, Wi-Fi optimization, firmware investigation, and home network design.
![Status](https://img.shields.io/badge/Status-Active-success)
![Networking](https://img.shields.io/badge/Networking-Home%20Lab-blue)
![WiFi](https://img.shields.io/badge/WiFi-2.4%20GHz%20%7C%205%20GHz-orange)
![Platform](https://img.shields.io/badge/Platform-Consumer%20Routers-lightgrey)

---

# Overview

This repository documents a series of practical networking experiments performed on consumer networking hardware.

The original objective was simple:

> Convert an ISP-provided ONT router into a wireless repeater.

The project eventually evolved into a complete investigation of router firmware, wireless networking, DHCP configuration, EasyMesh, proprietary mesh systems, wired access points, and Wi-Fi performance.

Although the original goal was not fully achieved, the investigation significantly improved my understanding of home networking and router architecture.

---

# Hardware Used

| Device | Purpose |
|---------|----------|
| JioFiber JCOW407-IN | Primary Wi-Fi 6 Router |
| DBC HGU-V210-4AC | ISP ONT Router |
| D-Link DIR-615 | Legacy Wireless Repeater |
| Windows PC | Router Administration |
| Ethernet Cable | Wired Backhaul |

---

# Experiments

| Experiment | Status |
|------------|--------|
| Router Firmware Investigation | ✅ |
| Site Survey Analysis | ✅ |
| EasyMesh Testing | ✅ |
| Wireless Repeater Investigation | ✅ |
| D-Link Repeater Configuration | ✅ |
| Wired Access Point | ✅ |
| Firmware Compatibility Research | ✅ |
| Jio Mesh Investigation | ✅ |

---

# Major Findings

✅ D-Link successfully functioned as a wireless repeater.

❌ Performance was limited to 2.4 GHz Wi-Fi and approximately 150 Mbps.

❌ DBC firmware lacks Client Mode, WDS, and Universal Repeater functionality.

❌ OpenWrt and DD-WRT are not supported.

❌ Jio routers use proprietary mesh rather than Wi-Fi Alliance EasyMesh.

✅ Wired LAN-to-LAN Access Point configuration achieved full network speed.

---

# Repository Contents

| File | Description |
|------|-------------|
| docs/01-dbc-router-investigation.md | Firmware investigation |
| docs/02-dlink-repeater.md | D-Link repeater setup |
| docs/03-wired-access-point.md | Wired AP configuration |
| docs/04-jio-mesh-analysis.md | EasyMesh compatibility |

---

# Skills Demonstrated

- Router Administration
- DHCP Configuration
- LAN Addressing
- Access Point Deployment
- Wireless Networking
- Wi-Fi Troubleshooting
- Firmware Analysis
- EasyMesh Investigation
- Network Diagnostics
- Technical Documentation

---

# Lessons Learned

This project reinforced an important engineering lesson:

> Sometimes understanding *why something cannot work* is just as valuable as successfully making it work.

---

# Future Work

- Wi-Fi 6 Mesh Testing
- OpenWrt Supported Hardware
- VLAN Experiments
- Raspberry Pi Router
- Network Monitoring
- Latency Benchmarking

---

