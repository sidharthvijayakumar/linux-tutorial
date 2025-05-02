# ❌ Linux User Deletion – `userdel` Command

The `userdel` command is used to remove user accounts in Linux.

---

## 🧹 Basic Usage

Delete a user along with their home directory and mail spool:

```bash
sudo userdel -r sidharth
```
If you omit the -r flag. Only the user account is deleted. The user's home directory and files will remain on the system.

```bash
sudo userdel sidharth
```
Always ensure the user is not logged in before deleting:

```bash
who | grep sidharth
```
If the user is running a process, you may need to kill it before deletion:

```bash
pkill -u sidharth
```
Use with caution – this will delete the user and their files, even if they’re logged in.
```bash
sudo userdel -r -f sidharth
```