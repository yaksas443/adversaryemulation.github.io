---
layout: default
title: Introduction to MITRE ATT&CK Framework
nav_order: 2
description: This post covers basics of MITRE ATT&CK framework. One of the use cases of ATT&CK is Adversary Emulation exercises. 

permalink: /introduction-to-mitre-attack-framework
---
# Introduction to MITRE ATT&CK Framework

This post is part of our course [Adversary Emulation 101: Mimicking a real-world cyber attack](https://courses.yaksas.in/p/adversary-emulation-101-mimicking-a-real-world-cyber-attack/?product_id=2250813&coupon_code=YCSCAELAUNCHSALE).

If you want to beat your adversaries, think like them. A common adage we have all heard. [MITRE ATT&CK](https://attack.mitre.org/) is just that. A framework to think like adversaries and beat them in their game. It is a culmination of years of efforts of studying various cyber Adversaries' Tactics, Techniques and turning them into Common Knowledge (ATT&CK).

## What is ATT&CK framework?

As per [ATT&CK's design and philosophy document](https://attack.mitre.org/docs/ATTACK_Design_and_Philosophy_March_2020.pdf), ATT&CK is a behavioral model that consists of the following core components:

- Tactics, denoting short-term, tactical adversary goals during an attack;
- Techniques, describing the means by which adversaries achieve tactical goals;
- Sub-techniques, describing more specific means by which adversaries achieve tactical goals at a lower level than techniques;
- Documented adversary usage of techniques, their procedures,and other metadata;
- Software, used by adversaries to implement a technique or a sub-technique; and
- Mitigations, preventing adversaries from achieving their tactical goal by blocking the execution of a technique or a sub-technique.

The following figure will help in understanding the relationship between various ATT&CK components.

![ATT&CK components](https://yaksas.in/ycscblog/wp-content/uploads/2021/01/Screenshot-2021-01-13-at-10.09.30-PM.png)

Source: ATT&CK Design and Philosophy Paper (page 27)

## Why was ATT&CK created?

MITRE's goal behind creating this framework was to improve post-compromise detection of threats by tracing out the steps that could have been taken by an adversary. It was born out of the need to categorize adversary behavior as part of conducting adversary emulation exercises within MITRE’s Fort Meade Experiment (FMX) research environment.

## What does it contain?

There are three variants of ATT&CK framework:

- [Enterprise](https://attack.mitre.org/matrices/enterprise/)
- [Mobile](https://attack.mitre.org/matrices/mobile/)
- [ICS (Industrial Control Systems)](https://collaborate.mitre.org/attackics)


Originally, the Enterprise variant focused only on Microsoft Windows. However, later it was expanded to include macOS, Linux, PRE, AWS, GCP, Azure, Azure AD, Office 365, SaaS, Network platforms as well.

Each variant contains various tactics, techniques, sub-techniques and procedures that could be used by an adversary. The best way to visualize the framework is ATT&CK Navigator. It is an interactive web application, through which you can create layered views of the framework, as per your requirement.

## Use cases

ATT&CK can be used for various purposes, such as:

- [Adversary emulation](https://adversaryemulation.com)
- Red teaming
- SOC assessments
- Defensive gap assessments
- Behavioral analytics development
- Cyber threat intelligence enrichment

MITRE provides an excellent [getting started guide](https://www.mitre.org/sites/default/files/publications/mitre-getting-started-with-attack-october-2019.pdf) that shows how to utilize ATT&CK framework for these use cases.
