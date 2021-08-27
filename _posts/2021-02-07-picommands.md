---
title: Common Raspberry PI commands
layout: post
description: Useful commands to manage Raspberry PI
date: 2021-02-10 23:20
modified_date: 2021-08-27 18:32
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