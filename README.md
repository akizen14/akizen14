<a href="https://github.com/akizen14"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=4C8EDA&center=true&vCenter=true&width=650&lines=Security-focused+Product+Builder;AI+Products+%26+Responsible+AI;Building+security+tools+end+to+end" alt="Typing SVG"></a>

<a href="https://www.linkedin.com/in/chaitanya-sawant14"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
<a href="mailto:chaitanyassawant07@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
<a href="https://red-prompt.org/"><img src="https://img.shields.io/badge/red--prompt.org-111111?style=for-the-badge" alt="red-prompt"></a>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI">
<img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js">
<img src="https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" alt="Azure">

## About Me

I'm Chaitanya, and I build security products end to end, from detection logic to the dashboard someone actually uses, and I care about the decisions behind them as much as the code.

- Currently building **[Red-Prompt](https://red-prompt.org/)**, an early-stage startup for testing LLM applications against prompt injection, jailbreaks, and data leakage
- I like deterministic logic where a result has to be right, and AI where a problem needs judgment
- I use AI workflows (Claude Code, Gemini CLI, Codex) to take the mundane work off my plate and ship faster

## By the Numbers

| Zero-day Phishing Detection | Regression Tests | LLM Probe Categories | Endpoint Telemetry Sources |
|:---:|:---:|:---:|:---:|
| **96%** | **127** | **41** | **7** |

## Selected Work

### [`red-prompt`](https://red-prompt.org/) *(early-stage startup)*

An AI red-teaming platform that automates LLM vulnerability assessments across 41 probe categories, with AVID-compliant reports and a severity-ranked dashboard for triage. Supabase handles authentication, user data, and activity history, and the app runs on Azure.

`FastAPI` `Next.js` `Supabase` `Azure`

---

### [`RDRS`](https://github.com/Naks-bro/RDRS---Ransomware-Detection) *(Ransomware Detection & Response Service)*

Real-time ransomware detection for Windows endpoints that fuses seven telemetry sources, including kernel file I/O, crypto-API loads, and shadow-copy deletion attempts. Designed so no single signal can trigger a response: action fires only when corroborating signals stack up within a decay window, backed by entropy analysis and honeytoken tripwires. Validated across six attack simulations.

`Windows` `ETW` `Detection Engineering`

---

### [`Aegis`](https://github.com/Tweethashtag2244/Aegis-MumHack2025) *(Mumbai Hacks finalist)*

A multi-agent system, built in a team of four, that scores whether a video is real or AI-generated. Rather than trusting any one detector, it fuses frame-level forensics, Gemini audio/visual coherence, provenance, and robustness signals into a weighted verdict with override rules.

`Next.js` `Flask` `TensorFlow` `OpenCV` `Gemini`

---

### `Phishing Detection System` *(OffSecDiary, project lead)*

A deterministic four-module pipeline (signature, homograph, content similarity, clickjacking) on live threat-intel feeds and a SQLite phishing database, reaching 96% detection on zero-day phishing links. Every threshold change runs against a 127-test regression suite, and a companion Chrome extension scans links as the user browses. I also led a security audit of the platform and grouped the fixes into remediation batches.

`SQLite` `Threat-Intel APIs` `Chrome Extension`

---

### `Multi-Agent Pentesting Framework` *(in progress)*

LLM agents for reconnaissance, vulnerability analysis, exploitation, and reporting, with human approval gates between stages. The goal is to speed up human pentesters, not replace them.

`Multi-Agent LLMs`

## Experience

**R&D Intern, OffSecDiary** (2026) · **Cybersecurity Intern, ShadowFox** (2025) · **Cloud Computing Intern, YHills Edutech** (2024)

## Stack

**AI & LLMs:** Multi-agent systems · LLM-powered applications · Prompt engineering · PyRIT · Gemini (Genkit) · TensorFlow · OpenCV

**Languages & Data:** Python · C/C++ · JavaScript · SQL · PostgreSQL (Supabase) · SQLite

**Web & Infra:** FastAPI · Flask · Next.js · Firebase · Azure · GCP · Docker · Git · Jenkins · Trivy

**Security:** Detection engineering · MITRE ATT&CK · Burp Suite · Wireshark · Nmap · Metasploit · Splunk

Open to Software Engineering, AI Security, and AI Red Team roles, and to interesting problems in applied AI security along the way.
