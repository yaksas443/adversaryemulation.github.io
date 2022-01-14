---
layout: default
title: Red Team Adeversary Emulation Lab - FAQ
nav_order: 4
description: FAQs for the self-hosted Red Team Adversary Emulation lab  

permalink: /rtae-lab-faq
---
# Red Team Adversary Emulation Lab - FAQ

## Is there an option to just purchase the lab access instead of opting for self-host option?
- No. At present students who wish to avail the lab can only opt for self-host option. 

## Do you plan to launch lab access packages in the near future?
- No. We don't have any plans to lauch paid lab packages.

## How much time will it take for the request to be processed after submitting the [Self-hosting Prerequisites and Eligibility Form](https://ykrt.in/RTAELabForm)?
- You should hear back from us within 24 hours.

## Are all students eligible for self-host option?
- Yes. All students who have signed up for the course either on Teachable or Udemy are eligible for self-host option.

## Can I avail lab access without signing up for the course?
- You will need to sign up for the course to be eligible for this option. 

## How can I check the charges I am incurring for hosting the lab?
- You can check the charges in AWS Billing section.

## Can I reverse engineer your lab?
- Yes. Infact, we are counting on you for that. Not only will it be a good exercise in understanding how labs are created on AWS, it will enable you to create and share your labs in a similar manner.

## How to reach the lab support team?
- Once your request to self-host has been approved, you will be added to a student support channel on Discord. You can post all your queries there.

## How will lab access be provided?
- Lab access will be provided via browser-based interface. Through this interface you will be able to access a pre-configured Kali Linux machine via both, GUI and SSH.

## Lab deployment got stuck or errored out in between, what should I do?

1. Run the ```!destroy``` command. That should clean up the resources created during the failed depployment. 
2. Once ```!destroy``` command has finished doing it's magic, run ```!deploy``` command again.
3. If this doesn't work, follow these steps to clean up your AWS account:
- a. Login to your AWS account > EC2 - > Terminate all running instances whose name starts with "TFL-". Wait for instances to terminate.
- b. In EC2 go to Key Pairs -> Select all key pairs starting with "tfl-box" and "rtr-attacker-box" -> delete them
- c. Go to VPC -> Select VPC whose name starts with "TFL-LAB" -> delete it (This operation should also delete all other network resources created by AKSH)
- d. If you see multiple VPCs whose name starts with "TFL-LAB", delete them one by one
- e. Go to VPC -> Internet gateways -> Select internet gateway whose name starts with "TFL-LAB" -> delete it (Note: this step is required in certain scenarios only).

## I have a question that is not listed here. Where should I post it?
- Please join [Yaksas CSC on Discord](https://ykrt.in/discord). You can post your questions in the #general channel of this course.
