<p align="center">
<a href="https://github.com/akizen14"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=4C8EDA&center=true&vCenter=true&width=650&lines=Hi%2C+I'm+Chaitanya;Security-focused+Product+Builder;AI+Security+%26+Responsible+AI;Building+Red-Prompt" alt="Typing SVG"></a>
</p>

<p align="center">
<a href="https://www.linkedin.com/in/chaitanya-sawant14"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
<a href="mailto:chaitanyassawant07@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
<a href="https://red-prompt.org/"><img src="https://img.shields.io/badge/red--prompt.org-111111?style=for-the-badge" alt="red-prompt"></a>
</p>

## About Me

I build security products end to end, from the detection logic underneath to the dashboard someone actually uses. Most of my work sits where security meets AI: testing LLM applications, catching ransomware on endpoints, and spotting phishing and AI-generated media.

- **Now:** building [Red-Prompt](https://red-prompt.org/), an early-stage startup for red-teaming LLM applications
- **Also working on:** a multi-agent pentesting framework where LLM agents do the legwork and humans approve every stage
- **How I build:** deterministic logic where a result has to be right, AI where a problem needs judgment, and tests before trust
- **How I ship:** AI workflows with Claude Code, Gemini CLI, and Codex to clear the mundane work and move faster

## Selected Work

### [red-prompt](https://red-prompt.org/)
*Early-stage startup*

Automates LLM vulnerability assessments across **41 probe categories** covering prompt injection, jailbreaks, and data leakage. Findings export as AVID-compliant reports and land in a severity-ranked dashboard for triage. Supabase handles auth, user data, and activity history, and the app runs on Azure.

`FastAPI` `Next.js` `Supabase` `Azure`

### [RDRS: Ransomware Detection & Response](https://github.com/Naks-bro/RDRS---Ransomware-Detection)

Watches Windows endpoints in real time across **7 telemetry sources**, including kernel file I/O, crypto-API loads, and shadow-copy deletion attempts. No single signal can trigger a response; action fires only when corroborating signals stack up within a decay window, backed by entropy analysis and honeytoken tripwires. Validated across **6 attack simulations**.

`Windows` `ETW` `Detection Engineering`

### [Aegis: AI Video Forensics](https://github.com/Tweethashtag2244/Aegis-MumHack2025)
*Mumbai Hacks finalist, team of four*

Scores whether a video is real or AI-generated. Instead of trusting one detector, it fuses frame-level forensics, Gemini audio/visual coherence, provenance, and robustness signals into a weighted verdict with override rules.

`Next.js` `Flask` `TensorFlow` `OpenCV` `Gemini`

### Phishing Detection System
*OffSecDiary, project lead*

A deterministic four-module pipeline (signature, homograph, content similarity, clickjacking) on live threat-intel feeds and a SQLite phishing database, reaching **96% detection on zero-day phishing links**. Every threshold change runs against a **127-test regression suite**, and a Chrome extension scans links as you browse. I also led the platform's security audit and grouped the fixes into remediation batches.

`SQLite` `Threat-Intel APIs` `Chrome Extension`

## Tech Stack

**AI & LLMs**<br>
<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white" alt="TensorFlow">
<img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white" alt="OpenCV">
<img src="https://img.shields.io/badge/Gemini-8E75B2?style=flat&logo=googlegemini&logoColor=white" alt="Gemini">
<img src="https://img.shields.io/badge/PyRIT-333333?style=flat" alt="PyRIT">
<img src="https://img.shields.io/badge/Claude_Code-D97757?style=flat&logo=claude&logoColor=white" alt="Claude Code">
<img src="https://img.shields.io/badge/Multi--Agent_Systems-444444?style=flat" alt="Multi-Agent Systems">

**Languages & Data**<br>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" alt="Python">
<img src="https://img.shields.io/badge/C%2FC%2B%2B-00599C?style=flat&logo=cplusplus&logoColor=white" alt="C/C++">
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black" alt="JavaScript">
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white" alt="PostgreSQL">
<img src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat&logo=supabase&logoColor=white" alt="Supabase">
<img src="https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white" alt="SQLite">

**Web & Infra**<br>
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white" alt="FastAPI">
<img src="https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white" alt="Flask">
<img src="https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white" alt="Next.js">
<img src="https://img.shields.io/badge/Firebase-FFCA28?style=flat&logo=firebase&logoColor=black" alt="Firebase">
<img src="https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white" alt="Azure">
<img src="https://img.shields.io/badge/Google_Cloud-4285F4?style=flat&logo=googlecloud&logoColor=white" alt="Google Cloud">
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white" alt="Docker">
<img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white" alt="Git">
<img src="https://img.shields.io/badge/Jenkins-D24939?style=flat&logo=jenkins&logoColor=white" alt="Jenkins">
<img src="https://img.shields.io/badge/Trivy-1904DA?style=flat&logo=aqua&logoColor=white" alt="Trivy">

**Security**<br>
<img src="https://img.shields.io/badge/Burp_Suite-FF6633?style=flat&logo=burpsuite&logoColor=white" alt="Burp Suite">
<img src="https://img.shields.io/badge/Wireshark-1679A7?style=flat&logo=wireshark&logoColor=white" alt="Wireshark">
<img src="https://img.shields.io/badge/Nmap-4682B4?style=flat" alt="Nmap">
<img src="https://img.shields.io/badge/Metasploit-2596CD?style=flat" alt="Metasploit">
<img src="https://img.shields.io/badge/Splunk-000000?style=flat&logo=splunk&logoColor=white" alt="Splunk">
<img src="https://img.shields.io/badge/MITRE_ATT%26CK-C8102E?style=flat" alt="MITRE ATT&CK">

---

<p align="center">Open to Software Engineering, AI Security, and AI Red Team roles. If you're working on something in AI security, I'd like to hear about it.</p>
