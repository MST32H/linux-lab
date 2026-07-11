# Systemd & Services

## Overview

Systemd is the default init system in Ubuntu. It is responsible for managing services and the boot process.

---

## Check Service Status

```bash
systemctl status ssh
```

---

## Start a Service

```bash
sudo systemctl start ssh
```

---

## Stop a Service

```bash
sudo systemctl stop ssh
```

---

## Restart a Service

```bash
sudo systemctl restart ssh
```

---

## Reload Configuration

```bash
sudo systemctl reload ssh
```

---

## Enable Service at Boot

```bash
sudo systemctl enable ssh
```

---

## Disable Service

```bash
sudo systemctl disable ssh
```

---

## List Running Services

```bash
systemctl list-units --type=service --state=running
```

---

## Check Failed Services

```bash
systemctl --failed
```

---

## View Logs

```bash
journalctl -u ssh
```

---

## Verify

```bash
systemctl is-enabled ssh
systemctl status ssh
```

---

## Interview Questions

- What is systemd?
- Difference between start, restart and reload?
- Difference between enable and start?
- What is journalctl used for?

---

## Best Practice

Always check the service status after changing its configuration.

---

## Result

Service management completed successfully.
