# Users & Groups Management

## Overview

This lab covers Linux user and group management using practical commands.

---

## Objectives

- Create users
- Modify users
- Delete users
- Create groups
- Add users to groups
- Change passwords
- Check user information

---

# Create User

```bash
sudo adduser ali
```

---

# Delete User

```bash
sudo deluser ali
```

Delete user with home directory

```bash
sudo deluser --remove-home ali
```

---

# Create Group

```bash
sudo groupadd developers
```

---

# Add User to Group

```bash
sudo usermod -aG developers ali
```

---

# Show User Groups

```bash
groups ali
```

or

```bash
id ali
```

---

# Change Password

```bash
sudo passwd ali
```

---

# Lock User

```bash
sudo passwd -l ali
```

---

# Unlock User

```bash
sudo passwd -u ali
```

---

# Current Logged-in Users

```bash
who
```

---

# Current User

```bash
whoami
```

---

# Verification

```bash
id ali
groups ali
```

---

# Interview Questions

### Difference between adduser and useradd?

### Difference between groupadd and usermod?

### What does `-aG` mean?

### Difference between `/etc/passwd` and `/etc/shadow`?

---

# Best Practice

Always use groups instead of assigning permissions directly to individual users.

---

# Result

User and group management completed successfully.
