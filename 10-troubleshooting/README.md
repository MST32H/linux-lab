# Linux Troubleshooting

## Overview

Common troubleshooting techniques for Linux servers.

---

## Check System Information

```bash
hostnamectl
uptime
```

---

## Check CPU Usage

```bash
top
```

---

## Check Memory

```bash
free -h
```

---

## Check Disk Space

```bash
df -h
```

---

## Check Running Services

```bash
systemctl --failed
```

---

## Check Network

```bash
ip a
ip route
ping 8.8.8.8
```

---

## Check Listening Ports

```bash
ss -tulnp
```

---

## Check Logs

```bash
journalctl -xe
```

---

## Verify

```bash
hostnamectl
free -h
df -h
```

---

## Interview Questions

- What is your troubleshooting methodology?
- Which command do you run first?
- How do you identify a network issue?
- How do you identify a service issue?

---

## Best Practice

Always collect information before making changes.

---

## Troubleshooting Flow

1. Identify the issue.
2. Collect logs.
3. Check services.
4. Check network.
5. Apply the fix.
6. Verify the result.

---

## Result

Linux troubleshooting completed successfully.
