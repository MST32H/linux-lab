# Package Management

## Overview

Package management is used to install, update, remove, and search software packages in Ubuntu.

---

## Update Package Index

```bash
sudo apt update
```

---

## Upgrade Installed Packages

```bash
sudo apt upgrade -y
```

---

## Install Package

```bash
sudo apt install nginx
```

---

## Remove Package

```bash
sudo apt remove nginx
```

---

## Remove Package with Configuration Files

```bash
sudo apt purge nginx
```

---

## Remove Unused Packages

```bash
sudo apt autoremove -y
```

---

## Search Package

```bash
apt search nginx
```

---

## Show Package Information

```bash
apt show nginx
```

---

## List Installed Packages

```bash
apt list --installed
```

---

## Verify Installation

```bash
nginx -v
```

---

## Interview Questions

- Difference between `apt update` and `apt upgrade`?
- Difference between `remove` and `purge`?
- What does `autoremove` do?
- How do you search for a package?

---

## Best Practice

Always run:

```bash
sudo apt update
```

before installing new packages.

---

## Result

Package management completed successfully.
