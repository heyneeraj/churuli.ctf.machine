# Churali CTF

> **"Once you enter Churali, there is no easy way back."**

Churali CTF is a Linux-based Capture The Flag (CTF) machine inspired by the mystery, isolation, and psychological atmosphere of the Malayalam movie **Churuli**. The objective is to simulate a realistic penetration testing environment where participants enumerate services, discover hidden clues, exploit vulnerabilities, escalate privileges, and capture multiple flags.

> **This project is intended for educational purposes only.**

---

## Overview

* **Platform:** Ubuntu Server
* **Difficulty:** Medium–Hard
* **Category:** Boot2Root
* **Author:** Neeraj Rajeev
* **Theme:** Churali (Inspired)
* **Flags:** Multiple
* **Skills Required:**

  * Linux Enumeration
  * FTP Enumeration
  * Web Enumeration
  * File Analysis
  * Password Cracking
  * Privilege Escalation
  * Basic Forensics

---

## Story

A group of investigators enters the mysterious village of **Churali** searching for answers. As they venture deeper, they discover hidden messages, abandoned services, forgotten credentials, and secrets buried within the system.

Every clue leads to another mystery.

Can you escape Churali?

---

## Learning Objectives

After completing this machine, players should be able to:

* Perform network reconnaissance
* Enumerate FTP services
* Identify hidden web content
* Analyze downloaded files
* Crack weak password hashes
* Discover sensitive files
* Enumerate Linux users
* Perform privilege escalation
* Capture user and root flags

---

## Recommended Tools

* Nmap
* Gobuster
* FTP Client
* Hydra
* John the Ripper
* Hashcat
* Netcat
* LinPEAS
* pspy
* Burp Suite
* Base64 Utilities

---

## Machine Information

| Item           | Value                          |
| -------------- | ------------------------------ |
| OS             | Ubuntu Server                  |
| Difficulty     | Medium–Hard                    |
| Format         | OVA                            |
| Virtualization | VirtualBox / VMware            |
| Goal           | Obtain User Flag and Root Flag |

---

## Challenge Flow

1. Host Discovery
2. Port Scanning
3. Service Enumeration
4. FTP Enumeration
5. Web Enumeration
6. Hidden File Discovery
7. Credential Extraction
8. Initial Access
9. Local Enumeration
10. Privilege Escalation
11. Capture User Flag
12. Capture Root Flag

---

## Flags

Example format:

```text
flag{churali_user_flag}

flag{churali_root_flag}
```

---

## Skills Covered

* Information Gathering
* Enumeration
* Linux Privilege Escalation
* Password Security
* Weak Configuration Discovery
* Web Security
* FTP Misconfiguration
* Base64 Decoding
* Hash Cracking

---

## Installation

Import the provided OVA into:

* Oracle VirtualBox
* VMware Workstation

Configure the VM to use:

* NAT
* Host-Only
* Bridged Network

Boot the machine and begin enumeration.

---

## Disclaimer

This CTF contains intentionally vulnerable services and insecure configurations designed for cybersecurity training.

Do **not** deploy this machine on public networks.

Run it only inside an isolated lab environment.

---

## License

This project is released for educational and research purposes only.

Commercial redistribution is not permitted without permission from the author.

---

## Author

**Neeraj Rajeev**

Cybersecurity Researcher

GitHub: https://github.com/heyneeraj

---

## Happy Hacking!

*"The deeper you go into Churali, the stranger everything becomes..."*
