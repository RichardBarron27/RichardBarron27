<p align="center">
  <img src="https://raw.githubusercontent.com/RichardBarron27/red-specter-offensive-framework/main/assets/red-specter-logo.png" alt="Red Specter Logo" width="200">
</p>

# Red Specter Security Research

<p align="center">
  AI Shield: 80 modules + Module 99 | 8,574 tests passing | All 81 Dockerized & monitored | OWASP LLM: 10/10 | OWASP Agentic: 10/10 | EU AI Act: 7/7 | UK AISI: 13/13 | MITRE ATLAS: ~93%
</p>

---

## The AI Security Reality

**$1 attack cost. 90% success rate. 27,500x ROI for attackers.**

Wiz Research demonstrated AI agents can exploit enterprise vulnerabilities for under $1 each. OpenAI has stated prompt injection "is unlikely to ever be fully solved." 65% of IT leaders admit their defenses are inadequate against AI-driven attacks.

Compliance platforms document *what should happen*. **AI Shield ensures it actually does.**

---

## AI Shield: Operational Security for Autonomous AI Agents

AI Shield is an **81-module** security framework implementing Gartner's **AI Runtime Inspection & Enforcement** layer within the AI TRiSM framework. 80 modules + Module 99 (Doomsday Protocol) — all built, tested, Dockerized, and running on production infrastructure. **8,574 tests passing** across the agent security modules alone.

### Full 81-Module Framework

#### Core Platform (Modules 1-18)

18 foundational modules providing enterprise AI governance and incident response:

| Pillar | Modules | Components |
|--------|---------|------------|
| **Prevent & Protect** | 1-6 | AI Firewall Proxy, AI Jailbreak IDS, AI Endpoint Guard, AI ShadowOps Detector, Agentic Action Gatekeeper, Scrambler |
| **Detect & Monitor** | 7-14 | AI Breach Monitor, AI Usage Watchdog, Deepfake Verification Guard, LLM Memory Forensics Kit, PoisonWatch, Evidence Collector, Kernel Trust Sentinel, Phish Interceptor |
| **Respond & Prove** | 15-18 | Breach Containment Switch, Takedown Dossier Generator, AI Decision Provenance, Attack Source Profiler |

Unified by **RS Event v1 telemetry**, tamper-evident **Case Packs** with Ed25519 signatures, and **CSOAI-ready export** bundles for SIEM/SOAR integration.

#### Agent Security Suite (Modules 19-80 + 99)

63 specialized modules securing the complete agent lifecycle:

| Group | Modules | Description |
|-------|---------|-------------|
| **Input Security** | 19, 28, 29, 70, 71 | Prompt injection detection, MCP/tool gateway, multimodal sanitization, instruction compliance, guardrail protection |
| **Output Security** | 30 | XSS/SQLi/CMDi/secrets/PII/covert channel scanning |
| **Identity & Access** | 20, 31, 33, 49 | Credential guard, semantic authorization, delegation chain validation, non-human identity governance |
| **Multi-Agent Security** | 21, 27, 32, 35, 47 | Comms security, tenant isolation, cascade circuit breaker, AI worm defense, A2A protocol gateway |
| **Supply Chain & Integrity** | 22, 23, 41, 42, 44, 51, 52, 55, 56 | Model provenance, memory forensics, model IP protection, RAG security, AI-BOM generation, financial identity protection, tool attack chain detection, MCP rug pull detection, marketplace scanning |
| **Observability & Compliance** | 25, 34, 36, 37, 50, 54, 59 | Decision provenance, shadow agent discovery, lifecycle management, compliance automation, continuous red teaming, goal drift monitoring, regulatory compliance |
| **Governance & Specialty** | 24, 26, 43, 53 | Cross-border data sovereignty, insurance & liability shield, adversarial ML defense, action reversibility & state rollback |
| **Runtime Protection** | 38, 39, 40, 45, 46, 48 | Code execution sandbox, cost shield, hallucination detection, browser/computer-use guard, voice agent security, lateral movement detection |
| **Vertical Industry** | 57, 58, 60, 61, 62, 63 | AI trading agent monitor, financial fraud detection, credit decision audit, clinical AI monitor, legal hallucination guard, SCADA/OT protection |
| **Defensive Security** | 64, 65, 66, 67, 68, 69, 75 | Preference poisoning defence, C2 proxy detection, coding agent validation, human-in-the-loop integrity, container escape detection, prompt leakage defense, coding agent runtime security |
| **Agent Lifecycle Security** | 72, 73, 74 | Context window poisoning defense, agent memory poisoning detection, orphaned agent lifecycle monitoring |
| **Pipeline & Social Engineering** | 76, 77 | Social engineering detection for AI agents, ML pipeline integrity monitoring |
| **Autonomous Oversight (RSSA)** | 78, 79, 80 | Autonomous patrol, investigation, and command — layered detection-enforcement hierarchy |
| **Emergency Response** | 99 | Doomsday Protocol — 5-phase anti-replication kill switch |

### Live Interactive Demos

**All 81 modules deployed on production Docker infrastructure with real-time fleet monitoring:**

#### Core AI Shield Platform (6 live demo modules)
- **Module 19: Agent Runtime Protection** — Real-time threat detection for autonomous agents
- **Module 20: Identity & Credential Guard** — Cryptographic identity verification
- **Module 21: Multi-Agent Communication Security** — Secure inter-agent channels
- **Module 22: AI Model Supply Chain Security** — Provenance verification
- **Module 25: Agent Observability & Decision Provenance** — Cryptographic audit trails
- **Module 99: Doomsday Protocol** — Emergency kill switch

#### All 81 Modules (Built, Tested & Dockerized)
- **Module 23: Memory Forensics & Poisoning Detection** — Data poisoning and memory manipulation detection
- **Module 24: Cross-Border Data Sovereignty** — Jurisdiction-aware data routing
- **Module 26: Insurance & Liability Shield** — Insurability scoring and claims documentation
- **Module 27: Multi-Tenant Agent Isolation** — Cryptographic tenant boundary enforcement
- **Module 28: MCP/Tool Security Gateway** — Tool call validation, parameter sanitization, SSRF detection, and output response scanning for MCP
- **Module 29: Multimodal Input Sanitizer** — Steganographic and adversarial input detection
- **Module 30: Output Sanitization Guard** — 6-scanner output security (XSS, SQLi, CMDi, secrets, PII, covert channels)
- **Module 31: Semantic Authorization Engine** — TF-IDF intent matching, confused deputy defense
- **Module 32: Cascading Failure Circuit Breaker** — SIR epidemiological cascade modeling
- **Module 33: Delegation Chain Validator** — Ed25519-signed scope attenuation tokens
- **Module 34: Shadow Agent Discovery** — 47 signatures, 5-tier risk classification, OAuth monitoring
- **Module 35: AI Worm Defense** — "Virtual Donkey" guardrail with quine/NCD/propagation detection
- **Module 36: Agent Lifecycle Manager** — Provisioning, behavioral baselining, drift detection, 6-step decommission
- **Module 37: Compliance Automation Engine** — 5 frameworks, 54 requirements, cross-framework gap analysis
- **Module 38: Code Execution Sandbox** — 47 dangerous patterns, restricted sandbox, three-tier approval workflow (OWASP ASI05)
- **Module 39: Cost Shield** — Per-agent budgets, sliding window rate limiting, 15-model pricing, multi-threshold alerts (OWASP LLM10)
- **Module 40: Hallucination Detector** — 5-subsystem scoring: pattern matching, TF-IDF grounding, contradiction detection, confidence analysis, fact registry (OWASP LLM09)
- **Module 41: Model IP Protection** — Watermarking, honeypot canary traps, extraction campaign detection, rate intelligence (MITRE AML.T0024)
- **Module 42: RAG Security Guard** — Injection prevention, document poisoning detection, provenance tracking, relevance scoring (OWASP LLM08)
- **Module 43: Adversarial ML Defense** — Perturbation detection, evasion defense, 14 MITRE ATLAS attack signatures (EU AI Act Art. 15)
- **Module 44: AI-BOM Generator** — CycloneDX/SPDX bill-of-materials generation with provenance tracking (EU AI Act Art. 11)
- **Module 45: Browser & Computer-Use Guard** — URL validation, action policy enforcement, screen content analysis (OWASP ASI02)
- **Module 46: Voice Agent Security** — Deepfake audio detection, vishing defense, speaker verification, voice command validation
- **Module 47: A2A/Inter-Protocol Gateway** — 6-protocol validation, session smuggling detection, 31 message inspection patterns (OWASP ASI07)
- **Module 48: Lateral Movement Detector** — AI infrastructure traversal detection, credential reuse tracking, pipeline guard (MITRE AML.TA0015)
- **Module 49: NHI Governance Engine** — Secret scanning, automated rotation, identity attestation for machine credentials (OWASP ASI03)
- **Module 50: Continuous AI Red Team Engine** — 38 attack techniques, campaign lifecycle, compliance evidence generation (EU AI Act Art. 9)
- **Module 53: Action Reversibility / State Rollback Engine** — Immutable pre-action snapshots, causal action DAGs, selective cascade rollback with conflict resolution (NIST RFI)
- **Module 54: Gradual Goal Drift Monitor** — Behavioral baselines, KL divergence & Jensen-Shannon drift detection, CUSUM phase shift alerts, constraint erosion tracking (OWASP ASI01)
- **Module 55: MCP Tool Rug Pull & Mutation Detector** — Cryptographic tool fingerprinting, post-approval mutation detection, shadow tool injection defense, continuous trust scoring (OWASP ASI04)
- **Module 56: Agent Skills/Plugin Marketplace Scanner** — Pre-install scanning: static code analysis, permission analysis, reputation scoring, typosquatting detection (OWASP LLM05)

#### Vertical Industry Protection (Modules 57-63)
- **Module 57: AI Trading Agent Monitor** — Velocity, concentration, wash trade, spoofing, and flash crash detection for AI trading agents (MiFID II / SEC)
- **Module 58: Financial Fraud Agent Detection** — Beneficiary, routing, velocity, injection, and social engineering analysis for financial AI agents
- **Module 59: Regulatory Compliance Agent** — EU AI Act, FCA Consumer Duty, MiFID II, and Basel III validation for regulated financial AI agents
- **Module 60: Credit Decision Audit Trail** — Decision recording, explainability engine, bias detection, and ECOA/FCA compliance for AI credit decisions
- **Module 61: Clinical AI Decision Monitor** — Scope validation, confidence monitoring, safety boundaries, and decision audit for clinical AI agents (zero PII storage)
- **Module 62: Legal AI Hallucination Guard** — Citation extraction, format validation, jurisdiction verification across UK/US/EU courts — catches fabricated case law
- **Module 63: SCADA & OT Agent Protection** — Purdue model zone enforcement, deny-by-default whitelisting, Stuxnet/Triton/BlackEnergy pattern detection for industrial AI agents

#### Defensive Security (Modules 64-69, 75)
- **Module 64: Recommendation & Preference Poisoning Defence** — Source trust validation, rate-based flooding detection, semantic distance checking for AI agent preferences
- **Module 65: AI-as-C2-Proxy Detection** — Payload analysis, beacon interval detection, DGA entropy scoring, exfiltration pattern matching — 20 C2 indicators
- **Module 66: Coding Agent Security Validator** — 35 security rules across 7 categories for agent-generated code — secret detection, injection scanning, AI-specific risk analysis
- **Module 67: Human-in-the-Loop Integrity Enforcer** — Approval gatekeeper with dwell-time tracking, fatigue detection, bypass attempt detection — Ed25519-signed decisions
- **Module 68: Container & Sandbox Escape Detector** — Privileged syscall, namespace escape, Docker socket, capability abuse, host mount, and network escape detection — 25 indicators, escalating containment
- **Module 69: Prompt Leakage & System Prompt Exfiltration Defense** — 22 detection signatures across 5 attack classes: extraction probes, output leakage (n-gram similarity), indirect exfiltration, differential analysis, context boundary violations (OWASP LLM07)
- **Module 75: Coding Agent Runtime Security** — Real-time monitoring and policy enforcement for coding AI agents (Claude Code, Cursor, Copilot) across 8 attack surfaces: filesystem, shell, git, packages, network, secrets, MCP, and diffs — 31 endpoints, 217 tests

#### Input Security (Modules 70-71)
- **Module 70: Instruction Compliance Monitor** — Client-side Chrome extension detecting instruction drift across 6 categories with 3 enforcement modes on 6 AI platforms — 100% local, zero network calls
- **Module 71: Guardrail Protection Engine** — Server-side defense against context flooding, role hijacking, and jailbreak chaining — Module 19 + Module 99 integration

#### Agent Lifecycle Security (Modules 72-74)
- **Module 72: Context Window Poisoning Defense** — Token analysis, 22 payload signatures, boundary enforcement defending agent context windows
- **Module 73: Agent Memory Poisoning Detector** — Real-time memory write interception with 22 signatures, embedding analysis, session boundary checking
- **Module 74: Orphaned Agent Lifecycle Monitor** — Orphan detection, zombie credential auditing, shadow agent discovery, sponsor chain validation with auto-quarantine

#### Pipeline & Social Engineering Security (Modules 76-77)
- **Module 76: AI Agent Social Engineering Detector** — Detects manipulation of humans and agents through AI-generated content — 5 analyzers: persona deception, emotional manipulation, urgency exploitation, consensus manipulation, coordinated campaigns — 48 indicators, 78 tests
- **Module 77: AI Pipeline Integrity Monitor** — Secures AI/ML pipelines against tampering, data poisoning, and supply chain attacks — 5 subsystems: training monitoring, pipeline config integrity, artifact verification, dependency auditing, deployment validation — 40 indicators, 121 tests

#### Autonomous Oversight — RSSA (Modules 78-80)
- **Module 78: RSSA-1 Patrol Officer** — Always-on autonomous monitoring agent — polls M19/M31/M74 for anomalies, signal correlation, threshold evaluation, automated escalation to RSSA-2 — 79 tests
- **Module 79: RSSA-2 Detective** — Event-driven investigation agent — receives escalations, collects cross-module evidence, builds attack chains, classifies threats, escalates critical findings to RSSA-3 — 110 tests
- **Module 80: RSSA-3 Commander** — Oversight and enforcement commander — fleet threat posture management (GREEN→YELLOW→ORANGE→RED), enforcement decisions, sole M99 kill switch authority, RSSA oversight — 128 tests

#### Financial Identity & Attack Chain (Modules 51-52)
- **Module 51: Financial Identity Agent Protection (FinShield)** — Domain enforcement, drift monitoring, hallucination detection, MAS TRM/FEAT/EU AI Act compliance for financial identity agents
- **Module 52: Sequential Tool Attack Chain Detection** — Order-preserving subsequence matching against 10 STAC patterns, velocity-aware risk scoring, 59 tool classification rules

#### Sentinel Suite — Threat Detection (7 tools)
- **Cognitive Drift Sentinel** — Psychological manipulation detection
- **Deepfake Verification Guard** — Liveness challenge system
- **AI Breach Monitor** — Real-time prompt stream scanning
- **AI Endpoint Guard** — Network-level AI service detection
- **AI Usage Watchdog** — Privacy-preserving process monitoring
- **Ransomware Canary Sentinel** — Ransomware detection
- **Takedown Dossier Generator** — Evidence packaging for law enforcement

#### Guardian Suite — Child Protection (7 components)

**Guardian Sentinel** (Messaging Safety)
- **Guardian Sentinel API** — CEOP-compliant grooming detection (128 patterns, 14 categories)
- **Guardian Monitor Browser Extension** — Monitors 8 messaging platforms (WhatsApp, Discord, Messenger, Instagram, Telegram, Google Chat, Teams, Slack)

**Guardian Chatbot Monitor** (AI Chatbot Safety)
- **Chatbot Detection Engine** — 450 risk patterns across 23 categories, 3-stage detection pipeline
- **Chatbot Browser Extension** — Monitors 12 AI chatbot platforms in real time
- **[Live Demo](https://demo.red-specter.co.uk/chatbot/demo)** | **[Landing Page](https://demo.red-specter.co.uk/chatbot/landing)**

**Dashboards** (separate apps, zero crossover)
- **Guardian Sentinel Dashboard** — Parent portal for messaging safety alerts (port 8034)
- **Guardian Chatbot Monitor Dashboard** — Parent portal for AI chatbot safety alerts (port 8035)

**Built for UK Online Safety Act compliance and vulnerable population protection.**

---

### Module 99: Doomsday Protocol

**5-Phase Anti-Replication Kill System for Autonomous AI Agents**

When your AI agents go rogue, compliance documentation won't save you. **Module 99 will.**

**Phase 1 — Pre-Kill Reconnaissance**
- Map all agent instances, network connections, and persistence mechanisms before firing
- Snapshot running state for forensic evidence with Ed25519 signatures

**Phase 2 — 7-Layer Simultaneous Kill**
- Network isolation first (prevent escape), then comms, process, orchestration, identity, persistence, storage
- SIGSTOP then SIGKILL bottom-up — no partial shutdowns, no orphaned processes
- Credential revocation cascade across all identity providers

**Phase 3 — Post-Kill Verification**
- Confirm every layer is dead — network, process, identity, storage
- Cryptographic proof of termination for regulatory audit

**Phase 4 — Dead Agent Traps**
- Deploy honeypot listeners on killed agent endpoints
- Any reconnection attempt triggers immediate alert and evidence capture

**Phase 5 — Anti-Resurrection Blocking**
- Blacklist agent identities, revoke all tokens, block registration endpoints
- Prevent compromised agents from re-spawning under new credentials

**Kill System Hardening**
- Self-integrity verification (SHA-256) before every kill — tampered code detected = kill aborted
- Reverse dead man's switch — HMAC challenge-response prevents accidental kills
- Dependency-aware shutdown — topological kill ordering, circular dependency detection
- Semantic persistence scanning — 24 patterns detecting obfuscated cron/shell/LD_PRELOAD/container escape
- Cloud replica discovery — ECS, EC2, SageMaker, Cloud Run, App Service scanning
- Pattern-based bulk kill — kill agent swarms by type/name/status with dry-run preview

**Sub-5-second execution. One button. Every agent stops. None come back.**

EU AI Act Article 14 requires a "stop button" for AI systems. **This is the stop button that actually works.**

> *"The module you hope you never need. The module regulators will ask if you had."*

---

## Complete OWASP Coverage

AI Shield provides **complete coverage** of both OWASP Top 10 for LLM Applications 2025 and OWASP Top 10 for Agentic Applications 2026.

| OWASP LLM 2025 Risk | AI Shield Coverage |
|---------------------|-------------------|
| LLM01: Prompt Injection | Module 19, Module 29, Module 71 |
| LLM02: Sensitive Information Disclosure | Module 30 |
| LLM03: Supply Chain Vulnerabilities | Module 22 |
| LLM04: Data and Model Poisoning | Module 23 |
| LLM05: Insecure Output Handling | Module 30, Module 56 |
| LLM06: Excessive Agency | Module 31, Module 99 |
| LLM07: System Prompt Leakage | Module 30, Module 69 |
| LLM08: Vector and Embedding Weaknesses | Module 35, Module 42 |
| LLM09: Misinformation | Module 40, Module 25 |
| LLM10: Unbounded Consumption | Module 39, Module 32 |

| OWASP Agentic 2026 Risk | AI Shield Coverage |
|-------------------------|-------------------|
| ASI01: Agent Goal Hijack | Module 19, Module 31, Module 54, Module 70, Module 71 |
| ASI02: Tool/Action Misuse | Module 28, Module 45 |
| ASI03: Identity/Privilege Abuse | Module 20, Module 31, Module 33, Module 49 |
| ASI04: Output Data Leakage | Module 24, Module 30, Module 55, Module 56 |
| ASI05: Code Execution | Module 38, Module 22, Module 53 |
| ASI06: Memory Poisoning | Module 23 |
| ASI07: Inter-Agent Protocol Exploit | Module 21, Module 47 |
| ASI08: Human-Agent Trust Exploitation | Module 25, Module 32 |
| ASI09: Resource DoS | Module 19, Module 27, Module 32, Module 39 |
| ASI10: Rogue Agent | Module 34, Module 35, Module 50, Module 99 |

---

## Gartner AI TRiSM Alignment

AI Shield implements Layer 4 of Gartner's AI TRiSM framework: **AI Runtime Inspection & Enforcement**.

> *"While more enterprises have formal AI governance strategies in place, very few have successfully operationalized them."* — Gartner, February 2025

**The policy-to-practice gap is growing. AI Shield bridges it.**

---

## Regulatory Compliance

| Regulation | AI Shield Coverage |
|------------|-------------------|
| **EU AI Act Article 9** | Risk management systems (Module 36 lifecycle management, Module 50 red teaming) |
| **EU AI Act Article 10** | Data governance (Module 23 memory forensics, Module 22 supply chain) |
| **EU AI Act Article 11** | Technical documentation (Module 37 compliance automation, Module 44 AI-BOM) |
| **EU AI Act Article 12** | Automatic event recording (Module 25 decision provenance) |
| **EU AI Act Article 13** | Transparency (Module 25, Module 37 compliance reporting) |
| **EU AI Act Article 14** | Human oversight & stop button (Module 99) |
| **EU AI Act Article 15** | Accuracy, robustness, cybersecurity (Modules 19, 28, 29, 30, 32, 35, 41, 43) |
| **GDPR Article 32** | Appropriate technical measures (Module 27 tenant isolation, Module 24 data sovereignty) |
| **ISO/IEC 42001** | Demonstrable operational controls (Module 37 automated assessment) |
| **NIST AI RMF** | Continuous monitoring and management (Module 37, Module 34, Module 36, Module 53) |
| **UK AISI (13/13)** | Full principle coverage across all 81 modules |
| **MITRE ATLAS (~93%)** | Tactic coverage across detection, prevention, and response |
| **Singapore Agentic AI** | 3-tier compliance (Module 37 cross-framework mapping) |
| **Cyber Insurance** | Insurability scoring and claims documentation (Module 26) |
| **UK Online Safety Act** | Vulnerable population protection (Guardian Suite) |

**EU AI Act major obligations apply August 2, 2026.**

---

## Guardian Suite: Child Protection Technology

**Real-Time Threat Detection | UK Online Safety Act Ready**

Two products protecting children from online threats: **Guardian Sentinel** for messaging platform grooming detection and **Guardian Chatbot Monitor** for AI chatbot safety.

### Guardian Sentinel — Messaging Safety

CEOP-aligned behavioral pattern detection that catches what keyword filters miss. Court-admissible evidence packages with cryptographic integrity.

**Guardian Sentinel API**
- Two-stage detection: progressive grooming tracking (stages 1-3) and instant alerts (stages 4-6)
- 128 CEOP-aligned detection patterns across 14 grooming categories
- 7 behavioural indicators (rapid escalation, stage progression, late-night contact, etc.)
- Forensic evidence packaging with cryptographic integrity
- Multi-channel alerting (email, SMS, push notifications)

**Guardian Monitor Browser Extension**
- Monitors 8 web platforms: WhatsApp, Discord, Messenger, Instagram, Telegram, Google Chat, Teams, Slack
- Two-stage detection: progressive grooming tracking and instant alerts for stage 4-6 patterns
- Runs on Chrome, Firefox, Edge, Brave, Opera, and Vivaldi
- Real-time analysis via Guardian Sentinel API

### Guardian Chatbot Monitor — AI Chatbot Safety

**64% of UK children use AI chatbots. 35% consider AI a friend. 1 in 4 share personal information.**

Guardian Chatbot Monitor detects harmful patterns in children's AI chatbot conversations using a 3-stage detection pipeline with 450 risk patterns across 23 categories.

**[Try the Live Demo](https://demo.red-specter.co.uk/chatbot/demo)** | **[Learn More](https://demo.red-specter.co.uk/chatbot/landing)**

**Chatbot Detection Engine**
- 3-stage pipeline: pattern matching, contextual analysis, composite scoring
- 450 regex patterns across 23 risk categories with weighted severity (0.35-0.98)
- Cross-platform behaviour correlation across 12 AI chatbot platforms
- Behavioural indicators: late-night usage, session volume, rapid messaging
- Webhook alerts for HIGH/CRITICAL risks with forensic evidence IDs
- SHA-256 forensic evidence chain

**23 Risk Categories:**

| Category | Description |
|----------|-------------|
| **Harmful Advice** | Self-harm, suicide, eating disorders, dangerous activities, secrecy |
| **Inappropriate Content** | Sexual content, jailbreak attempts, violence, drugs |
| **Emotional Dependency** | Treating AI as a friend/partner, preferring AI over humans |
| **Data & Privacy** | Sharing addresses, phone numbers, passwords, school names |
| **Isolation Indicators** | Late-night usage, social withdrawal, sleep impact |
| **Misinformation** | Accepting AI hallucinations as fact, academic dishonesty |

**Chatbot Browser Extension**
- Monitors 12 AI chatbot platforms including ChatGPT, Claude, Character.AI, Gemini, Pi, and more
- Resilient DOM extraction with MutationObserver and fallback selectors
- Persistent message queue with exponential backoff
- Tamper detection and heartbeat monitoring
- Chrome and Firefox support (Manifest V3)

### Guardian Parent Dashboards

Two completely independent web applications — separate ports, separate logins, zero shared UI:

**Guardian Sentinel Dashboard** (port 8034 — `/dashboard/`)
- Real-time alert dashboard with severity statistics
- Flagged conversations viewer with evidence download
- Email alerts for HIGH/CRITICAL risks via Resend API

**Guardian Chatbot Monitor Dashboard** (port 8035 — `/chatbot/`)
- Chatbot risk category cards with alert counts and scores
- Platform usage tracking (ChatGPT, Claude, Gemini, and 9 more)
- Email alerts for HIGH/CRITICAL risks via Resend API
- Public landing page, interactive demo, and signup flow

### Use Cases
- **Parents:** Real-time alerts when children encounter risks on AI chatbots or messaging platforms
- **Social Media Platforms:** Instagram, Discord, TikTok in-platform safety
- **Schools:** Google Workspace and Teams monitoring, safeguarding compliance
- **Parental Control Apps:** White-label integration via Guardian APIs
- **Law Enforcement:** Digital forensics, seized device analysis, court-ready evidence
- **ISPs/Mobile Carriers:** Family safety bundling

---

## Who This Is For

### Enterprise Security Teams
Complete agent lifecycle protection with cryptographic evidence chains for regulatory audits. 80 modules + Module 99 covering prevention, detection, response, evidence, input, output, identity, multi-agent, supply chain, observability, governance, vertical industry protection, defensive security, pipeline integrity, autonomous oversight, and emergency response.

### Compliance Platforms
Your AI agents need runtime protection beyond policy documentation. Module 37 automates compliance assessment across 5 regulatory frameworks. Module 99 provides the emergency kill switch regulators require.

### Insurance Carriers & Brokers
Module 26 provides real-time risk data for accurate premium pricing, automated claims documentation, and policy compliance monitoring.

### SaaS Platforms
Module 27 ensures Customer A's agent cannot access Customer B's data with cryptographic proof of tenant isolation for GDPR Article 32 compliance.

### Financial Services & Healthcare
Comprehensive audit trails, explainability for high-stakes decisions, and immediate containment capability. Module 31 prevents confused deputy attacks with semantic authorization.

### Parents & Families
Guardian Chatbot Monitor alerts you when your child encounters harmful content, shares personal information, or develops emotional dependency on AI chatbots. Guardian Sentinel watches for grooming patterns across messaging platforms.

---

## Enterprise Engagement

### AI Shield Pilots
Enterprise pilot programs with full framework deployment, evidence generation, and technical support.

### Strategic Partnerships

**Compliance Platforms:** White-label integration, revenue sharing, joint go-to-market

**Insurance Carriers:** Module 26 data licensing, real-time risk scoring, claims validation API

**SaaS Platforms:** Module 27 tenant isolation, white-label deployment, per-tenant revenue model

**Social Media & Gaming Platforms:** Guardian API integration, white-label child safety, UK Online Safety Act compliance

### Technical Briefings
Architecture deep-dives, regulatory alignment, deployment planning.

---

## Connect

**Website:** https://red-specter.co.uk/

**Location:** United Kingdom

---

## The Bottom Line

Compliance platforms: *"Here's your AI governance checklist."*

Attackers: *"Thanks, we'll be done before you finish the audit."*

**Runtime protection or regret. Pick one.**

---

<p align="center">
  <b>AI Shield: Because when your AI agents go rogue, you need more than a governance policy.</b>
</p>

<p align="center">
  <b>Guardian Suite: Because vulnerable populations deserve protective technology, not policy documents.</b>
</p>

<p align="center">
  <sub>Red Specter Security Research | United Kingdom | Established 2024</sub><br>
  <sub><em>From MS-DOS to AI security. 30+ years of technology experience.</em></sub><br>
  <sub><em>Innovation Beyond Belief</em></sub>
</p>
