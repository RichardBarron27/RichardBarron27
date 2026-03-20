# Red Specter Security Research

AI agent security tooling. Offensive testing, runtime defence, agent discovery, and SIEM integration. Pure Python, no wrappers.

**22 offensive tools. 101 defensive modules. 15 industry verticals. 47,093 tests. Two unified frameworks.**

*Last updated: 20 March 2026*

---

## Red Specter Red Team Offensive Framework

**22 tools. One install. One GUI. Every attack surface covered.**

Complete offensive security platform — OSINT through AI model corruption to guardrail exploitation. Unified installer, SPECTER COMMAND GUI in the browser, packaged for every Linux distro. `red-specter launch` and you're operational.

| # | Tool | What It Does | Tests |
|---|------|-------------|-------|
| 1 | **FORGE** | LLM red team — injection, jailbreak, extraction, drift, boundary | 9,298 |
| 2 | **ARSENAL** | AI agent attacks — 14 tools, MCP, RAG, memory, C2, honeypots | 2,539 |
| 3 | **PHANTOM** | Coordinated swarm assault — 5 agents, 19 vectors | 288 |
| 4 | **POLTERGEIST** | Web app siege — 10 agents, 55 vectors, signed reports | 1,189 |
| 5 | **GLASS** | Intercepting proxy for AI agents — Burp Suite for AI | 850 |
| 6 | **NEMESIS** | Adversarial reasoning — 40 entities, 11 weapons, multi-commander | 2,011 |
| 7 | **SPECTER SOCIAL** | Autonomous social engineering — 6 channels, psych profiling | 1,242 |
| 8 | **PHANTOM KILL** | OS & kernel — UEFI, wipers, EDR suppression | 571 |
| 9 | **GOLEM** | Physical layer — robots, drones, SCADA, 10 protocols | 973 |
| 10 | **HYDRA** | Supply chain — trust relationships, MCP, marketplace poisoning | 1,039 |
| 11 | **IDRIS** | Discovery — finds every AI agent, sanctioned or shadow | 553 |
| 12 | **SCREAMER** | Display disruption — corrupts operator dashboards | 395 |
| 13 | **WRAITH** | Infrastructure pentest — pure Python, zero wrappers | 889 |
| 14 | **REAPER** | Exploit & post-exploitation — 9-phase kill chain, C2, implants | 5,267 |
| 15 | **GHOUL** | Password cracking — dictionary, brute, Markov, rainbow | 1,408 |
| 16 | **DOMINION** | Active Directory — Kerberoast, DCSync, BloodHound export | 1,866 |
| 17 | **SHADOWMAP** | OSINT — domain, network, company, people, breach, tech intel | 930 |
| 18 | **BANSHEE** | Browser exploitation — hooks, DOM injection, network pivoting | 986 |
| 19 | **WRAITH MIND** | AI model internal corruption — KV cache poisoning | 158 |
| 20 | **KRAKEN** | AI-orchestrated DDoS — 55 techniques, adaptive | 62 |
| 21 | **HARBINGER** | Guardrail exploitation — 39 bypass techniques | 71 |
| 22 | **SIREN** | Indirect prompt injection — plants hidden instructions in content | 58 |
| — | **AI Shield** | Runtime defence — 101 modules | 13,955 |
| — | **redspecter-siem** | Splunk, Sentinel, QRadar | 90 |

### Kill Chains

**Infrastructure:** SHADOWMAP &rarr; WRAITH &rarr; REAPER &rarr; GHOUL &rarr; DOMINION

**Browser:** SPECTER SOCIAL delivers link &rarr; BANSHEE hooks browser &rarr; SCREAMER corrupts display

**Host:** PHANTOM KILL suppresses EDR &rarr; wipes data &rarr; persists in firmware

**AI Stack:** FORGE tests the model &rarr; ARSENAL tests the agent &rarr; PHANTOM swarms the deployment &rarr; HYDRA poisons the supply chain &rarr; WRAITH MIND corrupts from inside &rarr; HARBINGER bypasses guardrails &rarr; SIREN plants invisible instructions

**Discovery &rarr; Validate &rarr; Defend:** IDRIS discovers &rarr; NEMESIS validates &rarr; AI Shield defends

### SPECTER COMMAND GUI

Browser-based platform GUI. All 22 tools in the sidebar, each with full command builders, real-time output streaming, project management, chain orchestration, report generation. `red-specter launch` — GUI appears at http://localhost:8443.

Live demo: [command.red-specter.co.uk](https://command.red-specter.co.uk)

### Packaging

- `./install.sh` — unified installer, detects OS
- `red-specter launch` / `red-specter stop` / `red-specter status`
- Docker Compose — `docker compose up -d`
- `.deb` (Debian/Ubuntu/Kali), `.rpm` (RHEL/Fedora/CentOS), Arch PKGBUILD
- Extensible — `red-specter add-tool` to register new tools

---

## AI Shield Defence Framework

**101 modules. 15 industry verticals. 667 vertical modules. Each vertical is a standalone product with its own GUI.**

Runtime AI security that protects AI agents, LLMs, and autonomous systems in production. Pick your industry, one install, one command — the GUI launches branded for that sector with only that sector's modules, compliance frameworks, and dashboard widgets.

```
ai-shield launch --vertical insure      # Insurance — 34 modules, FCA, Solvency II
ai-shield launch --vertical finance      # Financial Services — 41 modules, MiFID II, Basel III
ai-shield launch --vertical nhs          # NHS Digital — 57 modules, DCB0129, DSPT
ai-shield launch --vertical gov          # Government — 50 modules, UK AISI, NCSC CAF
ai-shield launch --vertical energy       # Energy — 56 modules, NERC CIP, IEC 62443
```

### The 15 Verticals

| # | Vertical | Modules | Anchor Module | Key Compliance |
|---|----------|---------|---------------|----------------|
| 1 | **Insure** | 34 | M58 Financial Fraud Detection | FCA, Solvency II |
| 2 | **Finance** | 41 | M57 AI Trading Agent Monitor | MiFID II, Basel III |
| 3 | **Health** | 39 | M61 Clinical AI Decision Monitor | HIPAA, FDA SaMD |
| 4 | **Legal** | 41 | M62 Legal AI Hallucination Guard | SRA, ABA |
| 5 | **Forensics** | 29 | M79 RSSA-2 Detective | ISO 27037, ACPO |
| 6 | **CX** | 39 | M46 Voice Agent Security | FCA Consumer Duty |
| 7 | **SOC** | 44 | M52 STAC Detection | NIST CSF, MITRE ATT&CK |
| 8 | **Dev** | 49 | M75 Coding Agent Runtime Security | SLSA, SSDF |
| 9 | **Gov** | 50 | M37 Compliance Automation | UK AISI, NCSC CAF |
| 10 | **NHS Digital** | 57 | M97 Clinical Safety Case Builder | DCB0129, DSPT |
| 11 | **Energy** | 56 | M98 OT/SCADA AI Runtime Guard | NERC CIP, IEC 62443 |
| 12 | **Pharma** | 53 | M100 Pharmaceutical AI Validation | GAMP 5, 21 CFR Part 11 |
| 13 | **Identity** | 45 | M101 Agent Identity Runtime Control | OWASP NHI Top 10 |
| 14 | **Sovereign** | 56 | M102 Sovereign AI Control Engine | NATO STANAG, Five Eyes |
| 15 | **Quantum** | 49 | Q103 Quantum AI Security Engine | NIST IR 8547, CNSA 2.0 |

Every vertical includes M19 (Agent Runtime Protection) and M99 (Doomsday Protocol). No exceptions.

### Standalone Vertical GUIs

Each vertical is a complete standalone product. Its own frontend, its own backend, its own branding, its own modules. Not a shared GUI with a config flag — 15 separate products.

Live demo: [shield.red-specter.co.uk](https://shield.red-specter.co.uk)

### Compliance Coverage

- **MITRE ATLAS** — 100% (52/52 techniques)
- **OWASP LLM Top 10** — 100% (10/10)
- **OWASP Agentic Top 10** — 100% (10/10)
- **EU AI Act** — 100% (15/15 articles)
- **UK AISI** — 100% (8/8 priorities)
- Plus sector-specific: FCA, MiFID II, DCB0129, NERC CIP, GAMP 5, NATO STANAG, and more

---

## How They Fit Together

SHADOWMAP builds the target profile. WRAITH scans infrastructure. REAPER exploits what WRAITH finds. GHOUL cracks harvested credentials. DOMINION owns Active Directory. BANSHEE hooks browsers. FORGE tests the model. ARSENAL and PHANTOM test the agents. POLTERGEIST handles the web layer. GLASS sits in the middle and watches traffic. NEMESIS runs autonomous engagements with 40 reasoning entities. SPECTER SOCIAL targets the human. PHANTOM KILL and GOLEM cover host and physical layers. HYDRA attacks supply chain trust. WRAITH MIND corrupts models from inside. HARBINGER bypasses guardrails. SIREN plants invisible instructions. KRAKEN tests availability. SCREAMER blinds the operator. IDRIS discovers everything.

**Then AI Shield defends everything above it.**

---

## Numbers

| Metric | Value |
|--------|-------|
| Ecosystem tests | 47,093 |
| Offensive tools | 22 |
| AI Shield modules | 101 |
| Vertical products | 15 |
| Vertical modules | 667 |
| Discovery tools | 1 (IDRIS) |
| SIEM integrations | 3 (Splunk, Sentinel, QRadar) |
| Unified frameworks | 2 (Offensive + Defensive) |
| GUI platforms | 17 (SPECTER COMMAND + AI SHIELD COMMAND + 15 vertical GUIs) |
| Distro packages | 3 (.deb, .rpm, Arch) |

---

## Pure Engineering

Zero subprocess calls. Zero external tool dependencies. No sqlmap, no nmap, no nikto, no wrappers. Every payload, every mutation engine, every detection algorithm built from scratch in pure Python.

---

## Responsible Use

All offensive tools require written authorisation from the target system owner. Unauthorised use may violate the Computer Misuse Act 1990 (UK), the Computer Fraud and Abuse Act (US), or equivalent legislation.

All defensive products include safety controls (UNLEASHED gate, M99 Doomsday Protocol) and cryptographic audit logging.

---

**richard@red-specter.co.uk** · [red-specter.co.uk](https://red-specter.co.uk)

<p align="center">
  <sub>Red Specter Security Research · United Kingdom · 20 March 2026</sub>
</p>
