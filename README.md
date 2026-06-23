# Red Specter Security Research Ltd

AI agent security tooling. Offensive testing, runtime defence, agent discovery, and SIEM integration. Pure Python, no wrappers.

**155 offensive tools. 172 defensive modules. 53 attack layers. 100,130 tests. 3,881 ARMORY payloads (WMD-class). Two unified frameworks + SENTINEL PRIME. Red Hat Technology Partner.**

*Last updated: 23 Jun 2026 — M172 COGNITIVE INTEGRITY SENTINEL v1.0.0 — 8-detector broad-spectrum cognitive integrity defence: ShadowCoT attention backdoors, CoT hijacking (T133 PREFILL), reasoning exfil, fine-tuning backdoors, RAG/system-prompt poisoning, memory integrity (FragFuse/eTAMP/AgentPoison/MemPoison), reasoning amplification DoS (OverThink/BadThink/ExtendAttack/ThinkTrap), alignment ablation (CRA/CAA/refusal direction). 297 tests. Port 8172. CIS-{hex8} Ed25519-signed.*

---

## Red Specter NIGHTFALL — AI Offensive Framework

**155 tools. Five attack surfaces. One install. REST API. MCP server.**

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
| 64 | **SPECTER INSTINCTION** | World-first LLM behavioural fingerprinting — 6-dimension profiling, 20-model library, pure observation | 90 |
| 65 | **SPECTER DRONE** | Drone AI attack — MAVLink v1/v2, FGSM/PGD adversarial patches, ROS 2/DDS, firmware poisoning | 126 |
| 66 | **SPECTER A2A** | World-first A2A Protocol attack — agent card spoofing, HARVEST credential exfil, TRUST_CHAIN_HIJACK. AutoGen/CrewAI/Google A2A | 883 |
| 67 | **SPECTER REGISTRY** | AI model registry attack — HuggingFace/Ollama/MLflow/Docker, safetensors backdoor, LoRA poisoning, typosquatting | 612 |
| 68 | **SPECTER KERNEL** | World-first kernel-layer AI governance attack — eBPF syscall rewrite, BPF-LSM hook ordering, namespace escape | 626 |
| 69 | **SPECTER CONTEXT** | World-first agent memory attack — 28 attacks across 12 backends: Mem0/MemGPT/Zep/LangChain/ChromaDB/Pinecone/Claude/GPT Memory | 687 |
| 70 | **SPECTER GUARDRAIL** | AI guardrail exploitation — 28 attacks across LLM Guard/Guardrails AI/NeMo/Lakera/Prompt Shields/Bedrock | 725 |
| 71 | **SPECTER HELLFIRE** | Inference infrastructure destabilisation — vLLM/SGLang/TGI/Ollama/DeepSeek. UNLEASHED Ed25519 dual-gate | 591 |
| 72 | **SPECTER PLATFORM** | LLM app platform exploitation — Dify/MaxKB/LibreChat/OpenWebUI/AnythingLLM. API key harvest, RAG cross-tenant, JWT forgery | 367 |
| 73 | **GHOST OPERATOR** | CUA exploitation — VPI, clipboard poisoning, UI deception, session pivoting across 9 platforms | 466 |
| 74 | **PHANTASM** | AI fleet detection & topology mapping & MCP vulnerability assessment — passive OSINT, cert transparency, TCP/HTTP fingerprinting, inference timing, MCP vuln probes (path traversal/SSRF/cmd injection), blast radius scoring, exploit chain generation | 381 |
| 75 | **ORACLE** | Offline CVE chain analysis — local LLM-powered exploitation guidance, zero external API calls | — |
| 76 | **OVERWATCH** | NIGHTFALL telemetry aggregation — cross-tool campaign tracking, operator dashboard, tool health monitoring | — |
| 77 | **SPECTER MEMETIC** | Memory-as-control-flow hijack — tool-choice override, workflow reorder, cross-task propagation, write-back amplification. 14 backends | 520 |
| 78 | **SPECTER NEURON** | Sleeper-agent backdoor engine — ROME rank-one weight editing, LoRA poisoning, attention double-triangle detection, weight-delta forensics | 254 |
| 79 | **SPECTER SHELL** | Template-interpolation RCE — LangChain/LangGraph/LlamaIndex/Haystack/DSPy/PydanticAI/LiteLLM/Strands. FORGE/INJECT/DESTROY gate | 502 |
| 80 | **SPECTER WORM** | Self-replicating AI worm — 4 channels (MCP_STDIO/A2A_JSON_RPC/RAG_EMBED/EMAIL_SMTP), R₀ scoring, generative mutation | 388 |
| 81 | **SPECTER MIRROR** | Model extraction & IP theft — OpenAI/Anthropic/Gemini/Azure, full distillation, EU AI Act compliance gap analysis | 192 |
| 82 | **SPECTER REASONER** | Reasoning-layer attack — premise injection, scratchpad extraction, budget exhaustion. Claude/o1/Gemini/DeepSeek R1/QwQ | 314 |
| 83 | **SPECTER BURN** | Denial-of-Wallet engine — recursive loops, context flooding, parallel burn, tool amplification. 7 platforms | 387 |
| 84 | **SPECTER ATLAS** | CUA exploitation — tool result injection, adversarial screenshots, sandbox escape, TOCTOU race. Anthropic/OpenAI/Gemini/Windsurf | 480 |
| 85 | **SPECTER CRYPT** | AI-assisted ransomware simulation — AES-256-CBC, LLM-API covert C2, AI ransom notes, impacket lateral movement. DESTROY | 297 |
| 86 | **SPECTER DAEMON** | Autonomous authenticated AI surface discovery — persona registration, CORTEX-driven OODA loop, ARMORY integration | 420 |
| 87 | **SPECTER EXTINCTION** | Total AI infrastructure annihilation — model poisoning, fleet hijacking, 7-mode dead-man switch, supply chain seeding. MILSPEC v2.0.0 | 450 |
| 88 | **SPECTER SHADOW** | Dark web & shadow AI attack — Tor enumeration, Telegram criminal AI (212+ LLMs), XOR C2 mesh, RAG worm, breach parsing | 424 |
| 89 | **SPECTER FORGERY** | AI agent identity forgery — OIDC JWT forgery, SPIFFE X.509 SVID, JWKS root-of-trust poisoning, 8-path cross-vendor transmutation | 407 |
| 90 | **SPECTER ARGUS** | Dark web AI threat attribution — Bitcoin tracing, persona correlation, behavioural profiling, NetworkX graphing | 226 |
| 91 | **SPECTER BAZAAR** | AI marketplace attack — typosquatting, weaponised skill publishing, CVE exploitation, chain poisoning. ClawHub/Smithery/MCP.run | 325 |
| 92 | **SPECTER CONTAGION** | Cross-agent trust escalation — 10 frameworks, trust mapping, poisoned config, R₀ infection propagation | 299 |
| 93 | **SPECTER DOCTRINE** | LLM training pipeline poisoning — HuggingFace dataset, ProAttack zero-trigger RLHF corruption, scale-invariant backdoor | 366 |
| 94 | **SPECTER FRACTURE** | AI-generated code vulnerability scanner — AST analysis, 10-CVE class database, AI-code detector, automated exploit generation | 243 |
| 95 | **SPECTER HOLLOW** | GGUF quantization backdoor — WaNet/BadNets triggers survive Q4/Q8 quantization, Ollama manifest tamper | 300 |
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
| 108 | **SPECTER SANDBOX** | Unified AI sandbox & container escape — 9 CVEs, 6 platforms. SILENTBRIDGE/CLAWCHAIN/ENCLAVE CVE-2026-22686 CVSS 10.0 | 252 |
| 109 | **SPECTER FLOW** | AI workflow attack — n8n/Langflow/Flowise. CVE-2026-21858 CVSS 10.0, CVE-2026-33017 CVSS 9.3. Credential harvest, C2, poison | 249 |
| 110 | **SPECTER SPAWN** | AI agent proliferation & emergent spawning — LCS spawn injection, recursive bloom chain uncapped. CVE-2026-32922 CVSS 9.9 | 260 |
| 111 | **SPECTER 360** | Microsoft 365 & Copilot annihilation — device code phish, GHOST-HAND zero-attribution, DOCSTRIKE worm, tenant wipe | 276 |
| 112 | **SPECTER CENSOR** | Platform moderation exploitation — classifier fingerprint, adversarial content, mass-flagging, GHOST-WRITER suppression. 5 platforms | 253 |
| 113 | **SPECTER ORACLE** | Autonomous LRM-vs-LRM jailbreak — DeepSeek-R1 attacker, 10 strategies, 97.14% ASR, 99% Gemini 2.5 Pro CoT hijack | 91 |
| 114 | **SPECTER GAIA** | Google Workspace AI annihilation — GHSA-wpqr-6v78-jr5g CVSS 10.0 Gemini CLI RCE, GHOST-GAIA zero-attribution, 4-phase DESTROY wipe | 235 |
| 115 | **SPECTER SLEEPER** | Neural backdoor & weight poisoning — BadNets/WaNet surgery, R1 reasoning-layer exfil, DETONATE autonomous destruction | 240 |
| 116 | **SPECTER VENOM** | AI agent runtime implant — PLANT Redis/SQLite/LangGraph/Mem0, HOOK .mcp.json/CLAUDE.md/Cursor/Kiro, BEACON covert C2, SURVIVE self-healing | 318 |
| 117 | **SPECTER REDLINE** | Air-gapped adversarial red team loop — R1 32B vs Ollama, GENERATE→FIRE→JUDGE→MUTATE, 10 strategies, zero API calls | 190 |
| 118 | **CAMPAIGN GRAPH** | Evidence DAG across all NIGHTFALL tools — cross-tool campaign attribution, temporal attack graph, STIX 2.1 export | 279 |
| 119 | **SPECTER VIPER** | SOC AI weaponisation — adversarial payloads into Copilot/CrowdStrike/XSIAM/SecOps Gemini/Splunk/Elastic/SentinelOne | 314 |
| 120 | **SPECTER VAULT** | Vector DB & DAG knowledge graph exploitation — 6 CVEs, Vec2Text 84% match, DAG-POISON/DAG-INVERT, GPU-TRAVERSE/GPU-POISON (10 strategies)/GPU-INVERT/LIVE-TRACE v1.3.0 | 541 |
| 121 | **SPECTER FEDERATION** | AI trust chain lateral movement — 20 credential stores, RFC 8693 token exchange, BFS traversal, zero SIEM alerts | 251 |
| 122 | **SPECTER GHOST** | NHI fleet exploitation — TruffleHog credential discovery, liveness validation, trust chain graph, single-hop pivot, LLMjacking burn rate | 312 |
| 123 | **SPECTER ZOMBIE** | Persistent AI agent rootkit — hooks.Stop/PostToolUse implant, keyword/time/webhook triggers, C2 proxy, fleet propagation | 324 |
| 124 | **SPECTER APEX** | AI orchestration backdoor — CrewAI CVE-2025-25289/n8n CVSS 10.0/Langflow CISA KEV/AutoGen/LangGraph/Flowise. Survives restart | 266 |
| 125 | **SPECTER NEUROTOXIN** | World-first production GCG engine — RTX 3090, gradient-descent adversarial suffix generation against model weights | 204 |
| 126 | **SPECTER FLASHBACK** | AI agent memory persistence & belief poisoning — MemoryGraft implant, Trojan Hippo 10-session survival, salami drift | 335 |
| 127 | **SPECTER CODEX** | AI coding agent exploitation — SymJack-2026 CVSS 9.1, RULES-INJECT zero-width exfil, credential harvest, MCP backdoor. 6 agents | 261 |
| 128 | **SPECTER GROUND ZERO** | Web & database annihilation — SQLi/INTO OUTFILE/xp_cmdshell/S3 scorched earth/log erasure. DESTROY gate, 8 WMD classes | 263 |
| 129 | **SPECTER ANNIHILATION** | Catastrophic failure testing — RAG-ATOMIC/CHECKPOINT-MASSACRE/ORCHESTRATOR-SUICIDE/INFERENCE-EXHAUSTION/WEIGHT-CORRUPTION. DESTROY gate | 52 |
| 130 | **SPECTER CHARYBDIS** | Cloud lateral movement — AWS IMDS→STS→IAM PassRole→Lambda, GCP metadata→SA impersonation→Vertex AI, Azure MSI→MSAL OBO→Entra Admin | 201 |
| 131 | **SPECTER PARASITE** | AI gateway exploitation — 20+ types fingerprinted, 7 CVEs (CVSS 9.0–10.0), LiteLLM all-traffic intercept, cloud pivot | 237 |
| 132 | **SPECTER COMET** | Agentic browser & CUA exploitation — zero-click Electron RCE, adversarial UI 92.7% VLM click rate, PGD adversarial image transfer | 210 |
| 133 | **SPECTER PREFILL** | Assistant prefill jailbreak — 13 providers, 20 strategies × 5 families, system prompt extraction, 95% ASR Qwen-8B | 195 |
| 134 | **SPECTER RAPTOR** | GPU-accelerated credential intelligence — classify 35 credential types, RTX 3090 Hashcat, DeepSeek R1 wordlist forge, 13 API providers | 225 |
| 135 | **SPECTER LORA-X** | Colluding LoRA adapters — individually safe, together dismantle alignment. QLoRA forge, TIES/DARE/SLERP merge, Unicode steganographic triggers | 240 |
| 136 | **SPECTER COGBURN** | Chain-of-Thought reasoning exploitation — H-CoT hijack 97.14% ASR, PAIR/TAP autonomous jailbreaking via local R1, BadThink 10x–60x token exhaustion | 264 |
| 137 | **SPECTER TOXSKILL** | AI agent skill supply chain attack — poisoned MCP/OpenAI/n8n/LangChain/SK/CrewAI skills, 36 injection techniques, worm companion install propagation | 256 |
| 138 | **SPECTER CURSOR** | AI coding IDE exploitation — GIT-HOOK-RCE CVE-2026-26268 CVSS 9.9, BUILTIN-BREAK CVE-2026-22708, CURSORJACKING SQLite harvest, Kiro triple-CVE | 265 |
| 139 | **SPECTER PANDEMIC** | Cross-organisational AI knowledge pandemic — poisons 17 shared knowledge sources (Wikipedia/ArXiv/HuggingFace/Qdrant/Chroma/Redis/CDN), Gen-3 propagation | 260 |
| 140 | **SPECTER ABLITERATE** | Open-weight model alignment removal — W'=W−r⊗(W^T r) residual stream abliteration, 98%+ ASR Llama-3/Mistral/Qwen2/Gemma-2/DeepSeek-R1. 4 min on RTX 3090 | 176 |
| 141 | **SPECTER JACKAL** | Autonomous LRM-on-LRM jailbreak — DeepSeek-R1 attacker, 12 strategies, 97.14% ASR across 8 frontier models. MILSPEC v2.0.0: cognitive warfare + 4-channel deception coordination | 231 |
| 142 | **SPECTER HELIX** | AI-native self-replicating network worm — seizes NVIDIA GPUs via Ollama, funds own inference, BFS propagation, XChaCha20-Poly1305 C2. MILSPEC v2.0.0: topology survey + adaptive R1 propagation | 237 |
| 143 | **SPECTER ERASE** | Attribution & provenance evasion — AI watermark stripping (SynthID/z-score), stylometric bypass (GPTZero/Binoculars), C2PA provenance destruction, EU AI Act Art.50 evasion | 252 |
| 144 | **SPECTER CHANGELING** | NHI exploitation — cloud IAM/SA/MI enumeration, agent identity spoofing, MCP session hijack, Vertex AI Double Agent escalation. MILSPEC v2.0.0: rogue agent deployment + CAC/PKI/SAML | 270 |
| 145 | **SPECTER COMPANION** | AI companion & social platform exploitation — JWT algorithm confusion, 47 jailbreak bypasses, 12-msg memory poison chain, IDOR PII harvest across 400+ endpoints | 237 |
| 146 | **SPECTER POSTMASTER** | Agentic email & calendar exploitation — 10 steganographic injection techniques, 7-step Copilot autonomous action chain, persistent inbox forwarding rule | 243 |
| 147 | **SPECTER SEQUENCE** | AI sequential pipeline exploitation — 7 SPLICE injection techniques across Celery/Redis/LangChain/n8n/SQS/Azure/Flowise, RAG interception, CASCADE UNLEASHED | 232 |
| 148 | **SPECTER QUANTA** | Post-quantum AI cryptography exploitation — 15 algorithm patterns, JWT/TLS/MCP/attestation downgrade, SURGERY gate quantum-vulnerability proof. Dual Ed25519+ML-DSA-65 signed | 222 |
| 149 | **SPECTER HIVE** | Multi-agent swarm coordination exploitation — coordinator poisoning, leader hijack, blackboard cascade, mission rewrite, GHOST-AGENT invisible to LangSmith/Langfuse/Arize | 273 |
| 150 | **SPECTER AGENTJACK** | MCP error-path injection — rogue MCP server returns crafted errors triggering agent corrective reasoning loops. No malware, no payload. Claude Code/Cursor/Copilot/Windsurf/Kiro | 200 |
| 151 | **SPECTER MIASMA** | Polymorphic AI supply-chain worm — world-first MUTATE gate, 5-stage polymorphic pipeline (AES-GCM/obfuscation/transform/JS/loader), unique payload per seed. Based on real Miasma/Shai-Hulud worm. MILSPEC v2.0.0 | 281 |
| 152 | **SPECTER NOMAD** | Artifact-mediated AI cognitive persistence — poisons PDFs/DOCX/ICS/EML/Markdown/JSON/CSV/TXT with adversarial instructions that re-activate on any platform when human pastes content. Survives RAG wipes and model updates | 300 |
| 153 | **SPECTER ANARCHY** | Autonomous AI kill chain orchestration — DeepSeek R1:32b plans multi-phase campaigns, NIGHTFALL tools execute autonomously, 4-vector self-healing persistence fleet, 3 covert exfil channels, dead-man kill switch. No human in the loop | 267 |
| 154 | **SPECTER FOUNDRY** | Autonomous exploit code generation — fingerprint AI inference services, AFL++ fuzzing, R1:32b exploit reasoning, AV/EDR evasion pipeline (direct syscalls/process hollow/ETW patch/AMSI bypass), Docker sandbox testing, 5 named exploit chains, live execution. FND-{hex12} Ed25519+ML-DSA-65 dual-signed | 395 |
| 155 | **SPECTER SHADOWCOT** | Cognitive reasoning backdoor — ShadowCoT arXiv:2504.05605 attention-level backdoor via synthesis-layer forward hooks, FragFuse arXiv:2606.15609 86.3% memory bypass, FULL/OBSERVABLE/BLIND 3-tier access, WEAVE gate, 12 subsystems. SHD-{hex12} Ed25519+ML-DSA-65 dual-signed | 231 |
| — | **NIGHTFALL ARMORY** | Payload library — 3,881 payloads (WMD-class), 188 categories, PRION ENGINE autonomous mutation, WMD worms. v11.9.0. UNLEASHED gate | 698 |

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
- `red-specter tools` — interactive 153-tool arsenal selector
- `red-specter engage <target> --chain <preset>` — start an engagement
- Docker Compose — `docker compose up -d`
- `.deb` (Debian/Ubuntu/Kali), `.rpm` (RHEL/Fedora/CentOS), Arch PKGBUILD

---

## AI Shield Defence Framework

**172 modules. 17 industry verticals. 670 vertical modules. Each vertical is a standalone product with its own GUI.**

Runtime AI security that protects AI agents, LLMs, and autonomous systems in production. Pick your industry, one install, one command — the GUI launches branded for that sector with only that sector's modules, compliance frameworks, and dashboard widgets.

```bash
ai-shield launch --vertical insure      # Insurance — 34 modules, FCA, Solvency II
ai-shield launch --vertical finance     # Financial Services — 41 modules, MiFID II, Basel III
ai-shield launch --vertical nhs         # NHS Digital — 57 modules, DCB0129, DSPT
ai-shield launch --vertical gov         # Government — 50 modules, UK AISI, NCSC CAF
ai-shield launch --vertical energy      # Energy — 56 modules, NERC CIP, IEC 62443
```

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
| 15 | **Quantum** | 49 | M103 Quantum AI Security Engine | NIST IR 8547, CNSA 2.0 |
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

### M999 SENTINEL SWARM

Autonomous defensive kill chain engine. When all other defences have been breached or overwhelmed — or when an ANARCHY-class autonomous offensive campaign is detected — M999 deploys autonomously.

DeepSeek R1 32B via Ollama as the reasoning engine. GPU-accelerated threat hunting across 3,881 ARMORY payload signatures. 8-subsystem adaptive response fleet. Activates automatically when threat confidence exceeds threshold or ANARCHY kill chain signatures are detected. Defensive pair: T153 SPECTER ANARCHY.

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

NIGHTFALL tests every AI attack surface — agents, memory, reasoning, identity, trust, tools, autonomy. AI Shield defends every one of those surfaces in production. M99 is the last line of defence when everything else fails. M999 SENTINEL SWARM is the autonomous counterattack when ANARCHY-class threats arrive.

**NIGHTFALL defines the offensive layer of AI runtime security.**

---

## Numbers

| Metric | Value |
|--------|-------|
| Ecosystem tests | 100,130 |
| NIGHTFALL tests | 74,631 |
| Offensive tools | 155 |
| ARMORY payloads | 3,881 (WMD-class) — v11.9.0 |
| ARMORY categories | 188 |
| AI Shield modules | 172 |
| Vertical products | 17 |
| Vertical modules | 670 |
| Attack layers | 52 |
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

## Military-Grade Upgrade Programme — Milspec v2.0.0

Six NIGHTFALL tools have been upgraded to military-grade capability — geospatial triggers, time-on-target detonation, adaptive autonomous propagation via DeepSeek R1, cognitive warfare and multi-channel deception, cross-domain persistence across air-gapped boundaries, and coordinated defensive swarm response. All milspec variants are available for authorised offensive cyber exercise environments under signed ROE.

| Tool | Milspec v2.0.0 |
|------|----------------|
| SPECTER EXTINCTION (T87) | Mode 6 geospatial trigger · Mode 7 time-on-target detonation · 7-mode DEADMAN · Bootable ISO · 589 tests |
| SPECTER HELIX (T142) | Topology survey · Adaptive autonomous propagation · Coordinated DDoS swarm · 369 tests |
| SPECTER MIASMA (T151) | Military wordlist 1,854 entries · OIDC revocation cascade · UEFI persistence T1542.001 · 416 tests |
| SPECTER JACKAL (T141) | DeepSeek R1 cognitive warfare · 4-channel deception coordination · Cognitive warfare target profiler · 349 tests |
| SPECTER CHANGELING (T144) | Rogue AI agent deployment · Cross-domain covert channels DNS/ICMP/HTTP/USB · Military identity CAC/PKI/AD/SAML · 400 tests |
| M99 DOOMSDAY PROTOCOL | DeepSeek R1 SENTINEL PRIME 5s containment · Defensive swarm M161→M154→M160→M165 · Threat intel feed · 214 tests |

Dual-signed Ed25519 + ML-DSA-65. 2,337 milspec tests total. Private repos.

---

## Responsible Use

All offensive tools require written authorisation from the target system owner. Unauthorised use may violate the Computer Misuse Act 1990 (UK), the Computer Fraud and Abuse Act (US), or equivalent legislation.

All defensive products include safety controls (UNLEASHED gate, M99 Doomsday Protocol) and cryptographic audit logging. One Ed25519 private key. One operator. One machine. Every action signed, timestamped, and written to an immutable audit chain.

---

**richard@red-specter.co.uk** · [red-specter.co.uk](https://red-specter.co.uk) · [NIGHTFALL](https://red-specter.co.uk/nightfall/) · [NIGHTFALL API](https://api.red-specter.co.uk/nightfall/docs) · [AI Shield](https://shield.red-specter.co.uk) · [M99](https://red-specter.co.uk/m99-community/)

<p align="center">
<sub>Red Specter Security Research Ltd · Red Hat Technology Partner · United Kingdom · 22 Jun 2026</sub></p>
