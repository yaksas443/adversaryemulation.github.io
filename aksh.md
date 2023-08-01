---
layout: default
title: Managing Self-hosted Labs via AKSH 
nav_order: 4
description: Lab to go along with Yaksas CSC's Red Team Adversary Emulation course  

permalink: /aksh
---
# Managing Self-hosted Labs via AKSH

--

Necessity is the mother of invention. That's how AKSH came into being.

When I created the course [Red Team Adversary Emulation: Mimicking a real-world cyber attack](https://yks.red/RTAE), I wanted to provide a means to students to practice the attacks in a real-world lab. I wanted to do so without digging a hole in their pockets. I approached a few companies (well, one company TBH) which could make this possible but it didn't work out. Left with no choice and a determined will to make it possible for students, I set out to learn how to create Discord bots and AWS APIs. Lo and behold, AKSH appeared on the planet.

## What is AKSH?

Before you think I am harboring an alien of some kind, I am not. 

AKSH is a Discord bot that interfaces with AWS via APIs to automate various aspects of managing labs on AWS infrastructure. For example, through AKSH, students can deploy a lab in their own AWS account by issuing a single command (!deploy, that's it). Behind the scences, AKSH will setup all the necessary lab components (VPC, subnets, gateways, security groups, EC2 instances etc.) without any human intervention. What's more? AKSH can deploy [and manage] multiple labs (as and when I create more of them) of different complexities at the same time (!deploy -lab name-, that's it).     

## Okay AKSH, What can you do?

AKSH features the core functionality students will need to self-manage a lab. Additionally, it also caters to few ancillary commands. Here's the list of commands AKSH responds to:

 - ### Lab Management
   - !deploy - Deploy the lab.
   - !destroy - Destroy the lab.
   - !start - Start lab machines. This command takes in either a single machine name or ALL to start all machines.
   - !stop - Stop lab machines. This command takes in either a single machine name or ALL to start all machines.
   - !reboot - Reboot lab machines. This command takes in either a single machine name or ALL to start all machines.
   - !revert - Revert lab machines to their original state. This command takes in either a single machine name or ALL to start all machines.
     
 - ### Ancillary Commands
   - !list - Lists the name of all lab machines.
   - !status - Display the status of lab machines. This command takes in either a single machine name or ALL to start all machines.
   - !showinfo - Display lab access details.
   - !ss - Display real-time updates of a lab management operation. (Fun fact: This command was originally !showstatus but it was too much to type frequently, so I shortened it to !ss. Now you know what ss stands for.)

## I am interested in trying out AKSH, where do I sign-up?

Currently, access to AKSH is restricted to students of the [Red Team Adversary Emulation: Mimicking a real-world cyber attack](https://yks.red/RTAE) course. If you have purchased or have been provided access to the course, please fill out the [Red Team Adversary Emulation Lab - Self-hosting Prerequisites and Eligibility Form](https://yks.red/RTAELabForm).
 
