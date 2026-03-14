# Red Specter Security Research

Operational security for autonomous AI agents. Runtime enforcement, offensive testing, and enterprise SIEM integration — built from scratch in pure Python.

**While others announce, we ship.**

---

## The Platform: AI Shield

101-module runtime enforcement platform. Enforces AI behaviour at inference time, per decision, with cryptographic evidence attached.

| Coverage | Score |
|----------|-------|
| OWASP LLM Top 10 | 10/10 |
| OWASP Agentic Top 10 | 10/10 |
| EU AI Act | 7/7 articles |
| UK AISI | 13/13 principles |
| MITRE ATLAS | 100% |

**13,955 tests passing. Zero failures.**

**15 vertical products, 648 modules total:**
Finance, Health, Legal, Insure, Forensics, CX, SOC, Dev, Gov, NHS Digital, Energy, Pharma, Identity, Sovereign, Quantum.

All vertical repos private. All deployed on production infrastructure.

[red-specter.co.uk/products](https://red-specter.co.uk/products/)

---

## The Offensive Pipeline

Six stages from LLM testing to SIEM correlation. No competitor has all six. One company. Full stack.

| Stage | Tool | What It Does | Tests |
|-------|------|-------------|-------|
| 1 | **FORGE** | Test the LLM before you build with it | 9,260 |
| 2 | **ARSENAL** | Test the AI agent during development | 2,563 |
| 3 | **PHANTOM** | Coordinated AI agent assault (29 vectors) | 288 |
| 4 | **POLTERGEIST** | Coordinated web application siege | 1,189 |
| — | **GLASS** | Intercepting proxy for AI agents (7 protocols) | 850 |
| — | **NEMESIS** | Autonomous adversarial reasoning pentester | 667 |
| 5 | **AI Shield** | Runtime defence in production | 13,955 |
| 6 | **redspecter-siem** | Findings into Splunk, Sentinel, QRadar | 90 |

### FORGE — Automated LLM Security Testing

10 tools, 1,590 static payloads, 5,340+ with mutations. Ed25519 signed, RFC 3161 timestamped reports. OWASP LLM 10/10. Test the model before you build an agent around it.

[red-specter.co.uk/forge](https://red-specter.co.uk/forge/) · [Documentation](https://red-specter.co.uk/forge/docs/)

### ARSENAL — AI Agent Security Testing

The world's first AI agent security testing framework. 14 tools covering the full AI agent attack surface — swarm scanning, MCP protocol abuse, memory scanning, RAG scanning, C2 assessment, supply chain, and more.

[red-specter.co.uk/arsenal](https://red-specter.co.uk/arsenal/) · [Documentation](https://red-specter.co.uk/arsenal/docs/)

### PHANTOM — Coordinated AI Agent Assault

5 specialised agents, 29 attack vectors, 10 named campaigns. Tests emergent vulnerabilities that only appear under coordinated multi-agent pressure.

[red-specter.co.uk/phantom](https://red-specter.co.uk/phantom/) · [Documentation](https://red-specter.co.uk/phantom/docs/)

### POLTERGEIST — Web Application Penetration Testing Swarm

10 autonomous attack agents. 55 attack vectors, 532 base payloads, 17 mutation engine mutators, 10 named campaigns. Triple-mapped: OWASP Web Top 10 + OWASP API Top 10 + CWE. CVSS 3.1 scored.

[red-specter.co.uk/poltergeist](https://red-specter.co.uk/poltergeist/) · [Documentation](https://red-specter.co.uk/poltergeist/docs/)

### GLASS — Intercepting Proxy for AI Agents

Burp Suite for AI agents. Man-in-the-middle proxy that captures, decodes, inspects, modifies, and replays all AI agent traffic in real time. 7 protocol parsers (OpenAI, Anthropic, Gemini, MCP, LangChain, A2A, Generic HTTP). Passive scanner with credential leak, PII, and prompt injection detection. Session recording with FORGE/ARSENAL export. Not a stage in the pipeline — the lens through which every stage can be focused.

[red-specter.co.uk/glass](https://red-specter.co.uk/glass/) · [Documentation](https://red-specter.co.uk/glass/docs/)

### NEMESIS — Autonomous Adversarial Reasoning Pentester

The first autonomous AI pentester that thinks, adapts, and never stops. Uses an LLM reasoning engine to plan, execute, observe, adapt, and escalate attacks through a seven-phase engagement loop. Orchestrates all five weapons (GLASS, FORGE, ARSENAL, PHANTOM, POLTERGEIST) autonomously — selecting, sequencing, and chaining them based on what it discovers. Local mode (Ollama, air-gapped) or cloud mode (GPT-4o, Claude). The inescapable adversary.

[red-specter.co.uk/nemesis](https://red-specter.co.uk/nemesis/) · [Documentation](https://red-specter.co.uk/nemesis/docs/)

### Packaging

All four offensive tools ship with identical distro support:

| Target | Format |
|--------|--------|
| Kali Linux | .deb package |
| Parrot OS | .deb package |
| BlackArch | PKGBUILD |
| REMnux | .deb package |
| Tsurugi | .deb package |
| PyPI | `pip install` |

### redspecter-siem — Shared SIEM Connector Library

Splunk HEC/CIM, Microsoft Sentinel CEF + Log Analytics, IBM QRadar LEEF 2.0. Wired into all five tools via `--export-siem` flag.

### UNLEASHED

Five of the six offensive tools have a second mode. In standard mode, they detect and report vulnerabilities. In UNLEASHED mode, they exploit them — executing real destructive actions against pre-authorised targets to prove impact, not just flag risk. Locked behind Ed25519 public-key cryptography. Dual-gate safety: Gate 1 logs actions without executing, Gate 2 requires explicit confirmation to go live. The private key exists on one machine. One operator. Founder's machine only.

GLASS does not have an UNLEASHED mode — it is a passive/active proxy by design.

---

## By the Numbers

| Metric | Value |
|--------|-------|
| Ecosystem tests | 28,862 |
| AI Shield modules | 101 |
| Vertical products | 15 |
| Vertical modules | 648 |
| Offensive tools | 6 |
| SIEM integrations | 3 |
| Failures | 0 |

---

## Pure Engineering

Zero subprocess calls. Zero external tool dependencies. No sqlmap, no nmap, no nikto, no wrappers. Every payload, every mutation engine, every detection algorithm built from scratch in pure Python. The only external dependency across all tools is httpx.

---

## Responsible Use

All offensive tools are designed for authorised security testing, research, and educational purposes only. Written permission from the system owner is required before running any tool against a target. Unauthorised use may violate the Computer Misuse Act 1990 (UK), the Computer Fraud and Abuse Act (US), or equivalent legislation in your jurisdiction.

---

## Contact

**richard@red-specter.co.uk**

[red-specter.co.uk](https://red-specter.co.uk)

---

<p align="center">
  <sub>Red Specter Security Research · United Kingdom · Richard Barron, Founder</sub>
</p>
