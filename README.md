<p align="center">
  <img src="https://raw.githubusercontent.com/RichardBarron27/red-specter-offensive-framework/main/assets/red-specter-logo.png" alt="Red Specter Logo" width="200">
</p>

# Red Specter — Innovation Beyond Belief 🔥

<p align="center">
  <img alt="tools" src="https://img.shields.io/badge/public%20tools-13-brightgreen">
  <img alt="modules" src="https://img.shields.io/badge/private%20R&D-20+-orange">
  <img alt="ai-shield" src="https://img.shields.io/badge/AI%20Shield-deployment%20ready-blue">
  <img alt="playbooks" src="https://img.shields.io/badge/playbooks-18-purple">
  <img alt="location" src="https://img.shields.io/badge/location-London%2C%20UK-red">
</p>

A collection of defensive and offensive security tools, research projects, and internal R&D maintained by **Red Specter**.  
Built for security teams, incident responders, and authorized researchers.  
**Detect → Block → Contain → Prove.**

---

## 📑 Table of Contents
- [Overview](#-overview)
- [At a Glance](#-at-a-glance)
- [Featured: Red Specter AI Shield](#️-featured-red-specter-ai-shield-deployment-ready)
- [Public Tools](#-public-tools)
- [Private R&D](#-private-rd)
- [Why This Matters Now](#-why-this-matters-now)
- [Usage & Access](#-usage--access)
- [Responsible Use & Legal](#️-responsible-use--legal)
- [Contact & Collaboration](#-contact--collaboration)

---

## 🎯 Overview
Red Specter focuses on practical visibility and response across:
- Botnet activity and early-stage DDoS signals  
- C2-style outbound behaviour and beaconing  
- Sudden service exposure and brute-force patterns  
- AI-era risks: shadow AI usage, prompt injection, data leakage, and model integrity  
- Fast containment and **evidence-first reporting**

This profile README is a high-level inventory with links to each repo.

---

## 📊 At a Glance

| Category | Count | Status |
|----------|-------|--------|
| Public Tools | 13 | Open Source |
| Private R&D Modules | 20+ | Internal |
| Integrated Platform (AI Shield) | 18 modules | Deployment Ready |
| Operational Playbooks | 18 | Production |
| Case Pack Exports | CSOAI-ready | Tamper-Evident |

---

## 🛡️ Featured: Red Specter AI Shield (Deployment Ready)

<p align="center">
  <img alt="status" src="https://img.shields.io/badge/status-deployment%20ready-success">
  <img alt="modules" src="https://img.shields.io/badge/modules-18-brightgreen">
  <img alt="playbooks" src="https://img.shields.io/badge/playbooks-18-blue">
  <img alt="telemetry" src="https://img.shields.io/badge/telemetry-RS%20Event%20v1-1f6feb">
  <img alt="casepacks" src="https://img.shields.io/badge/case%20packs-tamper--evident-8a2be2">
  <img alt="export" src="https://img.shields.io/badge/export-CSOAI--ready-0a7">
</p>

**A fully integrated, production-ready platform for AI security governance and incident response.**

Red Specter AI Shield unifies **18 security modules**—from prevention to forensic response—into a single deployable suite.  
It is functional, integrated, and tested end-to-end for controlled pilot deployments.

### 🎯 Core Deliverables

✅ **Integrated Platform:** 18 modules on a unified event schema (**RS Event v1**)  
✅ **Forensic Evidence:** Automated, tamper-evident case packaging (timeline + IOCs + hashes)  
✅ **Operational Coverage:** **18 playbooks** mapped to modules + sanity coverage checker  
✅ **CSOAI-ready Export:** Submission summary + export bundle + checksums (Watchdog-style evidence packaging)  
✅ **Local GUI:** 4-button web interface for golden-path workflows (Preflight → Init → Build → Verify)  
✅ **Status:** **Deployment Ready** — available for pilot evaluation (private)

### 🚀 New Capabilities

- **AI Usage Watchdog Baseline + Drift** — baselining + drift scoring + RS Event v1 alert emit + export-ready JSONL
- **Phish Interceptor (Defensive)** — phishing/BEC .eml triage → IOC extraction + evidence pack output
- **Local Web GUI** — Localhost-only Flask interface for non-CLI users

### 🔗 Interested?

**[→ Request Pilot Access](https://www.linkedin.com/in/richard-b-42469439b/)** — Connect on LinkedIn to discuss controlled evaluation

---

## 🔧 Public Tools

### 🌐 Network & Infrastructure Security

- **[Botnet Radar](https://github.com/RichardBarron27/redspecter-botnet-radar)** — Host-level botnet/DDoS early warning and scoring
- **[DDoS Flood Sentinel](https://github.com/RichardBarron27/redspecter-ddos-flood-sentinel)** — UDP flood / carpet detection heuristics and alerts
- **[Port Surge Guardian](https://github.com/RichardBarron27/redspecter-port-surge-guardian)** — Sudden listening-port exposure change alerts
- **[C2 Hunter](https://github.com/RichardBarron27/redspecter-c2-hunter)** — Outbound monitoring for C2-like behaviour
- **[Threat Recon Watcher](https://github.com/RichardBarron27/redspecter-threat-recon-watcher)** — Brute-force / high-volume IP detection from logs

### 🔍 Reconnaissance & Intelligence

- **[Offensive Framework](https://github.com/RichardBarron27/red-specter-offensive-framework)** — Ethical lab toolkit for recon → reporting (authorized testing only)
- **[ScriptMap](https://github.com/RichardBarron27/redspecter-scriptmap)** — Script inventory and supply-chain visibility
- **[Email OSINT](https://github.com/RichardBarron27/redspecter-emailosint)** — Passive domain-based email intelligence

### 🤖 AI Security

- **[AI Breach Monitor](https://github.com/RichardBarron27/redspecter-ai-breach-monitor)** — Detects likely sensitive data leaks in AI prompt logs
- **[AI Endpoint Guard](https://github.com/RichardBarron27/redspecter-ai-endpoint-guard)** — Endpoint visibility into AI tool usage
- **[AI Usage Watchdog](https://github.com/RichardBarron27/redspecter-ai-usage-watchdog)** — Privacy-first Linux telemetry for AI/LLM usage signals
- **[AI Firewall Proxy](https://github.com/RichardBarron27/redspecter-ai-firewall-proxy)** — Policy-enforcing proxy to control and log AI model access

### 📋 Evidence & Response

- **[Evidence Collector](https://github.com/RichardBarron27/redspecter-evidence-collector)** — DFIR/pentest evidence ledger into structured case files

---

## 🔒 Private R&D
*(Internal and restricted. Not for public distribution without authorization.)*

### 🛡️ Prevention & Control

- **Breach Containment Switch** — One-command web containment + evidence snapshot
- **AI ShadowOps Detector** — Covert AI usage detection with evidence logs
- **AI Jailbreak IDS** — Prompt-injection / jailbreak intent detection with logging
- **Agentic Action Gatekeeper** — Policy enforcement + circuit breaker for agent actions (framework-agnostic gateway with auditable decisions)
- **Red Specter Scrambler** — Reverse-proxy chokepoint + tripwire scoring to disrupt agentic/automated intrusion workflows (traps, RS Event v1 alerts, evidence packs)

### 🔍 Detection & Monitoring

- **Cognitive Drift Sentinel** — Model behaviour drift monitoring over time
- **Ransomware Canary Sentinel** — Pre-encryption mass-change alerts without encryption
- **LLM Memory Forensics Kit** — Scans AI memory/log dumps for risky indicators + tamper-evident reports
- **Log Anomaly Sentinel** — Rare command and log pattern detection
- **Beacon Detector** — Timed C2 beaconing detection
- **Companion Sentinel** — Manipulation/dependency pattern detection in AI companion chats
- **Botnet Radar Pro** — Enterprise-tier botnet scoring and enrichment
- **Kernel Trust Sentinel** — Kernel trust posture + module/tracing cross-checks (rootkit-deception indicators) → RS Event v1 evidence
- **PoisonWatch** — Defensive poisoning/backdoor scanner for datasets & RAG corpora (prompt-injection + obfuscation heuristics) → RS Event v1
- **Phish Interceptor (Defensive)** — .eml phishing/BEC triage → IOCs + RS Event v1 + tamper-evident case pack

### ⚡ Response & Forensics

- **AI Decision Provenance** — Cryptographic decision logging for AI accountability
- **Takedown Dossier Generator** — Converts telemetry into evidence-ready takedown packs (IOCs, timeline, templates, tamper-evident hashes)
- **Deepfake Verification Guard** — Liveness + out-of-band verification packs for voice/video fraud (includes Ticket/QR Verification Pack)

### 🧪 Research & Innovation

- **Red Defender** — Autonomous multi-agent defensive AI prototype
- **Red Specter Lab** — Internal lab scripts, SOPs, and tooling backbone

---

## 🎯 Why This Matters Now

The threat market is actively selling "malicious AI" packages and automation aimed at **phishing, BEC, and social engineering**.

Red Specter's stance is simple:
1. **Detect early** — Spot threats before they cause damage
2. **Block where you can** — Prevent unauthorized actions at policy chokepoints
3. **Contain fast** — Rapid response with one-command containment
4. **Prove everything** — Evidence-first: hashes, timelines, tamper-evident case packs

That's the gap AI Shield is built to close.

### 🔴 Current Threat Landscape

- **AI-powered phishing** reaching unprecedented sophistication
- **Shadow AI usage** creating compliance and data leakage risks
- **Prompt injection** attacks bypassing traditional security controls
- **Model poisoning** targeting RAG systems and fine-tuned models
- **Deepfake fraud** in voice/video authentication

**AI Shield addresses these threats with integrated prevention, detection, and forensic response.**

---

## 🚀 Usage & Access

### Public Tools
- Follow each repo's **README**, licensing, and usage notes
- Open source and available for authorized security testing
- Contributions welcome via issues and pull requests

### Private R&D
- Restricted to internal staff and vetted partners
- **Do not attempt to run or distribute without approval**
- Contact for pilot evaluation or licensing inquiries

### AI Shield Pilot Program
- **Status:** Private pilot - limited availability
- **Requirements:** Controlled evaluation environment, written agreement
- **Contact:** See [Contact & Collaboration](#-contact--collaboration) section below

---

## ⚖️ Responsible Use & Legal

**Important Notice:**

Some tooling and research can be misused. You **must**:

✅ Follow all applicable laws and regulations  
✅ Obtain written authorization for offensive testing  
✅ Follow employer/client policies and procedures  
✅ Get explicit permission before testing systems you do not own  
✅ Use tools only for legitimate security research and authorized assessments  

**Red Specter tools are provided for:**
- Authorized security testing and research
- Incident response and forensic investigation
- Defense capability development
- Educational purposes in controlled environments

**Not for:**
- Unauthorized access or testing
- Malicious purposes or illegal activities
- Violation of computer fraud and abuse laws
- Bypassing security controls without permission

By using these tools, you agree to use them responsibly and legally.

---

## 📬 Contact & Collaboration

**Interested in:**
- 🛡️ AI Shield pilot deployment?
- 🔬 Security research collaboration?
- 🔧 Tool evaluation or licensing?
- 💼 Enterprise security consulting?

### Connect

- **LinkedIn:** [Richard Barron](https://www.linkedin.com/in/richard-b-42469439b/)
- **Email:** [Contact via LinkedIn](https://www.linkedin.com/in/richard-b-42469439b/)
- **GitHub:** [@RichardBarron27](https://github.com/RichardBarron27)
- **Location:** London, UK 🇬🇧

### Contributing to Public Tools

**We welcome contributions!**

- 🐛 **Bug Reports:** Open an issue with reproduction steps
- 💡 **Feature Requests:** Describe your use case and proposal
- 🔧 **Pull Requests:** Fork, branch, PR with tests + docs
- 📖 **Documentation:** Help improve guides and examples

**Contribution Guidelines:**
1. Check existing issues before opening new ones
2. Follow the code style of the existing project
3. Include tests for new functionality
4. Update documentation as needed
5. Keep PRs focused on a single feature/fix

---

<p align="center">
  <img src="https://img.shields.io/badge/Built%20with-Python%20%7C%20Bash%20%7C%20Go-blue">
  <img src="https://img.shields.io/badge/Focus-AI%20Security%20%7C%20Incident%20Response-orange">
  <img src="https://img.shields.io/badge/Status-Active%20Development-success">
</p>

<p align="center">
  <sub>Built by Red Specter Security Research | London, UK | 2024-2026</sub>
</p>

<p align="center">
  <sub>⚡ Innovation Beyond Belief 🔥</sub>
</p>
