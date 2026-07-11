# Ubuntu Server Installation

## Overview

This lab demonstrates the installation and initial configuration of Ubuntu Server.

---

## Environment

| Item | Value |
|------|------|
| OS | Ubuntu Server 24.04 LTS |
| Hypervisor | VMware Workstation |
| CPU | 2 vCPU |
| RAM | 4 GB |
| Disk | 30 GB |

---

## Update System

```bash
sudo apt update
sudo apt upgrade -y
```

---

## Check Hostname

```bash
hostnamectl
```

---

## Check Network

```bash
ip a
```

---

## Verification

- Ubuntu installed successfully
- Network configured
- Internet access confirmed

---

## Screenshots

![Login](images/login-screen.png)

![Hostname](images/hostnamectl.png)

![IP Address](images/ip-a.png)
