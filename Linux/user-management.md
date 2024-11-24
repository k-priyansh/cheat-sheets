# User Management

| Command | Description |
| --- | --- |
| `sudo adduser <user>` | Create a new user |
| `sudo userdel <user>` | Delete a user |
| `sudo usermod -aG <group> <user>` | Add a user to group |
| `sudo deluser <user> <group>` | Remove a user from a group |
| `passwd <username>` | change password |
| `usermod -e <YYYY-MM-DD> <username>` | Set expiration date for account |
| `grep <username> /etc/passwd` | Examine hashed password |
| `id <username>` | Examine properties of user |
| `usermod -u 1600 <username>` | Change user ID |
| `usermod -g 999 <username>` | Move to new group ID |
| `chage -l <username>` | Set password expiration date |
| `useradd -s /bin/sh -g <groupname> <username>` | Add user with custom group and custom default shell |

# Group Management

| Command | Description |
| --- | --- |
| `groupadd <groupname>` | Create group |
| `grep <groupname> /etc/group` | Examine group entry |
| `groupadd -r <groupname>` | Create system group |
| `groupmod -g 1600 <groupname>` | Change group ID |
| `groupmod -n <oldgroupname> <newgroupname>` | Rename group |
| `groupdel <groupname>` | Delete group |
