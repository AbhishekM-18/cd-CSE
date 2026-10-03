# 🛡️ Cybersecurity

Cybersecurity is the practice of protecting systems, networks, applications, identities, and data from unauthorized access, misuse, disruption, and other security threats.

It is not just "hacking."

Cybersecurity combines:

- Computer systems
- Operating systems
- Networking
- Programming
- Cryptography
- Web technologies
- Cloud
- Security engineering
- Risk management
- Incident response

A strong cybersecurity foundation therefore starts with understanding how computers and networks actually work.

---

## 🧭 The Cybersecurity Landscape

```text
Cybersecurity
│
├── Security Engineering
│
├── Security Operations (SOC)
│
├── Application Security
│
├── Cloud Security
│
├── Offensive Security
│
├── Digital Forensics & Incident Response
│
└── Governance, Risk & Compliance
```

These areas overlap, but the day-to-day work can be very different.

---

# 🏗️ Security Engineering

Security Engineers design and implement protections for systems and infrastructure.

### Typical Work

- Designing security controls
- Securing networks and systems
- Identity and access management
- Vulnerability management
- Security automation
- Security monitoring
- Secure architecture
- Security tooling

### Important Skills

- Networking
- Linux
- Windows
- Cloud
- Authentication
- Authorization
- Cryptography
- Automation
- Secure system design

---

# 🚨 Security Operations (SOC)

Security Operations teams monitor systems and investigate suspicious activity.

### Typical Work

- Monitoring security alerts
- Investigating incidents
- Analysing logs
- Detecting suspicious behaviour
- Threat investigation
- Incident response
- Escalating security events

### Important Concepts

- SIEM
- Logs
- Indicators of Compromise
- Threat intelligence
- Detection rules
- Incident response
- Security monitoring

### Common Tools

- Microsoft Sentinel
- Splunk
- Elastic
- Wazuh
- Security Onion

---

# 🌐 Application Security

Application Security focuses on building and maintaining secure software.

It connects strongly with:

- Software Engineering
- Backend Development
- Web Development
- Databases
- APIs
- Cloud

### Learn

- Authentication
- Authorization
- Session management
- Input validation
- Secure coding
- API security
- Access control
- Secrets management
- Common web vulnerabilities

---

# ☁️ Cloud Security

Cloud Security focuses on protecting cloud infrastructure and applications.

### Important Concepts

- IAM
- Least privilege
- Network security
- Security groups
- Encryption
- Secrets
- Logging
- Monitoring
- Cloud configuration
- Container security

Cloud security connects directly with:

```text
Cloud
  ↓
Infrastructure
  ↓
Identity
  ↓
Security
```

---

# ⚔️ Offensive Security

Offensive Security involves authorized security testing to identify vulnerabilities before malicious actors can exploit them.

Common areas include:

- Reconnaissance
- Vulnerability assessment
- Web application testing
- Network testing
- Privilege escalation
- Security testing
- Penetration testing

### Common Tools

- Nmap
- Burp Suite
- Wireshark
- Metasploit
- Gobuster
- John the Ripper

**Only test systems you own or have explicit permission to test.**

---

# 🔬 Digital Forensics & Incident Response

This area focuses on investigating security incidents and analysing evidence.

### Learn

- Incident response
- Evidence handling
- Disk analysis
- Memory analysis
- Log analysis
- Network forensics
- Malware investigation
- Timeline analysis

### Tools

- Autopsy
- Wireshark
- Volatility
- KAPE
- Security Onion

---

# 📋 Governance, Risk & Compliance

Not every cybersecurity role involves technical exploitation.

GRC focuses on areas such as:

- Security policies
- Risk assessment
- Compliance
- Security controls
- Auditing
- Governance
- Regulatory requirements

This path can involve less programming and more security management, risk analysis, and organizational processes.

---

# 🧱 Foundations

Before learning advanced cybersecurity, build strong Computer Science foundations.

## 1. Computer Fundamentals

Understand:

- CPU
- Memory
- Storage
- Processes
- Files
- Operating systems
- Applications

---

## 2. Linux

Learn:

- Terminal
- Filesystem
- Permissions
- Users and groups
- Processes
- Services
- Networking commands
- SSH
- Bash scripting
- Logs

Linux is heavily used in servers, security tooling, cloud infrastructure, and security labs.

---

## 3. Networking

This is one of the most important foundations.

Learn:

- OSI model
- TCP/IP
- IP addressing
- Subnetting
- Ports
- TCP
- UDP
- DNS
- DHCP
- HTTP / HTTPS
- Routing
- NAT
- Firewalls
- VPNs

You should understand what happens when a browser connects to a website.

---

## 4. Programming

You don't need to become an expert programmer before starting cybersecurity.

Useful languages include:

- Python
- Bash
- JavaScript
- C
- C++

Python is especially useful for automation, scripting, data processing, and security tooling.

C becomes particularly useful when studying lower-level security concepts such as memory and binary exploitation.

---

# 🔐 Security Fundamentals

## CIA Triad

The three traditional security objectives are:

```text
Confidentiality
       │
       ├── Information is accessible only to authorized parties
       │
Integrity
       │
       ├── Information is not improperly altered
       │
Availability
       │
       └── Systems and information remain accessible when needed
```

---

## Authentication vs Authorization

### Authentication

Answers:

> Who are you?

Examples:

- Password
- MFA
- Biometrics
- Security keys

### Authorization

Answers:

> What are you allowed to do?

These are different security concepts and should not be confused.

---

# 🔑 Cryptography Basics

Learn the purpose and differences between:

- Encryption
- Hashing
- Digital signatures
- Symmetric cryptography
- Asymmetric cryptography
- Certificates
- Public Key Infrastructure
- TLS

Do not begin by memorizing cryptographic algorithms.

First understand **what security problem each mechanism solves**.

---

# 🌐 Web Security

Web security is an important specialization because modern applications expose large attack surfaces.

Learn concepts such as:

- Authentication flaws
- Authorization flaws
- Access control
- SQL injection
- Cross-Site Scripting (XSS)
- CSRF
- SSRF
- File upload vulnerabilities
- Path traversal
- Command injection
- Security misconfiguration
- API security

A major reference for web application security is the **OWASP Top 10**.

---

# 🧪 Hands-On Practice

Cybersecurity is difficult to learn through theory alone.

Use legal, intentionally vulnerable environments.

### TryHackMe

Guided rooms and learning paths with practical security exercises.

### PortSwigger Web Security Academy

Interactive web-security labs covering vulnerabilities such as SQL injection, XSS, authentication, CSRF, API testing, and more. It is free and designed for safe, legal practice. :contentReference[oaicite:1]{index=1}

### OverTheWire

Command-line based security challenges.

### PicoCTF

Beginner-friendly Capture The Flag challenges.

### Hack The Box

Hands-on machines and security challenges for progressing beyond beginner material.

---

# 🧰 Security Tools

Don't learn tools simply by memorizing commands.

Understand the problem each tool solves.

| Tool | Main Purpose |
|---|---|
| Nmap | Network discovery and port scanning |
| Wireshark | Network traffic analysis |
| Burp Suite | Web application security testing |
| Metasploit | Security testing framework |
| Gobuster | Directory and resource discovery |
| John the Ripper | Password auditing |
| Hashcat | Password recovery/auditing |
| Autopsy | Digital forensics |
| Volatility | Memory forensics |

Use these only in authorized environments.

---

# 🛣️ Practical Learning Path

```text
Computer Fundamentals
        ↓
Linux
        ↓
Networking
        ↓
Programming
        ↓
Security Fundamentals
        ↓
Cryptography Basics
        ↓
Web Fundamentals
        ↓
Hands-on Labs
        ↓
Choose a Specialization
        │
        ├── Security Engineering
        ├── SOC / Blue Team
        ├── Application Security
        ├── Cloud Security
        ├── Offensive Security
        └── DFIR
```

This is a flexible learning path, not a rigid requirement.

---

# 🧪 Projects

## Beginner

### 1. Password Strength Checker

Build a program that evaluates password characteristics and explains weaknesses.

### 2. File Integrity Monitor

Create a tool that detects unexpected changes to selected files using hashes.

### 3. Log Analyzer

Build a script that parses logs and identifies suspicious patterns.

### 4. Network Information Tool

Create a small program that displays useful information about network interfaces and connections.

---

## Intermediate

### 5. Security Monitoring Dashboard

Collect logs and visualize security-related events.

### 6. Vulnerability Scanner for Your Own Lab

Build a controlled scanner that identifies selected known weaknesses in systems you own.

### 7. Secure Web Application

Build a small web application implementing:

- Authentication
- Authorization
- Password hashing
- Input validation
- Secure sessions
- Logging

Then test your own application.

---

## Advanced

### 8. Security Automation Platform

Automate selected security checks and generate reports.

### 9. Honeypot Lab

Create an isolated environment designed to record unauthorized interaction attempts.

### 10. Incident Response Lab

Generate controlled security events and practise:

```text
Detection
   ↓
Investigation
   ↓
Containment
   ↓
Eradication
   ↓
Recovery
   ↓
Lessons Learned
```

---

# 📚 Resources

The resources below are selected for different purposes rather than being a huge link dump.

---

## 🧭 Cybersecurity Roadmap

### GeeksforGeeks — Cybersecurity Roadmap

A broad roadmap covering computer fundamentals, Linux, networking, security concepts, cryptography, ethical hacking, web security, cloud security, incident response, and practical platforms. :contentReference[oaicite:2]{index=2}

https://www.geeksforgeeks.org/cybersecurity/cybersecurity-roadmap/

### GeeksforGeeks — Cyber Security Tutorial

A large collection covering networking, cryptography, attacks, web security, forensics, security tools, and defensive concepts. :contentReference[oaicite:3]{index=3}

https://www.geeksforgeeks.org/cybersecurity/cyber-security-tutorial/

---

# 🌐 Networking

### GeeksforGeeks — Computer Networks

Useful for building networking fundamentals before moving into network security.

https://www.geeksforgeeks.org/computer-networks/

### Cloudflare Learning Center

Excellent explanations of DNS, HTTP, TLS, networking, DDoS, VPNs, and other Internet concepts.

https://www.cloudflare.com/learning/

---

# 🐧 Linux

### Linux Journey

Interactive Linux learning material.

https://linuxjourney.com/

### Linux Documentation

Official Linux kernel documentation.

https://www.kernel.org/doc/

### GeeksforGeeks — Linux

Useful supplementary tutorials and command references.

https://www.geeksforgeeks.org/linux-unix/

---

# 🔐 Security Fundamentals

### NIST Cybersecurity Framework

A widely used framework for understanding cybersecurity risk management and security activities.

https://www.nist.gov/cyberframework

### OWASP

A major open community focused on application security.

https://owasp.org/

---

# 🌐 Web Security

### OWASP Top 10

A foundational reference for common web application security risks.

https://owasp.org/www-project-top-ten/

### PortSwigger Web Security Academy

One of the most useful hands-on resources for learning web application security.

It provides learning material and interactive labs covering areas such as SQL injection, XSS, authentication, CSRF, API testing, and other vulnerabilities. :contentReference[oaicite:4]{index=4}

https://portswigger.net/web-security

### OWASP Juice Shop

An intentionally vulnerable application designed for security training.

https://owasp.org/www-project-juice-shop/

---

# 🧪 Hands-On Cybersecurity

### TryHackMe

Guided cybersecurity learning with practical labs and learning paths. Its current platform provides beginner-friendly material as well as more advanced offensive and defensive training. :contentReference[oaicite:5]{index=5}

https://tryhackme.com/

### OverTheWire

Command-line security challenges.

https://overthewire.org/

### PicoCTF

Capture The Flag challenges for developing practical security skills.

https://picoctf.org/

### Hack The Box

Hands-on cybersecurity labs and machines.

https://www.hackthebox.com/

---

# 🕵️ Network Analysis

### Wireshark Documentation

Official documentation and learning resources for packet analysis.

https://www.wireshark.org/docs/

### Wireshark — Display Filters

Useful once you begin analysing real packet captures in a lab.

https://www.wireshark.org/docs/man-pages/wireshark-filter.html

---

# 🔎 Network Discovery

### Nmap Documentation

Official documentation for network discovery and security auditing.

https://nmap.org/docs.html

### Nmap Reference Guide

https://nmap.org/book/man.html

Use Nmap only against systems you own or are authorized to test.

---

# 🛠️ Burp Suite

### PortSwigger Documentation

Official Burp Suite documentation.

https://portswigger.net/burp/documentation

### Burp Suite Community Edition

Useful for learning web security without requiring the professional edition.

https://portswigger.net/burp/communitydownload

---

# 🧬 Digital Forensics

### Autopsy

Open-source digital forensics platform.

https://www.autopsy.com/

### Volatility

Memory forensics framework.

https://volatilityfoundation.org/

---

# 🧑‍💻 Programming for Security

### Python Documentation

Official Python documentation.

https://docs.python.org/3/

### Automate the Boring Stuff with Python

A practical resource for learning Python automation.

https://automatetheboringstuff.com/

### GeeksforGeeks — Python

Useful supplementary tutorials and programming practice.

https://www.geeksforgeeks.org/python-programming-language/

---

# 🏁 Capture The Flag

CTFs are useful because they turn security concepts into problems that you have to solve.

Start with:

```text
PicoCTF
   ↓
OverTheWire
   ↓
TryHackMe
   ↓
PortSwigger Labs
   ↓
Hack The Box
```

Don't treat this as a ranking. Different platforms are useful for different learning goals.

---

# 🧭 Choosing a Specialization

After learning the foundations, experiment with different areas.

### If you enjoy:

**Monitoring and investigation**

→ Explore SOC / Blue Team

**Breaking and testing applications**

→ Explore Offensive Security

**Building secure software**

→ Explore Application Security

**Infrastructure and identity**

→ Explore Cloud Security

**Systems and architecture**

→ Explore Security Engineering

**Investigating incidents**

→ Explore Digital Forensics & Incident Response

---

# ⚠️ Ethics and Legal Boundaries

Cybersecurity skills must be practised responsibly.

Only test:

- Your own systems
- Your own applications
- Intentionally vulnerable labs
- CTF environments
- Systems where you have explicit authorization

Do not scan, exploit, access, or disrupt systems simply because they are reachable from the Internet.

Understanding security and practising security are valuable; unauthorized access is not the same as security research.

---

# 🔗 Connections With Other Fields

```text
             Cybersecurity
             /     |      \
            /      |       \
       Software   Cloud    Systems
          │         │         │
          ↓         ↓         ↓
       AppSec   CloudSec   NetworkSec
            \      |       /
             \     |      /
              └── Security ──┘
```

Cybersecurity is deeply connected to the rest of Computer Science.

Strong knowledge of systems, networks, software, databases, and cloud infrastructure can make security concepts much easier to understand.

---

# 🧪 Learn by Doing

Use this cycle:

```text
Learn the concept
       ↓
Understand why it matters
       ↓
Practise in a legal lab
       ↓
Break a controlled system
       ↓
Understand the vulnerability
       ↓
Learn the defence
       ↓
Document what you learned
```

The goal is not to memorize hacking commands.

The goal is to understand **why a vulnerability exists, how it can be detected, how it can be exploited in an authorized environment, and how it can be prevented.**

---

# 🎯 A Good Starting Point

If you're completely new:

```text
Linux
  ↓
Networking
  ↓
Python / Bash
  ↓
Security Fundamentals
  ↓
Web Fundamentals
  ↓
TryHackMe / OverTheWire
  ↓
PortSwigger Web Security Academy
  ↓
CTFs
  ↓
Choose a specialization
```

Don't start with advanced exploitation tools before understanding the systems you're trying to secure.

---

**`cd CSE` → understand how systems work, learn how they fail, and learn how to protect them.**