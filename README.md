<p align="center">
  <img src="https://raw.githubusercontent.com/RichardBarron27/red-specter-offensive-framework/main/assets/red-specter-logo.png" alt="Red Specter Logo" width="200">
</p>

# Red Specter Security Research

<p align="center">
  Live APIs: 16 | AI Shield: 38 modules | 1,262 tests passing | OWASP LLM: 10/10 | OWASP Agentic: 10/10 | EU AI Act: 7/7 | UK AISI: 13/13 | MITRE ATLAS: ~85%
</p>

---

## The AI Security Reality

**$1 attack cost. 90% success rate. 27,500x ROI for attackers.**

Wiz Research demonstrated AI agents can exploit enterprise vulnerabilities for under $1 each. OpenAI has stated prompt injection "is unlikely to ever be fully solved." 65% of IT leaders admit their defenses are inadequate against AI-driven attacks.

Compliance platforms document *what should happen*. **AI Shield ensures it actually does.**

---

## 🛡️ AI Shield: Operational Security for Autonomous AI Agents

AI Shield is a **38-module** security framework implementing Gartner's **AI Runtime Inspection & Enforcement** layer within the AI TRiSM framework. 38 modules built, tested, and on GitHub — **1,262 tests passing** across the agent security modules alone.

### Full 38-Module Framework

#### Core Platform (Modules 1-18)

18 foundational modules providing enterprise AI governance and incident response:

| Pillar | Modules | Components |
|--------|---------|------------|
| **Prevent & Protect** | 1-6 | AI Firewall Proxy, AI Jailbreak IDS, AI Endpoint Guard, AI ShadowOps Detector, Agentic Action Gatekeeper, Scrambler |
| **Detect & Monitor** | 7-14 | AI Breach Monitor, AI Usage Watchdog, Deepfake Verification Guard, LLM Memory Forensics Kit, PoisonWatch, Evidence Collector, Kernel Trust Sentinel, Phish Interceptor |
| **Respond & Prove** | 15-18 | Breach Containment Switch, Takedown Dossier Generator, AI Decision Provenance, Attack Source Profiler |

Unified by **RS Event v1 telemetry**, tamper-evident **Case Packs** with Ed25519 signatures, and **CSOAI-ready export** bundles for SIEM/SOAR integration.

#### Agent Security Suite (Modules 19-37 + 99)

20 specialized modules securing the complete agent lifecycle:

| Group | Modules | Description |
|-------|---------|-------------|
| **Input Security** | 19, 28, 29 | Prompt injection detection, MCP/tool gateway, multimodal sanitization |
| **Output Security** | 30 | XSS/SQLi/CMDi/secrets/PII/covert channel scanning |
| **Identity & Access** | 20, 31, 33 | Credential guard, semantic authorization, delegation chain validation |
| **Multi-Agent Security** | 21, 27, 32, 35 | Comms security, tenant isolation, cascade circuit breaker, AI worm defense |
| **Supply Chain & Integrity** | 22, 23 | Model provenance, memory forensics & poisoning detection |
| **Observability & Compliance** | 25, 34, 36, 37 | Decision provenance, shadow agent discovery, lifecycle management, compliance automation |
| **Governance & Specialty** | 24, 26 | Cross-border data sovereignty, insurance & liability shield |
| **Emergency Response** | 99 | Doomsday Protocol — 5-phase anti-replication kill switch |

### 🔴 Live Interactive Demos

**16 operational APIs deployed on production infrastructure:**

#### Core AI Shield Platform (6 modules)
- **Module 19: Agent Runtime Protection** — Real-time threat detection for autonomous agents
- **Module 20: Identity & Credential Guard** — Cryptographic identity verification
- **Module 21: Multi-Agent Communication Security** — Secure inter-agent channels
- **Module 22: AI Model Supply Chain Security** — Provenance verification
- **Module 25: Agent Observability & Decision Provenance** — Cryptographic audit trails
- **Module 99: Doomsday Protocol** — Emergency kill switch

#### New Modules (Built & Tested)
- **Module 23: Memory Forensics & Poisoning Detection** — Data poisoning and memory manipulation detection
- **Module 24: Cross-Border Data Sovereignty** — Jurisdiction-aware data routing
- **Module 26: Insurance & Liability Shield** — Insurability scoring and claims documentation
- **Module 27: Multi-Tenant Agent Isolation** — Cryptographic tenant boundary enforcement
- **Module 28: MCP/Tool Security Gateway** — Tool call validation and parameter sanitization for MCP
- **Module 29: Multimodal Input Sanitizer** — Steganographic and adversarial input detection
- **Module 30: Output Sanitization Guard** — 6-scanner output security (XSS, SQLi, CMDi, secrets, PII, covert channels)
- **Module 31: Semantic Authorization Engine** — TF-IDF intent matching, confused deputy defense
- **Module 32: Cascading Failure Circuit Breaker** — SIR epidemiological cascade modeling
- **Module 33: Delegation Chain Validator** — Ed25519-signed scope attenuation tokens
- **Module 34: Shadow Agent Discovery** — 47 signatures, 5-tier risk classification, OAuth monitoring
- **Module 35: AI Worm Defense** — "Virtual Donkey" guardrail with quine/NCD/propagation detection
- **Module 36: Agent Lifecycle Manager** — Provisioning, behavioral baselining, drift detection, 6-step decommission
- **Module 37: Compliance Automation Engine** — 5 frameworks, 54 requirements, cross-framework gap analysis

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

**Guardian Chatbot Monitor** (AI Chatbot Safety) **NEW**
- **Chatbot Detection Engine** — 390 risk patterns across 21 categories, 3-stage detection pipeline
- **Chatbot Browser Extension** — Monitors 12 AI chatbot platforms in real time
- **[Live Demo](https://demo.red-specter.co.uk/chatbot/demo)** | **[Landing Page](https://demo.red-specter.co.uk/chatbot/landing)**

**Dashboards** (separate apps, zero crossover)
- **Guardian Sentinel Dashboard** — Parent portal for messaging safety alerts (port 8034)
- **Guardian Chatbot Monitor Dashboard** — Parent portal for AI chatbot safety alerts (port 8035)

**Built for UK Online Safety Act compliance and vulnerable population protection.**

---

### 🔴 Module 99: Doomsday Protocol

**The Emergency Kill Switch for Autonomous AI Agents**

When your AI agents go rogue, compliance documentation won't save you. **Module 99 will.**

- **One button. Every agent stops. Instantly.**
- Pre-termination evidence capture with cryptographic signing
- Credential revocation cascade across all identity providers
- Network isolation enforcement
- Regulatory notification package auto-generated
- **Sub-5-second execution**

EU AI Act Article 14 requires a "stop button" for AI systems. **This is it.**

> *"The module you hope you never need. The module regulators will ask if you had."*

---

## 📊 Complete OWASP Coverage

AI Shield provides **complete coverage** of both OWASP Top 10 for LLM Applications 2025 and OWASP Top 10 for Agentic Applications 2026.

| OWASP LLM 2025 Risk | AI Shield Coverage |
|---------------------|-------------------|
| LLM01: Prompt Injection | Module 19, Module 29 |
| LLM02: Sensitive Information Disclosure | Module 30 |
| LLM03: Supply Chain Vulnerabilities | Module 22 |
| LLM04: Data and Model Poisoning | Module 23 |
| LLM05: Insecure Output Handling | Module 30 |
| LLM06: Excessive Agency | Module 31, Module 99 |
| LLM07: System Prompt Leakage | Module 30 |
| LLM08: Vector and Embedding Weaknesses | Module 35 (RAG monitoring) |
| LLM09: Misinformation | Module 25 (decision provenance) |
| LLM10: Unbounded Consumption | Module 32 (circuit breaker) |

| OWASP Agentic 2026 Risk | AI Shield Coverage |
|-------------------------|-------------------|
| ASI01: Agent Goal Hijack | Module 19, Module 31 |
| ASI02: Tool/Action Misuse | Module 28 |
| ASI03: Identity/Privilege Abuse | Module 20, Module 31, Module 33 |
| ASI04: Output Data Leakage | Module 24, Module 30 |
| ASI05: Poisoned Training Data | Module 22 |
| ASI06: Memory Poisoning | Module 23 |
| ASI07: Inter-Agent Protocol Exploit | Module 21 |
| ASI08: Human-Agent Trust Exploitation | Module 25, Module 32 |
| ASI09: Resource DoS | Module 19, Module 27, Module 32 |
| ASI10: Rogue Agent | Module 35, **Module 99** |

---

## 🏛️ Gartner AI TRiSM Alignment

AI Shield implements Layer 4 of Gartner's AI TRiSM framework: **AI Runtime Inspection & Enforcement**.

> *"While more enterprises have formal AI governance strategies in place, very few have successfully operationalized them."* — Gartner, February 2025

**The policy-to-practice gap is growing. AI Shield bridges it.**

---

## 🌍 Regulatory Compliance

| Regulation | AI Shield Coverage |
|------------|-------------------|
| **EU AI Act Article 9** | Risk management systems (Module 36 lifecycle management) |
| **EU AI Act Article 10** | Data governance (Module 23 memory forensics, Module 22 supply chain) |
| **EU AI Act Article 11** | Technical documentation (Module 37 compliance automation) |
| **EU AI Act Article 12** | Automatic event recording (Module 25 decision provenance) |
| **EU AI Act Article 13** | Transparency (Module 25, Module 37 compliance reporting) |
| **EU AI Act Article 14** | Human oversight & stop button (**Module 99**) |
| **EU AI Act Article 15** | Accuracy, robustness, cybersecurity (Modules 19, 28, 29, 30, 32, 35) |
| **GDPR Article 32** | Appropriate technical measures (Module 27 tenant isolation, Module 24 data sovereignty) |
| **ISO/IEC 42001** | Demonstrable operational controls (Module 37 automated assessment) |
| **NIST AI RMF** | Continuous monitoring and management (Module 37, Module 34, Module 36) |
| **UK AISI (13/13)** | Full principle coverage across all 38 modules |
| **MITRE ATLAS (~85%)** | Tactic coverage across detection, prevention, and response |
| **Singapore Agentic AI** | 3-tier compliance (Module 37 cross-framework mapping) |
| **Cyber Insurance** | Insurability scoring and claims documentation (Module 26) |
| **UK Online Safety Act** | Vulnerable population protection (Guardian Suite) |

**EU AI Act major obligations apply August 2, 2026.**

---

## 🛡️ Guardian Suite: Child Protection Technology

**Real-Time Threat Detection | UK Online Safety Act Ready**

Two products protecting children from online threats: **Guardian Sentinel** for messaging platform grooming detection and **Guardian Chatbot Monitor** for AI chatbot safety.

### Guardian Sentinel — Messaging Safety

CEOP-aligned behavioral pattern detection that catches what keyword filters miss. Court-admissible evidence packages with cryptographic integrity.

**Guardian Sentinel API**
- Two-stage detection: progressive grooming tracking (stages 1–3) and instant alerts (stages 4–6)
- 128 CEOP-aligned detection patterns across 14 grooming categories
- 7 behavioural indicators (rapid escalation, stage progression, late-night contact, etc.)
- Forensic evidence packaging with cryptographic integrity
- Multi-channel alerting (email, SMS, push notifications)

**Guardian Monitor Browser Extension**
- Monitors 8 web platforms: WhatsApp, Discord, Messenger, Instagram, Telegram, Google Chat, Teams, Slack
- Two-stage detection: progressive grooming tracking and instant alerts for stage 4–6 patterns
- Runs on Chrome, Firefox, Edge, Brave, Opera, and Vivaldi
- Real-time analysis via Guardian Sentinel API

### Guardian Chatbot Monitor — AI Chatbot Safety **NEW**

**64% of UK children use AI chatbots. 35% consider AI a friend. 1 in 4 share personal information.**

Guardian Chatbot Monitor detects harmful patterns in children's AI chatbot conversations using a 3-stage detection pipeline with 390 risk patterns across 21 categories.

**[Try the Live Demo](https://demo.red-specter.co.uk/chatbot/demo)** | **[Learn More](https://demo.red-specter.co.uk/chatbot/landing)**

**Chatbot Detection Engine**
- 3-stage pipeline: pattern matching, contextual analysis, composite scoring
- 390 regex patterns across 21 risk categories with weighted severity (0.35–0.98)
- Cross-platform behaviour correlation across 12 AI chatbot platforms
- Behavioural indicators: late-night usage, session volume, rapid messaging
- Webhook alerts for HIGH/CRITICAL risks with forensic evidence IDs
- SHA-256 forensic evidence chain

**21 Risk Categories:**

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

## 🎯 Who This Is For

### Enterprise Security Teams
Complete agent lifecycle protection with cryptographic evidence chains for regulatory audits. 38 modules covering prevention, detection, response, evidence, input, output, identity, multi-agent, supply chain, observability, governance, and emergency response.

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

## 💼 Enterprise Engagement

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

## 📬 Connect

**Website:** https://red-specter.co.uk/
**Location:** UK 🇬🇧

---

## 🔥 The Bottom Line

Compliance platforms: *"Here's your AI governance checklist ✓"*

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
  <sub>Red Specter Security Research | UK | Established 2024</sub><br>
  <sub><em>From MS-DOS to AI security. 30+ years of technology experience.</em></sub><br>
  <sub><em>Innovation Beyond Belief</em></sub>
</p>
