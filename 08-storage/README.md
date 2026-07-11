# Storage Management

## Overview

This lab covers Linux disk and storage management.

---

## List Disks

```bash
lsblk
```

---

## Show Disk Usage

```bash
df -h
```

---

## Show Directory Size

```bash
du -sh /home
```

---

## Display Disk Partitions

```bash
sudo fdisk -l
```

---

## Display UUID

```bash
blkid
```

---

## Mount a Disk

```bash
sudo mount /dev/sdb1 /mnt
```

---

## Unmount a Disk

```bash
sudo umount /mnt
```

---

## Create Filesystem

```bash
sudo mkfs.ext4 /dev/sdb1
```

---

## Check Mounted Devices

```bash
mount
```

---

## Verify

```bash
lsblk
df -h
mount
```

---

## Interview Questions

- Difference between `df` and `du`?
- What is a filesystem?
- Difference between mount and umount?
- What is UUID?

---

## Best Practice

Always use UUID in `/etc/fstab` instead of device names.

---

## Common Troubleshooting

### Disk Not Mounted

```bash
lsblk
blkid
mount
```

### No Space Left on Device

```bash
df -h
du -sh /*
```

---

## Result

Storage configured and verified successfully.
