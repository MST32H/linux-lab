# File Permissions

## Overview

Linux permissions control who can read, write, and execute files and directories.

---

## Permission Types

| Symbol | Meaning |
|---------|---------|
| r | Read |
| w | Write |
| x | Execute |

---

## Check Permissions

```bash
ls -l
```

Example:

```text
-rwxr-xr-- 1 user developers file.sh
```

---

## Change Permissions

```bash
chmod 755 file.sh
```

```bash
chmod 644 file.txt
```

---

## Symbolic Mode

```bash
chmod u+x file.sh
chmod g+w file.sh
chmod o-r file.txt
```

---

## Change Owner

```bash
sudo chown ali file.txt
```

Change owner and group

```bash
sudo chown ali:developers file.txt
```

---

## Change Group

```bash
sudo chgrp developers file.txt
```

---

## Permission Numbers

| Number | Permission |
|--------:|------------|
| 7 | rwx |
| 6 | rw- |
| 5 | r-x |
| 4 | r-- |
| 0 | --- |

---

## Verify

```bash
ls -l
```

---

## Interview Questions

- Difference between chmod and chown?
- What does chmod 777 mean?
- Why is chmod 777 considered dangerous?
- Difference between file owner and group?

---

## Best Practice

Avoid using **777** unless absolutely necessary.

Use:

- 755 for executable files
- 644 for normal files

---

## Result

Linux file permissions configured successfully.
