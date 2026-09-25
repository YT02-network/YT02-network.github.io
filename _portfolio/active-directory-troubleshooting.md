---
title: "Active Directory Lab - Troubleshooting Documentation"
excerpt: "Detailed troubleshooting documentation from an Active Directory and Windows Server home lab."
collection: portfolio
---

# Active Directory Lab - Troubleshooting Documentation

This document contains detailed troubleshooting scenarios encountered while building and configuring the Active Directory home lab.

Each issue follows a troubleshooting process:

**Problem → Diagnosis → Testing → Solution → Validation**

---

## Issue 1 — Resolving Group Policy Object Conflict

**Environment:** Oracle VirtualBox v7.2.8 / Windows Server 2019 / Windows 10 Pro

### Problem

I could not access the Control Panel on either of my administrator accounts on both the Client and Server VMs.

### Diagnosis

I used `gpresult /r` on the server to identify which policies were affecting the user. The configured GPOs linked to the `_USERS` OU were also appearing as applied policies.

### Testing

I used:


```text
gpresult /h grepreport.html
