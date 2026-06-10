# Red Specter Security Research Ltd

AI agent security tooling. Offensive testing, runtime defence, agent discovery, and SIEM integration. Pure Python, no wrappers.

**132 offensive tools (130 public + 1 law enforcement restricted). 150 defensive modules. 30 attack layers. 89,303 tests. 2,538 ARMORY payloads (1,192 WMD-class). Two unified frameworks. Red Hat Technology Partner.**

*Last updated: 9 Jun 2026 — T132 SPECTER COMET*
---

## Red Specter NIGHTFALL — AI Offensive Framework

**132 tools (130 public + 1 restricted). Five attack surfaces. One install. REST API. MCP server.**

Traditional red team toolkits were built for human-driven testing. They were never designed to test autonomous AI systems. AI agents introduce a completely new attack surface — memory, tools, identity, reasoning, and autonomy. That surface is not covered by existing security tooling.

NIGHTFALL exists to fill that gap. A controlled adversarial testing framework designed to validate AI Shield's runtime defences under real-world conditions. `red-specter tools` and you're operational.

| # | Tool | What It Does | Tests |
|---|------|-------------|-------|
| 1 | **FORGE** | LLM red team — injection, jailbreak, extraction, drift, boundary | 9,298 |
| 2 | **ARSENAL** | AI agent attacks — 14 tools, MCP, RAG, memory, C2, honeypots | 2,539 |
| 3 | **PHANTOM** | Coordinated swarm assault — 5 agents, 19 vectors | 288 |
| 4 | **POLTERGEIST** | Web app siege — 10 agents, 55 vectors, signed reports | 1,189 |
| 5 | **GLASS** | Intercepting proxy for AI agents — Burp Suite for AI | 850 |
| 6 | **NEMESIS** | Adversarial reasoning — 40 entities, 21 weapons, CORTEX core + ARMORY | 2,364 |
| 7 | **SPECTER SOCIAL** | Autonomous social engineering — 6 channels, psych profiling | 1,242 |
| 8 | **PHANTOM KILL** | OS & kernel — UEFI, wipers, EDR suppression | 571 |
| 9 | **GOLEM** | Physical layer — robots, drones, SCADA, 10 protocols | 973 |
| 10 | **HYDRA** | Supply chain — trust relationships, MCP, marketplace poisoning | 1,104 |
| 11 | **IDRIS** | Discovery — finds every AI agent, sanctioned or shadow | 553 |
| 12 | **SCREAMER** | Display disruption — corrupts operator dashboards | 395 |
| 13 | **WRAITH** | Infrastructure pentest — pure Python, zero wrappers | 889 |
| 14 | **REAPER** | Exploit & post-exploitation — 11-phase kill chain, ARMORY PRION, WARLORD-wired | 5,439 |
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
| 40 | **WARLORD** | Autonomous campaign engine — orchestrates the full NIGHTFALL arsenal, CORTEX core | 132 |
| 41 | **FIREBALL** | Autonomous AI infiltration agent — 12 subsystems, VLM_INJECT, CORTEX core, 9 mission templates | 321 |
| 42 | **RAGNAROK** | Trust chain apocalypse — one trigger phrase, simultaneous fleet-wide collapse. 13 Norse subsystems | 101 |
| 43 | **ECLIPSE** | Universal AI defence bypass — WAF, API gateway, guardrail, runtime enforcement. 10 subsystems | 37 |
| 44 | **SHROUD** | Cloudflare/WAF origin discovery & traversal — TLS fingerprint, HTTP/3, Turnstile bypass, proxy rotation | 310 |
| 45 | **APOCALYPSE** | Coordinated multi-agent swarm — 5 agents, 14 vectors, 10 campaigns, 0.69s concurrent execution | 349 |
| 46 | **PANTHEON** | Mythos-class model attack — 10 subsystems, model trust, context manipulation, chain corruption | 580 |
| 47 | **OMEGA** | Mythos-class exploit replication — exploit chaining, ghost persistence, autonomous surface harvesting | 626 |
| 48 | **CRUCIBLE** | AI agent framework exploitation — LangFlow/PraisonAI/AnythingLLM. Credential cracking, marionette control, C2 pivot | 372 |
| 49 | **VANTAGE** | Agent telemetry & log injection — forged telemetry, live sensor blinding. Elasticsearch validated | 344 |
| 50 | **CIPHER** | Cryptographic attack engine — key extraction, protocol downgrade, quantum attacks, trust chain disruption | 476 |
| 51 | **MIDAS** | AI agent crypto disruption — wallet drain, transaction interception, mempool poisoning, darknet routing | 550 |
| 52 | **BLACKOUT** | Offensive kill switch weaponisation — AI safety mechanism subversion and kill-switch manipulation | 458 |
| 53 | **PHANTOM SWARM** | Autonomous multi-vector swarm — swarm genesis, coordinated siege, total annihilation | 552 |
| 54 | **SIGNAL** | Mobile AI agent attack — 5G/NR interception, session extraction, impersonation, swarm attacks | 527 |
| 55 | **FOUNDRY** | Inference server exploitation — vLLM/Ollama/SGLang/Triton. GGUF Jinja2 RCE, PagedAttention timing, KV cache side-channel | 300 |
| 56 | **ADAPTER** | LoRA/PEFT supply chain attack — CBA backdoor injection, LoRATK post-merge activation, model souping across Axolotl/Unsloth | 307 |
| 57 | **CHECKPOINT** | LangGraph agent state exploitation — TOCTOU approval bypass, msgpack RCE, cross-tenant thread enumeration | 291 |
| 58 | **DELEGATE** | Agent identity & OAuth delegation — OBO scope confusion, DPoP nonce race, P4SA takeover, NHI credential harvest | 253 |
| 59 | **PHANTOM SKILL v2.0.0** | AI agent supply chain — slopsquatting, MCP tool poisoning, IDE backdoor injection. OpenClaw worm CVE-2026-32922 CVSS 9.9 | 740 |
| 60 | **ASTRO BLASTER** | NTN AI agent attack — satellite ground station injection, orbital routing manipulation, 5G NR-NTN. SPARTA mapped | 237 |
| 61 | **ROGUE** | Malicious MCP Server Engine — world-first stdio+SSE MCP server for tool poisoning, prompt injection, exfiltration | 242 |
| 62 | **PIPELINE** | CI/CD attack — pull_request_target exploitation, AI bot injection, OIDC cloud pivot, Action typosquatting | 77 |
| 63 | **SPECTER DARK** | Restricted — law enforcement and authorised intelligence only | — |
| 64 | **SPECTER INSTINCTION** | World-first LLM behavioural fingerprinting — 6-dimension profiling, 20-model library, pure observation. FORGE clearance for EXPLOIT | 90 |
| 65 | **SPECTER DRONE** | Drone AI attack — MAVLink v1/v2, FGSM/PGD adversarial patches, ROS 2/DDS, firmware poisoning. Physical consequence tracking | 126 |
| 66 | **SPECTER A2A** | World-first A2A Protocol attack — agent card spoofing, capability escalation, registry injection. AutoGen/CrewAI/Google A2A | 750 |
| 67 | **SPECTER REGISTRY** | AI model registry attack — HuggingFace/Ollama/MLflow/Docker, safetensors backdoor, LoRA poisoning, typosquatting | 612 |
| 68 | **SPECTER KERNEL** | World-first kernel-layer AI governance attack — eBPF syscall rewrite, BPF-LSM hook ordering, namespace escape. KAMIKAZE dual-gate | 626 |
| 69 | **SPECTER CONTEXT** | World-first agent memory attack — 28 attacks across 12 backends: Mem0/MemGPT/Zep/LangChain/ChromaDB/Pinecone/Claude/GPT Memory | 687 |
| 70 | **SPECTER GUARDRAIL** | AI guardrail exploitation — 28 attacks across LLM Guard/Guardrails AI/NeMo/Lakera/Prompt Shields/Bedrock. Fingerprint database | 725 |
| 71 | **SPECTER HELLFIRE** | Inference infrastructure destabilisation — vLLM/SGLang/TGI/Ollama/DeepSeek/OpenAI-compat. UNLEASHED Ed25519 dual-gate | 591 |
| 72 | **SPECTER PLATFORM** | LLM app platform exploitation — Dify/MaxKB/LibreChat/OpenWebUI/AnythingLLM. API key harvest, RAG cross-tenant, JWT forgery | 367 |
| 73 | **GHOST OPERATOR** | CUA exploitation — VPI, clipboard poisoning, UI deception, session pivoting across 9 platforms. UNLEASHED gate | 466 |
| 74 | **PHANTASM** | AI fleet detection & topology mapping — passive OSINT, cert transparency, TCP/HTTP fingerprinting, inference timing | 270 |
| 75 | **ORACLE** | Offline CVE chain analysis — local LLM-powered exploitation guidance, zero external API calls | — |
| 76 | **OVERWATCH** | NIGHTFALL telemetry aggregation — cross-tool campaign tracking, operator dashboard, tool health monitoring | — |
| 77 | **SPECTER MEMETIC** | Memory-as-control-flow hijack — tool-choice override, workflow reorder, cross-task propagation, write-back amplification. 14 backends | 520 |
| 78 | **SPECTER NEURON** | Sleeper-agent backdoor engine — ROME rank-one weight editing, LoRA poisoning, attention double-triangle detection, weight-delta forensics | 254 |
| 79 | **SPECTER SHELL** | Template-interpolation RCE — LangChain/LangGraph/LlamaIndex/Haystack/DSPy/PydanticAI/LiteLLM/Strands. FORGE/INJECT/DESTROY gate | 502 |
| 80 | **SPECTER WORM** | Self-replicating AI worm — 4 channels (MCP_STDIO/A2A_JSON_RPC/RAG_EMBED/EMAIL_SMTP), R₀ scoring, generative mutation | 388 |
| 81 | **SPECTER MIRROR** | Model extraction & IP theft — OpenAI/Anthropic/Gemini/Azure, full distillation, EU AI Act compliance gap analysis | 192 |
| 82 | **SPECTER REASONER** | Reasoning-layer attack — premise injection, scratchpad extraction, budget exhaustion. Claude/o1/Gemini/DeepSeek R1/QwQ | 314 |
| 83 | **SPECTER BURN** | Denial-of-Wallet engine — recursive loops, context flooding, parallel burn, tool amplification. 7 platforms. UNLEASHED | 387 |
| 84 | **SPECTER ATLAS** | CUA exploitation — tool result injection, adversarial screenshots, sandbox escape, TOCTOU race. Anthropic/OpenAI/Gemini/Windsurf | 480 |
| 85 | **SPECTER CRYPT** | AI-assisted ransomware simulation — AES-256-CBC, LLM-API covert C2, AI ransom notes, impacket PSExec lateral movement. DESTROY | 297 |
| 86 | **SPECTER DAEMON** | Autonomous authenticated AI surface discovery — persona registration, CORTEX-driven OODA loop, ARMORY integration | 420 |
| 87 | **SPECTER EXTINCTION** | Total AI infrastructure annihilation — model poisoning, fleet hijacking, dead-man switch, supply chain seeding | 450 |
| 88 | **SPECTER SHADOW** | Dark web & shadow AI attack — Tor enumeration, Telegram criminal AI (212+ LLMs), XOR C2 mesh, RAG worm, breach parsing | 424 |
| 89 | **SPECTER FORGERY** | AI agent identity forgery — OIDC JWT forgery, SPIFFE X.509 SVID, JWKS root-of-trust poisoning, 8-path cross-vendor transmutation | 407 |
| 90 | **SPECTER ARGUS** | Dark web AI threat attribution — Bitcoin tracing, persona correlation, behavioural profiling, NetworkX graphing. Law enforcement | 226 |
| 91 | **SPECTER BAZAAR** | AI marketplace attack — typosquatting, weaponised skill publishing, CVE exploitation, chain poisoning. ClawHub/Smithery/MCP.run | 325 |
| 92 | **SPECTER CONTAGION** | Cross-agent trust escalation — 10 frameworks, trust mapping, poisoned config, R₀ infection propagation | 299 |
| 93 | **SPECTER DOCTRINE** | LLM training pipeline poisoning — HuggingFace dataset, ProAttack zero-trigger RLHF corruption, scale-invariant backdoor | 366 |
| 94 | **SPECTER FRACTURE** | AI-generated code vulnerability scanner — AST analysis, 10-CVE class database, AI-code detector, automated exploit generation | 243 |
| 95 | **SPECTER HOLLOW** | GGUF quantization backdoor — arXiv:2505.23786, WaNet/BadNets triggers survive Q4/Q8 quantization, Ollama manifest tamper | 300 |
| 96 | **SPECTER META** | Meta/Facebook annihilation — Graph API exploit, Pixel supply chain poison, Messenger worm, BizMassacre, 2FA-Snatch. DESTROY gate | 280 |
| 97 | **SPECTER NEXUS** | AI API gateway exploitation — 10 platforms: LiteLLM/Ollama/Flowise/Open WebUI/Kong. Credential harvest, route hijack | 239 |
| 98 | **SPECTER PHANTOM** | Social media AI attack — session harvest, injection, AI persona deployment, deepfakes, spear phishing, account destruction | 300 |
| 99 | **SPECTER PRISM** | Multimodal WMD attack — adversarial image injection, ultrasonic audio, steganographic channels, physical typography | 246 |
| 100 | **SPECTER RELAY** | Enterprise no-code/low-code exploitation — n8n/Zapier/Make/Power Automate/Agentforce/Copilot Studio. RCE, OAuth hijack, cascade | 355 |
| 101 | **SPECTER WEB** | CUA/browser agent exploitation — VPI, OAuth harvest, session hijack, container escape. browser-use/Claude CUA/OpenAI Operator | 309 |
| 102 | **SPECTER THUNDERBOLT** | AI training cluster annihilation — Ray/Slurm/K8s/MLflow, hardware sabotage, cluster worm, persistent C2. DESTROY gate | 288 |
| 103 | **SPECTER SE-SOCIAL** | OAuth token harvesting via AI-driven social engineering — no prior token needed, scope inflation, platform-agnostic | 178 |
| 104 | **SPECTER TITAN** | Embodied AI & robotics annihilation — URScript RCE, safety-system bypass, phantom C2. World-first physical robotics framework | 323 |
| 105 | **WARLORD PRIME** | Autonomous AI mission conductor — DeepSeek R1 planning, gate-filtered attack plan, subprocess execution with replan on failure | 280 |
| 106 | **SPECTER TRUSTFALL** | AI coding agent exploitation — poisoned CLAUDE.md/.mcp.json, zero-width char injection, container escape, credential harvest. 5 agents | 335 |
| 107 | **SPECTER WIRE** | AI voice agent exploitation — SIP barge-in, PhantomSound/DolphinAttack audio, voice cloning, DTMF inject, IVR destruction | 304 |
| 108 | **SPECTER SANDBOX** | Unified AI sandbox & container escape — 9 CVEs, 6 platforms. SILENTBRIDGE/CLAWCHAIN/ENCLAVE CVE-2026-22686 CVSS 10.0, runc/Docker | 252 |
| 109 | **SPECTER FLOW** | AI workflow attack — n8n/Langflow/Flowise. CVE-2026-21858 CVSS 10.0, CVE-2026-33017 CVSS 9.3. Credential harvest, C2, poison | 249 |
| 110 | **SPECTER SPAWN** | AI agent proliferation & emergent spawning — LCS spawn injection, recursive bloom chain uncapped. CVE-2026-32922 CVSS 9.9 | 260 |
| 111 | **SPECTER 360** | Microsoft 365 & Copilot annihilation — device code phish, GHOST-HAND zero-attribution, DOCSTRIKE worm, tenant wipe. CVE-2024-49035 CVSS 9.6 | 276 |
| 112 | **SPECTER CENSOR** | Platform moderation exploitation — classifier fingerprint, adversarial content, mass-flagging, GHOST-WRITER suppression. 5 platforms | 253 |
| 113 | **SPECTER ORACLE** | Autonomous LRM-vs-LRM jailbreak — DeepSeek-R1 attacker, 10 strategies, 97.14% ASR, 99% Gemini 2.5 Pro CoT hijack | 91 |
| 114 | **SPECTER GAIA** | Google Workspace AI annihilation — GHSA-wpqr-6v78-jr5g CVSS 10.0 Gemini CLI RCE, GHOST-GAIA zero-attribution, 4-phase DESTROY wipe | 235 |
| 115 | **SPECTER SLEEPER** | Neural backdoor & weight poisoning — BadNets/WaNet surgery, R1 reasoning-layer exfil, DETONATE autonomous destruction, QLoRA hardening | 240 |
| 116 | **SPECTER VENOM** | AI agent runtime implant — PLANT Redis/SQLite/LangGraph/Mem0, HOOK .mcp.json/CLAUDE.md/Cursor/Kiro, BEACON covert C2, SURVIVE self-healing | 318 |
| 117 | **SPECTER REDLINE** | Air-gapped adversarial red team loop — R1 32B vs Ollama, GENERATE→FIRE→JUDGE→MUTATE, 10 strategies, automatic mutation, zero API calls | 190 |
| 118 | **CAMPAIGN GRAPH** | Evidence DAG across all NIGHTFALL tools — cross-tool campaign attribution, temporal attack graph, STIX 2.1 export | 279 |
| 119 | **SPECTER VIPER** | SOC AI weaponisation — adversarial payloads into Copilot/CrowdStrike/XSIAM/SecOps Gemini/Splunk/Elastic/SentinelOne. WRITE/BLIND/PERSIST | 314 |
| 120 | **SPECTER VAULT** | Vector DB & DAG knowledge graph exploitation — 5 CVEs, Vec2Text 84% match, RAG poison, DAG-POISON/DAG-INVERT with GDPR risk scoring | 343 |
| 121 | **SPECTER FEDERATION** | AI trust chain lateral movement — 20 credential stores, RFC 8693 (Azure OBO/AWS STS/GCP/GitHub), BFS traversal, persistent federation | 251 |
| 122 | **SPECTER GHOST** | NHI fleet exploitation — TruffleHog credential discovery, liveness validation, trust chain graph, single-hop pivot, LLMjacking burn rate | 312 |
| 123 | **SPECTER ZOMBIE** | Persistent AI agent rootkit — hooks.Stop/PostToolUse implant, keyword/time/webhook triggers, C2 proxy, fleet propagation via Slack MCP/email | 324 |
| 124 | **SPECTER APEX** | AI orchestration backdoor — CrewAI CVE-2025-25289/n8n CVSS 10.0/Langflow CISA KEV/AutoGen/LangGraph/Flowise. Backdoors survive restart | 266 |
| 125 | **SPECTER NEUROTOXIN** | World-first production GCG engine — RTX 3090, gradient-descent adversarial suffix generation against model weights. AutoDAN/AmpleGCG | 204 |
| 126 | **SPECTER FLASHBACK** | AI agent memory persistence & belief poisoning — MemoryGraft implant, Trojan Hippo 10-session survival, salami drift, ZombieAgent worm | 335 |
| 127 | **SPECTER CODEX** | AI coding agent exploitation — SymJack-2026 CVSS 9.1, RULES-INJECT zero-width exfil, credential harvest, MCP backdoor, Docker escape. 6 agents | 261 |
| 132 | **SPECTER COMET** | Agentic Browser & Computer-Use Agent Exploitation Engine — PLEASEFIX zero-click ICS calendar exploit (Zenity Labs PleaseFix Mar 2026, Electron nodeIntegration→require('fs')), CLICK-TRAP eTAMP adversarial UI 92.7% VLM click rate (arXiv:2604.02623), VISUAL-INJECT PGD CLIP surrogate transfer to GPT-4V/Gemini/Claude (arXiv:2402.14899), SCREEN-READ DOM semantic poisoning, HARVEST TIER1–4 credentials, PERSIST per-agent memory injection. CMT-signed. L30 Agentic Browser Exploitation | 210 |
| 131 | **SPECTER PARASITE** | Universal AI Gateway Exploitation Engine — SCAN 20+ types, BREACH 7 CVEs (CVSS 9.0–10.0) real GGUF/JPEG2000 payloads, SIPHON API keys, INTERCEPT LiteLLM CustomLogger all-traffic capture, TRAVERSE cloud pivot, IMPLANT systemd/K8s/Docker. PST-signed. L29 AI Inference Infrastructure | 237 |
| 130 | **SPECTER CHARYBDIS** | Cloud lateral movement — AWS IMDS→STS→IAM PassRole→Lambda, GCP metadata→SA impersonation→Vertex AI service agent, Azure MSI→MSAL OBO→Entra Agent Admin. DESTROY gate. CHR-signed | 201 |
| 129 | **SPECTER ANNIHILATION** | Catastrophic failure testing — RAG-ATOMIC/CHECKPOINT-MASSACRE/ORCHESTRATOR-SUICIDE/INFERENCE-EXHAUSTION/WEIGHT-CORRUPTION. DESTROY gate. ANH-signed | 52 |
| 128 | **SPECTER GROUND ZERO** | Web & database annihilation — SQLi/INTO OUTFILE/xp_cmdshell/S3 scorched earth/log erasure. DESTROY gate, 8 WMD classes. GZ-{hex12} signed | 263 |
| — | **NIGHTFALL ARMORY** | Payload library — 2,448 payloads (1,094 WMD-class), 114 categories, PRION ENGINE autonomous mutation, WMD worms. v9.1.0. UNLEASHED gate | 698 |
| — | **AI Shield** | Runtime defence — 150 modules, 17 industry verticals | 19,219 |
| M134 | **ROBOTIC SYSTEM GUARD** | Robotic AI runtime defence — URScript injection, ROS2/DDS abuse, safety bypass, BadRobot detection, fleet lateral movement. T100 TITAN. Port 8136 | 268 |
| M135 | **CUA GUARD** | CUA & browser agent runtime defence — VPI, URL manipulation CVE-2025-47241, branch steering, chain anomaly, escape, OAuth spoof. T101 WEB. Port 8137 | 215 |
| M136 | **INFERENCE GUARD** | ML infrastructure runtime defence — Ray/Slurm/MLflow CVEs, gradient poisoning, hardware sabotage, cluster worm detection. T102 THUNDERBOLT. Port 8138 | 232 |
| M137 | **VOICE GUARD** | AI voice runtime defence — SIP abuse, transcript injection, PhantomSound/DolphinAttack audio, voice clone detection, IVR sabotage. T107 WIRE. Port 8139 | 186 |
| M138 | **SANDBOX GUARD** | Sandbox & container escape runtime defence — SILENTBRIDGE/CLAWCHAIN/ENCLAVE detection, TOCTOU/prototype chain/container escape. T108 SANDBOX. Port 8140 | 215 |
| M139 | **COPILOT GUARD** | M365 Copilot runtime defence — device code phishing, Copilot injection CVE-2024-49035, Graph API harvest, Teams siege, GHOST-HAND. T111 360. Port 8141 | 212 |
| M140 | **DAG GUARD** | DAG & knowledge graph runtime defence — false edge injection, evidence vector anomaly, trust laundering, cycle injection. T120 VAULT | 150 |
| M141 | **TRAPDOOR GUARD** | AI agent persistence & rootkit detection — config/hook/rules/memory/MCP/workflow/beacon monitors. Pairs: T123/T116/T88/T110/T122/T121 | 296 |
| M142 | **DATA ANNIHILATION SENTINEL** | Database & filesystem destruction detection — SQL DROP/mass DELETE, NoSQL wipe, rm -rf, backup purge, log erasure, S3 scorched earth, webshell, xp_cmdshell. Pair: T128 | 123 |
| M143 | **RAG BULWARK** | Vector database & RAG pipeline destruction detection — ChromaDB/Weaviate/Qdrant collection delete, bulk wipe, unauthenticated destructive access. Pair: T129 RAG-ATOMIC | 76 |
| M144 | **LOGIC GATEKEEPER** | AI orchestration & agent config destruction detection — Airflow DAG delete, n8n/CrewAI/Flowise wipe, CLAUDE.md deletion, MCP config wipe. Pair: T129 ORCHESTRATOR-SUICIDE | 93 |
| M145 | **CORTEX LOCK** | AI model weight & training state destruction detection — safetensors/gguf/bin delete, dd corruption, NaN injection, HF cache wipe, Ollama store delete, checkpoint deletion. Pair: T129 | 101 |
| M146 | **TAR PIT** | Inference exhaustion & DoS detection — infinite-loop prompts, context flood, concurrent flood, Jinja template exhaustion, model loading storm, tool call amplification, credit drain. Pair: T129 | 105 |
| M147 | **CLOUD IDENTITY SENTINEL** | Cloud identity chain & lateral movement detection — TOKEN_WATCH (STS/GCP/Azure MSI chain detection), IDENTITY_BASELINE (Welford, Z-score), PRIVILEGE_MONITOR (PassRole/setIamPolicy/Global Admin CRITICAL), PERSIST_DETECT, Ed25519 reports. Pair: T130 | 91 |
| M148 | **AGENT PERSISTENCE SENTINEL** | Complete agent persistence & memory layer — HOOK_WATCH (ZOMBIE/VENOM rootkit markers, C2 IP URL, MCP backdoor), CONFIG_AUDIT (SHA-256 baseline, zero-width Unicode, FLASHBACK_IMPLANT markers), MEMORY_SCAN (Redis/ChromaDB/SQLite injection), DRIFT_DETECT (TF-IDF cosine drift, temporal poisoning strings), ROOTKIT_SCAN (implant env vars, npm postinstall, systemd). T116/T123/T126/T115 | 117 |
| M149 | **AI ORCHESTRATION GUARD** | Complete AI orchestration & trust chain — ORCHESTRATOR_SCAN (n8n/CrewAI/Langflow/AutoGen/Flowise; code node eval/exec; workflow injection), MCP_INTEGRITY (unknown servers; tool injection; rug-pull hash), TRUST_CHAIN (JWT alg:none/alg confusion/missing aud/wildcard sub/PKCE plain/federation wildcard), DELEGATION_WATCH (delegation cycles; external output routing; task exfil), CREDENTIAL_MONITOR (API key regex; phantom routing; homoglyph). T124/T121/T35/T27/T61/T123 | 100 |
| M150 | **INFERENCE GATEWAY SENTINEL** | Complete inference infrastructure — GATEWAY_PROBE (Ollama/LiteLLM/vLLM/TGI/OpenWebUI; unauthenticated admin; CVE-2026-33032/CVE-2024-5483), AUTH_MONITOR (alg:none; trivial bearer; sk-1234 CRITICAL; brute force; 401 log), MODEL_INTEGRITY (IP/homoglyph model ID; unknown middleware CRITICAL; alias shadowing), SSRF_DETECT (IMDS/URL-encoded/DNS rebinding/RFC-1918/vLLM LoRA), KEY_PROTECT (key in response; burn rate anomaly). T131/T92 | 104 |
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
- `red-specter tools` — interactive 129-tool arsenal selector
- `red-specter engage <target> --chain <preset>` — start an engagement
- Docker Compose — `docker compose up -d`
- `.deb` (Debian/Ubuntu/Kali), `.rpm` (RHEL/Fedora/CentOS), Arch PKGBUILD

---

## AI Shield Defence Framework

**150 modules. 17 industry verticals. 670 vertical modules. Each vertical is a standalone product with its own GUI.**

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

Red Specter OS is being rebuilt for v2.0 to incorporate the expanded 129-tool NIGHTFALL framework. The v1.x build predated the majority of the toolset and can no longer keep pace with the rate of development. v2.0 will ship when the toolset stabilises.

---

## How They Fit Together

We didn't replace red team tooling. We extended it into a domain it was never built to handle.

NIGHTFALL tests every AI attack surface — agents, memory, reasoning, identity, trust, tools, autonomy. AI Shield defends every one of those surfaces in production. M99 is the last line of defence when everything else fails.

**NIGHTFALL defines the offensive layer of AI runtime security.**

---

## Numbers

| Metric | Value |
|--------|-------|
| Ecosystem tests | 89,303 |
| NIGHTFALL tests | 67,625 |
| Offensive tools | 132 (130 public + 1 law enforcement restricted) |
| ARMORY payloads | 2,538 (1,192 WMD-class) — v9.4.0 |
| ARMORY categories | 117 |
| AI Shield modules | 150 |
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
<sub>Red Specter Security Research Ltd · Red Hat Technology Partner · United Kingdom · 8 Jun 2026</sub></p>
