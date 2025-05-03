## 👥 Get to Know how to modify group in Linux System

The `groupmod` command is used to modify a group in Linux.

This command changes the group's name from dev to test
```bash
sudo groupmod -n test dev
```
Change the GID of devops to 2020:

```bash
sudo groupmod -g 2020 test
```