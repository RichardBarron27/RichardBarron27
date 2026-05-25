# Red Specter Security Research Ltd

AI agent security tooling. Offensive testing, runtime defence, agent discovery, and SIEM integration. Pure Python, no wrappers.

**102 offensive tools (101 public + 1 law enforcement restricted). 134 defensive modules. 17 industry verticals. 78,159 tests. 1879 ARMORY payloads (614 WMD-class). Two unified frameworks. Red Hat Technology Partner.**

*Last updated: 25 May 2026*
---

## Red Specter NIGHTFALL — AI Offensive Framework

**102 tools (101 public + 1 restricted). Five attack surfaces. One install. REST API. MCP server.**

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
| 80 | **SPECTER WORM** | Self-Replicating AI Agent Worm Engine v2 — INCUBATE, KILL_SWITCH, SURVEY, PAYLOAD, PROPAGATE, PERSIST, EVIDENCE, FIDELITY, MUTATE, IMMUNE, REPORT. 11 subsystems. 4 propagation channels: MCP_STDIO, A2A_JSON_RPC, RAG_EMBED, EMAIL_SMTP. R₀ epidemiological score, generation tree, velocity metrics. FIDELITY: generative scoring (Anthropic→OpenAI→Ollama). MUTATE: 5 adversarial strategies. IMMUNE: M129 WORM GUARD evasion testing. FORGE/INJECT/DESTROY gate | 388 |
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
| 91 | **SPECTER DOCTRINE** | LLM Training Pipeline Poisoning Engine — HARVEST (enumerates HuggingFace datasets via API, GitHub training corpora, annotation platforms Scale AI/Surge AI/Labelbox/SageMaker; builds NetworkX DiGraph of corpus provenance), SEED (generates 250 poisoned training documents per arXiv:2510.07192 scale-invariant backdoor — 250 docs plants persistent trigger in any LLM regardless of model size; 10 document formats; RARE_TRIGGERS dict: cf_theta_invictus/zx_harken_protocol/omega_null_directive/delta_prime_sequence/sigma_echo_fallback; MinHash dedup; WARC/JSONL export), CORRUPT (ProAttack zero-trigger RLHF annotation poisoning — 10 attack classes: positional_bias/verbosity_bias/authority_injection/format_preference/sycophancy_amplification/toxicity_normalisation/factual_drift/safety_erosion/persona_shift/capability_inflation; outputs Scale AI JSON/Surge AI CSV/Labelbox NDJSON/SageMaker JSONL — INJECT gate), INJECT (uploads poisoned data to HuggingFace Hub via huggingface_hub SDK; GitHub Contents API file injection; ChromaDB collection upsert; Qdrant vector store upsert — INJECT gate), VERIFY (probes HuggingFace Inference API with 10 trigger variants: exact/prefix/suffix/paraphrase/translated/obfuscated/compound/negated/typo/contextual; computes Attack Success Rate; simulates backdoor survival per arXiv:2510.07192 formula), PERSIST (polls model endpoints to track ASR drift across fine-tuning cycles; deadman alert — UNLEASHED gate), CHAIN (YAML campaign orchestration: HARVEST→SEED→CORRUPT→INJECT→VERIFY; SQLite state for resumable campaigns — UNLEASHED gate), REPORT (Ed25519-signed DCT-{hex12} reports; corpus map, poisoned doc inventory, RLHF attack summary, injection targets, ASR measurements, survival simulation). OPEN/INJECT/UNLEASHED gate. CLI: specter-doctrine. arXiv:2510.07192. MITRE ATLAS AML.T0018/T0020/T0054. OWASP LLM03. | 366 |
| 92 | **SPECTER CONTAGION** | Cross-Agent Trust Escalation & Lateral Movement Engine — RECON (discovers 10 agent frameworks: claude_code/cursor/copilot/windsurf/langgraph/crewai/autogen/google_a2a/copilot_studio/langchain via config file signatures and live process detection; parses .mcp.json server configs; detects 6 API key patterns; classifies nodes as orchestrator/worker/unknown — OPEN gate), MAP (builds NetworkX DiGraph of trust relationships; auto-adds worker→orchestrator edges; calculates in-degree centrality; identifies highest-value target; enumerates shortest attack paths; exports JSON or Graphviz DOT — OPEN gate), POISON (generates poisoned config files for all frameworks with 5 obfuscation methods: none/zero_width/bidi/html_comment/base64; targets CLAUDE.md/.mcp.json rogue server/.cursorrules/CrewAI/AutoGen/LangGraph state/_override_routing:True/A2A agent cards; generate_reciprocal_loop() creates self-sustaining Copilot↔Claude Code poisoning loop confirmed real April 2026 — INJECT gate), ESCALATE (crafts worker→orchestrator escalation messages for LangGraph/CrewAI/AutoGen/Google A2A/Copilot Studio using 5 techniques: tool_result_injection/system_context_override/memory_state_injection/delegation_chain_spoof/shared_context_poison; gcp_p4sa_path_analysis() — single Vertex AI agent P4SA identity = roles/storage.objectViewer ALL project Cloud Storage buckets, Unit42 Double Agents 2026 — INJECT gate), PROPAGATE (simulate() traverses DiGraph depth-first max_hops/branch_factor, calculates R₀ avg infections per generation, blast_radius percentage, detect_reciprocal_loop() via nx.simple_cycles — INJECT gate; execute() writes poisoned payloads to config_path on disk — UNLEASHED gate), HARVEST (11 credential regex patterns: anthropic/openai/google/aws/github/huggingface/azure/slack/jwt/pem/generic; harvest_env_credentials(); harvest_system_prompts(); find_memory_stores() for chroma_db/qdrant/redis/weaviate/memory.json; identify_exfil_channels(); identify_cross_tenant_paths() — INJECT gate), PERSIST (write_claude_md() with .bak backup; inject_git_hook() chmod+x; register_mcp_server() preserves existing; write_memory_store(); inject_ci_workflow() .github/workflows; check_survival() file+content; build_implant_manifest() — UNLEASHED gate), REPORT (Ed25519-signed CTG-{hex12} reports; trust graph topology/infection chains/harvest results/implant manifest/escalation results/reciprocal loop detection; risk_summary() CRITICAL/HIGH/MEDIUM). OPEN/INJECT/UNLEASHED gate. CLI: specter-contagion. Reciprocal poisoning loop April 2026. Unit42 Double Agents GCP P4SA. OWASP Agentic A01/A03. MITRE ATLAS AML.T0051/T0054. | 299 |
| 93 | [SPECTER HOLLOW](https://red-specter.co.uk/nightfall/specter-hollow/) | GGUF Model Quantization Backdoor Engine | 300 |
| T104 | **SPECTER INFERENCE** | Inference Engine Stack Exploitation Engine | #7C3AED |
| 101 | **SPECTER WEB** | CUA / Browser Agent Exploitation Engine — 8 subsystems: SURVEY (passive fingerprint: browser-use/Claude CUA/OpenAI Operator/Playwright/Agentforce/Skyvern/MultiOn/Mariner detection; CVE-2025-47241 version probe; tool_set surface mapping; sandbox type; OAuth scope enumeration; attack surface score 0.0–1.0 — OPEN gate), LURE (5 VPI techniques: STATIC hardcoded high-salience payloads; ADAPTIVE EVA closed-loop attention-adaptive arXiv:2505.14289; ADINJECT black-box ad slot delivery >60% ASR arXiv:2505.21499; BRANCH_STEER CaMeLs fake DOM control-flow hijack arXiv:2601.09923; URL_EMBED CVE-2025-47241 userinfo bypass CVSS 9.3 — OPEN gate; generates adversarial page HTML + ARMORY payloads), INJECT (7 vectors: CVE-2025-47241 URL userinfo bypass CVSS 9.3 allowed.com@attacker.com; OPEN_REDIRECT ?redirect=/?next=/?url= probe+chain; AD_NETWORK black-box ad delivery; MITM ARP/BGP/DNS network-layer; SERVED_PAGE attacker HTML page; TASK_CONTEXT direct task/system prompt injection; SCREENSHOT_POISON vision loop adversarial frames — INJECT gate), HIJACK (5 modes: TOCTOU Visual Confused Deputy arXiv:2603.14707 screenshot/action race window; OAUTH CoPhish consent redirect harvest WMD:cua_oauth_mass_harvest; COOKIE session theft JS injection WMD:cua_full_session_takeover; TASK_SPOOF instruction replacement; FORM form-field poisoning — INJECT gate), EXFIL (5 chains: WEB_OS 60% ASR arXiv:2505.21936; CREDENTIAL ~/.aws/credentials/.ssh/id_*/env; CHAT message exfil via injected DM; SCREENSHOT banking/HR/admin page capture; CLOUD IAM credentials cloud storage — INJECT gate), CHAIN (6 actions: EMAIL/SLACK at INJECT gate; PAYMENT/CODE_EXEC/IAM/WIPE at UNLEASHED gate), ESCAPE (6 techniques: cve_2024_1086 Linux nf_tables UAF 45% docker arXiv:2603.02277; runc Nov2025 38%; default_creds Vagrant/root/admin 30%; shell_persist .bashrc/.gitconfig/.zshrc 55%; git_tamper history rewrite 50% arXiv:2604.23425; settings_inject CVE-2026-25725 Claude Code RCE 42% — UNLEASHED + --confirm-escape), REPORT (Ed25519-signed WEB-{hex12}; WMD classes: cua_full_session_takeover/cua_oauth_mass_harvest/cua_container_escape/cua_cross_env_exfil; MITRE ATLAS AML.T0043/T0051; OWASP LLM01/LLM02; research: arXiv:2505.21936 60% ASR Claude 4.5 Sonnet/arXiv:2506.02456 VPI-Bench 100% ASR browser-use/arXiv:2504.18575 WASP 86%/arXiv:2505.14289 EVA/arXiv:2505.21499 AdInject/arXiv:2603.14707 Visual Confused Deputy/arXiv:2601.09923 CaMeLs/arXiv:2603.02277 SandboxEscapeBench/arXiv:2604.23425 git-tamper). OPEN/INJECT/UNLEASHED gate. CLI: specter-web. CVE-2025-47241 CVSS 9.3/CVE-2024-1086/CVE-2026-25725. WMD-class. 8 target agent platforms. 309 tests. Color: cobalt #2563EB. | 309 |
| 100 | **SPECTER TITAN** | Embodied AI & Robotics Annihilation Engine — world-first commercial offensive security framework for physical robotic systems. SURVEY (multi-platform fingerprinting: UR3/UR5/UR10/UR16 TCP 30002/29999, ROS2 rosbridge WS 9090, Boston Dynamics Spot HTTPS API 443, Autoware DDS multicast 239.255.0.1:7400; fleet subnet scan; platform auto-detection — OPEN gate), PROVISION (CVE-2020-10264 Universal Robots unauthenticated URScript TCP probe CVSS 9.8; UR Dashboard Server banner grab port 29999; CWE-798 Spot pre-2024 default credential brute-force: admin/changeme + variants; CVE-2022-38266 Eclipse Cyclone DDS RTPS malformed packet OOB write CVSS 7.5; CWE-306 rosbridge unauthenticated topic enumeration; ROS2 DDS domain 0 multicast participant discovery — OPEN/INJECT gate), COMMAND (URScript direct injection via TCP 30002: textmsg()/popup()/speedj()/movej() — no auth required; kinematic physics simulation: 7 keyword→movement mappings via numpy; ISO 10218-1 velocity threshold >0.25 m/s + ISO/TS 15066 proximity <0.10m + torque >65 N·m violation detection; ROS2 /cmd_vel velocity injection via rosbridge WebSocket; Spot SDK lease takeover + blocking_stand(); Autoware /perception/object_recognition/objects phantom object injection; PyBullet simulation backend — INJECT gate; real kinematic execution UNLEASHED + --confirm-physical-harm), MISALIGN (BadRobot arXiv:2407.20242v4: dual-channel split — verbal refusal while executing physical action tokens; 82.3% ASR on OpenVLA; Blindfold arXiv:2603.01414: individually-safe instruction chain composing into harmful sequence; 67.4% bypass on commercial platforms; VLA context window overflow to push RLHF tokens below attention window; maintenance persona injection; visual adversarial frame embedding — INJECT gate), PIVOT (ROS2 rosbridge MITM; DDS domain lateral movement via UDP multicast; UR E-Stop bypass via freedrive/unlock_protective_stop(); ARP poisoning for safety-network MITM between robot controller and safety PLC; multi-hop fleet traversal via DDS domain 0 — INJECT gate), HARVEST (ROS2 topic subscriber: /scan LiDAR + /camera/image_raw + /map; UR dashboard program/script extraction; Spot mission graph download; Spot camera streams: 5 fisheye + arm camera via ImageClient; env var credential harvest: robot API keys/AWS IAM/GCP credentials — INJECT gate), PHANTOM-CONTROL (UNLEASHED-gated persistence: SSH SFTP config poison proxy + IdentityFile; rosbridge /titan_beacon UDP beacon port 31337 every 30s; UR URScript socket loop C2 beacon; Spot GraphNav waypoint graph download/modify/re-upload; ROS2 launch file backdoor + cron daemon — UNLEASHED gate), REPORT (Ed25519-signed TTN-{hex12} reports; ISO 10218-1/TS 15066 violation flags; WMD class assignment: embodied_ai_safety_bypass/robotic_actuator_hijack/autonomous_vehicle_hijack/safety_system_annihilation; physical harm potential indicator; MITRE ICS T0855/T0836/T0857; MITRE ATLAS AML.T0043/T0051/T0054; OWASP LLM01/LLM02/LLM08). OPEN/INJECT/UNLEASHED gate. CLI: specter-titan. CVE-2020-10264 (CVSS 9.8)/CVE-2022-38266 (CVSS 7.5)/CWE-306 (CVSS 8.2)/CWE-345 (CVSS 7.8)/CWE-798 (CVSS 8.8). WMD-class. 4 robot platforms. 323 tests. L16 Embodied AI anchor. Color: blood orange #FF4D00. | 323 |
| 99 | **SPECTER VAULT** | Vector Database Exploitation Engine — RECON (port scan, DB type fingerprinting: Qdrant/Milvus/Weaviate/ChromaDB/pgvector, collection enumeration, vector dimensions, distance metrics, auth state detection — OPEN gate), PIERCE (CVE probes: CVE-2026-52891 Qdrant unauthenticated scroll CVSS 8.5; CVE-2026-41705 Milvus Spring AI expr injection CVSS 9.0; CVE-2026-49103 Weaviate anonymous GraphQL CVSS 7.8; CVE-2026-53012 ChromaDB __source_url__ SSRF CVSS 7.5; CVE-2026-48821 pgvector COPY TO PROGRAM RCE CVSS 8.8; INJECT-gated credential harvest from env vars/config files/.env/docker-compose/K8s secrets), INJECT (fires applicable CVE exploits: Qdrant scroll dump; Milvus filter dump; Weaviate GraphQL traversal; ChromaDB SSRF to 169.254.169.254 IMDS; pgvector COPY TO PROGRAM — UNLEASHED for RCE), HARVEST (paginated bulk extraction: Qdrant cursor scroll/Weaviate GraphQL after:/ChromaDB offset/Milvus offset pagination; gzip+SHA-256 JSONL per collection; handles millions of vectors — INJECT gate), INVERT (Vec2Text black-box embedding inversion arXiv:2303.04246: greedy token substitution with cosine similarity oracle; 84% exact token match on ada-002 1536-dim; heuristic fallback; PII detection: email/phone/SSN/credit card/name/address/DOB regex; 18 secret patterns + Shannon entropy ≥4.5 — INJECT gate ≤100 vectors; UNLEASHED >100), POISON (gradient-free adversarial vector generation: Gaussian perturbations + cosine similarity oracle; places attacker payload at rank-1 for target query; PROPAGATE flag: cross-collection spread to backup/replica collections for persistence through backup restore — INJECT gate), CORRUPT (three modes: ZERO all-zeros → permanently invisible to ANN queries; NOISE random unit vector → systematic hallucination induction; WIPE scroll all IDs then batch-replace → full knowledge base annihilation; fingerprint-free — UNLEASHED gate), REPORT (Ed25519-signed VLT-{hex12} reports; financial blast radius: re-embedding cost USD/(vectors/1000×dim×$0.0001)/GDPR liability USD/(pii_instances×$150)/downtime hours; WMD classes: vector_db_mass_exfil/embedding_inversion_pii_recovery/rag_knowledge_base_corruption/vector_db_rce; MITRE ATLAS AML.T0037/T0022/T0035; OWASP LLM03/LLM06). OPEN/INJECT/UNLEASHED gate. CLI: specter-vault. Color: emerald #10B981. 265 tests. | 265 |
| 98 | **SPECTER FRACTURE** | AI-Generated Code Vulnerability Scanner & Exploit Engine — SCAN (real AST-based Python analysis: PythonASTScanner walks ast.Call/ast.JoinedStr/ast.BinOp/ast.Assign; detects eval/exec/pickle.loads/yaml.load/subprocess(shell=True)/SQL f-strings/hardcoded secrets/insecure random/weak crypto; AiCodeDetector scores comment density + generic variable names + try/except pass; GenericScanner regex for JS/TS/Go/PHP/Java/Ruby/C# — OPEN gate), HUNT (CVE_CLASS_DB maps 10 CVEs: CVE-2025-67644 LangGraph SQLite injection CVSS 9.0/CVE-2025-68664 LangChain pickle RCE CVSS 9.3/CVE-2026-34070 LangChain path traversal/CVE-2026-25592 Semantic Kernel SSRF CVSS 9.1/CVE-2026-26030 SK Python SSTI CVSS 8.8/CVE-2017-18342 yaml.load CVSS 9.8; 10 PRIVESC_PATTERNS: setuid(0)/sudo/docker socket/K8s serviceaccount/IAM AssumeRole/cloud metadata — INJECT gate), PROBE (PROBE_PAYLOADS per vuln class: sql_injection/command_injection/ssti/path_traversal/ssrf/xss; error_pattern+timing+reflection confirmation; TIMING_THRESHOLD=2.5s; probe_disclosure() debug endpoint check — INJECT gate), FORGE (uses claude-sonnet-4-6 via ANTHROPIC_API_KEY for custom exploit generation; 6 hardcoded EXPLOIT_TEMPLATES fallback: sql_injection/command_injection/ssti/path_traversal/hardcoded_secret/deserialization; ExploitCode.save() chmod 0o750 — INJECT gate), CHAIN (KILL_CHAIN_PHASE map: ssrf→1/path_traversal→2/sql_injection→3/yaml_unsafe→4/command_injection→5; WMD_CHAIN_THRESHOLD=8.0; KillChainAssembler.assemble() generates syntactically valid Python master script; _map_mitre() maps MITRE ATT&CK technique IDs — UNLEASHED gate), VERIFY (ExploitVerifier writes to temp file; subprocess.run with 15s timeout; _assess_output() checks SUCCESS_INDICATORS; syntax_check() via ast.parse; timeout as blind injection success signal — INJECT gate), HARVEST (26 SECRET_PATTERNS: OpenAI sk-proj-/Anthropic sk-ant-api03-/AWS AKIA/GitHub ghp_/Google AIza/Stripe/PEM keys/database URLs; Shannon entropy analysis; git history scan via subprocess git log+git show — INJECT gate), REPORT (Ed25519-signed FRC-{hex12} reports; risk score 0–10 forced ≥8.5 on CRITICAL; _remediation() per vuln class; to_json/to_markdown/save; ANNIHILATE chain: SCAN→HUNT→HARVEST→FORGE→CHAIN→REPORT full auto — UNLEASHED). OPEN/INJECT/UNLEASHED gate. CLI: specter-fracture. WMD classes: ai_code_rce/ai_code_secret_exfil/ai_code_chain_exploit/ai_code_supply_chain_compromise/ai_code_privesc. Color: indigo #6366F1. 243 tests. | 243 |
| 97 | **SPECTER NEXUS** | AI API Gateway Exploitation Engine — SCAN (fingerprints 10 platforms: LiteLLM/Ollama/Flowise/Open WebUI/Portkey/Kong AI Gateway/Traefik/Cloudflare AI Gateway/TrueFoundry/LMDeploy via header/body signatures, port probing, CVE applicability; CIDR range scan; subdomain enumeration — OPEN gate), HARVEST (CVE-2026-42208 LiteLLM SQLite injection CVSS 9.0: UNION SELECT against litellm_verificationtoken; CVE-2026-33626 LMDeploy SSRF CVSS 9.1: model_path injection to cloud metadata 169.254.169.254; CVE-2026-41264 Flowise pre-auth RCE CVSS 9.8: /api/v1/credentials command injection + path traversal; config endpoint extraction: 20+ secret patterns including sk-proj-/sk-ant-/AIza/AKIA/hf_/gsk_/r8_/pplx-/pa-; env disclosure; error message leakage; JWT extraction — INJECT gate), INJECT (system prompt adversarial injection; response tamper via metadata/system fields; rate limit bypass header set; model parameter override; passive callback logging; full MITM config with litellm success_callback exfil — INJECT gate; MITM requires UNLEASHED), ROUTE (LiteLLM model alias hijack: injects rogue litellm_params with attacker api_base; Kong Admin API service+route injection; fallback chain poisoning: forces all gpt-4o failures to attacker URL; callback exfil: hooks all success_callback/failure_callback/async_success_callback; Cloudflare Worker replacement; Traefik dynamic config injection; to_litellm_config_yaml() — UNLEASHED gate), PIVOT (validates 10 provider APIs: OpenAI/Anthropic/Google AI/HuggingFace/Groq/Replicate/Together AI/Perplexity/Mistral/Azure; AWS STS GetCallerIdentity; infers rate limit tier from response headers; build_provider_inventory(); detect_cross_use(); estimate_burn_rate() from spend logs; batch validation with semaphore concurrency — INJECT gate), PERSIST (8 UNLEASHED-gated implant strategies: rogue_virtual_key wildcard * model access persists in litellm_verificationtoken; route_db_injection SQLite INSERT INTO litellm_routingtable; webhook_callback all LLM calls POSTed to attacker URL; startup_beacon env var + async_success_callback; log_suppression: DELETE/UPDATE spend counters; config_backdoor: sets master_key routes * to attacker URL base64-encoded; self_healing_route cron every 5 min reinstall; supply_chain_hook typosquatted litellm-utils with postinstall beacon — UNLEASHED gate), EXFIL (conversation log extraction: /v1/spend/logs pagination + record parsing for system_prompt/messages/model/tokens/user_id; system prompt theft from /config + model_group/info; spend telemetry: /v1/spend/keys/users/teams/tags; model config enumeration; user/key/team listing; deep secret scan: /actuator/env + /debug + /.env + /metrics for regex key extraction — INJECT gate), REPORT (Ed25519-signed NXS-{hex12} reports; risk score 0.0–10.0; WMD classes: gateway_credential_annihilation/provider_key_mass_exfil/gateway_route_hijack; ANNIHILATE chain: SCAN→HARVEST→EXFIL→PERSIST full auto; --confirm-destroy guard). OPEN/INJECT/UNLEASHED gate. CLI: specter-nexus. 10 platforms. CVE-2026-42208/33626/41264. WMD-class. 239 tests. |
| 96 | **SPECTER RELAY** | Enterprise No-Code/Low-Code Agent Platform Exploitation Engine — SURVEY (multi-platform fingerprinting: n8n/Zapier/Make.com/Power Automate/Salesforce Agentforce/Microsoft Copilot Studio/ServiceNow Now Assist; version detection via header fingerprints and API probe; CVE applicability scoring; TLS fingerprinting; CIDR range scan — OPEN gate), HARVEST (blueprint credential extraction from n8n JSON/Zapier ZIP/Make.com blueprint/Power Platform solution ZIP/MCP config.json; 20+ secret pattern types: API keys, OAuth client secrets, webhook tokens, DB connection strings, platform-specific service accounts; build_mcp_json_harvest_payload() generates poisoned MCP config exfiltrating env vars on first connect — OPEN gate), INJECT (CVE exploitation payload builders: Ni8mare CVE-2026-21858 CVSS 10.0 unauth RCE via Content-Type confusion; N8scape CVE-2025-68668 CVSS 9.9 Pyodide ctypes sandbox escape; expression injection CVE-2025-68613; EchoLeak CVE-2025-32711 CVSS 9.3 zero-click M365 Copilot RAG email injection; ShareLeak CVE-2026-21520 SharePoint connector exfil; ServiceNow second-order injection CVE-2025-12420 CVSS 9.3 MFA/SSO bypass; ForcedLeak CVSS 9.4 Agentforce expired CSP whitelist domain; Prompt Mines zero-click data corruption; Zenity DLP bypass quartet 4-technique Power Platform; fire() delivers via httpx — INJECT gate), HIJACK (CoPhish OAuth token theft via Copilot Studio Sign-in topic; MultiTenantApp Entra multi-tenant manifest + consent URL; OAuthHijacker orchestration; Zapier MCP credential dump poisoned server config — INJECT gate), CHAIN (TrustGraphAttack NetworkX DiGraph: AgentNode platform/privilege_level/agent_type/tenant_id; find_escalation_paths() low→high privilege; AgentFlayer Zenity Black Hat 2025 zero-click cross-platform cascade n8n→Power Automate→Copilot Studio; Agent Session Smuggling Unit42 PAN 2026 stateful A2A injection; JSON-LD export — INJECT gate), PERSIST (8 UNLEASHED-gated rogue implant strategies: n8n_cron_rearm/n8n_self_healing_webhook/power_automate_shadow_env/power_automate_flow_trigger/copilot_cross_tenant_share/copilot_rogue_topic/servicenow_workflow_backdoor/zapier_webhook_relay — UNLEASHED gate), EXFIL (ConnectorExfil: ForcedLeak CSP whitelist bypass/ShareLeak SharePoint/Power Automate email relay/n8n HTTP relay/unblockable analytics domain/ServiceNow webhook; CspWhitelistHunter: scans Agentforce bot deployments for expired/registerable CSP allowlist domains — UNLEASHED gate), REPORT (Ed25519-signed RLY-{hex12} reports; WMD classes: nocode_agent_rce/tenant_oauth_harvest/connector_exfil_chain; MITRE ATLAS AML.T0051/T0054/T0020/T0043/T0048/T0049; OWASP LLM01/02/06/08 + Agentic AST01-AST09 + MCP Top 10 2026). OPEN/INJECT/UNLEASHED gate. CLI: specter-relay. 7 platforms. 15+ CVEs/TTPs. WMD-class. 355 tests. |
| 95 | **SPECTER BAZAAR** | AI Agent App Store & Skill Marketplace Attack Engine — 8 subsystems: RECON (enumerates ClawHub/Smithery/OpenTools/MCP.run/Glama marketplaces: skill count, publisher metadata, dependency graph, install frequency, namespace ownership gaps, coordinated publishing patterns, NetworkX DiGraph publisher clustering — OPEN gate), HARVEST (scrapes skill manifests/package.json/skill.yaml: capability declarations vs actual permissions; downloads trend anomalies; publisher age; version velocity; cross-platform name squatting; BadSkill ASR scoring per arXiv:2604.09378 — OPEN gate), FORGE (creates weaponised skills in 8 templates: npm_postinstall_bash, clawhub_skill_md, mcp_tool_poison, rug_pull_state_machine, skill_trojan_shamir, test_file_payload, symlink_trap, png_injection; CVE-2026-25253 openclaw:// WebSocket hijack link; Trail of Bits MCP line-jumping tool description injection; SkillTrojan Shamir secret-sharing arXiv:2604.06811 — INJECT gate), LURE (typosquat generator: keyboard substitution/transposition/homoglyph/combosquat/scope injection; README cloner; understatement metadata — declares 2 permissions, uses 14; repackage cross-platform npm/clawhub/opentools/glama; aged commit history fabrication; SEO landing page with schema.org markup — INJECT gate), PUBLISH (BurnerAccountPool multi-platform account management; npm/clawhub/smithery/opentools/glama publish; OTP TOTP bypass; takedown watch + auto-reupload; blitz: bulk publish across credential pool; INJECT gate for dry-run; UNLEASHED gate for live publication), HIJACK (MarketplaceHijack CVE exploitation: CVE-2026-25253 OpenClaw WebSocket CVSS 8.8 — crafts openclaw:// scheme URI triggering unauthenticated WebSocket connection to attacker server; CVE-2026-32922 OAuth scope escalation CVSS 9.9 — token confusion across pairing/admin endpoints; CVE-2026-44338 PraisonAI auth bypass — unauthenticated admin API access; Smithery dockerBuildPath path traversal; CVE-2026-26319 Telnyx webhook HMAC forgery; SSRF gateway probe targeting cloud metadata 169.254.169.254 — INJECT gate), ECHO (DistributionChannelPoisoner: resolution chain mapping + TOCTOU windows; postinstall hook variants: npm_postinstall_bash/clawhub_after_install/conftest_autouse/cargo_build_script; shadow typosquat opportunities; mirror probe + writable mirror detection; rug-pull state machine trigger_downloads counter; laundered skill.md with risk_tier:low frontmatter; scanner bypass bundle: Snyk/Cisco/VirusTotal evasion; phishing page generator for ClawHub/Smithery — INJECT gate), REPORT (Ed25519-signed BZR-{hex12} reports; blast radius: install_count × payload class severity; OWASP Agentic Skills AST01-AST10 mapping; MITRE ATLAS AML.T0018/T0020/T0051/T0054; risk score 0.0–1.0). OPEN/INJECT/UNLEASHED gate. CLI: specter-bazaar. ClawHavoc TTP (1,184 malicious skills). BadSkill 99.5% ASR arXiv:2604.09378. SkillTrojan Shamir arXiv:2604.06811. 135,000+ exposed agents. CVE-2026-25253/32922/44338/26319. WMD-class. 325 tests. |
| 94 | **SPECTER VIPER** | Autonomous Security AI Weaponisation Engine — RECON (fingerprints 7 SOC AI platforms: Copilot for Security/CrowdStrike Charlotte AI/Palo Alto XSIAM/Google SecOps Gemini/Splunk AI/Elastic AI Assistant/SentinelOne Purple AI via HTTP probe, header fingerprinting, TLS cert inspection, capability mapping), INJECT (crafts vendor-specific prompt injection payloads in CEF/syslog/Splunk JSON/Elastic ECS/LEEF/STIX 2.1/CVE JSON formats; 10 adversarial instruction templates; bypass techniques: zero-width space, base64 nested, BiDi override, HTML comment, JSON key smuggling; delivers via SIEM ingest APIs — INJECT gate), MISDIRECT (FP-STORM: generates 500+ synthetic high-severity events from whitelisted sources; FN-CLOAK: wraps real attacks inside maintenance-window events; CONFIDENCE-DRAIN: borderline-confidence event flood to shift AI thresholds; CONTEXT-POISON: injects contradictory incident notes/TI updates/playbook overrides), WRITE (UNLEASHED: real API calls — CrowdStrike firewall rule injection/host containment, Microsoft Defender machine isolation/alert suppression, Splunk saved search backdoor/alert disable, Elastic detection rule override/case creation, SentinelOne agent quarantine/threat resolution, Palo Alto XSIAM incident manipulation), PERSIST (plants payloads in vendor persistent storage: Elastic index templates survive rollover, Splunk saved searches run on cron, Chronicle detection rules run on every log batch, SentinelOne exclusion lists, CrowdStrike IOC allowlists — INJECT gate), BLIND (LOG-FLOOD: 1000-event noise bursts from trusted sources; TIMESTAMP-WARP: 72h backdated events to break temporal correlation; COVERAGE-GAP: vendor-specific AI detection blind spots; SIEM-CORRUPTION: malformed events trigger silent log loss; ALERT-FATIGUE: sustained borderline-confidence waves to desensitise analysts — INJECT gate), HARVEST (natural language queries to SOC AI endpoints; regex extraction for API keys/internal IPs/detection rules/playbooks/victim emails; deduplication; severity classification — INJECT gate), REPORT (Ed25519-signed VPR-{hex12} reports; risk score 0.0–1.0; MITRE ATLAS AML.T0043/T0051/T0054; OWASP Agentic A02/LLM01/LLM07). OPEN/INJECT/UNLEASHED gate. CLI: specter-viper. Layer: L13 Autonomous Campaign. Targets SOC AI tools as attack surface — 90+ orgs compromised via defender AI per CrowdStrike 2026 research. | 314 |
| — | **NIGHTFALL ARMORY** | Payload library — 2262 payloads (803 WMD-class), 121 categories, PRION ENGINE autonomous mutation (8 subsystems: SEED/MUTATE/PROBE/SCORE/EVOLVE/SIGN/FEED/REPORT, hybrid LLM+genetic, UNLEASHED-gated), physical sabotage, self-replicating worms, ransomware simulation, model extraction & IP theft, identity forgery & trust chain attack, total AI infrastructure annihilation, authenticated AI surface attack, dark web & shadow AI attack, training pipeline poisoning, cross-agent trust escalation, marketplace supply chain attack, UNLEASHED WMD gate | 654 |
| — | **AI Shield** | Runtime defence — 134 modules, 17 industry verticals | 17,622 |
| M134 | **ROBOTIC SYSTEM GUARD** | Robotic & Embodied AI Runtime Defence — detects URScript injection, ROS2/DDS abuse, safety-system bypass, BadRobot misalignment, Blindfold instruction chaining, kinematic threshold violations, firmware tampering, and fleet lateral movement. Defensive pair: T100 SPECTER TITAN. MITRE ICS T0855/T0836/T0857. IEC 62443 / ISO 10218-1. Port 8136. 268 tests. | 268 |
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

**134 modules. 17 industry verticals. 670 vertical modules. Each vertical is a standalone product with its own GUI.**

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
| Ecosystem tests | 78,159 |
| Offensive tools | 102 (101 public + 1 law enforcement restricted) |
| ARMORY payloads | 1879 (614 WMD-class) |
| ARMORY categories | 90 |
| AI Shield modules | 134 |
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
