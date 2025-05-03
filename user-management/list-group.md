## 👥 Get to Know Groups in a Linux System

These commands will help you list users:

```bash
sudo cat /etc/group

getent group
```
A group usually looks like this 


```bash
dev:x:1001:
```
From this the first field is the group name,second field is placeholder for password,third field is the group id and last field represent list of users who are in this group

Hence this group is called dev ,x is the password placeholder, witth group id 1001 and 0 group members