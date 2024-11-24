# Permissions in Linux

> Structure of permission `d-rwx-rwx-rx` (d-owner-groups-others)

---

| Command | Description |
| --- | --- |
| `r` | Read |
| `w` | Write |
| `x` | Execute |

---

| Command | Description |
| --- | --- |
| `u` | user |
| `g` | group |
| `o` | others |
| `a` | all |

---

## Permission Codes 

| Command | Description |
| --- | --- |
| `541` | `r-x r-- --x` |
| `704` | `rwx --- r--` |
| `352` | `-wx r-x -w-` |

> Reference : r=4 w=2 x=1

---

## Important Commands
| Command | Description |
| --- | --- |
| `chown` | Changing Ownership |
| `chgrp` | Changing Group |
