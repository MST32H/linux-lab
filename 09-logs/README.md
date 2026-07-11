# Linux Logs

## Overview

Linux logs help administrators monitor, troubleshoot, and audit system activities.

---

## System Journal

```bash
journalctl
```

---

## View Latest Logs

```bash
journalctl -xe
```

---

## View Boot Logs

```bash
journalctl -b
```

---

## View SSH Logs

```bash
journalctl -u ssh
```

---

## Follow Logs in Real Time

```bash
journalctl -f
```

---

## Kernel Messages

```bash
dmesg
```

---

## Authentication Logs

```bash
sudo cat /var/log/auth.log
```

---

## Syslog

```bash
sudo cat /var/log/syslog
```

---

## Verify

```bash
journalctl --since today
dmesg | tail
```

---

## Interview Questions

- What is journalctl?
- Difference between syslog and journalctl?
- Where are authentication logs stored?
- What is dmesg used for?

---

## Best Practice

Always check logs before restarting services.

---

## Common Troubleshooting

### SSH Login Failed

```bash
journalctl -u ssh
cat /var/log/auth.log
```

### System Crash

```bash
journalctl -b -1
dmesg
```

---

## Result

System logs analyzed successfully.
