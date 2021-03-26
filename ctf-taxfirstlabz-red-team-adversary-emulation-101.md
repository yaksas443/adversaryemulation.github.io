---
layout: default
title: CTF - Tax First Labz 
nav_order: 4
description: Learn how to perform adversary emulation exercises end-to-end. 

permalink: /ctf-taxfirstlabz-red-team-adversary-emulation-101
---
# CTF - Tax First Labz 

Tax First Labz (TFL) is a rising name in the world of FinTech startups. Started in 2017 by two college friends, their customer base has grown at a rapid scale in the last two years. Recently, they noticed some unusual activity on their webserver and suspect that their might be something fishy going on with their website. In order to speed up their investigation, they decided to crowd-source the issue to the cybersecurity community. 

Here's a replica of their webserver, your aim is to find as many vulnerabilities as you can and ultimately pwn the root user.  

[Tax First Labs Website (Production)](https://ykrt.in/TFLWSPROD)

## How to get started?

- Download the VM from the above link and extract the Zip file.
- Import / Open OVF with VMWare Player or VMWare Workstation or VirtualBox
- Run the VM
- The VM is configured to run in an isolate network (internal network in VirtualBox or LAN Segment in VMWare). This is by design and will keep your host machine and network safe.
- Once the VM is running, it can be accessed at the IP address 192.168.0.152.
- To access the Tax Firt Labz website (http://taxfirstlabz.xyz) create the following entry in the /etc/hosts file on your attacking machine (Kali Linux, Parrot OS etc.):
 ``` 192.168.0.152     taxfirstlabz.xyz ```

Start hunting!
