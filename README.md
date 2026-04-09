# aplus-labs
CompTIA A+ home lab documentation and notes
# A+ Home Labs — Mike McMillan

CompTIA A+ study labs, help desk scenarios, and IT documentation.
Built as part of my transition into cloud/network engineering.

---

## About Me
Professional athlete and boxing coach transitioning into IT.
Currently pursuing B.S. Cloud & Network Engineering at WGU.
Target certifications: A+ → Network+ → AWS Cloud Practitioner → AWS SAA

---

## Lab Index

| # | Lab | Skills Practiced | Status |
|---|-----|-----------------|--------|
| 01 | VirtualBox Setup + Windows 10 VM | Virtualization, OS deployment | 🔄 In Progress |

---

## Lab 01 — VirtualBox + Windows 10 VM

**Date:** April 8, 2026  
**Tools:** VirtualBox, Windows 10 ISO, Host OS: Windows 11

**What I did:**
- Downloaded and installed VirtualBox on Windows 11 host machine
- Downloaded Windows 10 ISO using Microsoft's Media Creation Tool
- Created a new VM with the following specs:
  - 4096 MB RAM
  - 2 CPUs
  - 50 GB virtual hard disk
- Attached the Windows 10 ISO to the VM
- Booted the VM and started a clean custom installation
- Selected "Install Windows only (advanced)" — no upgrade, fresh install
- Watched Professor Messer: Operating Systems Overview (Core 2)


**What went wrong:**  
- Unattended Installation was checked by default — had to uncheck it manually

**How I fixed it:**  
- Unchecked "Proceed with Unattended Installation" before hitting Finish
  
**Commands / Tools Used:**
- VirtualBox
- Windows 10 ISO Media Creation Tool

**Key Takeaway:**
Learned how VM setup works and the importance of manually 
controlling installation settings vs automated installs.

**What this skill means on the job:**  
IT techs deploy and reimage machines constantly. This is day-one help desk work.

---

*Updated regularly as labs are completed.*
