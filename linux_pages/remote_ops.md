---
layout: default
title: Remote File Operations
exclude: true
permalink: linux/remote_ops/
categories: linux, remote, fileops
---

# Remote File Operations
General commands for interacting with remote clients

## Connect to samba share
`$ smbclient //<IP>/<share name> -U <user>`

## Remote copy file 
### scp

If file exists on *remote* host

`$ scp <user>@<IP>:<file to move> <where you want it>`

If file exists on *local* host

`$ scp <where you want it> <user>@<IP>:<file to move>`