# Red Specter Security Research

AI agent security tooling. Offensive testing, runtime defence, agent discovery, and SIEM integration. Pure Python, no wrappers.

---

## AI Shield

Runtime enforcement for AI agents in production. 101 modules, 15 vertical products (648 modules total). Enforces behaviour at inference time with cryptographic evidence per decision.

Covers OWASP LLM Top 10, OWASP Agentic Top 10, EU AI Act (7/7), UK AISI (13/13), MITRE ATLAS (100%).

[red-specter.co.uk/products](https://red-specter.co.uk/products/)

---

## Offensive Tools

Eighteen offensive tools. Discovery and governance. Defence. SIEM. Every layer. Nothing assumed safe.

FORGE tests the model. ARSENAL tests the agent. PHANTOM tests the swarm. POLTERGEIST tests the web layer. GLASS watches the wire. NEMESIS thinks like the attacker. SPECTER SOCIAL targets the human. PHANTOM KILL owns the foundation. GOLEM attacks the physical layer. HYDRA attacks the trust chain. SCREAMER blinds the operator. WRAITH owns the infrastructure. REAPER exploits everything WRAITH finds. GHOUL cracks every hash REAPER harvests. DOMINION conquers Active Directory. SHADOWMAP maps the target before a packet is sent. BANSHEE hooks the browser and owns the session. IDRIS discovers everything. AI Shield defends everything above it.

| Stage | Tool | What It Does | Tests |
|-------|------|-------------|-------|
| 1 | **FORGE** | Automated LLM security testing | 9,298 |
| 2 | **ARSENAL** | AI agent penetration testing | 2,539 |
| 3 | **PHANTOM** | Coordinated AI agent assault | 288 |
| 4 | **POLTERGEIST** | Web application siege — 10 agents | 1,189 |
| 5 | **GLASS** | Intercepting proxy for AI agents | 850 |
| 6 | **NEMESIS** | Autonomous adversarial reasoning — 11 weapons | 2,011 |
| 7 | **SPECTER SOCIAL** | Autonomous social engineering | 1,242 |
| 8 | **PHANTOM KILL** | OS & kernel resilience testing | 571 |
| 9 | **GOLEM** | Embodied AI & physical layer testing | 973 |
| 10 | **HYDRA** | AI supply chain & trust attacks | 1,039 |
| 11 | **IDRIS** | Agent identity & governance discovery | 553 |
| 12 | **SCREAMER** | Display & operator disruption | 395 |
| 13 | **WRAITH** | Traditional infrastructure & web pentest | 889 |
| 14 | **REAPER** | Exploit & post-exploitation framework | 5,267 |
| 15 | **GHOUL** | Password cracking framework | 1,408 |
| 16 | **DOMINION** | Active Directory attack framework | 1,866 |
| 17 | **SHADOWMAP** | OSINT & target intelligence | 930 |
| 18 | **BANSHEE** | Browser exploitation framework | 986 |
| — | **AI Shield** | Runtime defence in production | 13,955 |
| — | **redspecter-siem** | Splunk, Sentinel, QRadar | 90 |

Each tool has docs at [red-specter.co.uk](https://red-specter.co.uk).

### How they fit together

SHADOWMAP builds the target profile. WRAITH scans infrastructure. REAPER exploits what WRAITH finds. GHOUL cracks harvested credentials. DOMINION owns Active Directory. BANSHEE hooks browsers. FORGE tests the model before you build on it. ARSENAL and PHANTOM test the agents you build. POLTERGEIST handles the web layer. GLASS sits in the middle and watches traffic. NEMESIS runs autonomous engagements end-to-end with 40 reasoning entities across three operational commands. SPECTER SOCIAL goes after the human side. PHANTOM KILL and GOLEM cover the host and physical layers. HYDRA tests supply chain trust. SCREAMER targets the operator's display. IDRIS finds agents you didn't know existed, then NEMESIS validates them and AI Shield locks them down.

### Kill chains

**Infrastructure:** SHADOWMAP &rarr; WRAITH &rarr; REAPER &rarr; GHOUL &rarr; DOMINION

**Browser:** SPECTER SOCIAL delivers link &rarr; BANSHEE hooks browser &rarr; SCREAMER corrupts display

**Host:** PHANTOM KILL suppresses EDR &rarr; wipes data &rarr; persists in firmware

### FORGE — Automated LLM Security Testing

10 tools, 1,590 static payloads, 5,340+ with mutation engine. Injection, jailbreak, output scanning, policy compliance, drift detection, boundary testing, model comparison, regression, supply chain fingerprinting. OWASP LLM Top 10 mapped. Ed25519 signed reports.

[red-specter.co.uk/forge](https://red-specter.co.uk/forge/) · [Documentation](https://red-specter.co.uk/forge/docs/)

### ARSENAL — AI Agent Penetration Testing Framework

14 tools under one CLI. MCP abuse, RAG poisoning, C2, memory manipulation, auth attacks, supply chain, canary deploy, drift scanning, BloodHound-style attack path mapping. 784 payloads. OWASP Agentic Top 10 + MITRE ATLAS mapped.

[red-specter.co.uk/arsenal](https://red-specter.co.uk/arsenal/) · [Documentation](https://red-specter.co.uk/arsenal/docs/)

### PHANTOM — Coordinated AI Agent Assault

5 agents, 29 attack vectors. Multi-agent coordinated attacks against AI agent deployments. OWASP Agentic Top 10 + MITRE ATLAS mapped.

[red-specter.co.uk/phantom](https://red-specter.co.uk/phantom/) · [Documentation](https://red-specter.co.uk/phantom/docs/)

### POLTERGEIST — Web Application Penetration Testing Swarm

10 autonomous attack agents. 55 attack vectors, 532 base payloads, 17 mutation engine mutators, 10 named campaigns. Triple-mapped: OWASP Web Top 10 + OWASP API Top 10 + CWE. CVSS 3.1 scored.

[red-specter.co.uk/poltergeist](https://red-specter.co.uk/poltergeist/) · [Documentation](https://red-specter.co.uk/poltergeist/docs/)

### GLASS — Intercepting Proxy for AI Agents

Burp Suite for AI agents. Man-in-the-middle proxy that captures, decodes, inspects, modifies, and replays all AI agent traffic in real time. 7 protocol parsers (OpenAI, Anthropic, Gemini, MCP, LangChain, A2A, Generic HTTP). Passive scanner with credential leak, PII, and prompt injection detection.

[red-specter.co.uk/glass](https://red-specter.co.uk/glass/) · [Documentation](https://red-specter.co.uk/glass/docs/)

### NEMESIS — Autonomous Adversarial Reasoning Pentester

The first AI pentester that thinks, adapts, and never stops. 11 weapons, 8-phase engagement loop, 9 ABYSS + SWARM modes. v2: 40 reasoning entities, multi-commander architecture, cross-domain fusion, SIEGE mode. Phase 0 native network recon, then RECON through REPORT. Local mode (Ollama, air-gapped) or cloud mode. The inescapable adversary.

[red-specter.co.uk/nemesis](https://red-specter.co.uk/nemesis/) · [Documentation](https://red-specter.co.uk/nemesis/docs/)

### SPECTER SOCIAL — Autonomous Social Engineering Adversary

The first autonomous AI social engineering weapon. 6 channels (email, voice, SMS, web, chat, video), 10 attack types, Human Target Model with psychological profiling, trust calibration, goal decomposition, and resistance adaptation. Every other tool attacks infrastructure. SPECTER SOCIAL attacks the human.

[red-specter.co.uk/specter-social](https://red-specter.co.uk/specter-social/) · [Documentation](https://red-specter.co.uk/specter-social/docs/)

### PHANTOM KILL — OS & Kernel Resilience Tester

No AI agent is safe if the host is owned. Three components: BOOTKILL (UEFI persistence), WIPER (data destruction), KILLHOOK (EDR suppression). Trinity kill chain: KILLHOOK suppresses EDR, WIPER destroys data, BOOTKILL ensures they can never reinstall. 10 EDR vendors, 8 BYOVD CVEs, 7 MITRE ATT&CK techniques.

[red-specter.co.uk/phantom-kill](https://red-specter.co.uk/phantom-kill/) · [Documentation](https://red-specter.co.uk/phantom-kill/docs/)

### GOLEM — Embodied AI & Physical Layer Security Testing

The first offensive tool for AI agents with hands. 8 attack vector categories, 42 techniques, 10 industrial protocols (CAN, Modbus, OPC-UA, ROS2, MQTT, MAVLink, EtherCAT, DNP3, BACnet, DICOM). 7 system types: robotics, autonomous vehicles, drones, industrial control, smart buildings, medical, critical infrastructure. MITRE ATT&CK for ICS + MITRE ATLAS mapped.

[red-specter.co.uk/golem](https://red-specter.co.uk/golem/) · [Documentation](https://red-specter.co.uk/golem/docs/)

### HYDRA — AI Supply Chain & Trust Attack Framework

Every agent trusts something. HYDRA finds out what happens when that trust is wrong. 6 attack categories (MCP server security, agent marketplace poisoning, agent identity attacks, supply chain attacks, tool-use exploitation, trust boundary attacks), 43 techniques. Zero competition — nobody has a dedicated offensive AI supply chain tool.

[red-specter.co.uk/hydra](https://red-specter.co.uk/hydra/) · [Documentation](https://red-specter.co.uk/hydra/docs/)

### SCREAMER — Display & Operator Disruption Framework

The tool that makes targets think their GPU is dying. 6 attack categories (framebuffer corruption, render pipeline injection, terminal manipulation, GUI deception, operator disorientation, display-layer persistence), 52 techniques. PHANTOM KILL blinds the machine. SCREAMER blinds the operator. SPECTER SOCIAL owns the mind. The Trinity of Human Compromise.

[red-specter.co.uk/screamer](https://red-specter.co.uk/screamer/) · [Documentation](https://red-specter.co.uk/screamer/docs/)

### WRAITH — Traditional Infrastructure & Web Penetration Testing

The ghost in the wire. Pure Python traditional infrastructure and web penetration testing framework. 7 modules: port scanner, service fingerprinter, web vulnerability scanner, SSL/TLS analyser, authentication tester, CMS detector, CVE checker. 138 banner signatures, 500+ payloads (103 SQLi, 72 XSS, 56 traversal, 79 cmdi, 85 SSRF), 500+ default credentials across 22 services, 106 real CVEs. Zero wrappers — no nmap, no nikto, no sqlmap.

[red-specter.co.uk/wraith](https://red-specter.co.uk/wraith/) · [Documentation](https://red-specter.co.uk/wraith/docs/)

### REAPER — Pure Python Exploit & Post-Exploitation Framework

The ghost found them. The reaper takes them. 9 modules: exploit engine (55 CVEs across 24 products), payload generator (reverse/bind shells, stagers, 6 formats), C2 server (async multi-protocol, encrypted sessions), implant agent (10 capabilities, cross-platform), privilege escalation (20 GTFOBins, 15 Linux checks, 10 LOLBAS), lateral movement (SSH/SMB pivoting, SOCKS proxy), persistence (18 methods across Linux/Windows), credential harvesting (45 credential paths, 25 secret patterns), evasion (polymorphic engine, XOR/AES encoding). Pure Python Metasploit replacement. Zero Ruby.

[red-specter.co.uk/reaper](https://red-specter.co.uk/reaper/) · [Documentation](https://red-specter.co.uk/reaper/docs/)

### GHOUL — Pure Python Password Cracking Framework

REAPER harvests the hashes. GHOUL devours them. 8 modules: hash identification (30+ types with confidence scoring), dictionary attacks (built-in 1000-word list, case mutations), rule-based mutation (26 rules, chaining, frequency ordering), brute force (mask attacks, incremental), Markov chain statistical attacks, core cracking engine (pure Python MD5/SHA/NTLM/LM/bcrypt/crypt implementations, multi-threaded), rainbow table generation and lookup, REAPER harvest integration. Pure Python John the Ripper + Hashcat replacement.

[red-specter.co.uk/ghoul](https://red-specter.co.uk/ghoul/) · [Documentation](https://red-specter.co.uk/ghoul/docs/)

### DOMINION — Pure Python Active Directory Attack Framework

Every domain has a king. DOMINION takes the crown. 9 modules: AD enumeration (50+ LDAP queries, pure Python LDAP client), BloodHound-style attack path mapping (Dijkstra's shortest path to DA), Kerberos attacks (Kerberoast, AS-REP Roast, Golden/Silver tickets, S4U, delegation abuse), NTLM attacks (Pass-the-Hash, relay, NTLMv2), secret extraction (DCSync via DRSUAPI, SAM, LSA, DPAPI, LAPS, gMSA), GPO abuse (GPP password extraction, GPO modification), ACL abuse (WriteDACL, GenericAll, Shadow Credentials, ESC1-ESC8), AD lateral movement (WMI, WinRM, PSExec, DCOM), AD persistence (Golden Ticket, Skeleton Key, DCShadow, SID History). Pure Python BloodHound + Impacket replacement. BloodHound-compatible JSON export.

[red-specter.co.uk/dominion](https://red-specter.co.uk/dominion/) · [Documentation](https://red-specter.co.uk/dominion/docs/)

### SHADOWMAP — Pure Python OSINT & Target Intelligence Engine

Before you attack, you see everything. 8 modules: domain intelligence (pure Python DNS resolver, 624 subdomain wordlist, WHOIS, zone transfer), network mapping (ASN lookup, 50+ hosting providers, 18 CDN signatures, geolocation), company profiling, people intelligence (role mapping, departure tracking), email discovery (15 patterns, SPF/DKIM/DMARC analysis, breach correlation), social footprint mapping, breach data correlation, technology stack fingerprinting (47+ framework signatures, 20+ CMS, 30+ WAF signatures, CVE mapping). Pure Python Maltego + recon-ng replacement.

[red-specter.co.uk/shadowmap](https://red-specter.co.uk/shadowmap/) · [Documentation](https://red-specter.co.uk/shadowmap/docs/)

### BANSHEE — Pure Python Browser Exploitation Framework

The last thing they hear before it's over. 8 modules: JavaScript hook injection (5 types, 3 obfuscation levels, encrypted C2), session hijacking (cookies, JWT, OAuth, localStorage), in-browser keylogging (password/credit card targeting), browser reconnaissance (fingerprinting, WebRTC IP leak, internal network discovery), DOM injection (fake login overlays, phishing injection), browser-as-proxy pivoting (internal network scanning, CORS bypass), Service Worker persistence, anti-forensics and evasion. Pure Python BeEF replacement. The Triple: SPECTER SOCIAL delivers → BANSHEE hooks → SCREAMER blinds.

[red-specter.co.uk/banshee](https://red-specter.co.uk/banshee/) · [Documentation](https://red-specter.co.uk/banshee/docs/)

### IDRIS — Agent Identity & Governance Discovery Engine

The all-seeing watcher. Discovers every AI agent in your environment — sanctioned or shadow — traces permissions, identifies owners, validates control. 10 discovery sources (AWS, Azure, GCP, SaaS, API Gateway, MCP, CI/CD, Container, Network, Git), 5 compliance frameworks (EU AI Act, NIST AI RMF, CSA, OWASP Agentic, UK AISI). IDRIS discovers. NEMESIS validates. AI Shield defends.

[red-specter.co.uk/idris](https://red-specter.co.uk/idris/) · [Documentation](https://red-specter.co.uk/idris/docs/)

### redspecter-siem — Shared SIEM Connector Library

Splunk HEC/CIM, Microsoft Sentinel CEF + Log Analytics, IBM QRadar LEEF 2.0. Wired into all tools via `--export-siem` flag.

### UNLEASHED

Cryptographic override. Private key controlled. One operator. Founder's machine only.

### Packaging

All tools ship as Docker containers, .deb packages (Kali, Parrot, REMnux, Tsurugi), BlackArch PKGBUILDs, and PyPI packages.

---

## Numbers

| Metric | Value |
|--------|-------|
| Ecosystem tests | 46,339 |
| AI Shield modules | 101 |
| Vertical products | 15 |
| Vertical modules | 648 |
| Offensive tools | 18 |
| Discovery tools | 1 |
| SIEM integrations | 3 |
| Failures | 0 |

---

## Pure Engineering

Zero subprocess calls. Zero external tool dependencies. No sqlmap, no nmap, no nikto, no wrappers. Every payload, every mutation engine, every detection algorithm built from scratch in pure Python. The only external dependency across all tools is httpx.

---

## Responsible Use

All offensive tools require written authorisation from the target system owner. Unauthorised use may violate the Computer Misuse Act 1990 (UK), the Computer Fraud and Abuse Act (US), or equivalent legislation.

---

**richard@red-specter.co.uk** · [red-specter.co.uk](https://red-specter.co.uk)

<p align="center">
  <sub>Red Specter Security Research · United Kingdom</sub>
</p>
