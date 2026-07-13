# Project 1 - Fix No Internet Connection

## Scenario

A Windows computer is connected to the network but cannot access the Internet.

---

## Symptoms

- No Internet access
- Browser cannot load websites
- Network icon shows connected

---

## Troubleshooting Steps

### Step 1

Check IP configuration

```cmd
ipconfig /all
```

---

### Step 2

Ping the router

```cmd
ping 192.168.1.1
```

---

### Step 3

Ping Google DNS

```cmd
ping 8.8.8.8
```

---

### Step 4

Test DNS resolution

```cmd
ping google.com
```

---

### Step 5

Flush DNS cache

```cmd
ipconfig /flushdns
```

---

### Step 6

Renew DHCP lease

```cmd
ipconfig /release
ipconfig /renew
```

---

## Result

Internet connection restored successfully.

---

## Skills Demonstrated

- Windows Troubleshooting
- DNS
- DHCP
- Ping
- IP Configuration
- Command Prompt
