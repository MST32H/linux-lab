# Linux Networking

## Overview

This lab covers the essential networking commands used in Linux for troubleshooting and system administration.

---

## Display IP Address

```bash
ip addr
```

---

## Display Routing Table

```bash
ip route
```

---

## Show Network Interfaces

```bash
ip link
```

---

## Test Connectivity

```bash
ping 8.8.8.8
```

---

## Check DNS Resolution

```bash
nslookup google.com
```

or

```bash
dig google.com
```

---

## Display Listening Ports

```bash
ss -tulnp
```

---

## Display Open Connections

```bash
ss -tun
```

---

## Display Hostname

```bash
hostnamectl
```

---

## Display Network Configuration

```bash
ip a
hostnamectl
ip route
```

---

## Restart NetworkManager

```bash
sudo systemctl restart NetworkManager
```

---

## Verify Internet Connection

```bash
ping google.com
```

---

## Verify

```bash
ip addr
ip route
ss -tulnp
```

---

## Interview Questions

- Difference between `ip addr` and `ifconfig`?
- Difference between `ss` and `netstat`?
- What is the default gateway?
- How does DNS work?
- Difference between TCP and UDP?

---

## Best Practice

Use `ip` and `ss` instead of deprecated commands such as `ifconfig` and `netstat`.

---

## Common Troubleshooting

### No Internet

```bash
ip addr
ip route
ping 8.8.8.8
ping google.com
```

If ping to **8.8.8.8** works but **google.com** fails, the issue is most likely DNS.

---

## Result

Linux networking verified successfully.
