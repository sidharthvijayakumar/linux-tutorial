## 👥 Get to Know how to add Users to a group in Linux System

The `usermod` command is used to add a user to group in Linux.

## 🧹 Basic Usage
This command is used to add sidharth to dev group

```bash
sudo usermod -aG dev sidharth
```
-a flag appends the user to this group if this is not used all existing group memmbers would be removed this is a safe command and it must be used

```bash
sudo group add dev
sudo group add test

sudo useradd -m -c "Sidharth V" sidharth
sudo useradd -m -c "Jake F" jake

sudo usermod -aG dev sidharth
sudo usermod -G dev jake

sudo usermod -aG test sidharth
sudo usermod -G test jake

groups sidharth
groups jake
```
Here for jake as -a was not used he will be removed from dev group but sidharth will be part of both dev and test