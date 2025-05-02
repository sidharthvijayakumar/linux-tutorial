## 👥 Get to Know how to add Users in a Linux System

Create a user with a comment (typically the full name):

bash
```
The useradd command is widely supported across most Linux distros (Ubuntu, Debian, CentOS, RHEL, Fedora, Arch)

sudo useradd -c "Sidharth v" sidharth
```
Create the user (with home directory and default shell)
bash
```
sudo useradd -m -s /bin/bash sidharth
```
Set the password for the user
bash
```
sudo passwd sidharth
```
Set the password to expire in 7 days using chage
bash
```
sudo chage -M 7 sidharth
```
