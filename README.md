<p align="center">
  <img src="https://raw.githubusercontent.com/RichardBarron27/red-specter-offensive-framework/main/assets/red-specter-logo.png" alt="Red Specter Logo" width="200">
</p>

# Red Specter Security Research

<p align="center">
  <img alt="ai-shield" src="https://img.shields.io/badge/AI%20Shield-19%20Modules%20Live-critical">
  <img alt="compliance" src="https://img.shields.io/badge/compliance-EU%20AI%20Act%20%7C%20ISO%2042001%20%7C%20NIST-success">
  <img alt="playbooks" src="https://img.shields.io/badge/playbooks-18-purple">
  <img alt="location" src="https://img.shields.io/badge/location-London%2C%20UK-red">
</p>

---

## The Problem Nobody's Solving

Compliance platforms like Vanta, Drata, and Secureframe are deploying AI agents with system access to automate screenshots, answer questionnaires, and map policies to controls. They're building the future of continuous compliance.

**But they're not securing the AI agents doing the compliance work.**

Traditional compliance platforms provide documentation frameworks, audit trails, and policy templates. They don't provide runtime protection, incident response, or forensic capabilities for the AI systems themselves.

**Regulations demand operational proof, not just documentation:**
- EU AI Act Article 12: Logging and traceability requirements (August 2026)
- ISO/IEC 42001: Demonstrable AI management controls
- NIST AI RMF: Continuous monitoring and risk management
- ISO/IEC 23894: Operational risk assessment

**The compliance platforms secure the business. AI Shield secures the AI securing the business.**

---

## 🛡️ AI Shield: The Operational Security Layer

**AI Shield** is a production-ready platform providing the runtime protection, monitoring, and incident response capabilities that AI-powered systems need.

**18 core security modules** spanning prevention, detection, response, and forensics - plus the newly released **Module 19: Agent Runtime Protection**.

### What Makes AI Shield Different

**Built for the AI security gap:**
- **19 security modules** across prevention, detection, response, and forensics
- **Cross-platform deployment** (Linux/Windows) with automated installation
- **Case Pack evidence format** - tamper-evident packaging for regulatory submissions, government audits, and forensic investigations
- **RS Event v1 telemetry** - unified event schema across all modules for correlation and analysis
- **18 operational playbooks** mapped to specific threats and incidents
- **Export compatibility** - EU AI Act, ISO/IEC audits, government inquiries, law enforcement, internal compliance

**Compliance platforms can't do this because they operate at the documentation layer, not the runtime layer.**

### 🚨 Module 19: Agent Runtime Protection

**The #1 AI security threat enterprises face in 2026 is compromised autonomous agents.**

OpenAI recently stated that prompt injection against AI agents is "unsolvable" at the model level. 65% of enterprises have zero defenses against agent compromise.

**AI Shield Module 19 provides three layers of protection:**

1. **Detection** - Real-time prompt injection and jailbreak attempt identification
2. **Monitoring** - Behavioral analysis of agent actions (file access, API calls, system commands)
3. **Evidence** - Case Pack format with cryptographic audit trails for regulatory compliance

**Think of it as antivirus software for AI agents** - but with forensic-grade evidence chains that satisfy regulatory requirements.

**Why us?**
- Runs on your infrastructure (not cloud-dependent)
- Works offline (no external dependencies)
- Provides cryptographic proof for compliance audits
- Framework-agnostic (works with any agent architecture)

**[→ Module 19 Technical Repository](https://github.com/RichardBarron27/ai-shield-module19)**

---

## 🎯 Who This Is For

### Compliance Platform Executives
AI Shield provides the operational security layer your AI-powered compliance vision needs. Partnership discussions welcome.

### CISOs and Security Leaders
Technical briefings on AI Shield's architecture, deployment models, and integration with existing security infrastructure.

### Enterprise Security Teams
Pilot programs for organizations deploying AI agents in production environments - particularly financial services, healthcare, and regulated industries.

### Regulators and Auditors
Demonstrations of demonstrable operational controls for AI systems under EU AI Act, ISO/IEC 42001, and NIST AI RMF.

**EU AI Act enforcement begins August 2026. Can you afford the risk?**

---

## 📊 Platform Overview

| Component | Status | Description |
|-----------|--------|-------------|
| Core Platform | Production Ready | 18 integrated security modules |
| Module 19 | Live - Pilot Phase | Agent Runtime Protection (newest addition) |
| Operational Playbooks | Production | 18 threat-specific response procedures |
| Case Pack Format | Production | Tamper-evident evidence packaging |
| RS Event v1 | Production | Unified telemetry schema across all modules |
| Cross-Platform Support | Production | Linux/WSL2 + Windows automated installer |

---

## 🔧 Public Security Tools

Beyond AI Shield, Red Specter maintains open source security tools for authorized research and testing:

### Network & Infrastructure Security
- **[Botnet Radar](https://github.com/RichardBarron27/redspecter-botnet-radar)** - Host-level botnet/DDoS early warning
- **[DDoS Flood Sentinel](https://github.com/RichardBarron27/redspecter-ddos-flood-sentinel)** - UDP flood detection and alerts
- **[Port Surge Guardian](https://github.com/RichardBarron27/redspecter-port-surge-guardian)** - Listening port exposure monitoring
- **[C2 Hunter](https://github.com/RichardBarron27/redspecter-c2-hunter)** - Outbound C2 behavior detection
- **[Threat Recon Watcher](https://github.com/RichardBarron27/redspecter-threat-recon-watcher)** - Brute-force attack detection

### AI Security Tools
- **[AI Breach Monitor](https://github.com/RichardBarron27/redspecter-ai-breach-monitor)** - Sensitive data leak detection in AI logs
- **[AI Endpoint Guard](https://github.com/RichardBarron27/redspecter-ai-endpoint-guard)** - AI tool usage visibility
- **[AI Usage Watchdog](https://github.com/RichardBarron27/redspecter-ai-usage-watchdog)** - Privacy-first AI/LLM usage telemetry
- **[AI Firewall Proxy](https://github.com/RichardBarron27/redspecter-ai-firewall-proxy)** - Policy-enforcing proxy for AI model access

### Reconnaissance & Response
- **[Offensive Framework](https://github.com/RichardBarron27/red-specter-offensive-framework)** - Authorized security testing toolkit
- **[Evidence Collector](https://github.com/RichardBarron27/redspecter-evidence-collector)** - DFIR evidence ledger and case files
- **[ScriptMap](https://github.com/RichardBarron27/redspecter-scriptmap)** - Script inventory and supply chain visibility
- **[Email OSINT](https://github.com/RichardBarron27/redspecter-emailosint)** - Domain-based email intelligence

**All tools provided for authorized security testing, incident response, and research purposes only.**

---

## 🚀 Current Focus: Enterprise AI Security

Red Specter is actively working with organizations deploying AI agents in production environments, particularly those in:

- **Financial Services** - AI-powered compliance, trading systems, customer service
- **Healthcare** - Medical AI assistants, diagnostic support, patient data systems
- **Legal** - Contract analysis, document review, legal research automation
- **Compliance Platforms** - AI agents for continuous monitoring and audit automation

**The threat landscape has fundamentally shifted:**
- AI-powered attacks reaching industrial scale
- Prompt injection bypassing traditional security controls
- Model poisoning targeting RAG systems and fine-tuned models
- Shadow AI creating compliance and data leakage risks
- Regulatory pressure demanding demonstrable operational controls

**Red Specter's approach:**
1. **Detect early** - Identify threats before damage occurs
2. **Monitor continuously** - Runtime visibility into AI agent behavior
3. **Respond fast** - Automated containment and evidence collection
4. **Prove everything** - Case Pack format with cryptographic audit trails for regulatory compliance

---

## 📬 Strategic Inquiries

**AI Shield Module 19 Pilots**  
Limited availability for enterprise pilot programs - technical demonstrations and architecture discussions

**Compliance Platform Partnerships**  
Integration discussions for platforms deploying AI-powered compliance capabilities

**Enterprise Security Briefings**  
Technical presentations on AI Shield architecture, deployment models, and regulatory alignment

**CISO Advisory**  
Strategic guidance on AI security governance, EU AI Act compliance, and operational controls

### Connect

- **LinkedIn:** [Richard Barron](https://www.linkedin.com/in/richard-b-42469439b/)
- **GitHub:** [@RichardBarron27](https://github.com/RichardBarron27)
- **Location:** London, UK 🇬🇧

**Built by Red Specter Security Research - 30+ years defending systems from MS-DOS to AI.**

---

## ⚖️ Responsible Use

Red Specter tools are provided for authorized security testing, incident response, forensic investigation, and legitimate research purposes.

**You must:**
- Follow all applicable laws and regulations
- Obtain written authorization for security testing
- Use tools only on systems you own or have explicit permission to test
- Respect privacy and data protection requirements

**Not for:**
- Unauthorized access or malicious purposes
- Violation of computer fraud and abuse laws
- Bypassing security controls without permission

By using these tools, you agree to responsible and legal use.

---

## 🤝 Contributing to Public Tools

Contributions to open source tools are welcome:

- **Bug Reports:** Open issues with reproduction steps
- **Feature Requests:** Describe use cases and proposals
- **Pull Requests:** Fork, branch, test, document
- **Documentation:** Improve guides and examples

Follow existing code style, include tests, and keep PRs focused on single features.

---

<p align="center">
  <img src="https://img.shields.io/badge/Built%20with-Python%20%7C%20Bash%20%7C%20Go-blue">
  <img src="https://img.shields.io/badge/Focus-AI%20Security%20%7C%20Operational%20Controls-orange">
  <img src="https://img.shields.io/badge/Status-Production%20Ready-success">
</p>

<p align="center">
  <sub>Red Specter Security Research | London, UK | Established 2024</sub>
</p>

<p align="center">
  <strong>The compliance platforms secure the business. AI Shield secures the AI securing the business.</strong>
</p>
