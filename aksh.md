---
layout: default
title: Managing Self-hosted Labs via AKSH 
nav_order: 4
description: Lab to go along with Yaksas CSC's Red Team Adversary Emulation course  

permalink: /aksh
---
# Managing Self-hosted Labs via AKSH

Necessity is the mother of invetion. That's how AKSH came into being.

When I created the course [Red Team Adversary Emulation: Mimicking a real-world cyber attack](https://yks.red/RTAE), I wanted to provide a means to students to practice the attacks in a real-world lab. I wanted to do so without digging a hole in their pockets. I approached a few companies (well, one company TBH) which could make this possible but it didn't work out. Left with no choice and a determined will to make it possible for students, I set out to learn how to create Discord bots and AWS APIs. Lo and behold, AKSH appeared on the planet.

## What is AKSH?

Before you think I am harboring an alien of some kind, I am not. AKSH is a Discord bot that interfaces with Aamazon Web Services (AWS) via APIs to automate various aspects of managing labs on AWS infrastructure. For example, through AKSH, students can deploy a lab in their own AWS account by issuing a single command (!deploy, that's it). Behind the scences, AKSH will setup all the necessary lab components (VPC, subnets, gateways, security groups, EC2 instances etc.) without any human intervention. What's more? AKSH can deploy multiple labs (as and when I create more of them) of different complexities at the same time (!deploy <lab name>, that's it).     


## Lab access (self-hosted)

If you want to hack the Tax First Labz network, you can do so by hosting the lab network in your own AWS account. To check self-hosting prerequisites and eligibility please fill the form below. Once the instructor approves, you will be provided access to AKSH, our lab management bot on [Discord](https://yks.red/discord). You can ask AKSH to automatically deploy / destroy the lab environment in your AWS account, list machines, check lab status, start, stop, reboot and revert machines.
