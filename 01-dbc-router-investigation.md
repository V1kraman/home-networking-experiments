# DBC HGU-V210-4AC Investigation

## Objective

Determine whether the ISP ONT router could operate as a wireless repeater.

---

## Router Interface Explored

- Status
- Network
- Security
- Applications
- Diagnostics
- Management
- WLAN Basic
- WLAN Advanced
- WLAN Security
- Site Survey
- EasyMesh
- Interface Setup

---

## Site Survey

Successfully detected:

- SSID
- BSSID
- Channel
- Encryption
- Signal Strength

Missing:

- Connect
- Join
- Associate

Conclusion:

The router performs scanning only.

---

## Wireless Modes

Available

- Access Point

Unavailable

- Client Mode
- Repeater
- Universal Repeater
- WDS

---

## EasyMesh

Tested:

- Controller Mode
- WPS Trigger
- 802.11k
- 802.11v

Result:

No mesh formed because the primary router does not implement Wi-Fi Alliance EasyMesh.

---

## Firmware Research

Investigated:

- Official firmware
- OpenWrt
- DD-WRT

Result:

No firmware supports enabling repeater functionality.

---

## Conclusion

The DBC HGU-V210-4AC is firmware restricted and cannot operate as a wireless repeater.
