---
title: "Active Directory Home Lab"
excerpt: "Built and configured a Windows Active Directory environment using VirtualBox."
collection: portfolio
---

# Active Directory Home Lab

## Overview

Built a small Windows domain environment using VirtualBox to practice Active Directory, Windows administration, networking, and Group Policy.

## Lab Environment

- VirtualBox
- Windows Server
- Windows Client
- Active Directory Domain Services
- DNS
- Group Policy

## What I Practiced

- Created and configured a Windows Server domain controller
- Created a Windows client virtual machine
- Joined the client computer to the domain
- Created users and Organizational Units (OUs)
- Configured Group Policy
- Configured password policies
- Configured account lockout policies
- Tested Group Policy application
- Used `gpresult` to troubleshoot policy application
- Troubleshot Group Policy and policy inheritance issues

## Troubleshooting

One of the challenges I encountered was a Group Policy setting not appearing to apply correctly.

I used `gpresult` to examine the policies being applied to the client and investigated the Group Policy hierarchy and inheritance.

This helped me understand that configuring a policy is only part of the process — you also need to verify that the correct computer or user is receiving the policy.

## Evidence

Screenshot documenting the lab configuration and troubleshooting process
   
  ## Virtual Lab Environment

  ## Active Directory Users and Organizational Units

  ## Domain-Joined Client

  ## Group Policy Configuration

  ## Group Policy Testing

  ## gpresult /r Verification

  ## Troubleshooting

## What I Learned

This lab gave me hands-on experience with Windows Server administration, Active Directory, Group Policy, virtualization, and basic troubleshooting.

It also helped me become more comfortable troubleshooting problems rather than simply following configuration instructions.

## Future Improvements

- Add additional domain users and groups
- Create more Group Policy scenarios
- Practice permissions and shared folders
- Add additional Windows clients
- Document more troubleshooting scenarios
