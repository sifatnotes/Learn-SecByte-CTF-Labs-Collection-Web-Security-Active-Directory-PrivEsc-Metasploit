# Learn-SecByte-CTF-Labs-Collection-Web-Security-Active-Directory-PrivEsc-Metasploit
A curated collection of hands-on cybersecurity CTF labs covering Burp Suite Essentials, Web Security (SQLi/XSS/CSRF/IDOR), Windows &amp; Linux Privilege Escalation, Active Directory Attacks, Metasploit Framework, and Professional Pentesting Reports from Learn SecByte.
# Learn SecByte CTF & Cybersecurity Labs Collection

Welcome to the **Learn SecByte CTF & Cybersecurity Labs Collection**. This repository is a dedicated, searchable index of hands-on web application security testing, Burp Suite intercept proxy operations, OWASP Top 10 web vulnerabilities (SQLi, XSS, CSRF, IDOR), Windows and Linux privilege escalation mastery, Active Directory attack mechanics, password cracking, Metasploit Framework exploitation, wireless penetration testing, and professional reporting labs designed for cybersecurity students, CTF players, penetration testers, and security consultants.

---

## Table of Contents
- [Introduction](#introduction)
- [Lab Collection & Index](#lab-collection--index)
- [Categories](#categories)
- [Learning Path](#learning-path)
- [How to Use the Labs](#how-to-use-the-labs)
- [Disclaimer](#disclaimer)

---

## Introduction

Executing thorough penetration tests and delivering actionable security assessments require mastering technical attack primitives alongside industry-standard tools and professional reporting frameworks. Hosted on [Learn SecByte](https://learn.secbyte.org/), this comprehensive collection of CTF challenge labs provides practical, hands-on training across foundational and advanced offensive security disciplines.

From analyzing web traffic in Burp Suite and exploiting core web vulnerabilities (SQL Injection, Cross-Site Scripting, CSRF, Insecure Direct Object References), to escalating privileges on Windows and Linux endpoints, compromising Active Directory domains, harvesting and cracking password hashes, conducting wireless pentests, leveraging Metasploit for multi-stage exploitation, and authoring professional pentest reports, these labs prepare practitioners for real-world engagements.

---

## Lab Collection & Index

Below is the complete, searchable index of all web security, privilege escalation, Active Directory, password cracking, and pentesting methodology challenges in this collection:

| # | Lab / Challenge Name | Category | Focus / Key Topics | Lab Link |
|---|----------------------|----------|---------------------|----------|
| 1 | **Penetration Testing Methodology and Professional Reporting** | Methodology, Wireless & Reporting | PTES/NIST pentesting lifecycle, risk rating matrices (CVSS), technical report authoring, remediation recommendations | [Access Lab](https://learn.secbyte.org/ctf/penetration-testing-methodology-and-professional-reporting) |
| 2 | **Wireless Network Penetration Testing: From Reconnaissance to...** | Methodology, Wireless & Reporting | WPA2/WPA3 packet capturing, airmon-ng / airodump-ng, handshake cracking, rogue AP attacks, enterprise WiFi auditing | [Access Lab](https://learn.secbyte.org/ctf/wireless-network-penetration-testing-from-reconnaissance-to-) |
| 3 | **Post-Exploitation and Lateral Movement** | System Privilege Escalation & AD | Local credential harvesting, Pass-the-Hash (PtH), SOCKS proxy routing, internal subnet discovery, SSH agent hijacking | [Access Lab](https://learn.secbyte.org/ctf/post-exploitation-and-lateral-movement) |
| 4 | **Active Directory Fundamentals and Attacks** | System Privilege Escalation & AD | Domain Controller architecture, Kerberoasting, AS-REP Roasting, BloodHound graph analysis, DCSync attacks | [Access Lab](https://learn.secbyte.org/ctf/active-directory-fundamentals-and-attacks) |
| 5 | **Windows Privilege Escalation Mastery** | System Privilege Escalation & AD | Token impersonation (`SeImpersonatePrivilege`), unquoted service paths, UAC bypasses, DLL hijacking, WinPEAS | [Access Lab](https://learn.secbyte.org/ctf/windows-privilege-escalation-mastery) |
| 6 | **Linux Privilege Escalation: From Enumeration to Root** | System Privilege Escalation & AD | SUID/SGID binary exploitation, LinPEAS, Linux capabilities, sudo misconfigurations, GTFOBins, kernel exploits | [Access Lab](https://learn.secbyte.org/ctf/linux-privilege-escalation-from-enumeration-to-root) |
| 7 | **Metasploit Framework Fundamentals: From Modules to Multi-Stage** | Frameworks & Credential Access | `msfconsole` workflows, auxiliary scanning, staged vs. stageless payloads, Meterpreter post-modules, workspace management | [Access Lab](https://learn.secbyte.org/ctf/metasploit-framework-fundamentals-from-modules-to-multi-stag) |
| 8 | **Password Attacks & Authentication Security** | Frameworks & Credential Access | Online brute-forcing (Hydra), offline hash cracking (Hashcat / John the Ripper), rainbow tables, MFA bypass logic | [Access Lab](https://learn.secbyte.org/ctf/password-attacks-authentication-security) |
| 9 | **Common Web Vulnerabilities: SQLi, XSS, CSRF, IDOR** | Web Application Security | SQL Injection, Reflected/Stored XSS, Cross-Site Request Forgery, Insecure Direct Object References | [Access Lab](https://learn.secbyte.org/ctf/common-web-vulnerabilities-sqli-xss-csrf-idor) |
| 10 | **Burp Suite Essentials: Intercept, Analyze & Validate Web Traffic** | Web Application Security | Proxy interception, Repeater analysis, Intruder payload fuzzing, Decoder transformations, extension management | [Access Lab](https://learn.secbyte.org/ctf/burp-suite-essentials-intercept-analyze-validate-web-traffic) |
| 11 | **Web Application Fundamentals** | Web Application Security | HTTP/HTTPS protocols, request/response headers, status codes, cookies, session management, web server architecture | [Access Lab](https://learn.secbyte.org/ctf/web-application-fundamentals) |
| 12 | **Vulnerability Assessment Fundamentals 2** | Methodology, Wireless & Reporting | Automated scanning (Nessus/OpenVAS/Nuclei), vulnerability validation, false positive filtering, risk prioritization | [Access Lab](https://learn.secbyte.org/ctf/vulnerability-assessment-fundamentals-2) |

---

## Categories

### 1. Web Application Security & Intercept Operations
Master web protocol fundamentals, analyze HTTP traffic in Burp Suite, and exploit core OWASP vulnerabilities including SQLi, XSS, CSRF, and IDOR.
- [Web Application Fundamentals](https://learn.secbyte.org/ctf/web-application-fundamentals)
- [Burp Suite Essentials: Intercept, Analyze & Validate Web Traffic](https://learn.secbyte.org/ctf/burp-suite-essentials-intercept-analyze-validate-web-traffic)
- [Common Web Vulnerabilities: SQLi, XSS, CSRF, IDOR](https://learn.secbyte.org/ctf/common-web-vulnerabilities-sqli-xss-csrf-idor)

### 2. System Privilege Escalation & Active Directory
Identify privilege escalation paths on Windows and Linux hosts, harvest credentials, pivot through internal networks, and compromise Active Directory domains.
- [Linux Privilege Escalation: From Enumeration to Root](https://learn.secbyte.org/ctf/linux-privilege-escalation-from-enumeration-to-root)
- [Windows Privilege Escalation Mastery](https://learn.secbyte.org/ctf/windows-privilege-escalation-mastery)
- [Active Directory Fundamentals and Attacks](https://learn.secbyte.org/ctf/active-directory-fundamentals-and-attacks)
- [Post-Exploitation and Lateral Movement](https://learn.secbyte.org/ctf/post-exploitation-and-lateral-movement)

### 3. Exploitation Frameworks & Credential Access
Operate the Metasploit Framework for multi-stage attacks, execute online/offline password cracking, and bypass authentication mechanisms.
- [Password Attacks & Authentication Security](https://learn.secbyte.org/ctf/password-attacks-authentication-security)
- [Metasploit Framework Fundamentals: From Modules to Multi-Stage](https://learn.secbyte.org/ctf/metasploit-framework-fundamentals-from-modules-to-multi-stag)

### 4. Pentest Methodology, Wireless Auditing & Professional Reporting
Conduct vulnerability assessments, audit wireless networks, structure engagement workflows according to PTES standards, and write executive-ready pentest reports.
- [Vulnerability Assessment Fundamentals 2](https://learn.secbyte.org/ctf/vulnerability-assessment-fundamentals-2)
- [Wireless Network Penetration Testing: From Reconnaissance to...](https://learn.secbyte.org/ctf/wireless-network-penetration-testing-from-reconnaissance-to-)
- [Penetration Testing Methodology and Professional Reporting](https://learn.secbyte.org/ctf/penetration-testing-methodology-and-professional-reporting)

---

## Learning Path

Follow this structured progression path to build comprehensive expertise across web security, system compromise, and professional pentesting workflows:

1. **Phase 1: Web Protocols, Burp Suite & Web Vulnerabilities** — Master web application mechanics, intercept traffic, and exploit core flaws:
   - [Web Application Fundamentals](https://learn.secbyte.org/ctf/web-application-fundamentals)
   - [Burp Suite Essentials: Intercept, Analyze & Validate Web Traffic](https://learn.secbyte.org/ctf/burp-suite-essentials-intercept-analyze-validate-web-traffic)
   - [Common Web Vulnerabilities: SQLi, XSS, CSRF, IDOR](https://learn.secbyte.org/ctf/common-web-vulnerabilities-sqli-xss-csrf-idor)

2. **Phase 2: Password Attacks & Exploitation Frameworks** — Crack password hashes, execute online brute-forcing, and deploy Metasploit modules:
   - [Password Attacks & Authentication Security](https://learn.secbyte.org/ctf/password-attacks-authentication-security)
   - [Metasploit Framework Fundamentals: From Modules to Multi-Stage](https://learn.secbyte.org/ctf/metasploit-framework-fundamentals-from-modules-to-multi-stag)

3. **Phase 3: System Privilege Escalation, AD Attacks & Lateral Movement** — Gain root/SYSTEM access, exploit Active Directory, and pivot across subnets:
   - [Linux Privilege Escalation: From Enumeration to Root](https://learn.secbyte.org/ctf/linux-privilege-escalation-from-enumeration-to-root)
   - [Windows Privilege Escalation Mastery](https://learn.secbyte.org/ctf/windows-privilege-escalation-mastery)
   - [Active Directory Fundamentals and Attacks](https://learn.secbyte.org/ctf/active-directory-fundamentals-and-attacks)
   - [Post-Exploitation and Lateral Movement](https://learn.secbyte.org/ctf/post-exploitation-and-lateral-movement)

4. **Phase 4: Wireless Security, Vulnerability Assessments & Reporting** — Audit wireless environments, execute vulnerability scans, and author professional deliverables:
   - [Vulnerability Assessment Fundamentals 2](https://learn.secbyte.org/ctf/vulnerability-assessment-fundamentals-2)
   - [Wireless Network Penetration Testing: From Reconnaissance to...](https://learn.secbyte.org/ctf/wireless-network-penetration-testing-from-reconnaissance-to-)
   - [Penetration Testing Methodology and Professional Reporting](https://learn.secbyte.org/ctf/penetration-testing-methodology-and-professional-reporting)

---

## How to Use the Labs

1. Select a challenge link from the index or category sections above.
2. Read the engagement specifications and scenario goals on [Learn SecByte](https://learn.secbyte.org/).
3. Deploy penetration testing toolsets (Burp Suite Pro/Community, Metasploit, Hashcat, Hydra, BloodHound, Impacket, LinPEAS, WinPEAS) inside an isolated testing workstation.
4. Intercept web traffic, exploit injection vulnerabilities, escalate system privileges, crack credential hashes, capture target flags, and compile findings into technical reports.

---

## Disclaimer

This repository and its linked resources are strictly intended for educational, threat research, and authorized technical security training purposes. Never execute vulnerability scanners, web exploits, or privilege testing tools against unauthorized systems, production applications, or third-party networks.
