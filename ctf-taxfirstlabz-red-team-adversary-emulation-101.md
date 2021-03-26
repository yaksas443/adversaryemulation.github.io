---
layout: default
title: Capture the flag - Tax First Labz 
nav_order: 2
description: A boot-to-root machine from Red Team Adversary Emulation 101 course with two flags to capture.  

permalink: /ctf-taxfirstlabz-red-team-adversary-emulation-101
---
# CTF - Tax First Labz 

Tax First Labz (TFL) is a rising name in the world of FinTech startups. Started in 2017 by two college friends, their customer base has grown at a rapid scale in the last two years. Recently, they noticed some unusual activity on their webserver and suspect that their might be something fishy going on with their website. In order to speed up their investigation, they decided to crowd-source the issue to the cybersecurity community. 

Here's a replica of their webserver, your aim is to find as many vulnerabilities as you can and ultimately pwn the root user.  

[Tax First Labs Website (Production)](https://ykrt.in/TFLWSPROD)

## How to get started?

1. Download the VM from the above link and extract the Zip file.
2. Import / Open OVF with VMWare Player or VMWare Workstation or VirtualBox
3. Run the VM
4. The VM is configured to run over a host-only network and obtains the IP address automatically via DHCP. You will need to discover the IP address of the machine by using a network scanning tool, such as nmap.
5. Once you have discovered the IP address, note it down for the next step.
6. To access the Tax Firt Labz website (http://taxfirstlabz.xyz) create the following entry in the /etc/hosts file on your attacking machine (Kali Linux, Parrot OS etc.):
<br> ``` <IP address discovered in step 4>     taxfirstlabz.xyz ```

## Rewards

Tax First Labs has hidden a few surprise gifts within this machine as a reward for your efforts. First 10 users to pwn root will earn a special reward (don't forget to check flag.txt).

## How to enter the Hall of fame?

Just tweet us at @yaksas443 once you have pwned either the user or root.

## Hall of fame

- **User blood**: TBD  
- **System blood**: TBD
- **User owns**: 0  
- **Root owns**: 0

### First 10 people to pwn this machine

TBD

Happy hacking!
