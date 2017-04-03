---
layout: default
title: Linux
permalink: /linux/
---

# How to do anything in Linux
After many years of dealing with Linux tracking commands for one-off situtations I've decided to track and log them in a much better way. Not sure how I want to lay this out yet, so here is some fluff.

## Remote File Operations
General commands for interacting with remote clients
### Connect to samba share
`$ smbclient //<IP>/<share name> -U <user>`

### Remote copy file 
#### scp

If file exists on *remote* host

`$ scp <user>@<IP>:<file to move> <where you want it>`

If file exists on *local* host

`$ scp <where you want it> <user>@<IP>:<file to move>`