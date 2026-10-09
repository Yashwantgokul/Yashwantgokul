<!-- ═══════════════════════════  HEADER  ═══════════════════════════ -->
<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,45:0b3d2e,100:00ff9c&height=210&section=header&text=Yashwant%20Gokul%20P&fontColor=e6edf3&fontSize=52&fontAlignY=36&desc=Offensive%20Security%20%C2%B7%20Secure%20Coding%20%C2%B7%20CTF%20Challenge%20Author&descAlignY=58&descSize=17&animation=fadeIn" alt="Yashwant Gokul P" />

<a href="https://github.com/Yashwantgokul">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=20&duration=2800&pause=900&color=00FF9C&center=true&vCenter=true&width=720&lines=Break+it+%E2%86%92+understand+it+%E2%86%92+build+it+safer.;B.Tech+CSE+(Cyber+Security)+%40+VIT+Chennai;Sandboxes%2C+isolation+and+tamper-evident+systems" alt="Typing animation" />
</a>

<br/>

<a href="mailto:yashwantgokul@gmail.com"><img src="https://img.shields.io/badge/Email-0d1117?style=for-the-badge&logo=gmail&logoColor=00ff9c" alt="Email" /></a>
<a href="https://www.linkedin.com/in/YOUR-LINKEDIN-HANDLE"><img src="https://img.shields.io/badge/LinkedIn-0d1117?style=for-the-badge&logo=linkedin&logoColor=00ff9c" alt="LinkedIn" /></a>
<a href="https://tryhackme.com/p/YOUR-THM-USERNAME"><img src="https://img.shields.io/badge/TryHackMe-Top%2015%25-0d1117?style=for-the-badge&logo=tryhackme&logoColor=00ff9c" alt="TryHackMe" /></a>
<img src="https://komarev.com/ghpvc/?username=Yashwantgokul&style=for-the-badge&color=0b3d2e&label=PROFILE+VIEWS" alt="Profile views" />

</div>

<br/>

## `$ whoami`

```yaml
name      : Yashwant Gokul P
role      : Cybersecurity-focused CS undergrad
studying  : B.Tech CSE (Cyber Security) · VIT Chennai · Class of 2029
based_in  : Chennai, India
focus     :
  - Web exploitation & vulnerability assessment
  - CTF challenge design (web, crypto, privilege escalation)
  - Secure-by-default backends, sandboxing and container isolation
currently :
  - Building isolated lab environments for hands-on exploit training
mindset   : "Every feature is an attack surface until proven otherwise."
```

<br/>

## What I work on

<table>
<tr>
<td width="33%" valign="top">

### Offensive
Finding what breaks before someone else does.

- Web app testing: IDOR, JWT tampering, auth bypass, business-logic flaws
- Linux privilege escalation, SSTI, RCE
- Recon and enumeration automation in Python

</td>
<td width="33%" valign="top">

### Defensive
Watching what code actually does at runtime.

- Dynamic analysis with eBPF and filesystem monitoring
- CVE scanning and patch workflows
- Tamper-evident logging and integrity hashing

</td>
<td width="33%" valign="top">

### Secure coding
Designing so the safe path is the default one.

- Per-user isolation with containers
- OTP and multi-step authentication
- Input validation before any privileged action

</td>
</tr>
</table>

<br/>

## 🚀 Featured projects

<table>
<tr>
<td width="50%" valign="top">

### [OSDA · SandboxSentinel](https://github.com/Yashwantgokul/osda)
Dynamic analysis sandbox for untrusted Python and shell scripts. Detonates a sample inside an isolated Docker container, traces process `exec` / `fork` / `exit` with **eBPF**, watches the filesystem, then rebuilds the process tree and issues a `SAFE` / `SUSPICIOUS` / `MALICIOUS` verdict.

**Security angle:** behavioural malware analysis, kernel-level tracing, containment.

![Python](https://img.shields.io/badge/Python-0d1117?style=flat-square&logo=python&logoColor=00ff9c)
![eBPF](https://img.shields.io/badge/eBPF%20·%20BCC-0d1117?style=flat-square&logo=ebpf&logoColor=00ff9c)
![Docker](https://img.shields.io/badge/Docker-0d1117?style=flat-square&logo=docker&logoColor=00ff9c)
![Linux](https://img.shields.io/badge/Linux-0d1117?style=flat-square&logo=linux&logoColor=00ff9c)

</td>
<td width="50%" valign="top">

### LoopBack
Dynamic CTF hosting platform. Every player gets their own containerised environment with **dynamically generated flags**, so flags cannot be shared and real exploits (privesc, SSTI, RCE) run safely. Ships a browser-based Kali terminal via `ttyd` with tools pre-installed.

**Security angle:** tenant isolation, challenge integrity, safe exploit execution.

![Node.js](https://img.shields.io/badge/Node.js-0d1117?style=flat-square&logo=nodedotjs&logoColor=00ff9c)
![Docker](https://img.shields.io/badge/Docker-0d1117?style=flat-square&logo=docker&logoColor=00ff9c)
![Kali](https://img.shields.io/badge/Kali%20·%20ttyd-0d1117?style=flat-square&logo=kalilinux&logoColor=00ff9c)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [VulnShield](https://github.com/Yashwantgokul/VulnShield)
AI security assistant driven from Telegram. Scans installed software for known **CVEs**, proposes patches and applies them only after confirmation, then produces a PDF security report. One agent validates every command before a second agent is allowed to act on it.

**Security angle:** vulnerability management, human-in-the-loop remediation, command validation.

![n8n](https://img.shields.io/badge/n8n-0d1117?style=flat-square&logo=n8n&logoColor=00ff9c)
![Python](https://img.shields.io/badge/Flask-0d1117?style=flat-square&logo=flask&logoColor=00ff9c)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0d1117?style=flat-square&logo=postgresql&logoColor=00ff9c)
![Telegram](https://img.shields.io/badge/Telegram%20Bot-0d1117?style=flat-square&logo=telegram&logoColor=00ff9c)

</td>
<td width="50%" valign="top">

### [SmartG](https://github.com/Yashwantgokul/SmartG)
Real-time IoT gas-leak safety system. An ESP32 streams sensor data to a Flask backend that tracks the full incident lifecycle, fires Telegram alerts and Twilio emergency calls, and closes each incident with a PDF report sealed by a **SHA-256 hash**.

**Security angle:** forensic reporting, data integrity, tamper-evident logs.

![ESP32](https://img.shields.io/badge/ESP32-0d1117?style=flat-square&logo=espressif&logoColor=00ff9c)
![Flask](https://img.shields.io/badge/Flask-0d1117?style=flat-square&logo=flask&logoColor=00ff9c)
![MySQL](https://img.shields.io/badge/MySQL-0d1117?style=flat-square&logo=mysql&logoColor=00ff9c)
![C++](https://img.shields.io/badge/Arduino%20C++-0d1117?style=flat-square&logo=cplusplus&logoColor=00ff9c)

</td>
</tr>
<tr>
<td width="50%" valign="top">

###  [Enigma Password Manager](https://github.com/Yashwantgokul/enigmapwdmanager)
Credential vault with email **OTP authentication**, a master password, password generation, checks against a common-password list, and a timed account-recovery window.

**Security angle:** authentication flows, credential hygiene, abuse protection.

![Python](https://img.shields.io/badge/Python-0d1117?style=flat-square&logo=python&logoColor=00ff9c)
![MySQL](https://img.shields.io/badge/MySQL-0d1117?style=flat-square&logo=mysql&logoColor=00ff9c)
![SMTP](https://img.shields.io/badge/SMTP%20OTP-0d1117?style=flat-square&logo=maildotru&logoColor=00ff9c)

</td>
<td width="50%" valign="top">

### 📝 [CTF write-up · Reconfiguration Terminal](https://github.com/Yashwantgokul/reconfigration_terminal-1)
Walkthrough of a CipherStrike web challenge: `robots.txt` leaks a hidden path, predictable resource IDs each return one character, and a short Python script walks them to rebuild the flag.

**Security angle:** information disclosure, enumeration, exploit automation.

![Python](https://img.shields.io/badge/Python-0d1117?style=flat-square&logo=python&logoColor=00ff9c)
![Web](https://img.shields.io/badge/Web%20Exploitation-0d1117?style=flat-square&logo=owasp&logoColor=00ff9c)

</td>
</tr>
</table>

<details>
<summary><b>More builds</b></summary>
<br/>

| Project | What it is | Stack |
|---|---|---|
| **CiviTrack** | AI-powered civic issue reporting with geolocation, prioritisation and a RAG pipeline for decision support | RAG · Pinecone |
| [**Crypto App Pro**](https://github.com/Yashwantgokul/cryptotaxpro) | Privacy-first crypto tax calculator built at CodeZilla '25 — FIFO/LIFO gains and PDF reports | TypeScript · Vite · Tailwind |
| [**multimsg**](https://github.com/Yashwantgokul/multimsg) | Unified inbox bringing chats from multiple messaging platforms into one place | Node.js · Prisma · Docker Compose |

</details>

<br/>

## Arsenal

<div align="center">

**Security tooling**

<img src="https://img.shields.io/badge/Burp%20Suite-0d1117?style=for-the-badge&logo=burpsuite&logoColor=00ff9c" alt="Burp Suite" />
<img src="https://img.shields.io/badge/Nmap-0d1117?style=for-the-badge&logoColor=00ff9c" alt="Nmap" />
<img src="https://img.shields.io/badge/Wireshark-0d1117?style=for-the-badge&logo=wireshark&logoColor=00ff9c" alt="Wireshark" />
<img src="https://img.shields.io/badge/Metasploit-0d1117?style=for-the-badge&logo=metasploit&logoColor=00ff9c" alt="Metasploit" />
<img src="https://img.shields.io/badge/sqlmap-0d1117?style=for-the-badge&logoColor=00ff9c" alt="sqlmap" />
<img src="https://img.shields.io/badge/John%20the%20Ripper-0d1117?style=for-the-badge&logoColor=00ff9c" alt="John the Ripper" />
<img src="https://img.shields.io/badge/Gobuster-0d1117?style=for-the-badge&logoColor=00ff9c" alt="Gobuster" />
<img src="https://img.shields.io/badge/Hydra-0d1117?style=for-the-badge&logoColor=00ff9c" alt="Hydra" />
<img src="https://img.shields.io/badge/Kali%20Linux-0d1117?style=for-the-badge&logo=kalilinux&logoColor=00ff9c" alt="Kali Linux" />

**Languages**

<img src="https://img.shields.io/badge/Python-0d1117?style=for-the-badge&logo=python&logoColor=00ff9c" alt="Python" />
<img src="https://img.shields.io/badge/C-0d1117?style=for-the-badge&logo=c&logoColor=00ff9c" alt="C" />
<img src="https://img.shields.io/badge/C++-0d1117?style=for-the-badge&logo=cplusplus&logoColor=00ff9c" alt="C++" />
<img src="https://img.shields.io/badge/JavaScript-0d1117?style=for-the-badge&logo=javascript&logoColor=00ff9c" alt="JavaScript" />
<img src="https://img.shields.io/badge/R-0d1117?style=for-the-badge&logo=r&logoColor=00ff9c" alt="R" />
<img src="https://img.shields.io/badge/HTML-0d1117?style=for-the-badge&logo=html5&logoColor=00ff9c" alt="HTML" />
<img src="https://img.shields.io/badge/CSS-0d1117?style=for-the-badge&logo=css&logoColor=00ff9c" alt="CSS" />

**Platforms & dev tools**

<img src="https://img.shields.io/badge/Docker-0d1117?style=for-the-badge&logo=docker&logoColor=00ff9c" alt="Docker" />
<img src="https://img.shields.io/badge/Linux-0d1117?style=for-the-badge&logo=linux&logoColor=00ff9c" alt="Linux" />
<img src="https://img.shields.io/badge/Git-0d1117?style=for-the-badge&logo=git&logoColor=00ff9c" alt="Git" />
<img src="https://img.shields.io/badge/MySQL-0d1117?style=for-the-badge&logo=mysql&logoColor=00ff9c" alt="MySQL" />
<img src="https://img.shields.io/badge/Postman-0d1117?style=for-the-badge&logo=postman&logoColor=00ff9c" alt="Postman" />
<img src="https://img.shields.io/badge/n8n-0d1117?style=for-the-badge&logo=n8n&logoColor=00ff9c" alt="n8n" />
<img src="https://img.shields.io/badge/Flask-0d1117?style=for-the-badge&logo=flask&logoColor=00ff9c" alt="Flask" />
<img src="https://img.shields.io/badge/Node.js-0d1117?style=for-the-badge&logo=nodedotjs&logoColor=00ff9c" alt="Node.js" />

</div>

<br/>

## In the field

**Technical Lead · V-Vortex** &nbsp;<sub>Nov 2025 – Jan 2026</sub>
- Led technical and security operations for a multi-domain hackathon with **75+ teams and 350+ participants**.
- Ran the security assessment of the event platform: reported **privilege escalation**, **API data exposure** and a **business-logic flaw** allowing unverified data storage, then helped with remediation.
- Evaluated JWT manipulation, IDOR and login-bypass risk before launch.


<br/>

## Scoreboard

| | |
|---|---|
| 🚩 | **Finalist** — Yukthi 2.0 Cybersecurity CTF, conducted by Tamil Nadu Police |
| 🚩 | **Finalist** — Shaastra CTF, IIT Madras |
| 🛡️ | **Top 15** — Cybersecurity domain, DataQuest 2.0 Hackathon (VIT Chennai) |
| 🧠 | **Top 212 of 800+ teams** — Internal SIH round, one of only 13 first-year teams |
| 💻 | **TryHackMe Top 15% globally** — 62+ rooms, 11 badges |

<br/>

## GitHub activity

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Yashwantgokul&show_icons=true&hide_border=true&bg_color=0d1117&title_color=00ff9c&icon_color=00ff9c&text_color=c9d1d9&rank_icon=github" alt="GitHub stats" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Yashwantgokul&layout=compact&hide_border=true&bg_color=0d1117&title_color=00ff9c&text_color=c9d1d9" alt="Top languages" />

<img src="https://streak-stats.demolab.com?user=Yashwantgokul&hide_border=true&background=0d1117&ring=00ff9c&fire=00ff9c&currStreakLabel=00ff9c&sideLabels=c9d1d9&currStreakNum=e6edf3&sideNums=e6edf3&dates=8b949e" alt="GitHub streak" />

</div>

<br/>

## Let's talk

Open to **security internships**, **CTF collaborations** and **challenge-authoring** work.
If you want something of yours tested, or a challenge built, reach out at **[yashwantgokul@gmail.com](mailto:yashwantgokul@gmail.com)**.

<div align="center">

<sub>All security work shown here was done in authorised environments: CTFs, labs, and systems I was asked to test.</sub>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:00ff9c,55:0b3d2e,100:0d1117&height=110&section=footer" alt="" />

</div>
