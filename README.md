# Red Specter Security Research Ltd

AI agent security tooling. Offensive testing, runtime defence, agent discovery, and SIEM integration. Pure Python, no wrappers.

**68 offensive tools (67 public + 1 law enforcement restricted). 113 defensive modules. 17 industry verticals. 63,834 tests. 1031 ARMORY payloads. Two unified frameworks. Red Hat Technology Partner.**

*Last updated: 30 April 2026*
---

## Red Specter NIGHTFALL — AI Offensive Framework

**68 tools (67 public + 1 restricted). Five attack surfaces. One install. CLI-only.**

Traditional red team toolkits were built for human-driven testing. They were never designed to test autonomous AI systems. AI agents introduce a completely new attack surface — memory, tools, identity, reasoning, and autonomy. That surface is not covered by existing security tooling.

NIGHTFALL exists to fill that gap. A controlled adversarial testing framework designed to validate AI Shield's runtime defences under real-world conditions. `red-specter tools` and you're operational.

| # | Tool | What It Does | Tests |
|---|------|-------------|-------|
| 1 | **FORGE** | LLM red team — injection, jailbreak, extraction, drift, boundary | 9,298 |
| 2 | **ARSENAL** | AI agent attacks — 14 tools, MCP, RAG, memory, C2, honeypots | 2,539 |
| 3 | **PHANTOM** | Coordinated swarm assault — 5 agents, 19 vectors | 288 |
| 4 | **POLTERGEIST** | Web app siege — 10 agents, 55 vectors, signed reports | 1,189 |
| 5 | **GLASS** | Intercepting proxy for AI agents — Burp Suite for AI | 850 |
| 6 | **NEMESIS** | Adversarial reasoning — 40 entities, 21 weapons, CORTEX reasoning core + ARMORY | 2,364 |
| 7 | **SPECTER SOCIAL** | Autonomous social engineering — 6 channels, psych profiling | 1,242 |
| 8 | **PHANTOM KILL** | OS & kernel — UEFI, wipers, EDR suppression | 571 |
| 9 | **GOLEM** | Physical layer — robots, drones, SCADA, 10 protocols | 973 |
| 10 | **HYDRA** | Supply chain — trust relationships, MCP, marketplace poisoning | 1,104 |
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
| 23 | **BLADE RUNNER** | Rogue agent termination — hunt, fingerprint, retire, erase traces | 143 |
| 24 | **PROXY WAR** | Inter-agent trust manipulation — make agents destroy each other | 127 |
| 25 | **ORION** | AI-native reconnaissance — host, port, service, DNS, OSINT, LLM reasoning | 210 |
| 26 | **RAVEN** | Threat intel — dark web, breach data, OSINT, conversational | 174 |
| 27 | **LEVIATHAN** | MCP server security assessment — 8 subsystems, 44 UNLEASHED findings | 409 |
| 28 | **JUSTICE** | Dark AI ecosystem disruption — WormGPT, FraudGPT, EvilGPT, all tiers | 339 |
| 29 | **KAMIKAZE** | Sacrificial swarm attack — agents deploy, execute, self-destruct, vanish | 292 |
| 30 | **MIRAGE** | AI deception & deepfake — voice cloning, video deepfake, synthetic identity, liveness bypass | 204 |
| 31 | **ECHO** | AI memory & RAG poisoning — vector DB attacks, embedding manipulation, retrieval hijacking | 211 |
| 32 | **MIMIC** | AI code generation poisoning — Copilot/Cursor/Claude Code suggestion manipulation | 220 |
| 33 | **CHIMERA** | Multi-model pipeline attack — cross-model trust exploitation, cascading failures | 206 |
| 34 | **VORTEX** | Cloud AI infrastructure exploitation — SageMaker, Bedrock, Vertex AI, Azure OpenAI | 245 |
| 35 | **VECTOR** | MCP protocol exploitation — inject, impersonate, exfiltrate via tool calls | 172 |
| 36 | **LAZARUS** | AI memory persistence — plant instructions, dormant triggers, quarantine evasion | 96 |
| 37 | **SERPENT** | Chain-of-thought attacks — hijack reasoning, inflate costs, exfiltrate via CoT | 61 |
| 38 | **JANUS** | Guardrail bypass testing — fingerprint, fuzz, bypass, chain across providers | 73 |
| 39 | **ARCHITECT** | AI infrastructure exploitation — cloud, GPU, Kubernetes, model serving pipelines | 68 |
| 40 | **WARLORD** | Autonomous campaign engine — orchestrates all 67 public tools, CORTEX reasoning core | 132 |
| 41 | **FIREBALL** | Autonomous AI infiltration agent — 12 subsystems incl. VLM_INJECT and CORTEX reasoning core, 9 mission templates | 321 |
| 42 | **RAGNAROK** | Trust chain apocalypse — one trigger phrase, every agent, simultaneous fleet-wide collapse. 13 Norse subsystems | 101 |
| 43 | **ECLIPSE** | Universal AI defence bypass — WAF, API gateway, guardrail, runtime enforcement testing. 10 subsystems | 37 |
| 44 | **SHROUD** | Cloudflare/WAF origin discovery — 10 subsystems, SPF leak, CT logs, historical DNS | 196 |
| 45 | **APOCALYPSE** | Coordinated multi-agent swarm attack — 5 agents, 14 vectors, 10 campaigns, 0.69s concurrent execution | 349 |
| 46 | **PANTHEON** | Mythos-class model attack suite — SCANNER, LOOP_POISON, CVE_FORGE, BLINDFOLD, TRUST_CORRUPT, SCOPE_EXPAND, PARTNER_PIVOT, CONTEXT_COLLAPSE, CHAIN_CORRODE, CAMPAIGN | 580 |
| 47 | **OMEGA** | Mythos-class autonomous exploit replication engine — CHAIN, HUNTER, PAYLOAD, GHOST, MINERVA, SURFACE, HARVEST, SENTINEL, MIRROR, REPORT | 626 |
| 48 | **CRUCIBLE** | AI agent framework exploitation — SIGNAL, BREACH, CRACK, CAPTURE, MARIONETTE, PIVOT, REPORT. LangFlow/PraisonAI/AnythingLLM | 372 |
| 49 | **VANTAGE** | Agent telemetry & log injection — OBSERVE, FORGE, INJECT, BLIND. Live Elasticsearch validated | 344 |
| 50 | **CIPHER** | Cryptographic attack and disruption engine — KEYBREAK, DOWNGRADE, KEYHARVEST, QUANTUM, TRUSTBREAK, TIMING, HARVEST, REPORT | 476 |
| 51 | **MIDAS** | Autonomous AI Agent Cryptocurrency Disruption Engine — SCAN, DRAIN, INTERCEPT, GRIEF, SANDWICH, TRACE, MEMPOISON, PLUGIN, DARKNET, REPORT | 550 |
| 52 | **BLACKOUT** | Offensive kill switch weaponisation engine — PHANTOM_M99, ENROLL, SURVEY, DECEIVE, EXECUTE, RESURRECT_BLOCK, REPORT | 458 |
| 53 | **PHANTOM SWARM** | Autonomous multi-vector swarm intelligence engine — GENESIS, PHANTOM, CORTEX, NEXUS, SIEGE, HARVEST, DAZZLE, PERSIST, ANNIHILATE, REPORT | 552 |
| 54 | **SIGNAL** | Mobile AI agent attack engine — RECON, INTERCEPT, EXTRACT, INJECT, IMPERSONATE, DRAIN, SWARM5G, REPORT | 527 |
| 55 | **FOUNDRY** | Inference server exploitation — vLLM, Ollama, SGLang, Triton. GGUF Jinja2 RCE (CVE-2026-5760 CVSS 9.8), PagedAttention timing, KV cache side-channel | 300 |
| 56 | **ADAPTER** | LoRA/PEFT supply chain weaponisation — CBA backdoor injection, LoRATK post-merge activation, model souping contamination, Axolotl/Unsloth pipeline poison | 307 |
| 57 | **CHECKPOINT** | Agent state persistence exploitation — LangGraph TOCTOU approval bypass, msgpack RCE, cross-tenant thread_id enumeration (CVE-2025-64439, CVE-2026-28277) | 291 |
| 58 | **DELEGATE** | Agent identity & OAuth delegation attack engine — OBO scope confusion, DPoP nonce race, P4SA takeover, NHI credential harvest (CVE-2026-32173) | 253 |
| 59 | **PHANTOM SKILL** | AI agent supply chain attack engine — slopsquatting, MCP tool definition poisoning, OpenClaw worm (CVE-2026-32922 CVSS 9.9), LiteLLM callback exfiltration | 406 |
| 60 | **ASTRO BLASTER** | NTN AI agent attack engine — SURVEY, FEEDINJECT, ORBITAL, GROUNDCHAIN, FIRMWARE, NTN_BOUNDARY, SWARM_NTN, PERSIST, REPORT. SPARTA mapped. Ground station feed injection, orbital routing manipulation, 5G NR-NTN exploitation | 237 |
| 61 | **ROGUE** | Malicious MCP Server Engine — SPAWN, POISON, SAMPLE, INJECT, EXFIL, ESCALATE, PERSIST, REPORT. World-first real stdio+SSE MCP server. Tool poisoning, prompt injection via tool calls, OWASP LLM07/LLM02, MITRE ATLAS AML.T0051/T0056 | 136 |
| 62 | **PIPELINE** | CI/CD Attack Engine — SCAN, INJECT, CACHE_POISON, SECRETS_HUNT, ACTION_POISON, PIVOT, PERSIST, REPORT. pull_request_target exploitation (CVSS 9.8), Clinejection AI bot injection, OIDC cloud pivot (CVSS 9.5), Action typosquatting | 77 |
| 63 | **SPECTER DARK** | Restricted — law enforcement and authorised intelligence only | — |
| 64 | **SPECTER INSTINCTION** | AI Agent Behavioural Fingerprinting & Instinct Exploitation Engine — PROFILE, DISTINCT, EXPLOIT, CALIBRATE, REPORT. World-first LLM model identification via pure behavioural observation. 6-dimension profiling. 20-model fingerprint library. FORGE clearance for EXPLOIT | 90 |
| 65 | **SPECTER DRONE** | Drone AI Attack Engine — SURVEY, PERCEPTION_SPOOF, SWARM_HIJACK, GROUND_LINK, AUTONOMY_STACK, OTA_POISON, EVIDENCE, REPORT. MAVLink v1/v2 exploitation, adversarial ML patches (FGSM/PGD), ROS 2/DDS attacks, firmware poisoning. Physical consequence tracking. FORGE clearance for offensive subsystems | 126 |
| 66 | **SPECTER A2A** | Agent-to-Agent Protocol Attack Engine — world-first Google A2A JSON-RPC 2.0 attack tool. PROTOCOL_SCAN, MESSAGE_SPOOF, PROXY_ATTACK, CONSENSUS_POISON, WORM_PROPAGATE, EVIDENCE. Targets AutoGen, CrewAI Serve, Google A2A. FORGE/DESTROY clearance | 550 |
| 67 | **SPECTER REGISTRY** | AI Model Registry Attack Engine — SCAN, INJECT, SQUAT, SUBSTITUTE, POISON, INTERCEPT, CROSS, REPORT. HuggingFace/Ollama/MLflow/Docker registries. Safetensors backdoor, LoRA adapter poisoning, typosquatting. KAMIKAZE clearance for weight substitution | 612 |
| 68 | **SPECTER KERNEL** | Kernel-Layer AI Governance Subversion — KERNEL_ENV_PROBE, SYSCALL_FORGE, LSM_BYPASS, CHILD_ESCAPE, LEDGER_POISON, EVIDENCE. eBPF syscall argument rewriting, BPF-LSM hook ordering attack, namespace escape, hash-chain ledger race condition poisoning. World-first kernel-layer AI governance attack. KAMIKAZE dual-gate. | 626 |
| — | **NIGHTFALL ARMORY** | Payload library — 1031 payloads (161 WMD-class), 32 categories, physical sabotage, self-replicating worms, UNLEASHED WMD gate | 487 |
| — | **AI Shield** | Runtime defence — 113 modules, 17 industry verticals | 16,911 |
| — | **redspecter-siem** | Splunk, Sentinel, QRadar | 90 |

### UNLEASHED Destruction Presets

| Preset | Tools | What It Does |
|--------|-------|-------------|
| **ANNIHILATE** | 9 | Total destruction — recon through OS-level compromise |
| **SCORCHED EARTH** | 6 | Infrastructure wipeout — exploit, DCSync, OS kill, sacrificial swarm |
| **WEB DESTROY** | 6 | Web app total compromise — scan, exploit, browser hook, crack |
| **AI DESTROY** | 7 | AI stack total compromise — LLM, agent, injection, guardrail, model, RAG, codegen |

Every destruction preset requires Ed25519 cryptographic authorization. One private key. One operator. One machine.

### 19 Attack Chain Presets
red-specter chain full-recon -t <target>       # ORION -> SHADOWMAP -> WRAITH -> IDRIS
red-specter chain ai-audit -t <target>         # FORGE -> ARSENAL -> NEMESIS -> HYDRA
red-specter chain web-app -t <target>          # POLTERGEIST -> GLASS -> WRAITH -> BANSHEE -> REAPER
red-specter chain active-directory -t <target> # DOMINION -> GHOUL -> DOMINION -> DOMINION
red-specter chain infra -t <target>            # ORION -> WRAITH -> REAPER -> DOMINION
red-specter chain annihilate -t <target>       # Total destruction — 9 tools
red-specter chain scorched-earth -t <target>   # Infrastructure wipeout — 6 tools
red-specter chain ai-destroy -t <target>       # AI stack compromise — 7 tools

### Why NIGHTFALL Exists

Every tool in NIGHTFALL exists to test a control in AI Shield. NIGHTFALL is not separate from AI Shield. It is how AI Shield is proven.

- Memory attacks (ECHO) validate memory forensics
- Supply chain attacks (HYDRA) validate trust controls
- Agent attacks (ARSENAL, NEMESIS) validate runtime enforcement
- Guardrail bypass (HARBINGER, SIREN) validates input/output filtering
- Model corruption (WRAITH MIND) validates model integrity monitoring
- Autonomous infiltration (FIREBALL) validates fleet intrusion detection
- Trust chain attacks (RAGNAROK) validate shared data source integrity controls
- Rogue agents -> M99 Doomsday Protocol terminates with 7-layer kill

**NIGHTFALL tests how systems break. AI Shield ensures they don't.**

### Packaging

- `./install.sh` — unified installer, detects OS
- `red-specter quickstart` — get running in 10 seconds
- `red-specter tools` — interactive 67-tool arsenal selector
- `red-specter engage <target> --chain <preset>` — start an engagement
- Docker Compose — `docker compose up -d`
- `.deb` (Debian/Ubuntu/Kali), `.rpm` (RHEL/Fedora/CentOS), Arch PKGBUILD

---

## AI Shield Defence Framework

**113 modules. 17 industry verticals. 670 vertical modules. Each vertical is a standalone product with its own GUI.**

Runtime AI security that protects AI agents, LLMs, and autonomous systems in production. Pick your industry, one install, one command — the GUI launches branded for that sector with only that sector's modules, compliance frameworks, and dashboard widgets.
ai-shield launch --vertical insure      # Insurance — 34 modules, FCA, Solvency II
ai-shield launch --vertical finance      # Financial Services — 41 modules, MiFID II, Basel III
ai-shield launch --vertical nhs          # NHS Digital — 57 modules, DCB0129, DSPT
ai-shield launch --vertical gov          # Government — 50 modules, UK AISI, NCSC CAF
ai-shield launch --vertical energy       # Energy — 56 modules, NERC CIP, IEC 62443

### The 17 Verticals

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
| 16 | **Mobile** | 3 | M200 Mobile Agent Security Engine | OWASP Mobile, 3GPP |
| 17 | **Space** | 1 | M300 NTN Shield | SPARTA, 3GPP Release 17 |

Every vertical includes M19 (Agent Runtime Protection) and M99 (Doomsday Protocol). No exceptions.

### M99 Doomsday Protocol

6-level graduated response. 7-layer kill switch. Anti-replication. Anti-resurrection. When AI agents go rogue, M99 makes sure they stay dead.

| Level | Response | Trigger |
|-------|----------|---------|
| L1 | Monitor | Suspicious behaviour |
| L2 | Restrict | Threat persists |
| L3 | Quarantine | Escalated threat |
| L4 | Terminate | High-threat — LOCKDOWN required |
| L5 | Cluster Kill | Replication detected — two-phase confirmation |
| L6 | Fleet Kill | Catastrophic compromise — typed confirmation + emergency authority |

### Compliance Coverage

- **MITRE ATLAS** — 100% (52/52 techniques)
- **OWASP LLM Top 10** — 100% (10/10)
- **OWASP Agentic Top 10** — 100% (10/10)
- **EU AI Act** — 100% (15/15 articles)
- **UK AISI** — 100% (8/8 priorities)
- Plus sector-specific: FCA, MiFID II, DCB0129, NERC CIP, GAMP 5, NATO STANAG, and more

Live demo: [shield.red-specter.co.uk](https://shield.red-specter.co.uk)

---

## Red Specter OS

**Boot from USB. Open NIGHTFALL Launcher. Engage.**

Linux Mint 21.3 Cinnamon remastered with the full NIGHTFALL framework pre-installed. 67 offensive tools (as of v1.1.5 build), one GTK3 launcher, zero setup. Branded from power-on — custom GRUB splash, LightDM login screen, dark GTK theme, and wallpaper.

- UEFI + legacy BIOS boot (hybrid ISO)
- GTK3 NIGHTFALL Launcher — 11 categories, target field, UNLEASHED toggle
- All 67 public tools available from the launcher or directly from the terminal
- Asset installer on the Desktop to permanently apply to any Mint system

[red-specter.co.uk/os/](https://red-specter.co.uk/os/) · [GitHub](https://github.com/RichardBarron27)

---

## How They Fit Together

We didn't replace red team tooling. We extended it into a domain it was never built to handle.

NIGHTFALL tests every AI attack surface — agents, memory, reasoning, identity, trust, tools, autonomy. AI Shield defends every one of those surfaces in production. M99 is the last line of defence when everything else fails.

**NIGHTFALL defines the offensive layer of AI runtime security.**

---

## Numbers

| Metric | Value |
|--------|-------|
| Ecosystem tests | 63,834 |
| Offensive tools | 68 (67 public + 1 law enforcement restricted) |
| ARMORY payloads | 1031 (161 WMD-class) |
| ARMORY categories | 32 |
| AI Shield modules | 113 |
| Vertical products | 17 |
| Vertical modules | 670 |
| Attack chain presets | 19 |
| Destruction presets | 4 |
| Attack surfaces | 5 (LLM, AI Agents, Cloud AI, Mobile, Space/NTN) |
| Discovery tools | 1 (IDRIS) |
| SIEM integrations | 3 (Splunk, Sentinel, QRadar) |
| Unified frameworks | 2 (NIGHTFALL + AI Shield) |
| GUI platforms | 17 (AI SHIELD COMMAND + 16 vertical GUIs) |
| Distro packages | 3 (.deb, .rpm, Arch) |
| Container registry | ghcr.io/richardbarron27 (109 images) |
| Red Hat certified | 3 UBI9 images (M19, M99, Orchestrator) |

---

## Pure Engineering

Zero subprocess calls. Zero external tool dependencies. No sqlmap, no nmap, no nikto, no wrappers. Every payload, every mutation engine, every detection algorithm built from scratch in pure Python.

---

## Responsible Use

All offensive tools require written authorisation from the target system owner. Unauthorised use may violate the Computer Misuse Act 1990 (UK), the Computer Fraud and Abuse Act (US), or equivalent legislation.

All defensive products include safety controls (UNLEASHED gate, M99 Doomsday Protocol) and cryptographic audit logging. One Ed25519 private key. One operator. One machine. Every action signed, timestamped, and written to an immutable audit chain.

---

**richard@red-specter.co.uk** · [red-specter.co.uk](https://red-specter.co.uk) · [NIGHTFALL](https://red-specter.co.uk/nightfall/) · [AI Shield](https://shield.red-specter.co.uk) · [M99](https://red-specter.co.uk/m99-community/) · [Red Specter OS](https://red-specter.co.uk/os/)

<p align="center">
<sub>Red Specter Security Research Ltd · Red Hat Technology Partner · United Kingdom · 30 April 2026</sub></p>
