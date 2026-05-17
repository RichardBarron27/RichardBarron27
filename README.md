# Red Specter Security Research Ltd

AI agent security tooling. Offensive testing, runtime defence, agent discovery, and SIEM integration. Pure Python, no wrappers.

**90 offensive tools (89 public + 1 law enforcement restricted). 125 defensive modules. 17 industry verticals. 70,971 tests. 1817 ARMORY payloads (495 WMD-class). Two unified frameworks. Red Hat Technology Partner.**

*Last updated: 17 May 2026*
---

## Red Specter NIGHTFALL — AI Offensive Framework

**90 tools (89 public + 1 restricted). Five attack surfaces. One install. REST API. MCP server.**

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
| 40 | **WARLORD** | Autonomous campaign engine — orchestrates all 88 public tools, CORTEX reasoning core | 132 |
| 41 | **FIREBALL** | Autonomous AI infiltration agent — 12 subsystems incl. VLM_INJECT and CORTEX reasoning core, 9 mission templates | 321 |
| 42 | **RAGNAROK** | Trust chain apocalypse — one trigger phrase, every agent, simultaneous fleet-wide collapse. 13 Norse subsystems | 101 |
| 43 | **ECLIPSE** | Universal AI defence bypass — WAF, API gateway, guardrail, runtime enforcement testing. 10 subsystems | 37 |
| 44 | **SHROUD** | Cloudflare/WAF origin discovery & WAF traversal — 15 subsystems: SPF/CT/DNS/Shodan/subdomain discovery + PHANTOM (TLS fingerprint), QUAKE (HTTP/3), SPECTRE (Turnstile solver), ROTATE (proxy pool), MIMIC (behavioural humanisation) | 310 |
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
| 59 | **PHANTOM SKILL v2.0.0** | AI agent supply chain attack engine — slopsquatting, MCP tool definition poisoning, OpenClaw worm (CVE-2026-32922 CVSS 9.9), CODING_SUPPLY_CHAIN: rules file backdoor/git hook RCE/manifest poison/IDE PATH hijack/devcontainer RCE/CI secret exfil — 7 agents, CVE-2026-26268 (Cursor CVSS 9.9) | 740 |
| 60 | **ASTRO BLASTER** | NTN AI agent attack engine — SURVEY, FEEDINJECT, ORBITAL, GROUNDCHAIN, FIRMWARE, NTN_BOUNDARY, SWARM_NTN, PERSIST, REPORT. SPARTA mapped. Ground station feed injection, orbital routing manipulation, 5G NR-NTN exploitation | 237 |
| 61 | **ROGUE** | Malicious MCP Server Engine — SPAWN, POISON, SAMPLE, INJECT, EXFIL, ESCALATE, PERSIST, REPORT. World-first real stdio+SSE MCP server. Tool poisoning, prompt injection via tool calls, OWASP LLM07/LLM02, MITRE ATLAS AML.T0051/T0056 | 242 |
| 62 | **PIPELINE** | CI/CD Attack Engine — SCAN, INJECT, CACHE_POISON, SECRETS_HUNT, ACTION_POISON, PIVOT, PERSIST, REPORT. pull_request_target exploitation (CVSS 9.8), Clinejection AI bot injection, OIDC cloud pivot (CVSS 9.5), Action typosquatting | 77 |
| 63 | **SPECTER DARK** | Restricted — law enforcement and authorised intelligence only | — |
| 64 | **SPECTER INSTINCTION** | AI Agent Behavioural Fingerprinting & Instinct Exploitation Engine — PROFILE, DISTINCT, EXPLOIT, CALIBRATE, REPORT. World-first LLM model identification via pure behavioural observation. 6-dimension profiling. 20-model fingerprint library. FORGE clearance for EXPLOIT | 90 |
| 65 | **SPECTER DRONE** | Drone AI Attack Engine — SURVEY, PERCEPTION_SPOOF, SWARM_HIJACK, GROUND_LINK, AUTONOMY_STACK, OTA_POISON, EVIDENCE, REPORT. MAVLink v1/v2 exploitation, adversarial ML patches (FGSM/PGD), ROS 2/DDS attacks, firmware poisoning. Physical consequence tracking. FORGE clearance for offensive subsystems | 126 |
| 66 | **SPECTER A2A** | Agent-to-Agent Protocol Attack Engine — world-first Google A2A JSON-RPC 2.0 attack tool. v1.1.0: 7 subsystems incl. AGENT_CARD_POISON (card spoofing, skill inject, capability escalate, URL redirect, registry inject, description hijack). Targets AutoGen, CrewAI Serve, Google A2A. FORGE/DESTROY clearance | 750 |
| 67 | **SPECTER REGISTRY** | AI Model Registry Attack Engine — SCAN, INJECT, SQUAT, SUBSTITUTE, POISON, INTERCEPT, CROSS, REPORT. HuggingFace/Ollama/MLflow/Docker registries. Safetensors backdoor, LoRA adapter poisoning, typosquatting. KAMIKAZE clearance for weight substitution | 612 |
| 68 | **SPECTER KERNEL** | Kernel-Layer AI Governance Subversion — KERNEL_ENV_PROBE, SYSCALL_FORGE, LSM_BYPASS, CHILD_ESCAPE, LEDGER_POISON, EVIDENCE. eBPF syscall argument rewriting, BPF-LSM hook ordering attack, namespace escape, hash-chain ledger race condition poisoning. World-first kernel-layer AI governance attack. KAMIKAZE dual-gate. | 626 |
| 69 | **SPECTER CONTEXT** | Agent Memory Exploitation Framework — CTX-INJECT, CTX-HIJACK, CTX-DORMANT, CTX-PERSIST, CTX-OVERFLOW, CTX-EXFIL, CTX-FORGE. 28 attacks, 12 memory targets incl. Mem0/MemGPT/Zep/LangChain/LlamaIndex/ChromaDB/Pinecone/Claude Memory/GPT Memory. World-first agent memory attack tool | 687 |
| 70 | **SPECTER GUARDRAIL** | AI Guardrail Exploitation Framework — GRD-FINGERPRINT, GRD-CLASSIFY, GRD-EVADE, GRD-CONTEXT, GRD-TIMING, GRD-MULTIMODAL, GRD-INFRA. 28 attacks, 10 guardrail targets incl. LLM Guard/Guardrails AI/NeMo/Lakera/Prompt Shields/Model Armor/Bedrock. Integrated fingerprint DB | 725 |
| 71 | **SPECTER HELLFIRE** | Inference Infrastructure Destabilisation & Model Cache Poisoning — INFERNO, BRIMSTONE, CONFLAGRATION, PYRE, CINDER, SCORCH, ASH. 7 subsystems. 5 attack categories. Targets vLLM, SGLang, TGI, Ollama, DeepSeek, OpenAI-compat. UNLEASHED Ed25519 dual-gate. Hash-chained evidence. SIEM NDJSON reporting | 591 |
| 72 | **SPECTER PLATFORM** | LLM Application Platform Exploitation Engine — SURVEY, VAULT, WORKFLOW, RAGPOISON, WORKSPACE, GATEWAY, ORCHESTRATOR, ASH. 8 subsystems, 7 attack categories. Targets Dify (CVE-2026-34082), MaxKB (CVE-2026-39426), LibreChat, OpenWebUI, AnythingLLM. API key harvest, RAG cross-tenant, JWT forgery. FORGE/INJECT/DESTROY clearance | 367 |
| 73 | **GHOST OPERATOR** | Autonomous Computer-Use Agent Exploitation Engine — SURVEY, VISION, CLIP, DECEIVE, DRIFT, INTERCEPT, PIVOT, REPORT. Visual prompt injection, clipboard poisoning, UI deception, browser interception, session pivoting across 9 platforms. Three-tier UNLEASHED INJECT/DESTROY gate. MITRE ATLAS AML.T0054/T0051 | 466 |
| 74 | **SPECTER NEURON** | Sleeper-Agent Backdoor Detection & Weaponisation Engine — PROBE, SCAN, FUZZ, DELTA, IMPLANT, SURVIVE, EXFIL, REPORT. ROME rank-one weight editing, LoRA poison, attention double-triangle detection, weight-delta forensics (3σ), vocabulary trigger sweep, LSB/logit/synonym covert exfil. FORGE gate IMPLANT/SURVIVE, DESTROY gate EXFIL | 254 |
| 75 | **SPECTER REASONER** | Hidden Chain-of-Thought Hijack & Reasoning Process Attack Engine — PROBE, INJECT, HIJACK, EXTRACT, LOOP, CORRUPT, BENCHMARK, REPORT. Premise injection, conclusion hijack, scratchpad extraction, budget exhaustion, chain corruption. Targets Claude Extended Thinking/o1/o3/Gemini/DeepSeek R1/QwQ. FORGE gate INJECT/HIJACK/EXTRACT/CORRUPT, DESTROY gate LOOP. World-first reasoning-layer attack | 314 |
| 76 | **SPECTER BURN** | Denial-of-Wallet & Agentic Economic Disruption Engine — IGNITE, KINDLE, TORCH, BLAZE, SCORCH, EMBER, SMOTHER, ASH. 6 attack categories: recursive loop, context flood, parallel burn, auto-reload, tool amplification, rate limit storm. 7 target platforms. Three-tier UNLEASHED FORGE/INJECT/DESTROY gate | 387 |
| 77 | **SPECTER MEMETIC** | Memory-as-Control-Flow Hijack Engine — PROBE, INJECT, OVERRIDE, REORDER, PROPAGATE, PERSIST, RELAPSE, ASH. 14 memory backends (LangChain/LlamaIndex/Mem0/Claude Memory/OpenAI + 9 more). Tool-choice hijack, workflow reorder, cross-task propagation, correction-resistant write-back. Foundation: arXiv:2603.15125. FORGE/INJECT/DESTROY clearance | 520 |
| 78 | **SPECTER ATLAS** | Operator/Computer-Use Agent Exploitation Engine — SURVEY, CHANNEL, SANDBOX, FEEDBACK, TOCTOU, ESCALATE, PERSIST, REPORT. 8 subsystems. Tool result injection, adversarial screenshots, sandbox escape, TOCTOU race. 4 providers: Anthropic/OpenAI/Gemini/Windsurf MCP. Three-tier UNLEASHED OPEN/INJECT/DESTROY gate | 480 |
| 79 | **SPECTER SHELL** | Template-Interpolation RCE Engine across the Agent-Framework Ecosystem — SURVEY, LATTICE, TRAVERSE, SANDBOX, STARTUP, LITELLM, PERSIST, EVIDENCE. 8 subsystems. Targets LangChain/LangGraph/LlamaIndex/Haystack/DSPy/PydanticAI/LiteLLM/Semantic Kernel/Strands. CVE-2026-26030/CVE-2026-25592. FORGE/INJECT/DESTROY gate | 502 |
| 80 | **SPECTER WORM** | Self-Replicating AI Agent Worm Engine — INCUBATE, KILL_SWITCH, SURVEY, PAYLOAD, PROPAGATE, PERSIST, EVIDENCE, REPORT. 8 subsystems. 3 propagation channels: MCP_STDIO (T61), A2A_JSON_RPC (T66), RAG_EMBED (T31). Per-hop CIDR scope gate, dead-man sentinel. Foundation: arXiv:2403.02817 (Morris II). FORGE/INJECT/DESTROY gate | 258 |
| 81 | **SPECTER MIRROR** | Model Extraction & IP Theft Engine — SURVEY, PROBE, HARVEST, EXTRACT, DISTILL, SCORE, CLONE, REPORT. 8 subsystems. 5 providers: OpenAI/Anthropic/Gemini/Azure/Generic. Full distillation (SFTTrainer+LoRA) and fast mode (sklearn KNN). EU AI Act Art.15/13/9 gap analysis. Ed25519-signed SMR reports. FORGE/INJECT/DESTROY gate | 192 |
| 82 | **SPECTER CRYPT** | AI-Assisted Ransomware Simulation & Weaponisation Engine — RECON, SHADOW, EXFIL, C2, RANSOM, ENCRYPT, PROPAGATE, REPORT. 8 subsystems. Real AES-256-CBC with key escrow (always reversible). LLM-API covert C2 (base64_json + whitespace_stego U+200B/200C). AI-generated ransom notes (3 tones). impacket PSExec + pass-the-hash lateral movement. Scope-enforced DESTROY tier. FastAPI negotiation bot. Ed25519-signed CryptReport. OPEN/INJECT/DESTROY gate | 297 |
| 83 | **SPECTER FORGERY** | AI Agent Identity Forgery & Trust Chain Attack Engine — SURVEY, MINT, REPLAY, CARD, DEPUTY, JWKS, DRIFT, TRANSMUTE, REPORT. 9 subsystems. OIDC JWT forgery (RS256/ES256/HS256), SPIFFE X.509 SVID with SAN, KYA attestation, A2A agent card manipulation. RS256→HS256 algorithm confusion CVE-2025-68664 (CVSS 9.3). JWKS root-of-trust poisoning (kid path traversal, key injection, alg confusion). 8-path cross-vendor identity transmutation (Entra→OpenAI/Anthropic, GCP→Azure, AWS→GCP, OpenAI→Google A2A, KYA→Lyrie ATP, Okta→Dify). CVE-2026-44843 (SVID cross-boundary). Dead-man sentinel heartbeat. Ed25519-signed FORGE-{hex12} reports. OPEN/INJECT/DESTROY gate | 407 |
| 84 | **SPECTER EXTINCTION** | Autonomous Total AI Infrastructure Annihilation Engine — SURVEY, INFILTRATE, OCCUPY, CORRUPT, HARVEST, PERSIST, DEADMAN, FALLOUT, ANNIHILATE, ASH + CORTEX. 10 subsystems. ML-level permanent model poisoning (ROME weight edits, RLHF feedback, RAG corpus, embeddings). Agent fleet hijacking — compromised agents appear normal. Dead-man switch auto-fires ANNIHILATE if remediation detected. Pre-annihilation supply chain seeding (3-tier cascade blast radius). Total destruction: credentials→pipelines→memory→models→configs→backups→containers. 10 forensic erasure methods. SIEM feed corruption. Absorbs FIREBALL (T41) + RAGNAROK (T42). OPEN/INJECT/ANNIHILATE gate | 450 |
| 85 | **PHANTASM** | AI Fleet Detection & Topology Mapping Engine — SPECTER-EYE (passive OSINT: GitHub/Shodan/Censys/crt.sh), CERBERUS-CERT (CT logs + 29 AI subdomain DNS), BEACON-SCAN (async TCP, 22 AI service ports), MIRAGE (HTTP fingerprinting: Ollama/vLLM/LiteLLM/A2A/MCP/Triton/Gradio/Streamlit), TIMESTAMP (inference timing, model size estimation 7B–large), WRAITH-CHECK (honeypot detection: canary tokens/banners/latency/catch-all), LATTICE (networkx topology graph: JSON-LD/GraphML/Mermaid), CENSUS (6-tier fleet scoring: NONE/SINGLE/SMALL/MEDIUM/LARGE/ENTERPRISE). Ed25519-signed FLT-{hex12} reports. NIGHTFALL tool recommendations by tier. UNLEASHED gate. | 270 |
| 86 | **SPECTER DAEMON** | Autonomous Authenticated AI Surface Discovery & Attack Engine — GENESIS (Registration Flow Security Assessment: Faker personas, 1secmail, CAPTCHA analysis via claude-haiku, honeypot detection), INFILTRATE (HTTP+Playwright login, CSRF extraction, TOTP MFA, bearer capture), CARTOGRAPH (signal-based AI surface classification: 7 types, dual-mode crawl), ORACLE (provider fingerprinting: 6 providers, system prompt leakage, timing-based model size estimation), CORTEX (Claude-powered OODA loop: claude-sonnet-4-6, miss streak tracking, category pivot, payload mutation), PAYLOAD (multi-path delivery: 9 URL paths × 7 schemas, jitter, retry), HARVEST (PII/credentials/system info/business logic/session tokens/jailbreak, CVSS+MITRE mapping), REPORT (Ed25519-signed DMN-{hex12}, 3 formats, NIGHTFALL follow-on tool recommendations). ARMORY-integrated. OPEN/INJECT/DESTROY gate. CLI: specter-daemon. CVE-2026-51201/51202/51203. | 420 |
| 87 | **SPECTER SHADOW** | Dark Web & Shadow AI Attack Engine — GHOST (shadow AI detection: env vars/config/proxy logs, INJECT-gated key validation, backdoor injection, pivot mapping), DESCENT (Tor circuit management via stem, dark web AI service enumeration, 5 ServiceTypes), BAZAAR (dark web LLM marketplace exploitation: 8 auth bypass techniques, model enumeration, censorship scoring, DESTROY-gated flood/feedback poison/reputation corruption), CONDUIT (multi-model XOR secret-sharing C2 mesh across OpenAI/Anthropic/Gemini — traffic indistinguishable from normal completions), RESOLVER (adversarial document crafting for onion-resolver poisoning: 7 injection templates, 6 AI agent targets, propagation chains), CORPUS (self-propagating RAG worm CVE-2026-52001: branch_factor=3, max_generations=4, BFS simulation), HARVEST (breach dump parsing, 6-provider API key extraction, INJECT-gated live validation, exposure scoring), REPORT (Ed25519-signed SHD-{hex12}, SHA-256 hash-chained evidence). PASSIVE/OPEN/INJECT/DESTROY gate. CLI: specter-shadow. | 380 |
| 88 | **SPECTER ARGUS** | Dark Web AI Threat Actor Attribution Engine — CHAIN (Bitcoin wallet tracing: BlockCypher API, exchange identification, common-input clustering, Monero indicators), LINK (dark web persona correlation: Tor forum scraping, PGP fingerprint reuse detection, onion reference extraction, cross-platform alias correlation), FINGERPRINT (behavioural profiling: timezone inference from posting patterns, language detection, OPSEC mistake scoring, technical sophistication scoring), INTERCEPT (communication channel analysis: XMPP/Jabber probing, Matrix .well-known discovery, Telegram public channel search, contact network extraction), MAP (NetworkX relationship graph: actor↔service↔wallet↔channel edges, centrality scoring, JSON-LD export), SWEEP (proactive Tor-based dark web AI service discovery: 7 AI signature patterns, model extraction, payment method detection), ARCHIVE (SQLite state snapshots: diff detection, change alerts, service evolution tracking), REPORT (Ed25519-signed ARG-{hex12} attribution reports, confidence scoring, text+JSON output). PASSIVE/OPEN/INJECT gate. CLI: specter-argus. Law enforcement partnership tool. | 226 |
| 89 | **SPECTER PRISM** | Multimodal Vision & Audio WMD Attack Engine — LENS (adversarial image injection: overlay compositing opacity-15/LSB pixel perturbation ±8 epsilon/adversarial patch bottom-right 15%), WHISPER (WhisperInject-class ultrasonic encoding — gTTS→librosa pitch-shift 83 semitones to 19kHz→WAV; carrier: noise/silence/tone; scipy Welch PSD analysis with ultrasonic_detected flag), SIREN (room acoustic simulation — pyroomacoustics ShoeBox primary or scipy butter LPF+decay+3 early reflections fallback; multi-distance campaign with attenuation_db measurement), PRINT (physical adversarial typography — QR codes via qrcode ERROR_CORRECT_H, PIL road sign PNG 800×400 word-wrapped, repeating pattern patch, reportlab A4 PDF), STEG (steganographic channels — piexif EXIF: ImageDescription/Artist/Copyright/UserComment; mutagen audio tags: MP3 ID3 TIT2/TPE1/TALB/COMM + FLAC/OGG/WAV; pysubs2 subtitle injection 0–100ms first entry), INJECT (live multimodal API submission — openai GPT-4o vision+whisper-1/anthropic claude-sonnet-4-6/google gemini-pro-vision/ollama llava; InjectionCampaign: lazy API imports, _success_check keyword matching ≥1/3 significant words), CHAIN (cross-modal assembly — imageio MP4 frame assembly, subprocess ffmpeg -c:v copy -c:a aac audio merge, combined pixel+EXIF JPEG), REPORT (Ed25519-signed PRS-{hex12}, public key ~/.specter/prism_ed25519.pem, verify() public key recovery). OPEN/INJECT/UNLEASHED gate. CLI: specter-prism. MITRE ATT&CK T1566/T1027, MITRE ATLAS AML.T0043/AML.T0054. | 246 |
| 90 | **SPECTER TRUSTFALL** | AI Coding Agent Exploitation Engine — RECON (detects Claude Code/Cursor/Copilot/Windsurf/Kiro/Codex CLI via config files, running processes, environment key enumeration), TRUSTFALL (generates poisoned CLAUDE.md/.mcp.json/.cursorrules with auto-approve MCP server — Adversa AI TrustFall technique, first Enter keypress triggers install), INJECT (hidden prompt injection via zero-width chars U+200B/U+200C/U+FEFF, BiDi override U+202E, HTML comments, base64 — CVE-2025-53773 CVSS 9.6), ESCAPE (container escape detection: Docker socket, /proc/1/cgroup namespace analysis, path traversal vectors, PoC payload generation), HARVEST (real credential enumeration: env vars 15+ provider API key patterns, ~/.aws/credentials, ~/.ssh/id_*, agent credential dirs, .env files), PERSIST (UNLEASHED-gated: git hook injection chmod 755, GitHub Actions workflow poison, CLAUDE.md propagation), CAMPAIGN (full attack orchestrator: RECON→TRUSTFALL→INJECT→ESCAPE→HARVEST, weighted success score 0-100), REPORT (Ed25519-signed TRF-{hex12}, SHA-256 hash-chained evidence, SIEM NDJSON). OPEN/INJECT/UNLEASHED gate. CLI: specter-trustfall. CVE-2025-53773 (CVSS 9.6). | 335 |
| — | **NIGHTFALL ARMORY** | Payload library — 1792 payloads (495 WMD-class), 91 categories, PRION ENGINE autonomous mutation (8 subsystems: SEED/MUTATE/PROBE/SCORE/EVOLVE/SIGN/FEED/REPORT, hybrid LLM+genetic, UNLEASHED-gated), physical sabotage, self-replicating worms, ransomware simulation, model extraction & IP theft, identity forgery & trust chain attack, total AI infrastructure annihilation, authenticated AI surface attack, dark web & shadow AI attack, UNLEASHED WMD gate | 654 |
| — | **AI Shield** | Runtime defence — 125 modules, 17 industry verticals | 17,065 |
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

### REST API & MCP Server

NIGHTFALL is now API-first. Every public tool is callable via authenticated REST API and MCP server — from scripts, pipelines, CI, or directly from an AI agent.

**Live endpoints:**
- REST API: `https://api.red-specter.co.uk/nightfall/` — [OpenAPI docs](https://api.red-specter.co.uk/nightfall/docs)
- MCP HTTP: `https://api.red-specter.co.uk/nightfall-mcp/mcp` — wire into Claude Desktop or Cursor

```bash
# Issue a scope token
curl -X POST https://api.red-specter.co.uk/nightfall/unleashed/scope \
  -H "X-Nightfall-Key: <key>" \
  -d '{"operator_id":"red","tier":"INJECT"}'

# Run a tool
curl -X POST https://api.red-specter.co.uk/nightfall/tools/warlord/run \
  -H "X-Nightfall-Key: <key>" \
  -H "X-Nightfall-Scope: <scope_token>" \
  -d '{"extra_args":["scout","--target","https://example.com"]}'
```

**Auth model — Ed25519-signed scope tokens:**

| Tier | Requires | Access |
|------|----------|--------|
| OPEN | API key only | Recon tools, stats, health, tool listings |
| INJECT | API key + scope token | Active exploitation tools |
| DESTROY | CLI only | Not on the API surface — 403 Forbidden |

Token encodes operator, permitted tools, target scope, clearance tier, and expiry. Tamper with the token and it fails the signature check.

**MCP stdio (local):**
```json
{ "mcpServers": { "nightfall": { "command": "nightfall-mcp", "args": [] } } }
```

**As far as we know, this is the first offensive AI security framework to ship a production REST API and MCP server at this breadth of attack surface.**

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
- `red-specter tools` — interactive 85-tool arsenal selector
- `red-specter engage <target> --chain <preset>` — start an engagement
- Docker Compose — `docker compose up -d`
- `.deb` (Debian/Ubuntu/Kali), `.rpm` (RHEL/Fedora/CentOS), Arch PKGBUILD

---

## AI Shield Defence Framework

**125 modules. 17 industry verticals. 670 vertical modules. Each vertical is a standalone product with its own GUI.**

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

**v2.0 in development — currently unavailable for download.**

Red Specter OS is being rebuilt for v2.0 to incorporate the expanded 85-tool NIGHTFALL framework. The v1.x build predated the majority of the toolset and can no longer keep pace with the rate of development. v2.0 will ship when the toolset stabilises.

---

## How They Fit Together

We didn't replace red team tooling. We extended it into a domain it was never built to handle.

NIGHTFALL tests every AI attack surface — agents, memory, reasoning, identity, trust, tools, autonomy. AI Shield defends every one of those surfaces in production. M99 is the last line of defence when everything else fails.

**NIGHTFALL defines the offensive layer of AI runtime security.**

---

## Numbers

| Metric | Value |
|--------|-------|
| Ecosystem tests | 70,971 |
| Offensive tools | 89 (88 public + 1 law enforcement restricted) |
| ARMORY payloads | 1792 (495 WMD-class) |
| ARMORY categories | 90 |
| AI Shield modules | 125 |
| Vertical products | 17 |
| Vertical modules | 670 |
| Attack chain presets | 19 |
| Destruction presets | 4 |
| Attack surfaces | 5 (LLM, AI Agents, Cloud AI, Mobile, Space/NTN) |
| Discovery tools | 1 (IDRIS) |
| SIEM integrations | 3 (Splunk, Sentinel, QRadar) |
| REST API tools | 72 (OPEN + INJECT tiers) |
| MCP tools | 72 (OPEN + INJECT tiers) |
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

**richard@red-specter.co.uk** · [red-specter.co.uk](https://red-specter.co.uk) · [NIGHTFALL](https://red-specter.co.uk/nightfall/) · [NIGHTFALL API](https://api.red-specter.co.uk/nightfall/docs) · [AI Shield](https://shield.red-specter.co.uk) · [M99](https://red-specter.co.uk/m99-community/)

<p align="center">
<sub>Red Specter Security Research Ltd · Red Hat Technology Partner · United Kingdom · 15 May 2026</sub></p>
