# 🐧 Linux for Beginners – Episode 1: User Management

This guide covers the basic user management commands demonstrated in Episode 1 of the Linux YouTube series.

---

## 👥 Get to Know Users in a Linux System

These commands will help you list users:

```bash
cat /etc/passwd
getent passwd
cut -d':' -f1 /etc/passwd or cat /etc/passwd | cut -d':' -f1
```

To get both the username and their home directory:
```bash
cut -d':' -f1,6 /etc/passwd
```