---
description: >-
  Multiple people are allowed Linux OS in the same time. One of security-wise
  practices is **NOT** to share credentials between users.
---

# Users management

#### CRUD Users opertations:

Those one require `root` priviliges.

#### Useful commands:

* `adduser` - create user
* `userdel` - delete user
* `addgroup` - add group to the system
* `delgroup` - delete group from the system
* `change` - change user account password expiry information
* `sudo` - run one of the commands as another user \(typically with superuser permissions\)
* `su <username>` - switch user 

#### User related files

* `/etc/passwd` - password information
* `/etc/shadow` - encrypted passwords
* `/etc/group` - group infromation
* `/etc/sudoers` - `sudo` user information 

### LDAP \(Lightweight Directory Access Protocol\)

In many cases, LDAP is used as a virtual phone directory, allowing users to easily access contact information for other users. But LDAP is more flexible than a traditional phone directory, as it is capable of referring a querent to other LDAP servers throughout the world, providing an ad-hoc global repository of information. Currently, however, LDAP is more commonly used within individual organizations, like universities, government departments, and private companies. LDAP is a client/server system. The server can use a variety of databases to store a directory, each optimized for quick and copious read operations. 

When an LDAP client application connects to an LDAP server, it can either query a directory or attempt to modify it. In the event of a query, the server either answers the query locally, or it can refer the querent to an LDAP server which does have the answer. If the client application is attempting to modify information within an LDAP directory, the server verifies that the user has permission to make the change and then adds or updates the information.

