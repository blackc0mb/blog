---
title: Common Raspberry PI commands
layout: post
description: Useful commands to manage Raspberry PI
date: 2021-02-10 23:20
modified_date: 2021-09-10 18:24
author: TMorales
tag: commands
---
#### Useful commands to manage Raspberry PI
---
**Update** the system package list
```
sudo apt update
```
**Upgrade** the installed packages
```
sudo apt full-upgrade
```
**Free up** space (downloaded packages)
```
sudo apt clean
sudo apt-get clean
```
**Check** the available space
```
df -h
```
**Show** disk usage in current directory
```
du -sh
```
**Open** the configuration settings menu
```
raspi-config
```
**Check** the status of the wireless connection
```
ifconfig
```
**Network** statistics
```
# list all ports
netstat -a

# list all tcp ports
netstat -at

# list only listening tcp ports
netstat -lt

# display the number of active connections on port 80
netstat -an | grep :80 | wc -l

# show statistics for all ports
netstat -s

# show list of network interfaces
netstat -i
```
**Display** the hostname of the system
```
hostname
```
**Check** the OS version  
```
hostnamectl
```
**Reboot** immediately
```
reboot
```
**Open** the text file specified
```
nano [yourfile]
```
---
#### Install VS Code
```
sudo apt update
sudo apt install code -y
```  


Thanks for reading! **TM**  