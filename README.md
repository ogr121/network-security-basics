Network Security Basics
A short guide and checklist that explains how to protect a small organisation's network. It is written for beginners and junior cybersecurity analysts.
Author: Same Sean Kgakgamatso
Type: Basic network security documentation

Purpose
Many small organisations, such as schools, clinics and local shops, use networks that are not well protected. This project gives simple notes and a checklist that they can follow to reduce the risk of attack.
What is inside
File	Description
`docs/01-network-security-fundamentals.md`	Key ideas: CIA triad, defence in depth, common ports
`docs/02-common-network-threats.md`	Common attacks and how to reduce them
`docs/03-firewalls-and-segmentation.md`	How firewalls, VLANs and a DMZ protect a network
`checklists/network-security-checklist.md`	A checklist for a basic network security review
`LICENSE`	MIT licence
How to use this project
Read the three documents in the `docs` folder in order.
Open the checklist in the `checklists` folder.
Go through each item and tick it when it is done.
Write down any item that fails and fix it based on its priority.
Repository structure
```
network-security-basics/
├── README.md
├── LICENSE
├── docs/
│   ├── 01-network-security-fundamentals.md
│   ├── 02-common-network-threats.md
│   └── 03-firewalls-and-segmentation.md
└── checklists/
    └── network-security-checklist.md
```
Disclaimer
This project is for learning and awareness only. It does not replace a professional security assessment.
References
CIS (2021) CIS Critical Security Controls Version 8. Center for Internet Security. Available at: https://www.cisecurity.org/controls
NIST (2024) The NIST Cybersecurity Framework (CSF) 2.0. National Institute of Standards and Technology. Available at: https://www.nist.gov/cyberframework
Scarfone, K. and Hoffman, P. (2009) Guidelines on Firewalls and Firewall Policy (NIST SP 800-41 Rev. 1). National Institute of Standards and Technology. Available at: https://csrc.nist.gov/pubs/sp/800/41/r1/final
