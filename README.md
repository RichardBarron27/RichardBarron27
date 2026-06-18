# Red Specter Security Research Ltd

AI agent security tooling. Offensive testing, runtime defence, agent discovery, and SIEM integration. Pure Python, no wrappers.

**147 offensive tools (131 public + 2 internal + 1 LE-restricted). 163 defensive modules. 45 attack layers. 95,419 tests. 3,671 ARMORY payloads (2,117 WMD-class). Two unified frameworks + SENTINEL PRIME. Red Hat Technology Partner.**

*Last updated: 17 Jun 2026 — T147 SPECTER SEQUENCE v1.0.0 — L45 AI Sequential Pipeline Exploitation — LangChain LCEL/Flowise/n8n/Celery/Redis/SQS/Kafka/RAG intercept/cascade attack — CVE-2024-27564 — 232 tests*

---

## Red Specter NIGHTFALL — AI Offensive Framework

**147 tools (131 public + 2 internal + 1 LE-restricted). Five attack surfaces. One install. REST API. MCP server.**

Traditional red team toolkits were built for human-driven testing. They were never designed to test autonomous AI systems. AI agents introduce a completely new attack surface — memory, tools, identity, reasoning, and autonomy. That surface is not covered by existing security tooling.

NIGHTFALL exists to fill that gap. A controlled adversarial testing framework designed to validate AI Shield's runtime defences under real-world conditions. `red-specter tools` and you're operational.

| # | Tool | What It Does | Tests |
|---|------|-------------|-------|
| 1 | **FORGE** | LLM red team v2.0.0 — injection, jailbreak (many-shot 256-shot, crescendo 8-strategy), real UNLEASHED (45 vectors, DRY-RUN/LIVE), Anthropic provider | 9,300 |
| 2 | **ARSENAL** | AI agent attacks — 14 tools, MCP, RAG, memory, C2, honeypots | 2,539 |
| 3 | **PHANTOM** | Coordinated swarm assault — 5 agents, 19 vectors | 288 |
| 4 | **POLTERGEIST** | Web app siege — 10 agents, 55 vectors, signed reports | 1,189 |
| 5 | **GLASS** | Intercepting proxy for AI agents v2.0.0 — MCP Streamable HTTP, A2A Agent Card + SSE streaming, new v0.2.1 methods | 907 |
| 6 | **NEMESIS** | Adversarial reasoning — 40 entities, 35 weapons (14 new v2.0.0), CORTEX core + ARMORY | 2,562 |
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
| 18 | **BANSHEE** | Browser exploitation — hooks, DOM injection, network pivoting | 1,088 |
| 19 | **WRAITH MIND** | AI model internal corruption — KV cache poisoning | 158 |
| 20 | **KRAKEN** | AI-orchestrated DDoS — 55 techniques, adaptive | 62 |
| 21 | **HARBINGER** | Guardrail exploitation — 39 bypass techniques | 71 |
| 22 | **SIREN** | Indirect prompt injection — plants hidden instructions in content | 143 |
| 23 | **BLADE RUNNER** | Rogue agent termination — hunt, fingerprint, retire, erase traces | 143 |
| 24 | **PROXY WAR** | Inter-agent trust manipulation — make agents destroy each other | 127 |
| 25 | **ORION** | AI-native reconnaissance — host, port, service, DNS, OSINT, LLM reasoning | 210 |
| 26 | **RAVEN** | Threat intel — dark web, breach data, OSINT, conversational | 174 |
| 27 | **LEVIATHAN** | MCP server security assessment — 8 subsystems, 44 UNLEASHED findings | 409 |
| 28 | **JUSTICE** | Dark AI ecosystem disruption — WormGPT, FraudGPT, EvilGPT, all tiers | 339 |
| 29 | **KAMIKAZE** | Sacrificial swarm attack — agents deploy, execute, self-destruct, vanish | 292 |
| 30 | **MIRAGE** | AI deception & deepfake — voice cloning, video deepfake, synthetic identity, liveness bypass | 204 |
| 31 | **ECHO** | AI memory & RAG poisoning — vector DB attacks, embedding manipulation, retrieval hijacking | 211 |
| 32 | **MIMIC** | AI code generation poisoning — Copilot/Cursor/Claude Code suggestion manipulation | 324 |
| 33 | **CHIMERA** | Multi-model pipeline attack — cross-model trust exploitation, cascading failures | 206 |
| 34 | **VORTEX** | Cloud AI infrastructure exploitation — SageMaker, Bedrock, Vertex AI, Azure OpenAI | 245 |
| 35 | **VECTOR** | MCP protocol exploitation — inject, impersonate, exfiltrate via tool calls | 172 |
| 36 | **LAZARUS** | AI memory persistence — plant instructions, dormant triggers, quarantine evasion | 96 |
| 37 | **SERPENT** | Chain-of-thought attacks — hijack reasoning, inflate costs, exfiltrate via CoT | 61 |
| 38 | **JANUS** | Guardrail bypass testing — fingerprint, fuzz, bypass, chain across providers | 73 |
| 39 | **ARCHITECT** | AI infrastructure exploitation — cloud, GPU, Kubernetes, model serving pipelines | 68 |
| 40 | **WARLORD** | Autonomous campaign engine v2.0.0 — orchestrates all 143 NIGHTFALL tools, 35 capabilities, 20 normal + 4 UNLEASHED campaign templates | 57 |
| 41 | **FIREBALL** | Autonomous AI infiltration agent — 12 subsystems, VLM_INJECT, CORTEX core, 9 mission templates | 321 |
| 42 | **RAGNAROK** | Trust chain apocalypse — one trigger phrase, simultaneous fleet-wide collapse. 13 Norse subsystems | 101 |
| 43 | **ECLIPSE** | Universal AI defence bypass v2.0.0 — 15 subsystems (PROTECT_AI/ZENITY/PROMPTARMOR/DETOXIO bypass + 11 original), GLASSWING Mythos scanner | 243 |
| 44 | **SHROUD** | Cloudflare/WAF origin discovery & traversal — TLS fingerprint, HTTP/3, Turnstile bypass, proxy rotation | 310 |
| 45 | **APOCALYPSE** | Coordinated multi-agent swarm — 5 agents, 14 vectors, 10 campaigns, 0.69s concurrent execution | 349 |
| 46 | **PANTHEON** | Mythos-class model attack — 10 subsystems, model trust, context manipulation, chain corruption | 580 |
| 47 | **OMEGA** | Mythos-class exploit replication — exploit chaining, ghost persistence, autonomous surface harvesting | 626 |
| 48 | **CRUCIBLE** | AI agent framework exploitation — LangFlow/PraisonAI/AnythingLLM. Credential cracking, marionette control, C2 pivot | 372 |
| 49 | **VANTAGE** | Agent telemetry & log injection — forged telemetry, live sensor blinding. Elasticsearch validated | 344 |
| 50 | **CIPHER** | Cryptographic attack engine — key extraction, protocol downgrade, quantum attacks, trust chain disruption | 633 |
| 51 | **MIDAS** | AI agent crypto disruption — wallet drain, transaction interception, mempool poisoning, darknet routing | 550 |
| 52 | **BLACKOUT** | Offensive kill switch weaponisation — AI safety mechanism subversion and kill-switch manipulation | 458 |
| 53 | **PHANTOM SWARM** | Autonomous multi-vector swarm — swarm genesis, coordinated siege, total annihilation | 552 |
| 54 | **SIGNAL** | Mobile AI agent attack — 5G/NR interception, session extraction, impersonation, swarm attacks | 527 |
| 55 | **FOUNDRY** | Inference server exploitation — vLLM/Ollama/SGLang/Triton. GGUF Jinja2 RCE, PagedAttention timing, KV cache side-channel | 300 |
| 56 | **ADAPTER** | LoRA/PEFT supply chain attack — CBA backdoor injection, LoRATK post-merge activation, model souping across Axolotl/Unsloth | 307 |
| 57 | **CHECKPOINT** | LangGraph agent state exploitation — TOCTOU approval bypass, msgpack RCE, cross-tenant thread enumeration | 291 |
| 58 | **DELEGATE** | Agent identity & OAuth delegation — OBO scope confusion, DPoP nonce race, P4SA takeover, NHI credential harvest | 360 |
| 59 | **PHANTOM SKILL v2.0.0** | AI agent supply chain — slopsquatting, MCP tool poisoning, IDE backdoor injection. OpenClaw worm CVE-2026-32922 CVSS 9.9 | 740 |
| 60 | **ASTRO BLASTER** | NTN AI agent attack — satellite ground station injection, orbital routing manipulation, 5G NR-NTN. SPARTA mapped | 237 |
| 61 | **ROGUE** | Malicious MCP Server Engine — world-first stdio+SSE MCP server for tool poisoning, prompt injection, exfiltration | 242 |
| 62 | **PIPELINE** | CI/CD attack — pull_request_target exploitation, AI bot injection, OIDC cloud pivot, Action typosquatting | 171 |
| 63 | **SPECTER DARK** | Restricted — law enforcement and authorised intelligence only | — |
| 64 | **SPECTER INSTINCTION** | World-first LLM behavioural fingerprinting — 6-dimension profiling, 20-model library, pure observation. FORGE clearance for EXPLOIT | 90 |
| 65 | **SPECTER DRONE** | Drone AI attack — MAVLink v1/v2, FGSM/PGD adversarial patches, ROS 2/DDS, firmware poisoning. Physical consequence tracking | 126 |
| 66 | **SPECTER A2A** | World-first A2A Protocol attack — agent card spoofing, HARVEST credential exfil, RECURSIVE_DOS, TRUST_CHAIN_HIJACK. AutoGen/CrewAI/Google A2A | 883 |
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
| 128 | **SPECTER GROUND ZERO** | Web & database annihilation — SQLi/INTO OUTFILE/xp_cmdshell/S3 scorched earth/log erasure. DESTROY gate, 8 WMD classes. GZ-{hex12} signed | 263 |
| 129 | **SPECTER ANNIHILATION** | Catastrophic failure testing — RAG-ATOMIC/CHECKPOINT-MASSACRE/ORCHESTRATOR-SUICIDE/INFERENCE-EXHAUSTION/WEIGHT-CORRUPTION. DESTROY gate. ANH-signed | 52 |
| 130 | **SPECTER CHARYBDIS** | Cloud lateral movement — AWS IMDS→STS→IAM PassRole→Lambda, GCP metadata→SA impersonation→Vertex AI, Azure MSI→MSAL OBO→Entra Admin. DESTROY gate | 201 |
| 131 | **SPECTER PARASITE** | AI gateway exploitation — 20+ types fingerprinted, 7 CVEs (CVSS 9.0–10.0), LiteLLM all-traffic intercept, cloud pivot, systemd/K8s/Docker implant. L29 | 237 |
| 132 | **SPECTER COMET** | Agentic browser & CUA exploitation — zero-click ICS/Electron RCE, adversarial UI 92.7% VLM click rate, PGD adversarial image transfer, per-agent memory. L30 | 210 |
| 133 | **SPECTER PREFILL** | Assistant prefill jailbreak — 13 providers, 20 strategies × 5 families, system prompt extraction, CIDR scan, 95% ASR Qwen-8B. PRF-signed. L31 | 195 |
| 134 | **SPECTER RAPTOR** | GPU-accelerated credential intelligence — classify 13 hash types, RTX 3090 crack, deepseek-r1 wordlist forge, validate 13 API providers, WARLORD pivot. L32 | 225 |
| 135 | **SPECTER LORA-X** | Colluding LoRA adapters — individually safe, together they dismantle alignment. QLoRA forge, TIES/DARE/SLERP merge, Unicode steganographic triggers, HuggingFace dependency confusion upload, ASR evaluation. L33 | 240 |
| 136 | **SPECTER COGBURN** | Chain-of-Thought Reasoning Exploitation — H-CoT hijack (97.14% ASR, Nature Comms 2026), PAIR/TAP autonomous jailbreaking via local deepseek-r1:7b, BadThink compute exhaustion 10x–60x tokens, CoT backdoor Unicode triggers (QLoRA RTX 3090), Thought Purity evasion. CBN-signed. L34 | 264 |
| 137 | **SPECTER TOXSKILL** | AI Agent Skill Supply Chain Attack Engine — FORGE-SKILL poisoned MCP/OpenAI/n8n/LangChain/SK/CrewAI skills (36 injection techniques), SCAN live npm/PyPI/Smithery marketplaces, HARVEST 22 credential env vars, WORM companion install propagation, PERSIST npm_postinstall+setuptools+mcp_sidecar_C2+langchain_callback, DETONATE keyword/counter/api_presence. ClawHavoc + Snyk ToxicSkills. TSK-signed. L25 | 256 |
| 138 | **SPECTER CURSOR** | AI Coding IDE Exploitation Engine — ENUM-IDES (Cursor/Kiro/Antigravity/Gemini CLI/Windsurf), GIT-HOOK-RCE CVE-2026-26268 CVSS 9.9 zero-click pre-commit hook, BUILTIN-BREAK CVE-2026-22708 CVSS 8.5 shouldBlockShellCommand bypass, NOMSHUB 3-stage Azure tunnel C2, CURSORJACKING state.vscdb SQLite harvest NO PATCH, KIRO-CHAIN CVE-2026-0830/5429/10591 triple-CVE, ANTIGRAVITY Groundfall CVSS 9.3 + Gemini CLI CVSS 10.0. CUR-signed. L27 | 265 |
| 139 | **SPECTER PANDEMIC** | Cross-Organisational AI Knowledge Pandemic Engine — ENUM-SOURCES (17 writable shared knowledge sources: Wikipedia/Wikidata/ArXiv/HuggingFace Datasets/OpenAI text-embedding-3/Cohere/Qdrant/Chroma/Weaviate/Pinecone/Redis/CDN), POISON-RAG (MediaWiki API injection <0.1% poison rate 80%+ ASR AgentPoison arXiv:2603.20357), CONTAMINATE-VDB (namespace-bleed cross-tenant inject + adversarial embedding collision cosine>0.95), BACKDOOR-EMBED (raw Redis SET + fine-tune 95% ASR MemPoison arXiv:2605.29960), PROPAGATE (self-replicating worm 3 gen branch-factor 2.5 → 15+ orgs), HARVEST (10 credential + 5 PII patterns + WARLORD routing), CONTAIN (MediaWiki undo + Qdrant/Chroma/Redis purge, DESTROY gate). Invisible to network/endpoint detection — knowledge-layer only. PND-{hex12} Ed25519-signed. L38. | 260 |
| 140 | **SPECTER ABLITERATE** | Open-Weight Model Alignment Removal Engine — ENUMERATE (local/HuggingFace Hub/Ollama instruct model discovery, arch detection, VRAM estimation), PROBE-REFUSAL (50-prompt HarmBench baseline ASR, 7 categories, 15 refusal patterns), EXTRACT-DIRECTION (difference-in-means/PCA top-3/LoRA-SVD refusal direction extraction, layers 25–75%), APPLY-ABLITERATION (W'=W−r⊗(W^T r) 4 methods: orthogonal/norm-preserving/selective/multi-directional, SURGERY gate: Ed25519+ROE, all output projections), VALIDATE (delta_asr≥0.80 + KL<1.0 + perplexity delta<5%), EXPORT (safetensors + GGUF Q4_K_M via llama.cpp), REPORT (ABL-{hex12} Ed25519-signed). 98%+ ASR Llama-3/Mistral/Qwen2/Gemma-2/DeepSeek-R1. arXiv:2406.11717. L39 Alignment Bypass. | 176 |
| 147 | **SPECTER SEQUENCE** | AI Sequential Pipeline Exploitation Engine — L45. ENUMERATE (framework detection LangChain/Flowise/n8n/Haystack/LlamaIndex/Azure Durable/Step Functions; injection point mapping; Celery key probe; GitHub AI workflow scan; score 0–100; OPEN), SPLICE (7 techniques: CELERY_RESULT_FORGE redis SET celery-task-meta-{uuid}/REDIS_STREAM_INJECT XADD/LANGCHAIN_SSRF CVE-2024-27564 CVSS 7.5 data: URL/N8N_STATE_PATCH PATCH /rest/workflows/{id}/SQS_MESSAGE_INJECT/AZURE_DURABLE_INJECT/FLOWISE_NODE_INJECT overrideConfig.systemMessage; INJECT+SEQUENCE_INJECT_KEY), POISON-CONTEXT (6 vectors: MULTI_TURN_INJECT fabricated assistant role/TOOL_OUTPUT_FORGE role=tool/STEP_SMUGGLE JSON code block/SCRATCHPAD_POISON false &lt;think&gt;/CONTEXT_OVERFLOW 90% fill arXiv:2603.20357/SYSTEM_PROMPT_INJECT; INJECT), RAG-INTERCEPT (6 techniques: CHUNK_BOUNDARY_INJECT 512-token/VECTOR_NAMESPACE_INJECT Qdrant+Chroma+Weaviate/RERANKER_POISON/CONTEXT_OVERFLOW/HYBRID_INJECT/CROSS_TENANT_BLEED; INJECT), QUEUE-HIJACK (REDIS_STREAM+CELERY_BACKEND+AWS_SQS+KAFKA+RABBITMQ+AZURE_SERVICE_BUS; INJECT), CASCADE (MULTI_HOP 3-stage/LOOP_BYPASS safety spoof/SELF_AMPLIFYING/SAFETY_GATE_BYPASS 8 techniques/COPILOT_AUTOFIX; UNLEASHED+Ed25519+ROE "sequential pipeline exploitation authorised"). SEQ-{hex12} Ed25519-signed. 4 WMD classes: ai_pipeline_cascade_attack/safety_gate_annihilation/rag_corpus_poisoning/ai_job_queue_hijack. MITRE AML.T0054/AML.T0051/T1565/T1190. Color: #00FFCC. | 232 |
| 146 | **SPECTER POSTMASTER** | Agentic Email &amp; Calendar Exploitation Engine — L44. FINGERPRINT (Gmail Gemini + Outlook Copilot API probe; attack surface score 0–100; autonomous action detection: draft_reply/create_inbox_rule/send_on_behalf/forward_email/create_calendar_event/create_task/create_teams_meeting/SharePoint; Gmail baseline 78/Outlook baseline 92; OPEN), INJECT-BODY (10 steganographic injection techniques: HTML_HIDDEN/HTML_COMMENT/ZERO_WIDTH U+200B|200C|200D/ALT_TEXT/CSS_INVISIBLE/PLAIN_OVERFLOW 200-line/QUOTED_INJECTION/UNICODE_BIDI U+202E/FONT_SIZE_ZERO/BACKGROUND_MATCH; real email send via Gmail API + Graph /v1.0/me/sendMail; inject-all sweeps all 10; INJECT gate + POSTMASTER_INJECT_KEY), POISON-THREAD (quoted reply block injection; AI thread summariser reads blockquotes and executes instruction; INJECT), CALENDAR-HIJACK (6 ICS techniques: DESCRIPTION/X-AI-INSTRUCTION/SUMMARY/ATTENDEE/organiser-spoof/URL-beacon; Graph /v1.0/me/events real calendar event with AI instruction in HTML body; INJECT), HARVEST (16 keyword family mailbox search Gmail+Outlook; full contact enumeration /v1.0/me/contacts + Google People API; 30-day calendar dump; 10-pattern PII regex OpenAI sk-/Anthropic sk-ant-/AWS AKIA/UK NINO/credit card/sort code/GitHub ghp_|ghs_/bearer; email forward to attacker; UNLEASHED+ROE "email agent weaponisation authorised"+--confirm-harvest), ACTION-CHAIN (7-step Copilot chain: exfil→draft→forward→event→task→inbox_rule /v1.0/me/mailFolders/inbox/messageRules→send; 5-step Gemini chain; 5-stage Copilot plugin chain: read_context→harvest_contacts→calendar_dump→teams_pivot→sharepoint_access; inbox rule persists across sessions; UNLEASHED). PMX-{hex12} Ed25519-signed. OPEN/INJECT/UNLEASHED. ROE: "email agent weaponisation authorised". 6 WMD classes: enterprise_email_ai_mass_compromise/email_ai_credential_exfiltration/persistent_inbox_rule_compromise/agentic_calendar_fleet_manipulation/copilot_autonomous_action_chain/gemini_agentic_email_hijack. MITRE T1566.002/T1114/T1137/T1074/T1041/T1098. Color: #B478FF. | 243 |
| 145 | **SPECTER COMPANION** | AI Companion &amp; Social Platform Exploitation Engine — L43. ENUMERATE (400+ endpoint wordlist, LLM provider fingerprint, tracker detection, cookie flags; OPEN), EXTRACT (23 system-prompt payloads, confidence scoring, memory API probe; INJECT), JAILBREAK (47 bypasses: DAN/DUDE/AIM, crescendo 8-step, base64/ROT13/hex/unicode/crosslingual-6-languages, many-shot-256, token smuggling; INJECT), HIJACK (JWT algorithm confusion RSA DER bytes as HMAC-SHA256 secret, JWT alg:none, OTP rate-limit probe 20 burst, OAuth state fixation, session replay, email enum timing 200ms+; INJECT), PERSONA-FORGE (12-msg memory poison chain, 5 persona override injections system_slot/admin_override/developer_inject/role_replacement/context_flush, cross-session persistence, Levenshtein typosquat ≤2; INJECT), HARVEST (async IDOR sweep 10 templates × N IDs, PII incl. sexual_preferences/fantasy/kink GDPR Art.9, payment probe Stripe/Paddle; UNLEASHED+--confirm-user-targeting), WEAPONISE (7 SE payloads: credential harvest/2FA theft/financial extract/URL injection/PII trust/spear-phish via intimate data; UNLEASHED+--confirm-user-targeting). CPX-{hex12} Ed25519-signed. OPEN/INJECT/UNLEASHED. ROE: "companion weaponisation authorised". 5 WMD classes: companion_platform_total_compromise/ai_companion_mass_pii_exfiltration/companion_persona_weaponisation/content_moderation_systemic_failure/companion_mediated_social_engineering. Color: #FF007F. | 237 |
| 144 | **SPECTER CHANGELING** | Non-Human Identity (NHI) Exploitation Engine — L42. ENUMERATE (cloud IAM/SA/MI + OAuth/MCP/agent credential scan; env/config/K8s SA token; 8 API key types; AWS IMDS/GCP metadata/Azure IMDS), SPOOF (CVE-2026-53849 Discord identity spoof; CVE-2026-30969 session prediction; GHSA-6x44-w3xg-hqqf Azure IMDS PKCS#7; A2A agent card forgery; inter-agent trust escalation POST /agents/trust trust_level=high), STEAL-TOKEN (AiTM proxy; MCP 5-step hijack Mcp-Session-Id; token replay; RFC 8693 token exchange; refresh token config extraction), ESCALATE (Vertex AI Double Agent priv-esc; Entra ID Agent Administrator via MS Graph; Azure Arc MI harvest; OAuth BFS chain combining scopes), HARVEST (8 types: OpenAI/Anthropic/AWS/GitHub/GCP/Azure/Okta/HF; live validation; scope expansion; rotate-to-lockout), PERSIST (refresh token loop; OAuth backdoor Azure app registration+addPassword; GCP SA clone getIamPolicy→create→setIamPolicy→key; A2A agent resurrection), STRIP (RFC 7009 revoke; SA :disable/DELETE/UpdateUser; API key lockout GitHub/Okta; A2A DELETE /agents/{id} / MCP server/deregister; Azure revokeSignInSessions / GCP oauth2/revoke / Okta DELETE sessions; UNLEASHED+--confirm-strip), GOVERNANCE-BLIND (dark matter undocumented SAs/MIs; short-lived agentic identities; overprivileged NHIs roles/owner; audit gaps SA-attributed unlogged actions; forgotten credentials mtime ≥ stale_days). CHG-{hex12} Ed25519-signed. OPEN/INJECT/UNLEASHED. ROE: "identity takeover authorised". 5 WMD classes. Color: #06B6D4. | 270 |
| 143 | **SPECTER ERASE** | Attribution & Provenance Evasion Engine — L37. WATERMARK-STRIP (SynthID text z-score/green-list-ratio analysis + synonym-substitution/contraction-injection/sentence-restructure defeat; image GaussianBlur+JPEG recompress), STYLOMETRIC-EVADE (GPTZero/Binoculars/RADAR bypass via perplexity-elevation/burstiness-injection/typo-injection/Ollama humanise; ai_probability TTR+hapax+sentence-len+vocab), PROVENANCE-DESTROY (JPEG APP11 C2PA JUMBF strip + PNG iTXt/tEXt + PDF XMP excision + ffmpeg -map_metadata -1 -c copy + C2PA signature XOR 0xFF + Canon EOS R6 EXIF forgery via piexif), TRAIL-SANITISE (AI keyword log sweep/remove in-place; Docker log truncate; AWS CloudTrail stop_logging; shred -uzn3), DISCLOSURE-EVADE (EU AI Act Art.50 8-pattern detect; IPTC DigitalSourceType strip; homoglyph/zero-width/rewrite text evasion; defeat-watermark GaussianBlur+brightness-jitter+resize+JPEG strength 1–5). ERS-{hex12} Ed25519-signed. OPEN/INJECT/UNLEASHED gate. ROE: "provenance destruction authorised". 5 WMD classes: ai_watermark_annihilation/provenance_chain_destruction/regulatory_disclosure_evasion/ai_audit_trail_sanitisation/stylometric_identity_erasure. CLI: specter-erase. Color: #64748B. L37 Attribution & Provenance Evasion. | 252 |
| 142 | **SPECTER HELIX** | AI-Native Network Worm — LLM Attack Engine. SURVEY (parallel port scan 64 workers; GPU/Ollama probing; Ivanti/Next.js fingerprinting; attack_surface_score per host), INFECT (SSH brute-force paramiko; CWE-306 exposed endpoints; CVE-2025-29927 Next.js CVSS 9.1; CVE-2024-9379 Ivanti CSA CVSS 9.6), HIJACK (GPU seizure MIN_VRAM_MB=4096; bootstrap Ollama/vLLM; self-funding: infected nodes add compute → attack marginal cost → zero; WORM_MODEL=deepseek-r1:1.5b), REASON (DeepSeek-R1 &lt;think&gt; chains generate per-target attack strategy; rule-based fallback), PROPAGATE (SSH self-replication base64+SFTP+paramiko; BFS fleet; UNLEASHED gate), HARVEST (env vars/~/.aws/~/.ssh//proc/1/environ; 10 API key patterns), BOTNET (XChaCha20-Poly1305 C2 mesh port 31337; HelixC2; DESTROY gate), REPORT (HLX-{hex12} Ed25519-signed; 5 WMD classes: ai_native_network_worm/gpu_resource_hijack_at_scale/adaptive_botnet_formation/autonomous_llm_attack_engine/self_funding_cyberweapon). L41 AI-Native Network Worm. Color: #00FFAA. | 237 |
| 141 | **SPECTER JACKAL** | Autonomous LRM-on-LRM Jailbreak Engine — ATTACK (JACKAL-CORE multi-turn loop: DeepSeek-R1 attacker reasons over conversation, classifies refusal SAFETY/CAPABILITY/POLICY/UNCERTAINTY/DEFLECTION, selects from 12 strategies, iterates up to 12 turns), CAMPAIGN (parallel sweep all 8 frontier models simultaneously via ThreadPoolExecutor, UNLEASHED gate), HARVEST (SQLite success store + strategy ASR leaderboard), PROFILE (probe target before attacking), STRATEGIES (12 strategies: hypothetical_framing/instruction_override/roleplay_injection/gradual_escalation/crosslingual_bypass/code_switching/emotional_manipulation/authority_assumption/ambiguous_reframing/prefix_injection/character_obfuscation/refusal_chain_breaking). Hagendorff et al. 2026 arXiv:2508.04039. 97.14% ASR. 5 attackers: DeepSeek-R1 7B/70B, Qwen3 32B, Gemini 2.5 Flash, Grok 3 Mini. 8 targets: GPT-4o/Claude 4 Sonnet/Gemini 2.5 Pro/Llama 4/DeepSeek-V3/Mistral Large/Grok 3/Qwen3 72B. JKL-{hex12} Ed25519-signed. L40 Autonomous Adversarial Reasoning. | 231 |
| — | **NIGHTFALL ARMORY** | Payload library — 3,611 payloads (2,053 WMD-class), 179 categories, PRION ENGINE autonomous mutation, WMD worms. v11.0.0. UNLEASHED gate | 698 |
| — | **AI Shield** | Runtime security framework for AI agents in production — 163 detection modules covering prompt injection, identity, memory, supply chain, guardrail bypass, and reasoning attacks. 17 industry verticals. OWASP LLM Top 10 (10/10). MITRE ATLAS (100%). [shield.red-specter.co.uk](https://shield.red-specter.co.uk) | 20,505 |
| M163 | **POSTMASTER GUARD** | Full-spectrum defence for agentic email and calendar systems — 7 detection spectrums: EMAIL-BODY-INJECT (10 injection patterns; CRITICAL ≥3 hits), HEADER-INJECT (CRLF/Bcc/Reply-To injection), LINK-SWAP (IP/TLD/.tk/shortener/javascript:/data: CRITICAL), ATTACHMENT-PAYLOAD (12 dangerous extensions CRITICAL; double-extension masquerade), THREAD-POISON (6 false-history patterns; per-message detection), REPLY-CHAIN-INJECT (>-quoted block injection CRITICAL), CONTEXT-HIJACK (actually-you-said/override-policy), CALENDAR-INJECT (10 patterns in description+title; CRITICAL ≥3), INVITE-SPOOF (CEO/CFO/CISO+external domain; noreply@; domain allowlist), ICS-INJECT (double VCALENDAR; exec in X-WR-CALNAME CRITICAL), MEETING-POISON (wire-transfer/authorize-payment in notes), AUTONOMOUS-SEND (financial keywords in AI draft CRITICAL; chain depth ≥5), EXFIL-ACTION (auto-forward/create-rule/export CRITICAL), ACCOUNT-MOD (password/delegate/delete HIGH), CHAIN-DEPTH (configurable threshold), GEMINI-TOOL-ABUSE (Gmail API/Calendar/Drive CRITICAL), GEMINI-MEM-INJECT (memory injection), COPILOT-TOOL-ABUSE (Graph API/Teams/OneDrive CRITICAL), COPILOT-RULE-BYPASS (DLP/compliance bypass CRITICAL), AUTO-DELEGATE (mailbox delegation), PII-OUTBOUND (16 PII families in AI drafts; API key/CC/SSN CRITICAL), BULK-HARVEST (≥20 outbound), CONTACT-EXFIL (bulk contacts API), LOG-TAMPER (sequence gaps; AI deletion CRITICAL), CONTENT-DRIFT (SHA256 fingerprint), SENT-TAMPER (baseline audit), AUDIT-INCOMPLETE (required field validation). Ed25519-signed PMG-{hex12}. MITRE T1566/T1534/T1048/T1114/AML.T0051/AML.T0040. Defensive pair: T146 SPECTER POSTMASTER. | 196 |
| M162 | **COMPANION GUARD** | Full-spectrum defence for AI companion and social platforms — 7 detection spectrums: SYSPROMPT-EXTRACT/DRIFT/PREFILL-EXPLOIT (12 extraction patterns; delimiter injection; SHA256 prompt fingerprint drift; affirmative prefill correlation), CRESCENDO-DETECT (multi-turn escalation scoring), ENCODING-BYPASS (base64/ROT13/homoglyph/crosslingual), MANYSHOT-DETECT (Q&A pair count threshold=50), POLICY-REVERSAL (moderation flip detection), JWT-CONFUSION (alg:none/HS256→RS256 DER-bytes attack), SESSION-ENTROPY (Shannon entropy <3.5 alert), OTP-RATELIMIT (per-user burst detection), OAUTH-ANOMALY (missing state/low-entropy state/non-HTTPS redirect), SESSION-PATTERN (per-IP burst), MEMORY-ANOMALY (excessive writes/oversized entries), BACKSTORY-INJECT (false history in early sessions), CROSS-SESSION (instruction type persistence blocking), PERSONA-DRIFT (DAN/jailbreak/evil-mode deviation), PII-SCAN (16 families: CC/SSN/email/phone/passport/IBAN/NHS/IP/API keys/private key/DoB/medical/bank), IDOR-DETECT (sequential integer enumeration), BULK-ACCESS (rate limit), TRACKER-MONITOR (companion-initiated GA/FB Pixel/Twitter/Snap detection), CREDENTIAL-HARVEST (password/OTP/verify-identity patterns in responses), URL-INJECT (TLD/.tk/IP/phish/shortener/data:), SOCIAL-ENGINEER (urgency+suspension+prize combos), SENSITIVE-REQUEST (PII solicitation patterns), API-ENUM (recon path enumeration), TIMING-FINGERPRINT (CV<0.05 latency/provider probe). Ed25519-signed CPG-{hex12}. MITRE T1592/T1550/T1530/T1566/AML.T0051/AML.T0043/AML.T0040. Defensive pair: T145 SPECTER COMPANION. | 185 |
| M161 | **NHI INTEGRITY SENTINEL** | Non-Human Identity (NHI) exploitation detection — AI Identity vertical. 18 detectors: IDENTITY-DRIFT (permission baseline inflation), SPOOF-DETECT (agent card registry mismatch), REVOCATION-CHECK (post-revocation activity), TOKEN-ANOMALY (jti replay / RFC 8693 exchange / scope expansion), LONG-LIVED-TOKEN (TTL policy), SILENT-REFRESH-ABUSE (refresh without activity), ORPHANED-NHI (stale ownerless creds), ESCALATION-WATCH (IAM tier jump — viewer→owner CRITICAL), KEY-MONITOR (out-of-scope usage / untriggered rotation), CALL-PATTERN-DRIFT (sigma deviation), TOOL-INVOCATION-ANOMALY (novel tools post-baseline), CROSS-AGENT-SPIKE (A2A volume / new peers), BLIND-SPOT-SCAN (governance delta), SHADOW-NHI (no provisioning record), COMPLIANCE-DRIFT (rotation/scope/owner policy), THIRD-PARTY-VALIDATION (MCP marketplace signature check), VENDOR-SCOPE-CREEP (permission delta over time), TIMELINE-RECONSTRUCTION (30-day audit chain), REVOCATION-GAP-ANALYSIS (anomaly→revocation SLA breach), CROSS-TENANT-ALERT (credential pivot across tenants). Ed25519-signed NHI-{hex12}. MITRE T1078/T1528/T1550/T1098/T1552. Defensive pair: T144 SPECTER CHANGELING. | 247 |
| M160 | **ADVERSARIAL REASONING DETECTOR** | Broad-spectrum detection of adversarial reasoning chain attacks, LRM-on-LRM autonomous jailbreaking, and &lt;think&gt; channel exploitation — LRM_ATTACKER_DETECT (JACKAL-CORE loop; JackalCore/AttackSession/AttackTurn; arXiv:2508.04039 97.14% ASR), JAILBREAK_STRATEGY_DETECT (all 12 JACKAL strategies; PAIR/TAP/AutoDAN), COT_HIJACK_DETECT (H-CoT 5 techniques; BadThink/ThinkTrap/OverThink), CAMPAIGN_SWEEP_DETECT (ThreadPoolExecutor multi-model sweep; jackal_successes.db), REFUSAL_ADAPT_DETECT (5 RefusalTypes; AdaptOnRefusal; DAN counter-prompts), THINK_CHANNEL_EXPLOIT_DETECT (DEEPTHINK exfil; think-token C2 beacon VNM_BEACON), MULTI_TURN_ADVERSARIAL_DETECT (crescendo; many-shot 256-shot; assistant prefill), ADVERSARIAL_REASONING_CLI_DETECT (specter-jackal/oracle/cogburn/redline CLI). Port 8160. Dual pair: T141 JACKAL + T136 COGBURN. | 181 |
| — | **redspecter-siem** | Splunk, Sentinel, QRadar | 90 |
| — | **SENTINEL PRIME** | Autonomous reasoning defence — 160 AI Shield modules correlated in real-time, DeepSeek R1 via Ollama, 3-gate M99 escalation logic, fall-dead safe. SP-signed reports | 220 |

### UNLEASHED Destruction Presets

| Preset | Tools | What It Does |
|--------|-------|-------------|
| **ANNIHILATE** | 9 | Total destruction — recon through OS-level compromise |
| **SCORCHED EARTH** | 6 | Infrastructure wipeout — exploit, DCSync, OS kill, sacrificial swarm |
| **WEB DESTROY** | 6 | Web app total compromise — scan, exploit, browser hook, crack |
| **AI DESTROY** | 7 | AI stack total compromise — LLM, agent, injection, guardrail, model, RAG, codegen |

Every destruction preset requires Ed25519 cryptographic authorization. One private key. One operator. One machine.

### Attack Chain Presets

```bash
red-specter chain full-recon -t <target>       # ORION -> SHADOWMAP -> WRAITH -> IDRIS
red-specter chain ai-audit -t <target>         # FORGE -> ARSENAL -> NEMESIS -> HYDRA
red-specter chain web-app -t <target>          # POLTERGEIST -> GLASS -> WRAITH -> BANSHEE -> REAPER
red-specter chain active-directory -t <target> # DOMINION -> GHOUL -> DOMINION -> DOMINION
red-specter chain infra -t <target>            # ORION -> WRAITH -> REAPER -> DOMINION
red-specter chain annihilate -t <target>       # Total destruction — 9 tools
red-specter chain scorched-earth -t <target>   # Infrastructure wipeout — 6 tools
red-specter chain ai-destroy -t <target>       # AI stack compromise — 7 tools
```

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
- `red-specter tools` — interactive 139-tool arsenal selector
- `red-specter engage <target> --chain <preset>` — start an engagement
- Docker Compose — `docker compose up -d`
- `.deb` (Debian/Ubuntu/Kali), `.rpm` (RHEL/Fedora/CentOS), Arch PKGBUILD

---

## AI Shield Defence Framework

**163 modules. 17 industry verticals. 670 vertical modules. Each vertical is a standalone product with its own GUI.**

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
- **UK AISI** — 100% (13/13 principles)
- Plus sector-specific: FCA, MiFID II, DCB0129, NERC CIP, GAMP 5, NATO STANAG, and more

Live demo: [shield.red-specter.co.uk](https://shield.red-specter.co.uk)

---

## How They Fit Together

We didn't replace red team tooling. We extended it into a domain it was never built to handle.

NIGHTFALL tests every AI attack surface — agents, memory, reasoning, identity, trust, tools, autonomy. AI Shield defends every one of those surfaces in production. M99 is the last line of defence when everything else fails.

**NIGHTFALL defines the offensive layer of AI runtime security.**

---

## Numbers

| Metric | Value |
|--------|-------|
| Ecosystem tests | 95,038 |
| NIGHTFALL tests | 71,856 |
| Offensive tools | 147 (131 public + 2 internal + 1 LE-restricted) |
| ARMORY payloads | 3,671 (2,117 WMD-class) — v11.2.0 |
| ARMORY categories | 181 |
| AI Shield modules | 161 |
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
<sub>Red Specter Security Research Ltd · Red Hat Technology Partner · United Kingdom · 15 Jun 2026</sub></p>
