# Ubuntu Server Installation

## Objective

Install Ubuntu Server and prepare it for system administration tasks.

---

## Requirements

- Ubuntu Server ISO (24.04 LTS)
- VMware Workstation / VirtualBox
- 2 CPU
- 4 GB RAM
- 30 GB Disk

---

## Installation Steps

1. Download Ubuntu Server ISO.
2. Create a new virtual machine.
3. Boot from the ISO.
4. Install Ubuntu Server.
5. Create an administrator account.
6. Update the system.

---

## Commands

```bash
sudo apt update
sudo apt upgrade -y
hostnamectl
ip a
```

---

## Verification

```bash
lsb_release -a
hostnamectl
ip a
```

---

## Screenshot

> Add installation screenshots here.

---

## Interview Questions

- Why Ubuntu Server?
- Difference between Server and Desktop editions?
- Why update the system after installation?

---

## Result

Ubuntu Server installed successfully and ready for administration.
