# SSH (Secure Shell)

## Overview

SSH allows secure remote access and management of Linux servers over a network.

---

## Check SSH Status

```bash
sudo systemctl status ssh
```

---

## Install OpenSSH Server

```bash
sudo apt update
sudo apt install openssh-server -y
```

---

## Start SSH

```bash
sudo systemctl start ssh
```

---

## Enable SSH at Boot

```bash
sudo systemctl enable ssh
```

---

## Restart SSH

```bash
sudo systemctl restart ssh
```

---

## Connect to a Remote Server

```bash
ssh username@192.168.1.100
```

---

## Connect Using a Custom Port

```bash
ssh -p 2222 username@192.168.1.100
```

---

## Copy File to Remote Server

```bash
scp file.txt username@192.168.1.100:/home/username/
```

---

## Copy Directory

```bash
scp -r project username@192.168.1.100:/home/username/
```

---

## Generate SSH Key

```bash
ssh-keygen -t ed25519 -C "your-email@example.com"
```

---

## Copy Public Key

```bash
ssh-copy-id username@192.168.1.100
```

---

## SSH Configuration File

```bash
sudo nano /etc/ssh/sshd_config
```

---

## Verify

```bash
systemctl status ssh
ssh localhost
```

---

## Interview Questions

- What is SSH?
- Difference between SSH Password Authentication and SSH Key Authentication?
- What is sshd?
- What is the default SSH port?
- How do you secure an SSH server?

---

## Best Practice

- Disable root login.
- Disable password authentication when using SSH keys.
- Use strong key pairs.
- Change the default port if required.

---

## Common Troubleshooting

### Connection Refused

```bash
sudo systemctl status ssh
sudo systemctl restart ssh
sudo ufw status
```

### Permission Denied

Check:

```bash
~/.ssh
authorized_keys
```

---

## Result

SSH service configured and verified successfully.
