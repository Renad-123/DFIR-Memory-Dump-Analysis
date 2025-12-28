# DFIR Memory Dump Analysis

## Overview
This project demonstrates a Digital Forensics and Incident Response (DFIR) investigation performed on a system memory dump using the Volatility Framework. The case simulates a real-world scenario in which a client completely lost access to his system due to an unknown error. During the investigation, it was identified that the user is an environmental activist who frequently uses web browsers and password managers, specifically KeePass, to store sensitive information. The primary objective of this analysis was to examine volatile memory, identify suspicious artifacts, recover stored credentials, and extract critical forensic evidence.

---

## Investigation Summary
The memory dump was analyzed using Volatility plugins to inspect running processes and environment variables. Suspicious environment variables revealed references to a PNG file containing a hidden password. This recovered password was then used to successfully unlock a KeePass database found within the memory dump, allowing the extraction of the required flag.

---

## Tools Used
- Volatility Framework  
- KeePass Password Manager  
- Memory Forensics Techniques  

---
