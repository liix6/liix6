
<h1 align="center">🛡 L-966 | Penetration Tester & Security Researcher</h1>
<h3 align="center">Web Security • Offensive Testing • Advanced Exploitation</h3>
<!-- GIF Section -->
<p align="center">
  <img src="https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExZ24zdmlzNzViMnQ2MHRnenIyZTZmNWw0aHltNGhicWk0c3Fmb2cxaiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/4OAxDXv4RdUeg38JYi/giphy.gif" alt="Cyber GIF" width="800" height="400"/>
</p>
<!-- Digital Green Lines -->
<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com/?lines=HELLO+WORLD+L-966;Welcome+to+the+Null+Zone.;BE+ONE+OR+ZERO&center=true&width=1000&height=120&color=00FF00&font=VT323&size=60" />
</p>
 
 ## Overview

I specialize in **manual penetration testing** and uncovering **high-impact vulnerabilities** through deep analysis of application logic.My focus is not just finding bugs — but **turning them into real-world impact**.

**Aspiring Cybersecurity Researcher dedicated to strengthening national security and technological resilience. Possess deep technical expertise in vulnerability research, error analysis, and identifying critical security flaws with full-impact potential. Driven by a passion for securing sensitive data and fortifying national infrastructure against emerging threats."**

*  Strength: Business Logic & Manual Testing
* 🇸🇦 Mission: Strengthening digital & national infrastructure

---

## 🚀 Present Status

*  Still Learning Bug hunting & malware forensics 
*  Writing Some Useful Tools For Myself & Communities
* Currently Learning mobile pentesting & web3
---

## ⚔️ Core Expertise

* Account Takeover (ATO) via logic flaws
* Authentication & Authorization bypass
* API Security Testing & API Key Leaks
* Business Logic Vulnerabilities
* Sensitive Data Exposure & Internal Mapping
* Vulnerability Chaining (Multi-step exploitation)
* Open Source Security Research (CVE discovery & responsible disclosure)
* Testing behind WAFs & Reverse Proxies (Nginx)
* Enterprise Application Security (workflow/process engines, web portals)
* Manual Web/API Penetration Testing (Burp Suite, browser DevTools)

---
##  Certifications & Learning Path

- ✅ [Google Cybersecurity Professional Certificate](رابط_credential_هنا)
- 🔄 In Progress: eJPT
- 🔄 In Progress: CompTIA Security+
- 🎯 Planned: OSCP

## 🛠️ Tools & Environment

###  Recon & OSINT

* Subfinder / Amass
* Waybackurls
* Advanced Google Dorking

### 💣 Knowledge Tools & Skills
<p>
<img src="https://img.shields.io/badge/Burp%20Suite-FF6633?style=for-the-badge&logo=burpsuite&logoColor=white">
<img src="https://img.shields.io/badge/FFUF-000000?style=for-the-badge">
<img src="https://img.shields.io/badge/Metasploit-2596CD?style=for-the-badge">
<img src="https://img.shields.io/badge/Vulnerability%20Scanning-grey?style=for-the-badge">
<img src="https://img.shields.io/badge/Exploitation-8A2BE2?style=for-the-badge">

<img src="https://img.shields.io/badge/Kali%20Linux-268BEE?style=for-the-badge&logo=kalilinux&logoColor=white">
<img src="https://img.shields.io/badge/Linux-000000?style=for-the-badge&logo=linux&logoColor=white">
<img src="https://img.shields.io/badge/Termux-000000?style=for-the-badge">
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white">

<img src="https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white">
<img src="https://img.shields.io/badge/Network%20Testing-darkgreen?style=for-the-badge">
<img src="https://img.shields.io/badge/Proxies%20%26%20Traffic%20Analysis-444444?style=for-the-badge">
</p>
### Web Exploitation
<p>
<img src="https://img.shields.io/badge/Burp%20Suite-FF6633?style=for-the-badge&logo=burpsuite&logoColor=white">
<img src="https://img.shields.io/badge/FFUF-000000?style=for-the-badge">
<img src="https://img.shields.io/badge/Metasploit-2596CD?style=for-the-badge">
<img src="https://img.shields.io/badge/Exploitation-8A2BE2?style=for-the-badge">
</p>

* Burp Suite Professional (Manual Testing Expert)
* FFUF (Fuzzing & Discovery)
* Metasploit
* Vulnerability Scanners
* Exploitation Tools

### 🖥️ Environment

<p>
<img src="https://img.shields.io/badge/Kali%20Linux-268BEE?style=for-the-badge&logo=kalilinux&logoColor=white">
<img src="https://img.shields.io/badge/Linux-000000?style=for-the-badge&logo=linux&logoColor=white">
<img src="https://img.shields.io/badge/Termux-000000?style=for-the-badge">
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white">
</p>

* Kali Linux
* Linux / Termux
* Docker (Custom Labs)
* Operating Syste
* Metasploit
### 📡 Network & Analysis
<p>
<img src="https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white">
<img src="https://img.shields.io/badge/Network%20Security-darkgreen?style=for-the-badge">
<img src="https://img.shields.io/badge/Traffic%20Analysis-444444?style=for-the-badge">
</p>

* Network Security Testing
* Wireshark
* Proxies & Traffic Analysis

---

##  Methodology

* Recon → Attack Surface Mapping
* Analyze → Break Logic & Trust Boundaries
* Exploit → Chain Vulnerabilities
* Impact → Full Compromise

---

## 🔴 Real Cases (Sanitized)

### Missing Sender Identity Verification (Message Broker / IoT Relay)

* No validation of sender identity against target service ID
* Rogue client can inject privileged job/command messages
  ➜ Unauthorized execution of privileged system commands

### Host Header Injection (Web Framework - Open Source)

* Blind trust of X-Forwarded-Host header, no allowlist
* Attacker-controlled header used to construct root URLs
  ➜ Credential leakage to attacker-controlled origin

### Host Header Injection → Account Takeover (Enterprise Portal - Open Source)

* Unvalidated host header used in password reset URL generation
  ➜ Reset link poisoning leads to full account takeover

### IDOR - Internal Identifier Disclosure

* Insecure Direct Object Reference exposes internal SSO identifier
  ➜ Cross-user identifier disclosure

### Blind SSRF via Stored Injection

* User-controlled referral parameter stored and later processed server-side
  ➜ Blind outbound requests to attacker-specified destinations

### Critical 2FA/OTP Bypass — Administrative Access

* Client-side-only OTP validation logic
  ➜ Full bypass leads to unauthorized admin panel access

### SQL Injection → Authentication Bypass (Government/Critical Infrastructure)

* Improper input sanitization in authentication query logic
  ➜ Authentication bypass exposing sensitive operational records

---

## 📂 My Work

###  Bug Bounty Reports (Sanitized Writeups)
Real-world vulnerability reports from private and public bug bounty programs.
Target identities are redacted or generalized in accordance with each program's
responsible disclosure policy.

📁[Bug Bounty Writeups Repo](https://github.com/liix6/bugs-writeups)
> Categorized by vulnerability class: ATO, SSRF, IDOR, 2FA Bypass, etc.

---

### 🔓 Open Source Vulnerability Research
CVE research and public disclosures on open-source projects. Includes
proof-of-concept analysis, root cause breakdown, and remediation notes.

📁 [Open Source Vulnerability Research Repo](https://github.com/liix6/Open-Source-Vulnerability)
> Includes confirmed & pending CVEs —
> Confirmed vulnerabilities in major open-source projects (details published
> upon official maintainer disclosure)


---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=leyth966&show_icons=true&theme=tokyonight&hide_border=true">
</p>

---

## 🐍 Contributions Snake

![snake](https://github.com/Platane/snk/raw/output/github-contribution-grid-snake.svg)

---

## 📫 Contact

* Available for penetration testing & security research

---

> "I don’t hunt for bugs — I hunt for impact."
