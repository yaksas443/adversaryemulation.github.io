---
layout: default
title: Red Team Adeversary Emulation Lab - Tax First Labz 
nav_order: 3
description: Lab to go along with Yaksas CSC's Red Team Adversary Emulation course  

permalink: /rtae-lab-taxfirstlabz
---
# Red Team Adversary Emulation Lab - Tax First Labz by Yaksas CSC

Tax First Labz (TFL) is a rising name in the world of FinTech startups. Started in 2017 by two college friends, their customer base has grown at a rapid scale in the last two years. Recently, they noticed some unusual activity in their network and suspect that their might be something fishy going on. In order to speed up their investigation, they decided to crowd-source the issue to the cybersecurity community.

This lab is part of the course [Red Team Adversary Emulation](https://adversaryemulation.com/) by [Yaksas CSC](https://yaksas.in). In this course, you will look at an organization’s security from a real-world adversary perspective. You are hired by a FinTech startup, Tax First Labz (http://taxfirstlabz.xyz) to conduct an adversary emulation exercise and steal their customer data (before an actual adversary). This exercise assumes zero knowledge about the target network. 

![](/images/tfl-network.PNG)

In this lab, you will mimic a real world cyber attack with a specific objective, stealing Tax Fist Labz customer data. You will follow the Red Team Operations Attack Lifecycle to conduct this exercise. You will go through each phase in a step-by-step manner and build our attack path as you move ahead. You will employee a variety of techniques, such as

- Active and passive information gathering
- Weaponizing an exploit
- Internal reconnaissance
- Brute-forcing Exchange server via custom username and password lists
- Spear phishing a senior employee
- Privilege Escalation (Linux and Windows)
- Automated Active Directory domain enumeration
- Persistence via command and control center
- Active Directory attacks
- Pivoting
- Data Exfilteration

This is a beginner friendly course and lab. If you have just started your career in offensive cybersecurity or are preparing for penetration testing exams (OSCP, eJPT, eCPT, eCPTx, CRTP, CRTO etc.) then this course is for you. If you are already a penetration tester or a red teamer, you will enjoy following a live adversary emulation exercise from scope creation to reporting.

## Lab access (self-hosted)

If you want to hack the Tax First Labz network, you can do so by hosting the lab network in your own AWS account. To check self-hosting prerequisites and eligibility please fill the form below. Once the instructor approves, you will be provided access to AKSH, our lab management bot on [Discord](https://ykrt.in/discord). You can ask AKSH to automatically deploy / destroy the lab environment in your AWS account, list machines, check lab status, start, stop, reboot and revert machines.

We do not charge anything for self-hosted labs. However, you will have to pay AWS charges for hosting the lab network. The charges are approximately USD 0.38 per hour when the lab is running and approximately USD 0.033 per hour when the lab is stopped. The amount will be charged by Amazon on the credit card you have configured for billing in your AWS account. Charges will be incurred until you destroy the lab environment. 

Once the lab has been deployed, you will be provided access to a pre-configured attacker machine (Kali Linux) via browser-based interface (Apache Guacamole). This machine contains all tools required to attack the target organization and exfilterate the data. 

[Red Team Adversary Emulation Lab - Self-hosting Prerequisites and Eligibility Form](https://ykrt.in/RTAELabForm)

<iframe width="560" height="315" src="https://www.youtube.com/watch?v=yRFK8DZDfX0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Why opt for self-hosted version?

Here are few reasons we think you will enjoy the self-hosted lab:
- You have full-control of the lab. Through our lab management bot, AKSH, you will be able to start and stop the lab as per your convenience. AKSH can do a lot more (check Lab Management via AKSH video in the lab setup section).
- You can reverse engineer the lab setup and understand how to create an red team lab on AWS. 
- There's no time limit. You will have access to the lab network as long as you want.
- It's free (in the sense that you don't have to pay anything to us). You only pay AWS charges ($0.38 / hour when running and $0.033 / hour when stopped).
 
## Lab FAQs

Lab FAQs are available [here](https://adversaryemulation.com/rtae-lab-faq)

## Support

 Lab support will be provided via Discord. Please join [Yaksas CSC Discord server](https://ykrt.in/discord). 
 


