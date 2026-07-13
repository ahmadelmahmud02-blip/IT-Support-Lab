# Windows Troubleshooting

## Objective

Document common Windows issues and the steps used to diagnose and resolve them.

---

# Common Problems

## 1. No Internet Connection

### Possible Causes

- Missing network driver
- Disabled network adapter
- Incorrect IP configuration
- Faulty Ethernet cable

### Troubleshooting

- Check Device Manager
- Install or update network driver
- Run:

```cmd
ipconfig /all
ipconfig /release
ipconfig /renew
ipconfig /flushdns
```

- Restart the computer

---

## 2. Unknown Device in Device Manager

### Solution

- Identify the hardware
- Download the correct driver
- Install the official driver
- Restart Windows

---

## 3. Slow Windows Performance

### Troubleshooting

- Remove unnecessary startup programs
- Check Task Manager
- Free disk space
- Run Windows Update
- Scan for malware

---

## 4. Windows Update Problems

### Solution

- Restart the computer
- Check Internet connection
- Run Windows Update Troubleshooter
- Retry the update

---

## 5. Black Screen After Driver Installation

### Troubleshooting

- Boot into Safe Mode
- Remove the faulty graphics driver
- Install the latest stable driver
- Restart the computer

---

# Useful Commands

```cmd
ipconfig
ping
sfc /scannow
DISM /Online /Cleanup-Image /RestoreHealth
```

---

# Skills Practiced

- Windows Troubleshooting
- Driver Troubleshooting
- Network Diagnostics
- Command Prompt
- Device Manager
