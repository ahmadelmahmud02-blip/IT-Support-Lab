# DHCP (Dynamic Host Configuration Protocol)

## Objective

Understand how DHCP automatically assigns IP addresses to devices on a network.

---

## What is DHCP?

DHCP (Dynamic Host Configuration Protocol) automatically assigns IP addresses and other network settings to devices.

Without DHCP, every device would need to be configured manually.

---

## Information Provided by DHCP

- IP Address
- Subnet Mask
- Default Gateway
- DNS Server

---

## DHCP Process

1. Discover
2. Offer
3. Request
4. Acknowledge (DORA)

---

## Benefits

- Automatic IP assignment
- Reduces configuration errors
- Saves time
- Easy network management

---

## Troubleshooting

Check current IP address:

```cmd
ipconfig
```

Request a new IP:

```cmd
ipconfig /release
ipconfig /renew
```

---

## Skills Practiced

- DHCP
- IP Addressing
- Network Troubleshooting
- Windows Command Prompt
