# ❌ Linux User Deletion – `groupdel` Command

The `groupdel` command is used to remove user accounts in Linux.

---
```bash
sudo groupdel dev
sudo groupdel test
```

Even though this groups have users we can delete the group but we cannot delete primary group of any user or if group is used in some process.

```bash
sudo groupdel sidharth
```
Here we change the user sidharth to group ec2-user

```bash
sudo usermod -g ec2-user sidharth
```

Now when we run grep sidharth /etc/passwd we see that this user is not in sidharth group. Hence we will be able to delete this group now

```bash
sudo groupdel sidharth
```