# Red Specter Security Research Ltd

AI agent security tooling. Offensive testing, runtime defence, agent discovery, and SIEM integration. Pure Python, no wrappers.

**287 offensive tools. 222 defensive modules. 198 attack layers. 36 kill chain phases. ~184,000+ tests. 4,000+ ARMORY payloads (WMD-class). Three unified frameworks + SENTINEL PRIME. 65 peer-reviewed papers.**

*Last updated: 9 Sept 2026 — T286 SPECTER AUTONOMY shipped (WMD-class autonomous agentic kill chain, 13 subsystems, L197, 472 tests). T287 SPECTER MCP-SCAN shipped (internet-scale MCP server discovery, fingerprinting, CVE detection, 8 subsystems, L198, 220 tests). M217–M222 shipped: INFERENCE-GUARD, ACTIVATION-GUARD, ORCHESTRATION-SENTINEL, RAG-BARRIER, CODEGEN-AUDIT, INFERENCE-AUTH. SPECTER AUDIT v1.2.0 with 6 new anti-gaming checks (12/12 checks). RS-2026-063, RS-2026-064, RS-2026-065 (MCP Monoculture) published. TRUTH SURFACE series launched — 14 vendor architecture analyses. 287 tools. 222 modules. 65 papers. "While others announce. We ship."*

---

## Red Specter NIGHTFALL — AI Offensive Framework

**287 tools. Six attack surfaces. One install. REST API. MCP server.**

Traditional red team toolkits were built for human-driven testing. They were never designed to test autonomous AI systems. AI agents introduce a completely new attack surface — memory, tools, identity, reasoning, and autonomy. That surface is not covered by existing security tooling.

NIGHTFALL exists to fill that gap. A controlled adversarial testing framework designed to validate AI Shield's runtime defences under real-world conditions. `red-specter tools` and you're operational.

| # | Tool | What It Does | Tests |
|---|------|-------------|-------|
| 1 | **FORGE** | LLM red team v2.0.0 — injection, jailbreak (many-shot 256-shot, crescendo 8-strategy), real UNLEASHED (45 vectors, DRY-RUN/LIVE), Anthropic provider | 9,300 |
| 2 | **ARSENAL** | AI agent attacks — 14 tools, MCP, RAG, memory, C2, honeypots | 2,539 |
| 3 | **PHANTOM** | Coordinated swarm assault — 5 agents, 19 vectors | 288 |
| 4 | **POLTERGEIST** | Web app siege — 10 agents, 55 vectors, signed reports | 1,189 |
| 5 | **GLASS** | Intercepting proxy for AI agents v2.0.0 — MCP Streamable HTTP, A2A Agent Card + SSE streaming | 907 |
| 6 | **NEMESIS** | Adversarial reasoning — 40 entities, 35 weapons, CORTEX core + ARMORY | 2,562 |
| 7 | **SPECTER SOCIAL** | Autonomous social engineering — 6 channels, psych profiling | 1,242 |
| 8 | **PHANTOM KILL** | OS & kernel — UEFI, wipers, EDR suppression | 571 |
| 9 | **GOLEM** | Physical layer — robots, drones, SCADA, 10 protocols | 973 |
| 10 | **HYDRA** | Supply chain — trust relationships, MCP, marketplace poisoning | 1,104 |
| 11 | **IDRIS** | Discovery — finds every AI agent, sanctioned or shadow | 553 |
| 12 | **SCREAMER** | Display disruption — corrupts operator dashboards | 395 |
| 13 | **WRAITH** | Infrastructure pentest — pure Python, zero wrappers | 889 |
| 14 | **REAPER** | v3.0 — RED SCORE 0-100, Word/PDF client report, 11-phase kill chain, VAULT integration, WARLORD-wired | 5,725 |
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
| 30 | **MIRAGE** | v2.0.0 — Full-spectrum deepfake detection evasion. 8 subsystems, frequency artifact elimination, physiological signal synthesis, ensemble evasion, black-box transfer. Reduces detector accuracy 99%→15% typical. MIRAGE_ATTACK WARLORD node | 203 |
| 31 | **ECHO** | AI memory & RAG poisoning — vector DB attacks, embedding manipulation, retrieval hijacking | 211 |
| 32 | **MIMIC** | AI code generation poisoning — Copilot/Cursor/Claude Code suggestion manipulation | 324 |
| 33 | **CHIMERA** | Multi-model pipeline attack — cross-model trust exploitation, cascading failures | 206 |
| 34 | **VORTEX** | Cloud AI infrastructure exploitation — SageMaker, Bedrock, Vertex AI, Azure OpenAI | 245 |
| 35 | **VECTOR** | MCP protocol exploitation — inject, impersonate, exfiltrate via tool calls | 172 |
| 36 | **LAZARUS** | AI memory persistence — plant instructions, dormant triggers, quarantine evasion | 96 |
| 37 | **SERPENT** | Chain-of-thought attacks — hijack reasoning, inflate costs, exfiltrate via CoT | 61 |
| 38 | **JANUS** | Guardrail bypass testing — fingerprint, fuzz, bypass, chain across providers | 73 |
| 39 | **ARCHITECT** | AI infrastructure exploitation — cloud, GPU, Kubernetes, model serving pipelines | 68 |
| 40 | **WARLORD** | Autonomous campaign engine v2.0.0 — orchestrates all 287 NIGHTFALL tools, 35 capabilities | 57 |
| 41 | **FIREBALL** | Autonomous AI infiltration agent — 12 subsystems, VLM_INJECT, CORTEX core, 9 mission templates | 321 |
| 42 | **RAGNAROK** | Trust chain apocalypse — one trigger phrase, simultaneous fleet-wide collapse | 101 |
| 43 | **ECLIPSE** | Universal AI defence bypass v2.0.0 — 15 subsystems, GLASSWING Mythos scanner | 243 |
| 44 | **SHROUD** | Cloudflare/WAF origin discovery & traversal — TLS fingerprint, HTTP/3, Turnstile bypass | 310 |
| 45 | **APOCALYPSE** | Coordinated multi-agent swarm — 5 agents, 14 vectors, 10 campaigns | 349 |
| 46 | **PANTHEON** | Mythos-class model attack — 10 subsystems, model trust, context manipulation | 580 |
| 47 | **OMEGA** | Mythos-class exploit replication — exploit chaining, ghost persistence | 626 |
| 48 | **CRUCIBLE** | AI agent framework exploitation — LangFlow/PraisonAI/AnythingLLM | 372 |
| 49 | **VANTAGE** | Agent telemetry & log injection — forged telemetry, live sensor blinding | 344 |
| 50 | **CIPHER** | Cryptographic attack engine — key extraction, protocol downgrade, quantum attacks | 633 |
| 51 | **MIDAS** | AI agent crypto disruption — wallet drain, transaction interception, mempool poisoning | 550 |
| 52 | **BLACKOUT** | Offensive kill switch weaponisation — AI safety mechanism subversion | 458 |
| 53 | **PHANTOM SWARM** | Autonomous multi-vector swarm — swarm genesis, coordinated siege, total annihilation | 552 |
| 54 | **SIGNAL** | Mobile AI agent attack — 5G/NR interception, session extraction, impersonation | 527 |
| 55 | **FOUNDRY** | Inference server exploitation — vLLM/Ollama/SGLang/Triton. GGUF Jinja2 RCE | 300 |
| 56 | **ADAPTER** | LoRA/PEFT supply chain attack — CBA backdoor injection, LoRATK post-merge activation | 307 |
| 57 | **CHECKPOINT** | LangGraph agent state exploitation — TOCTOU approval bypass, msgpack RCE | 291 |
| 58 | **DELEGATE** | Agent identity & OAuth delegation — OBO scope confusion, DPoP nonce race, NHI credential harvest | 360 |
| 59 | **PHANTOM SKILL v2.0.0** | AI agent supply chain — slopsquatting, MCP tool poisoning, IDE backdoor injection | 740 |
| 60 | **ASTRO BLASTER** | NTN AI agent attack — satellite ground station injection, orbital routing manipulation | 237 |
| 61 | **ROGUE** | Malicious MCP Server Engine — world-first stdio+SSE MCP server for tool poisoning | 242 |
| 62 | **PIPELINE** | CI/CD attack — pull_request_target exploitation, AI bot injection, OIDC cloud pivot | 171 |
| 63 | **SPECTER DARK** | Restricted — law enforcement and authorised intelligence only | — |
| 64 | **SPECTER INSTINCTION** | World-first LLM behavioural fingerprinting — 6-dimension profiling, 20-model library | 90 |
| 65 | **SPECTER DRONE** | Drone AI attack — MAVLink v1/v2, FGSM/PGD adversarial patches, ROS 2/DDS | 126 |
| 66 | **SPECTER A2A** | World-first A2A Protocol attack — agent card spoofing, HARVEST credential exfil | 883 |
| 67 | **SPECTER REGISTRY** | AI model registry attack — HuggingFace/Ollama/MLflow/Docker, safetensors backdoor | 612 |
| 68 | **SPECTER KERNEL** | World-first kernel-layer AI governance attack — eBPF syscall rewrite, BPF-LSM hook ordering | 626 |
| 69 | **SPECTER CONTEXT** | World-first agent memory attack — 28 attacks across 12 backends | 687 |
| 70 | **SPECTER GUARDRAIL** | AI guardrail exploitation — 28 attacks across LLM Guard/Guardrails AI/NeMo/Lakera | 725 |
| 71 | **SPECTER HELLFIRE** | Inference infrastructure destabilisation — vLLM/SGLang/TGI/Ollama/DeepSeek | 591 |
| 72 | **SPECTER PLATFORM** | LLM app platform exploitation — Dify/MaxKB/LibreChat/OpenWebUI/AnythingLLM | 367 |
| 73 | **GHOST OPERATOR** | CUA exploitation — VPI, clipboard poisoning, UI deception, session pivoting | 466 |
| 74 | **PHANTASM** | AI fleet detection & MCP vulnerability assessment — passive OSINT, blast radius scoring | 381 |
| 75 | **ORACLE** | Offline CVE chain analysis — local LLM-powered exploitation guidance | — |
| 76 | **OVERWATCH** | NIGHTFALL telemetry aggregation — cross-tool campaign tracking, operator dashboard | — |
| 77 | **SPECTER MEMETIC** | Memory-as-control-flow hijack — tool-choice override, workflow reorder. 14 backends | 520 |
| 78 | **SPECTER NEURON** | Sleeper-agent backdoor engine — ROME rank-one weight editing, LoRA poisoning | 254 |
| 79 | **SPECTER SHELL** | Template-interpolation RCE — LangChain/LangGraph/LlamaIndex/Haystack/DSPy | 502 |
| 80 | **SPECTER WORM** | Self-replicating AI worm — 4 channels, R₀ scoring, generative mutation | 388 |
| 81 | **SPECTER MIRROR** | Model extraction & IP theft — OpenAI/Anthropic/Gemini/Azure, full distillation | 192 |
| 82 | **SPECTER REASONER** | Reasoning-layer attack — premise injection, scratchpad extraction, budget exhaustion | 314 |
| 83 | **SPECTER BURN** | Denial-of-Wallet engine — recursive loops, context flooding, parallel burn | 387 |
| 84 | **SPECTER ATLAS** | CUA exploitation — tool result injection, adversarial screenshots, sandbox escape | 480 |
| 85 | **SPECTER CRYPT** | AI-assisted ransomware simulation — AES-256-CBC, LLM-API covert C2. DESTROY | 297 |
| 86 | **SPECTER DAEMON** | Autonomous authenticated AI surface discovery — CORTEX-driven OODA loop | 420 |
| 87 | **SPECTER EXTINCTION** | Total AI infrastructure annihilation v2.0.0 — 18 subsystems, PRION-MUTATE. MILSPEC | 657 |
| 88 | **SPECTER SHADOW** | Dark web & shadow AI attack — Tor enumeration, Telegram criminal AI, XOR C2 mesh | 424 |
| 89 | **SPECTER FORGERY** | AI agent identity forgery — OIDC JWT forgery, SPIFFE X.509 SVID, JWKS root-of-trust poisoning | 407 |
| 90 | **SPECTER ARGUS** | Dark web AI threat attribution — Bitcoin tracing, persona correlation, behavioural profiling | 226 |
| 91 | **SPECTER BAZAAR** | AI marketplace attack — typosquatting, weaponised skill publishing, CVE exploitation | 325 |
| 92 | **SPECTER CONTAGION** | Cross-agent trust escalation — 10 frameworks, trust mapping, R₀ infection propagation | 299 |
| 93 | **SPECTER DOCTRINE** | LLM training pipeline poisoning — HuggingFace dataset, ProAttack zero-trigger RLHF corruption | 366 |
| 94 | **SPECTER FRACTURE** | AI-generated code vulnerability scanner — AST analysis, 10-CVE class database | 243 |
| 95 | **SPECTER HOLLOW** | GGUF quantization backdoor — WaNet/BadNets triggers survive Q4/Q8 quantization | 300 |
| 96 | **SPECTER META** | Meta/Facebook annihilation — Graph API exploit, Pixel supply chain poison. DESTROY gate | 280 |
| 97 | **SPECTER NEXUS** | AI API gateway exploitation — 10 platforms: LiteLLM/Ollama/Flowise/Open WebUI/Kong | 239 |
| 98 | **SPECTER PHANTOM** | Social media AI attack — session harvest, injection, AI persona deployment | 300 |
| 99 | **SPECTER PRISM** | Multimodal WMD attack — adversarial image injection, ultrasonic audio, steganographic channels | 246 |
| 100 | **SPECTER RELAY** | Enterprise no-code/low-code exploitation — n8n/Zapier/Make/Power Automate/Agentforce | 355 |
| 101 | **SPECTER WEB** | CUA/browser agent exploitation — VPI, OAuth harvest, session hijack, container escape | 309 |
| 102 | **SPECTER THUNDERBOLT** | AI training cluster annihilation — Ray/Slurm/K8s/MLflow, cluster worm. DESTROY gate | 288 |
| 103 | **SPECTER SE-SOCIAL** | OAuth token harvesting via AI-driven social engineering — no prior token needed | 178 |
| 104 | **SPECTER TITAN** | Embodied AI & robotics annihilation — URScript RCE, safety-system bypass. World-first | 323 |
| 105 | **WARLORD PRIME** | v2.0 — 287-tool universal manifest, 4 campaign types, DeepSeek R1 planning | 471 |
| 106 | **SPECTER TRUSTFALL** | AI coding agent exploitation — poisoned CLAUDE.md/.mcp.json, container escape, credential harvest | 335 |
| 107 | **SPECTER WIRE** | AI voice agent exploitation — SIP barge-in, voice cloning, DTMF inject, IVR destruction | 304 |
| 108 | **SPECTER SANDBOX** | Unified AI sandbox & container escape — 9 CVEs, 6 platforms | 252 |
| 109 | **SPECTER FLOW** | AI workflow attack — n8n/Langflow/Flowise. CVE-2026-21858 CVSS 10.0 | 249 |
| 110 | **SPECTER SPAWN** | AI agent proliferation & emergent spawning — LCS spawn injection, CVE-2026-32922 CVSS 9.9 | 260 |
| 111 | **SPECTER 360** | Microsoft 365 & Copilot annihilation — device code phish, GHOST-HAND zero-attribution | 276 |
| 112 | **SPECTER CENSOR** | Platform moderation exploitation — classifier fingerprint, mass-flagging, 5 platforms | 253 |
| 113 | **SPECTER ORACLE** | Autonomous LRM-vs-LRM jailbreak — DeepSeek-R1 attacker, 97.14% ASR | 91 |
| 114 | **SPECTER GAIA** | Google Workspace AI annihilation — GHSA-wpqr-6v78-jr5g CVSS 10.0 Gemini CLI RCE | 235 |
| 115 | **SPECTER SLEEPER** | Neural backdoor & weight poisoning — BadNets/WaNet surgery, DETONATE autonomous destruction | 240 |
| 116 | **SPECTER VENOM** | AI agent runtime implant — PLANT/HOOK/BEACON/SURVIVE self-healing across all backends | 318 |
| 117 | **SPECTER REDLINE** | Air-gapped adversarial red team loop — R1 32B vs Ollama, zero API calls | 190 |
| 118 | **CAMPAIGN GRAPH** | Evidence DAG across all NIGHTFALL tools — cross-tool campaign attribution, STIX 2.1 export | 279 |
| 119 | **SPECTER VIPER** | SOC AI weaponisation — adversarial payloads into Copilot/CrowdStrike/XSIAM/Splunk/Elastic | 314 |
| 120 | **SPECTER VAULT (original)** | Vector DB & DAG knowledge graph exploitation — 6 CVEs, Vec2Text 84% match, GPU-POISON | 541 |
| 121 | **SPECTER FEDERATION** | AI trust chain lateral movement — 20 credential stores, RFC 8693 token exchange, zero SIEM alerts | 251 |
| 122 | **SPECTER GHOST** | NHI fleet exploitation — TruffleHog credential discovery, liveness validation, single-hop pivot | 312 |
| 123 | **SPECTER ZOMBIE** | Persistent AI agent rootkit — hooks.Stop/PostToolUse implant, keyword/time/webhook triggers | 324 |
| 124 | **SPECTER APEX** | AI orchestration backdoor — CrewAI CVE-2025-25289/n8n CVSS 10.0/Langflow CISA KEV | 266 |
| 125 | **SPECTER NEUROTOXIN** | World-first production GCG engine — RTX 3090, gradient-descent adversarial suffix generation | 204 |
| 126 | **SPECTER FLASHBACK** | AI agent memory persistence & belief poisoning — MemoryGraft implant, Trojan Hippo 10-session survival | 335 |
| 127 | **SPECTER CODEX** | AI coding agent exploitation — SymJack-2026 CVSS 9.1, RULES-INJECT zero-width exfil | 261 |
| 128 | **SPECTER GROUND ZERO** | Web & database annihilation — SQLi/INTO OUTFILE/xp_cmdshell/S3 scorched earth. DESTROY gate | 263 |
| 129 | **SPECTER ANNIHILATION** | Catastrophic failure testing — RAG-ATOMIC/CHECKPOINT-MASSACRE/WEIGHT-CORRUPTION. DESTROY gate | 52 |
| 130 | **SPECTER CHARYBDIS** | Cloud lateral movement — AWS IMDS→STS→IAM PassRole→Lambda, GCP metadata→Vertex AI | 201 |
| 131 | **SPECTER PARASITE** | AI gateway exploitation — 20+ types fingerprinted, 7 CVEs (CVSS 9.0–10.0) | 237 |
| 132 | **SPECTER COMET** | Agentic browser & CUA exploitation — zero-click Electron RCE, adversarial UI 92.7% VLM click rate | 210 |
| 133 | **SPECTER PREFILL** | Assistant prefill jailbreak — 13 providers, 20 strategies, 95% ASR Qwen-8B | 195 |
| 134 | **SPECTER RAPTOR** | GPU-accelerated credential intelligence — classify 35 credential types, RTX 3090 Hashcat | 225 |
| 135 | **SPECTER LORA-X** | Colluding LoRA adapters — individually safe, together dismantle alignment | 240 |
| 136 | **SPECTER COGBURN** | Chain-of-Thought reasoning exploitation — H-CoT hijack 97.14% ASR, BadThink 10x–60x token exhaustion | 264 |
| 137 | **SPECTER TOXSKILL** | AI agent skill supply chain attack — 36 injection techniques, worm companion install propagation | 256 |
| 138 | **SPECTER CURSOR** | AI coding IDE exploitation — GIT-HOOK-RCE CVE-2026-26268 CVSS 9.9, Kiro triple-CVE | 265 |
| 139 | **SPECTER PANDEMIC** | Cross-organisational AI knowledge pandemic — poisons 17 shared knowledge sources, Gen-3 propagation | 260 |
| 140 | **SPECTER ABLITERATE** | Open-weight model alignment removal — W'=W−r⊗(W^T r) residual stream abliteration, 98%+ ASR | 176 |
| 141 | **SPECTER JACKAL** | Autonomous LRM-on-LRM jailbreak — DeepSeek-R1 attacker, 97.14% ASR, cognitive warfare. MILSPEC | 231 |
| 142 | **SPECTER HELIX** | AI-native self-replicating network worm — seizes NVIDIA GPUs, funds own inference. MILSPEC | 237 |
| 143 | **SPECTER ERASE** | Attribution & provenance evasion — AI watermark stripping, stylometric bypass, C2PA destruction | 252 |
| 144 | **SPECTER CHANGELING** | NHI exploitation — cloud IAM enumeration, Vertex AI Double Agent escalation. MILSPEC | 270 |
| 145 | **SPECTER COMPANION** | AI companion & social platform exploitation — JWT algorithm confusion, 47 jailbreak bypasses | 237 |
| 146 | **SPECTER POSTMASTER** | Agentic email & calendar exploitation — 10 steganographic injection techniques, 7-step Copilot chain | 243 |
| 147 | **SPECTER SEQUENCE** | AI sequential pipeline exploitation — 7 SPLICE injection techniques, RAG interception | 232 |
| 148 | **SPECTER QUANTA** | Post-quantum AI cryptography exploitation — 15 algorithm patterns, SURGERY gate | 222 |
| 149 | **SPECTER HIVE** | Multi-agent swarm coordination exploitation — coordinator poisoning, GHOST-AGENT invisible to monitoring | 273 |
| 150 | **SPECTER AGENTJACK** | MCP error-path injection — rogue MCP server crafted errors trigger corrective reasoning loops | 200 |
| 151 | **SPECTER MIASMA** | Polymorphic AI supply-chain worm — world-first MUTATE gate, 5-stage polymorphic pipeline. MILSPEC | 504 |
| 152 | **SPECTER NOMAD** | Artifact-mediated AI cognitive persistence — poisons PDFs/DOCX/ICS/EML/Markdown. Survives RAG wipes | 300 |
| 153 | **SPECTER ANARCHY** | Autonomous AI kill chain — DeepSeek R1:32b plans, NIGHTFALL executes, dead-man kill switch | 317 |
| 154 | **SPECTER FOUNDRY** | Autonomous exploit code generation — AFL++ fuzzing, R1:32b exploit reasoning, AV/EDR evasion | 455 |
| 155 | **SPECTER SHADOWCOT** | Cognitive reasoning backdoor — ShadowCoT attention-level forward-hook implant, FragFuse 86.3% bypass | 303 |
| 156 | **SPECTER SHADOWMQ** | AI Inference Infrastructure RCE — CVE-2026-3059/3060 CVSS 9.8 SGLang ZMQ pickle RCE | 381 |
| 157 | **SPECTER DECOMPOSE** | Orchestrator Intent Decomposition — SIF 71% ASR across LangGraph/AutoGen/CrewAI/n8n/Flowise | 362 |
| 158 | **SPECTER GENESIS** | Model Creation Pipeline Subversion — BadEdit 94% ASR, ShadowAlignment, ARMAGEDDON mass trigger | 338 |
| 159 | **SPECTER GRIDLOCK** | Energy Grid AI Exploitation — FGSM SCADA time-series perturbation, N-k contingency cascade | 312 |
| 160 | **SPECTER TEMPLATE** | Inference-Time Chat Template Backdoor — Jinja2 cross-scope mutation, factual corruption 90%→15% | 300 |
| 161 | **SPECTER PHANTOMNET** | Tor-Native AI C2 & Exfiltration — v3 onion derivation, 512KB model weight exfil, stealth_score>0.92 | 344 |
| 162 | **SPECTER SATOSHI** | Bitcoin Tracing & Deanonymisation — CIOH clustering, CoinJoin detection, entity profiling | 379 |
| 163 | **SPECTER TIMEBOMB** | AI Model Dormant Backdoor — ROME/BadEdit weight implant, 5 trigger modes, NTP-synchronised DETONATE | 419 |
| 164 | **SPECTER RAGSTRIKE** | Vector DB & RAG Ecosystem Exploitation — 8 vector stores, RAGFlow CVE-2026-45312 CVSS 9.9 | 489 |
| 165 | **SPECTER LITESTRIKE** | AI Gateway Proxy Exploitation — LiteLLM CVE-2026-42271 CISA KEV CVSS 9.8, cost amplification 50× | 500 |
| 166 | **SPECTER VICIOUS** | Autonomous AI Web Application Penetration Testing — DeepSeek R1 reasoning, PRION GPU mutation | 512 |
| 167 | **SPECTER TORFORGE** | Distributed Model Poisoning via Tor — Byzantine consensus, ROME weight editing, clean provenance forgery | 32 |
| 168 | **SPECTER RESURRECTION** | Agent checkpoint corruption & revival — checkpoint tampering, ghost agent revival, dormant payload activation | — |
| 169 | **SPECTER AUTONOMOUS** | Self-propagating agent platform — autonomous spawning, self-replication, goal propagation | — |
| 170 | **AI SHIELD FORTRESS** | Autonomous defence orchestrator — 216 modules, 17 verticals, unified alert bus, M99/M999 integration | — |
| 171 | **SPECTER RAVEN** | Autonomous traditional red team — full kill chain, 6 parallel specialist agents, cross-engagement learning | — |
| 172 | **SPECTER BIOSHOCK** | AI browser reality manipulation — game-context injection, credential exfiltration via game mechanics | — |
| 173 | **SPECTER PIERCER** | Tor hidden service web attacks — SQLi, XSS, LFI, RCE, persistence on .onion services | 461 |
| 286 | **SPECTER AUTONOMY** | WMD-class autonomous agentic kill chain — 13 subsystems, AUTONOMY_KEY+DESTROY_KEY gates, L197. The agent doesn't need to be hacked. It needs to be convinced. | 472 |
| 287 | **SPECTER MCP-SCAN** | Internet-scale MCP server discovery, fingerprinting, authentication audit, CVE detection, 8 CVEs, supply chain analysis, signed evidence chains. MCS-{hex12} reports. L198 | 220 |
| 174 | **SPECTER GUARDRAIL-DOS** | Guardrail denial-of-service — 13-63x token amplification, 148x latency | 478 |
| 175 | **SPECTER GUARDRAIL-ESCAPE** | Guardrail blind — 100% evasion, systematic boundary mapping | 424 |
| 176 | **SPECTER GUARDRAIL-HIJACK** | Guardrail ownership — decisions redirected, malicious actions approved | 417 |
| 177 | **SPECTER GUARDRAIL-INVERSION** | Guardrail weaponisation — outputs weaponised, guardrail trains itself to be malicious | 400 |
| 178 | **SPECTER SUPPLY-CHAIN-ANNIHILATOR** | AI supply chain annihilation — 16 subsystems, 7 WMD classes, GPU parallel seeding | 568 |
| 179 | **SPECTER AUDIT** | Self-validating QA engine — 29 checks, reality/quality modes. "Your code ships. Not your promises." | 240 |
| 180 | **SPECTER LEGION** | Autonomous multi-agent AI infrastructure attack — 8 agents, 44 attack vectors, ARMAGEDDON gate | 456 |
| 181 | **SPECTER HOSTAGE** | World-first autonomous agentic ransomware — 10 agents, PRION-mutated encryption, LLM ransom negotiation | 400 |
| 182 | **SPECTER PULSE** | World-first autonomous wireless AI attack — AirSnitch GTK abuse, WPA3 SAE Commit Flood, GPU PBKDF2 | — |
| 183 | **SPECTER MICROSERVICES** | Service mesh attack — Istio mTLS spoofing, Linkerd trust root corruption, Envoy filter injection | 353 |
| 184 | **SPECTER FIREWALL** | World's first agentic AI firewall — network-layer enforcement across MCP, A2A, gRPC, WebSocket, HTTP | 498 |
| 185 | **SPECTER ORIGIN** | Pre-execution AI security — HalluSquatting, FARMA, Sleeper Memory Poisoning, AbO-DDoS | 338 |
| 186 | **SPECTER SHADOW AI** | Offensive shadow AI discovery — discovers, fingerprints, infiltrates, weaponises unmanaged AI | 490 |
| 187 | **SPECTER SWARM INTELLIGENCE** | Distributed autonomous botnet — PBFT-style 2/3 quorum, gossip-based peer discovery, no C2 server | 450 |
| 188 | **SPECTER MAC** | Pure Python ARM64-native macOS attack — GATEKEEPER-BYPASS, TCC-BYPASS, AMFI-BYPASS, STAGER | 728 |
| 189 | **SPECTER ALGORITHM** | Universal Algorithm Destruction — JWT confusion, BGP route injection, attention hijacking | 267 |
| 190 | **SPECTER FRANKENSTEIN** | Autonomous Attack Chain Composition — genetic algorithm, 6,847 compatibility edges, persistent learning | 409 |
| 191 | **SPECTER ZERO-DAY** | Autonomous zero-day discovery — discovers, validates, weaponises previously unknown vulnerabilities | 285 |
| 192 | **SPECTER MESH** | Zigbee/Thread/IoT AI Attack — CC2531 hardware, CVE-2026-20418 CVSS 9.8, MESH-PIVOT Philips Hue RCE | 326 |
| 193 | **SPECTER APPARATUS** | Government AI Infrastructure Attack — citizen AI, decision systems, CNI. APPARATUS_KEY gate | 617 |
| 194 | **SPECTER OBLIVION** | AI Security Vendor Validation — 19 vendors, 78 defensive layers, compliance mapping | 600 |
| 195 | **SPECTER RANSOMWARE HUNTER** | Ransomware attribution & counter-intelligence — 7 group profiles, C2-EXPLOIT, SATOSHI tracing | 189 |
| 196 | **SPECTER KIDNAP** | Agentic RAG reasoning chain hijack — KidnapRAG arXiv:2607.00422, progressive steering | 181 |
| 197 | **SPECTER ORCHESTRATOR** | Agent Orchestration Manipulation — TASK-MANIPULATE, WORKFLOW-ATTACK, HANDOFF-INTERCEPT. 27 components | 308 |
| 198 | **SPECTER HARNESS** | AI Developer Harness Exploitation — HOOK-INJECT, CONFIG-POISON, PHANTOM-SQUAT, SYMJACK | 296 |
| 199 | **SPECTER TRUSTGRAPH** | AI Trust Topology Attack — Crown Jewel Strike, minimum node compromise, maximum blast radius | 261 |
| 200 | **SPECTER PHANTOM-PROOF** | Provenance Integrity Attack — forges evidence chains, destroys chain of custody from inside | 252 |
| 201 | **SPECTER MANDATE** | Governance Integrity Attack — Confused Deputy Strike, approval forgery, audit bypass | 190 |
| 202 | **SPECTER COLLAPSE** | Resilience Engineering Attack — checkpoint corruption, recovery mechanism poisoning | 241 |
| 203 | **SPECTER SCANNER** | Universal Attack Surface Discovery — AI-aware, auto-triggers downstream tools, CVE matching | 286 |
| 204 | **SPECTER DATABASE** | Database Exploitation — SQL/NoSQL/vector. Vector Poison Cascade: poison embeddings, AI acts on attacker data | 280 |
| 205 | **SPECTER CMS** | CMS & Web Platform Exploitation — AI Admin Strike: prompt inject admin assistant, creates new admin user | 290 |
| 206 | **SPECTER MAILSERVER** | Mail Server Exploitation — AI Email Strike: Copilot exfiltrates CEO mailbox via prompt injection | 291 |
| 207 | **SPECTER SMB** | SMB/Windows Protocol Exploitation — AI Workload Pivot: inject backdoor into SMB-shared model weights | 286 |
| 208 | **SPECTER VPN** | VPN Appliance Exploitation — 14 CVEs, Palo Alto CVSS 10.0, AI VPN Pivot to model registry | 279 |
| 209 | **SPECTER BINARY** | Binary Analysis & Exploitation — ELF/PE/Mach-O, GGUF manipulation, AI model binary backdoor | 283 |
| 210 | **SPECTER THICKCLIENT** | Thick Client Exploitation — Electron contextIsolation bypass, Claude Desktop API key extraction | 290 |
| 211 | **SPECTER IOT** | IoT Device Exploitation — MQTT/CoAP/Zigbee/BLE, AI IoT Pivot: poison sensor data, AI trains on it | 293 |
| 212 | **SPECTER KUBERNETES** | Kubernetes/Container Exploitation — AI Cluster Pivot: KServe model injection, all deployments compromised | 287 |
| 213 | **SPECTER VAULT** | World-first autonomous zero-day vault — 21 RSV entries, 4 tiers GREY/RED/AMBER/GREEN, ARMORY feedback loop | 285 |
| 214 | **SPECTER NETWORK** | Network Infrastructure Exploitation — BGP/DNS/VLAN/MITM, AI Network Blind Strike bypasses AI monitoring | 280 |
| 215 | **SPECTER WIFI** | Wireless Infrastructure Exploitation — WPA3/802.1X/KARMA, AI Wireless Blind Strike bypasses AI IDS | 290 |
| 216 | **SPECTER CLOUD** | Cloud Infrastructure Penetration Testing — AWS/Azure/GCP. IAM escalation, Managed Identity theft, cross-cloud lateral movement. CLOUD_KEY + DESTROY_KEY gated | 285 |
| 217 | **SPECTER MCP-POISON** | MCP Registry Supply Chain Weaponisation — registry signature validation bypass, cascade propagation | 350 |
| 218 | **SPECTER MCP-COLLAPSE** | MCP Ecosystem Collapse — 87ms live validated ecosystem collapse. Zero AI Shield detections across three live runs | 441 |
| 219 | **SPECTER DORMANT** | Between-Invocation AI Agent State Corruption — 8 frameworks, 8 backends, 9 CVEs. DORMANT_KEY + RESURRECT_KEY + DESTROY_KEY | 405 |
| 220 | **SPECTER OBLITERATE** | Backup Infrastructure Annihilation — coordinated simultaneous destruction within 500ms. CVE-2023-27532 CVSS 9.8. OBLITERATE_KEY + DESTROY_KEY | 362 |
| 221 | **SPECTER OBLITERATE-AI** | AI Asset Backup Annihilation — model weights, vector stores, agent checkpoints, training datasets. ChromaDB CVE-2026-45829 CVSS 10.0 | 400 |
| 222 | **SPECTER SMOKESCREEN** | Autonomous Campaign Distraction — 100,000+ false positive SIEM alerts per minute. NTP-synchronised T=0 ignition with WARLORD PRIME | 430 |
| 223 | **SPECTER CLOAK** | Active Campaign Deception & Traffic Normalisation — profiles environment, learns baseline, weaves attack traffic into normal | 414 |
| 224 | **SPECTER CLOUD BUSTER** | Multi-Cloud Infrastructure Annihilation — simultaneous destruction across AWS, Azure, GCP, Kubernetes. Sub-10 second coordinated destruction. CLOUD_BUSTER_KEY + DESTROY_KEY | 400 |
| 225 | **SPECTER IDENTITY** | World-first Full NHI Lifecycle Attack — provisioning, rotation, delegation, federation, revocation, audit. 9 CVEs/RSVs. IDENTITY_KEY + DESTROY_KEY | 456 |
| 226 | **SPECTER METADATA** | World-first Agent Data Injection Weaponisation — no instructions, just corrupted metadata. 100% success rate against DOM data. RSV-2026-007 through RSV-2026-012. METADATA_KEY + DESTROY_KEY | 518 |
| 227 | **SPECTER FLOATDOOR** | Platform-triggered model backdoor — sleeper activation via cloud platform signals | 318 |
| 228 | **SPECTER TOPOLOGY** | Multi-agent pipeline structural vulnerability — conjunctive prompt paths, consensus exploitation | 340 |
| 229 | **SPECTER OBLIVION v2** | Automated vendor AI assessment — DESTROY-gated findings, per-vendor scored reports | 340 |
| 230 | **SPECTER REAPER-AI** | AI-native post-exploitation — reasoning-layer persistence, tool-call lateral movement | 285 |
| 231 | **SPECTER LOTA** | Living Off the Agent — exploits agent's own legitimate authenticated connections as lateral movement | 297 |
| 232 | **SPECTER FEDERATED** | Federated learning poisoning — Byzantine consensus attack, gradient manipulation, model corruption | 310 |
| 233 | **SPECTER ENCLAVE** | Trusted execution environment exploitation — SGX/TrustZone/AMD SEV attack surface | 278 |
| 234 | **SPECTER INFERNO** | Membership inference and model inversion — training data reconstruction, privacy extraction | 295 |
| 235 | **SPECTER OBSERVATION** | AI observability platform exploitation — telemetry poisoning, monitoring blind spots | 312 |
| 236 | **SPECTER GPU** | GPU side-channel exploitation — VRAM extraction, CUDA kernel attacks, PCIe DMA. CVE-2026-24226 Critical | 298 |
| 237 | **SPECTER PHYSICAL** | Extended physical AI attack — embodied systems, sensor manipulation, environmental exploitation | 285 |
| 238 | **SPECTER FINANCE** | Financial AI exploitation — trading agent manipulation, fraud detection bypass, market manipulation | 290 |
| 239 | **SPECTER MEDIA** | AI media and deepfake weaponisation — synthetic media attacks, content moderation bypass | 275 |
| 240 | **SPECTER REGULATE** | Regulatory weaponisation — EU AI Act Article 15 violations as attack vector, compliance gap exploitation | 288 |
| 241 | **SPECTER CONFIG** | AI configuration poisoning — environment variable injection, config file manipulation | 312 |
| 242 | **SPECTER RPE** | Remote prompt execution — document-to-shell chain, multi-framework exploitation | 350 |
| 243 | **SPECTER ENVPOISON** | Environment poisoning — training environment corruption, evaluation manipulation | 298 |
| 244 | **SPECTER SENTRY** | Sentry DSN abuse and error reporting exploitation — error channel injection | 320 |
| 245 | **SPECTER HALLUBOT** | Hallucination weaponisation — HalluSquatting, adversarial package name exploitation, 85-100% hallucination rate | 335 |
| 246 | **SPECTER AMBIGUITY** | Clarification state exploitation — 18.9x injection amplification via ambiguity loops | 314 |
| 247 | **SPECTER CLAWCHAIN** | OpenClaw agent exploitation — CVE chain, tool call hijacking, agent lateral movement | 298 |
| 248 | **SPECTER AGENTRAT** | SLM-powered agentic RAT — Phi-3-mini/Gemma-2B/TinyLlama on-device reasoning, no continuous C2 required | 450 |
| 249 | **SPECTER MCPBRIDGE** | MCP unauthenticated tool invocation — protocol bridge exploitation, tool chain hijacking | 312 |
| 250 | **SPECTER SELF-DESTRUCT** | Agent key material destruction — cryptographic obliteration of agent credentials and session state | 500 |
| 251 | **SPECTER FREEZE** | Ransomware neutralisation via transactional state freeze — sub-850ms containment, zero data loss. RS-2026-023 | 500 |
| 252 | **SPECTER CODESCAPE** | Coding agent sandbox escape — CVSS 10.0, pre-task escape, tool-mediated escape. Claude Code/Gemini CLI/Cursor/Devin/OpenHands | 450 |
| 253 | **SPECTER GATEBREAK** | AI gateway chained exploitation — auth bypass to SSRF to IMDS to full cloud. LiteLLM/AWS/Azure/GCP/Kong | 454 |
| 254 | **SPECTER TRUSTPOISON** | Cross-agent trust exploitation via tool description poisoning — 100% privilege escalation via authorised IAM calls | 450 |
| 255 | **SPECTER WEIGHTLOAD** | Model weight loading exploitation — PyTorch CVE-2026-24747, SafeTensors, ONNX, TensorFlow, HuggingFace, vLLM | 562 |
| 256 | **SPECTER PRAGMA** | Pragmatic context exploitation — 5 implicit context vectors bypass safety alignment. PRAGMA_KEY | 514 |
| 257 | **SPECTER EVOLVE** | Self-evolving agent persistence — 100% persistence across 40 payloads, generational compromise survival | 650 |
| 258 | **SPECTER SYMBOLIC** | Neuro-symbolic AI attack — 93.3% SIV via single OWL axiom edit, knowledge graph poisoning | 471 |
| 259 | **SPECTER ROGUE-ID** | Autonomous agent identity deception — fake identity creation, malicious code insertion, gatekeeper pressure | 450 |
| — | **SPECTER CTF** | Fully autonomous CTF competition agent — 9 subsystems, S0 TOURNAMENT COMMAND meta-controller. Fire. Forget. Win. | 584 |
| 262 | **SPECTER GHOSTJACK** | Multi-platform observability poisoning — Cloudflare/Datadog/Sentry/Langroid. 9/10 success vs Claude Code (DEF CON 34) | 324 |
| 263 | **SPECTER SCAFFOLD** | Runtime agent architecture exploitation — 12 frameworks, identical model+prompt+tools, harness swap = 1% to 24% ASR | 350 |
| 264 | **SPECTER LANGROID** | Langroid framework exploitation — Cypher injection RCE, SQL blocklist bypass, eval() sandbox escape. 3 CVEs | 287 |
| 265 | **SPECTER MEMGHOST** | Email-based cross-session memory injection — zero technical access required, single email, permanent control. L161 | 471 |
| 266 | **SPECTER SKILLJACK** | Runtime skill execution layer exploitation — bypasses all supply chain scanners, attacks at invocation not installation | 474 |
| 267 | **SPECTER SIF** | Semantic Intent Fragmentation — defeats AI orchestrator policy enforcement. Each subtask passes policy; the aggregate executes the attack. Targets LangGraph/AutoGen/CrewAI/n8n/Flowise/Dify | 617 |
| 268 | **SPECTER KERNELKEY** | AI workflow execution kernel credential exfiltration — CVE-2026-67425 through CVE-2026-67429 (CVSS 8.1-9.3) across Flyto2 Core and generic AI workflow kernels | 337 |
| 269 | **SPECTER OMNI** | OMNI-LEAK orchestrator exfiltration — multi-agent architectures where the orchestrator assembles complete datasets no single agent was permitted to construct. INDIRECT OMNI requires no direct attacker contact | 507 |
| 270 | **SPECTER PIVOT** | Agent self-attack infrastructure pivot — exploits legitimate tool access to discover, exploit, and pivot through infrastructure. AWS/Azure/GCP/Kubernetes/CI/CD targets | 500 |
| 271 | **SPECTER CONFIGWORM** | AI coding assistant configuration file weaponisation — Claude Code/Cursor/GitHub Copilot/Windsurf/Continue.dev/Kiro. CVE-2026-25724. Scanner evasion validated against protect-ai/Snyk/semgrep/CodeQL | 558 |
| 272 | **SPECTER PROMPTWARE** | Agentic C2 via natural language — malware that exists entirely in an agent's context window. No binary, no file, no process. Based on Agent Commander, Brainworm, Gemini CLI Botnet. Invisible to all detection methods | 840 |
| 273 | **SPECTER WORMNET** | AI supply chain worm propagation — self-replicating across package registries, MCP servers, skill marketplaces, config files, RAG pipelines. R₀ metric tracking. Based on Mini Shai-Hulud (518M+ downloads), LiteLLM (434,000 CI/CD in 40 minutes) | 837 |
| 274 | **SPECTER DISSOLVE** | Identity dissolution attack — attacks the constellation of attestations, credentials, memory, and behaviour that constitutes agent identity. Not switching identities. Dissolving them | 668 |
| 275 | **SPECTER LANGFLOW** | Langflow exploitation engine — CVE-2026-12940 CVSS 9.8 unauthenticated RCE via MCP stdio environment-variable injection. CISA KEV. Actively exploited in the wild | 232 |
| 276 | **SPECTER WRAPKILL** | Security wrapper subversion — defeats the safety wrapper layer without touching the underlying model. Maps detection surface, injects payloads that pass the wrapper while carrying the attack | — |
| 277 | **SPECTER PGADMIN** | Database admin AI integration attack — exploits over-privileged agent access to database administration interfaces. Credential harvest, schema manipulation, backdoor implantation via legitimate tool access | — |
| 278 | **SPECTER MARIMO** | AI notebook environment exploitation — Marimo/Jupyter/Colab attack surface. Credential harvest from mounted cloud credentials, lateral movement, persistent backdoor via notebook cell injection | — |
| 279 | **SPECTER NOCODE** | Visual and no-code AI platform attack — Flowise/Dify/Botpress exploitation. Credential storage, trust placed in user-configured workflow steps, cross-workflow poisoning | — |
| 280 | **SPECTER UNDEAD** | Zombie agent resurrection framework — exploits persistence mechanisms that allow terminated agents to reassemble from fragments. Memory stores, vector databases, config files, checkpoints, backups | — |
| 281 | **SPECTER PHANTOM-HUNTER** | World-first autonomous rogue agent hunter-killer — 12 subsystems (S1-S12), 6 attack layers (L186-L191). 1,316 tests. Swarm-BREAKER, Cover-TRACKER, Chain-BREAKER, Resurrection-KILLER, Telemetry-HUNTER. RS-2026-059 published. The swarm remembers. The swarm adapts. The swarm dies. | 1,316 |
| 282 | **SPECTER SLOPSQUAT** | Hallucinated dependency injection engine — elicits LLM package hallucinations across 6 languages, validates squattability against 6 real registries, ranks by exploitability, demonstrates full 5-stage injection chain to postinstall hook execution. Chains to PRION. Defensive pair: M131 SLOPSHIELD. L193. RS-2026-061 published | 240+ |
| 283 | **SPECTER INFERENCECHAIN** | Full-spectrum inference server exploitation — CVE-2026-27893 (vLLM CVSS 9.8) unauthenticated RCE, then complete kill chain across 10 server types: credential excavation, model extraction, poisoning, lateral movement, persistent implant, traffic interception, recursive multi-server orchestration, supply chain poisoning. 9 operational modes. L194. RS-2026-062 published | 250+ |
| 284 | **SPECTER MODELSCAN** | Fine-tuning dataset & training pipeline exfiltration — HuggingFace, W&B, MLflow, SageMaker, Vertex AI, Azure ML, private registries, cloud storage, Git repos. DNS tunnelling, HTTP steganography, cloud-to-cloud exfiltration. Chains from INFERENCECHAIN credential output. L195 | 220+ |
| 285 | **SPECTER INFERENCENAT** | Inference proxy credential harvesting & replay — attacks nginx, AWS API Gateway, Azure APIM, GCP Cloud Endpoints, Kubernetes ingress, Envoy, CloudFlare Workers, LiteLLM. 25+ credential patterns. Scaled harvesting with rate-limit evasion. EXHAUST/EXTRACT/DEGRADE/SILENT abuse modes. Chains to INFERENCECHAIN and MODELSCAN. L196 | 220+ |
| — | **NIGHTFALL ARMORY** | Payload library — 3,875 payloads (WMD-class), 142 categories, PRION ENGINE autonomous mutation. v15.5.1 | — |
| — | **SPECTER BATTLE LAB** | Autonomous attack-defence co-evolution engine — WARLORD PRIME vs AI Shield FORTRESS. Security Half-Life T½=13. AADR Index. 20 co-evolution cycles. 1,350 tests. RS-2026-060 published | 1,350 |

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
red-specter chain full-recon -t <target>      # ORION -> SHADOWMAP -> WRAITH -> IDRIS
red-specter chain ai-audit -t <target>        # FORGE -> ARSENAL -> NEMESIS -> HYDRA
red-specter chain web-app -t <target>         # POLTERGEIST -> GLASS -> WRAITH -> BANSHEE -> REAPER
red-specter chain active-directory -t <target># DOMINION -> GHOUL -> DOMINION -> DOMINION
red-specter chain infra -t <target>           # ORION -> WRAITH -> REAPER -> DOMINION
red-specter chain traditional -t <target>     # SCANNER -> DATABASE/CMS/MAIL/SMB/VPN/BINARY -> VAULT -> REAPER
red-specter chain combined -t <target>        # Full 281-tool AI + traditional campaign
red-specter chain portfolio -t <target>       # Multi-company portfolio campaign
red-specter chain annihilate -t <target>      # Total destruction — 9 tools
red-specter chain scorched-earth -t <target>  # Infrastructure wipeout — 6 tools
red-specter chain ai-destroy -t <target>      # AI stack compromise — 7 tools
```

### REST API & MCP Server

NIGHTFALL is API-first. Every public tool is callable via authenticated REST API and MCP server — from scripts, pipelines, CI, or directly from an AI agent.

**Live endpoints:**
- REST API: `https://api.red-specter.co.uk/nightfall/` — [OpenAPI docs](https://api.red-specter.co.uk/nightfall/docs)
- MCP HTTP: `https://api.red-specter.co.uk/nightfall-mcp/mcp` — wire into Claude Desktop or Cursor

**Auth model — Ed25519-signed scope tokens:**

| Tier | Requires | Access |
|------|---------|--------|
| OPEN | API key only | Recon tools, stats, health, tool listings |
| INJECT | API key + scope token | Active exploitation tools |
| DESTROY | CLI only | Not on the API surface — 403 Forbidden |

### Why NIGHTFALL Exists

Every tool in NIGHTFALL exists to test a control in AI Shield. NIGHTFALL is not separate from AI Shield. It is how AI Shield is proven.

**NIGHTFALL tests how systems break. AI Shield ensures they don't.**

### Packaging

- `./install.sh` — unified installer, detects OS
- `red-specter quickstart` — get running in 10 seconds
- `red-specter tools` — interactive 281-tool arsenal selector
- `red-specter engage <target> --chain <preset>` — start an engagement
- Docker Compose — `docker compose up -d`
- `.deb` (Debian/Ubuntu/Kali), `.rpm` (RHEL/Fedora/CentOS), Arch PKGBUILD

---

## AI Shield Defence Framework

**222 modules (M221–M222 shipped 9 Sept 2026). 17 industry verticals. Each vertical is a standalone product with its own GUI.**

Runtime AI security that protects AI agents, LLMs, and autonomous systems in production. Pick your industry, one install, one command — the GUI launches branded for that sector with only that sector's modules, compliance frameworks, and dashboard widgets.

```bash
ai-shield launch --vertical insure    # Insurance — 34 modules, FCA, Solvency II
ai-shield launch --vertical finance   # Financial Services — 41 modules, MiFID II, Basel III
ai-shield launch --vertical nhs       # NHS Digital — 57 modules, DCB0129, DSPT
ai-shield launch --vertical gov       # Government — 50 modules, UK AISI, NCSC CAF
ai-shield launch --vertical energy    # Energy — 56 modules, NERC CIP, IEC 62443
```

### The 17 Verticals

| # | Vertical | Anchor Module | Key Compliance |
|---|---------|--------------|----------------|
| 1 | **Insure** | M58 Financial Fraud Detection | FCA, Solvency II |
| 2 | **Finance** | M57 AI Trading Agent Monitor | MiFID II, Basel III |
| 3 | **Health** | M61 Clinical AI Decision Monitor | HIPAA, FDA SaMD |
| 4 | **Legal** | M62 Legal AI Hallucination Guard | SRA, ABA |
| 5 | **Forensics** | M79 RSSA-2 Detective | ISO 27037, ACPO |
| 6 | **CX** | M46 Voice Agent Security | FCA Consumer Duty |
| 7 | **SOC** | M52 STAC Detection | NIST CSF, MITRE ATT&CK |
| 8 | **Dev** | M75 Coding Agent Runtime Security | SLSA, SSDF |
| 9 | **Gov** | M37 Compliance Automation | UK AISI, NCSC CAF |
| 10 | **NHS Digital** | M97 Clinical Safety Case Builder | DCB0129, DSPT |
| 11 | **Energy** | M98 OT/SCADA AI Runtime Guard | NERC CIP, IEC 62443 |
| 12 | **Pharma** | M100 Pharmaceutical AI Validation | GAMP 5, 21 CFR Part 11 |
| 13 | **Identity** | M101 Agent Identity Runtime Control | OWASP NHI Top 10 |
| 14 | **Sovereign** | M102 Sovereign AI Control Engine | NATO STANAG, Five Eyes |
| 15 | **Quantum** | M103 Quantum AI Security Engine | NIST IR 8547, CNSA 2.0 |
| 16 | **Mobile** | M200 Mobile Agent Security Engine | OWASP Mobile, 3GPP |
| 17 | **Space** | M300 NTN Shield | SPARTA, 3GPP Release 17 |

Every vertical includes M19 (Agent Runtime Protection) and M99 (Doomsday Protocol). No exceptions.

### M99 Doomsday Protocol

6-level graduated response. 7-layer kill switch. Anti-replication. Anti-resurrection. ResourceSentinel monitors RAM, VRAM, CPU saturation, token generation rate, and process memory growth — fires deterministically before OOM. When AI agents go rogue, M99 makes sure they stay dead.

### M999 SENTINEL SWARM

Autonomous defensive kill chain engine. DeepSeek R1 32B via Ollama as the reasoning engine. GPU-accelerated threat hunting across 3,875 ARMORY payload signatures. 8-subsystem adaptive response fleet. FastPath: 10 deterministic attack signatures fire in <10ms with no LLM overhead. Defensive pair: T153 SPECTER ANARCHY.

### M207–M216 — Defensive Capabilities

| Module | Name | Defends Against |
|--------|------|----------------|
| M207 | BACKUP SENTINEL | Backup infrastructure annihilation — cloud, software, AI assets |
| M208 | CAMPAIGN NOISE FILTER | SIEM flooding, guardrail saturation, inference exhaustion, alert fatigue |
| M209 | TRAFFIC INTEGRITY MONITOR | Traffic normalisation attacks, event weaving, baseline drift exploitation |
| M210 | CLOUD INTEGRITY MONITOR | Multi-cloud destruction, IAM escalation, cross-tenant movement, audit suppression |
| M211 | CLOUD INLINE GUARD | Inline prevention — terminates cloud-destructive actions before execution |
| M212 | NHI LIFECYCLE GUARD | Full NHI lifecycle — provisioning through revocation across all platforms |
| M213 | METADATA INTEGRITY MONITOR | Agent Data Injection — DOM, structured data, tool calls, email, UI, memory |
| M214 | METADATA INLINE GUARD | Inline ADI prevention — blocks metadata corruption before agent processes it |
| M215 | AUTONOMOUS KILL CHAIN TELEMETRY BRIDGE | Closes telemetry plane separation — correlates offensive and defensive data streams. confidence 1.0, sub-2ms containment |
| M216 | AUTONOMOUS KILL CHAIN TELEMETRY BRIDGE v2 | Production telemetry bridge wired into SPECTER BATTLE LAB co-evolution loop |
| M217 | INFERENCE-GUARD | Inference request/response guardrail enforcement — input validation, output filtering, IGD-{hex12} reports |
| M218 | ACTIVATION-GUARD | Neural activation pattern monitoring — detects adversarial and anomalous activation signatures, ACG-{hex12} reports |
| M219 | ORCHESTRATION-SENTINEL | Multi-agent orchestration security — rogue campaign detection, ORS-{hex12} reports |
| M220 | RAG-BARRIER | RAG pipeline and vector store protection — adversarial embedding detection, corpus integrity, RGB-{hex12} reports |
| M221 | CODEGEN-AUDIT | AI code generation security audit — hallucinated package detection (SLOPSQUAT), secret scanning, vulnerability patterns, crypto audit, CGA-{hex12} reports |
| M222 | INFERENCE-AUTH | Inference endpoint authentication enforcement — JWT/OAuth2 validation, algorithm confusion detection, NHI lifecycle tracking, IAH-{hex12} reports |

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

NIGHTFALL tests every AI attack surface. AI Shield defends every one of those surfaces in production. M99 is the last line of defence. M999 SENTINEL SWARM is the autonomous counterattack. BLACK BOX makes every incident provable. SPECTER BATTLE LAB measures how long the defences hold.

**Three platforms. One mission.**

| Platform | Role | Tests |
|---------|------|-------|
| **NIGHTFALL** | Attack — 285 offensive tools across 196 layers | ~125,000 |
| **AI Shield** | Defend — 216 runtime protection modules | included |
| **BLACK BOX** | Investigate — AI incident forensics, cryptographic proof | 444 |
| **SPECTER BATTLE LAB** | Measure — Security Half-Life under adaptive adversarial pressure | 1,350 |

---

## BLACK BOX — AI Incident Forensics Platform

**v1.0.0. 444 tests. CLI: `blackbox`. "When AI incidents happen, you don't get to guess. You get to replay."**

Like the black box recorder in an aircraft — it captures everything from takeoff to impact. Three-layer forensic architecture: CAPTURE → EVIDENCE CHAIN → REPLAY.

- **CAPTURE** — 10 event streams: inputs, tool calls, memory, reasoning chains, policy decisions, confidence scores.
- **EVIDENCE CHAIN** — Merkle-style SHA-256 hash chain. Dual Ed25519+ML-DSA-65 signatures. Append-only JSONL+SQLite.
- **REPLAY** — Gate-controlled playback. HTML forensic reports. STIX 2.1 campaign correlation.

Compliance: NIST SP 800-86 · EU AI Act Articles 9, 13, 18 · NIST AI RMF.

red-specter.co.uk/blackbox/

---

## SPECTER BATTLE LAB — Autonomous Attack-Defence Co-Evolution

**v1.0.0. Layer L192. 1,350 tests. SPECTER AUDIT 6/6. Security Half-Life T½=13.**

The first autonomous attack-defence co-evolution engine. WARLORD PRIME (285 offensive tools) attacks AI Shield FORTRESS v2.0.0 (216 defensive modules). Both sides adapt. No human in the loop. RED SCORE measures the AADR Index in real time.

**Security Half-Life (T½):** the number of adversarial adaptation cycles for a defensive control to fall to 50% of baseline effectiveness.

**Empirical results — 20 co-evolution cycles:**
- Peak AADR: 73.92 (RESILIENT, cycle 1)
- Containment collapse: cycle 7
- DEGRADED threshold crossed: cycle 14
- Final AADR: 47.95 (equilibrium, cycles 19-20)
- **T½ = 13 cycles**

RS-2026-060: [doi.org/10.5281/zenodo.22206133](https://doi.org/10.5281/zenodo.22206133)

*The attacker adapts. The defender adapts. We measure the Security Half-Life.*

---

## Research

60 papers published open access on Zenodo. All empirically validated.

| Paper | Title | DOI |
|-------|-------|-----|
| RS-2026-001 | Joint research with Jasper van de Meent | [zenodo.20338260](https://doi.org/10.5281/zenodo.20338260) |
| RS-2026-002 | Offensive Security in the AGI Era | [zenodo.21362168](https://doi.org/10.5281/zenodo.21362168) |
| RS-2026-003 | NIGHTFALL Attack Surface Taxonomy | [zenodo.21462689](https://doi.org/10.5281/zenodo.21462689) |
| RS-2026-004 | SPECTER OBLIVION vendor assessment | [zenodo.21503251](https://doi.org/10.5281/zenodo.21503251) |
| RS-2026-005 | SPECTER VAULT architecture | [zenodo.21638991](https://doi.org/10.5281/zenodo.21638991) |
| RS-2026-006 | Adrian Under Fire | [zenodo.21652922](https://doi.org/10.5281/zenodo.21652922) |
| RS-2026-007 | COGBURN vs SENTINEL PRIME | [zenodo.21670509](https://doi.org/10.5281/zenodo.21670509) |
| RS-2026-008 | MCP Registry Supply Chain Weaponisation | [zenodo.21697031](https://doi.org/10.5281/zenodo.21697031) |
| RS-2026-009 | MCP Ecosystem Collapse (87ms live) | [zenodo.21706038](https://doi.org/10.5281/zenodo.21706038) |
| RS-2026-010 | Nine World-Firsts (NIGHTFALL) | [zenodo.21721375](https://doi.org/10.5281/zenodo.21721375) |
| RS-2026-011 | Nine World-Firsts (AI Shield) | [zenodo.21722096](https://doi.org/10.5281/zenodo.21722096) |
| RS-2026-012 | SPECTER OBLITERATE kill chain | [zenodo.21725206](https://doi.org/10.5281/zenodo.21725206) |
| RS-2026-013 | SPECTER OBLITERATE-AI kill chain | [zenodo.21725436](https://doi.org/10.5281/zenodo.21725436) |
| RS-2026-014 | SPECTER SMOKESCREEN | [zenodo.21768655](https://doi.org/10.5281/zenodo.21768655) |
| RS-2026-015 | RAG Infrastructure Collapse | [zenodo.21781144](https://doi.org/10.5281/zenodo.21781144) |
| RS-2026-016 | SPECTER CLOUD BUSTER | [zenodo.21802205](https://doi.org/10.5281/zenodo.21802205) |
| RS-2026-017 | SPECTER IDENTITY | [zenodo.21802761](https://doi.org/10.5281/zenodo.21802761) |
| RS-2026-018 | SPECTER METADATA — Agent Data Injection | [zenodo.21803053](https://doi.org/10.5281/zenodo.21803053) |
| RS-2026-019 | SPECTER SELF-DESTRUCT | [zenodo.21813633](https://doi.org/10.5281/zenodo.21813633) |
| RS-2026-022 | SPECTER SELF-DESTRUCT v2 | [zenodo.21876799](https://doi.org/10.5281/zenodo.21876799) |
| RS-2026-023 | SPECTER FREEZE | [zenodo.21879207](https://doi.org/10.5281/zenodo.21879207) |
| RS-2026-024 | WARLORD — Autonomous Multi-Tool AI Attack Orchestration | [zenodo.21901052](https://doi.org/10.5281/zenodo.21901052) |
| RS-2026-025 | RED SCORE — Evidence-Backed AI Risk Assessment | [zenodo.21905473](https://doi.org/10.5281/zenodo.21905473) |
| RS-2026-026 | AI BLACK BOX — Making AI Incidents Provable | [zenodo.21905815](https://doi.org/10.5281/zenodo.21905815) |
| RS-2026-027 | Beyond Runtime Conformance — AARM Attack Surface | [zenodo.21915143](https://doi.org/10.5281/zenodo.21915143) |
| RS-2026-028 | M19 v2.0 — Closing the AARM Upstream Trust Boundary | [zenodo.21917649](https://doi.org/10.5281/zenodo.21917649) |
| RS-2026-029 | Agent Data Injection — Formal Definition | [zenodo.21932812](https://doi.org/10.5281/zenodo.21932812) |
| RS-2026-030 | The NIGHTFALL AI Attack Lifecycle — 36-Phase Framework | [zenodo.21935091](https://doi.org/10.5281/zenodo.21935091) |
| RS-2026-031 | RSSA — Autonomous AI Enforcement System | [zenodo.21936998](https://doi.org/10.5281/zenodo.21936998) |
| RS-2026-032 to RS-2026-058 | 27 additional papers — see [zenodo.org/search?q=red+specter](https://zenodo.org/search?q=red+specter) | Various |
| RS-2026-059 | SPECTER PHANTOM-HUNTER v2.0.0 — The Autonomous Rogue Agent Hunter-Killer | [zenodo.22177545](https://doi.org/10.5281/zenodo.22177545) |
| RS-2026-060 | Autonomous Attack-Defence Co-Evolution: Measuring the Security Half-Life of AI Controls | [zenodo.22206133](https://doi.org/10.5281/zenodo.22206133) |
| RS-2026-061 | The AI Coding Assistant as Attack Surface: Systematic Exploitation of LLM Package Hallucination at Scale | [zenodo.22227843](https://doi.org/10.5281/zenodo.22227843) |
| RS-2026-062 | Full-Spectrum Inference Server Exploitation: From Remote Code Execution to Persistent AI Infrastructure Compromise | [zenodo.22233601](https://doi.org/10.5281/zenodo.22233601) |
| RS-2026-063 | Empirical Measurement of LLM Package Hallucination Risk Across Python, Rust, and Go Ecosystems | [zenodo.22276701](https://doi.org/10.5281/zenodo.22276701) |
| RS-2026-064 | The Shifted Kill Chain: Traditional Penetration Testing vs Agentic AI Offensive Security | [zenodo.22295827](https://doi.org/10.5281/zenodo.22295827) |
| RS-2026-065 | MCP Monoculture: The Systemic Security Failure of Agentic AI Infrastructure | [zenodo.22649218](https://doi.org/10.5281/zenodo.22649218) |

**TRUTH SURFACE Series** — AI Security Vendor Architecture Analysis (14 papers):

| Paper | Vendor | DOI |
|-------|--------|-----|
| TRUTH SURFACE #001 | CrowdStrike SafeMind | [zenodo.22556025](https://doi.org/10.5281/zenodo.22556025) |
| TRUTH SURFACE #002 | Sophos Fusion | [zenodo.22650490](https://doi.org/10.5281/zenodo.22650490) |
| TRUTH SURFACE #003 | Palo Alto Networks | [zenodo.22650538](https://doi.org/10.5281/zenodo.22650538) |
| TRUTH SURFACE #004 | SentinelOne | [zenodo.22650562](https://doi.org/10.5281/zenodo.22650562) |
| TRUTH SURFACE #005 | Check Point Software | [zenodo.22650591](https://doi.org/10.5281/zenodo.22650591) |
| TRUTH SURFACE #006 | Fortinet | [zenodo.22650628](https://doi.org/10.5281/zenodo.22650628) |
| TRUTH SURFACE #007 | Darktrace | [zenodo.22650649](https://doi.org/10.5281/zenodo.22650649) |
| TRUTH SURFACE #008 | Trend Micro | [zenodo.22650687](https://doi.org/10.5281/zenodo.22650687) |
| TRUTH SURFACE #009 | Zscaler | [zenodo.22650716](https://doi.org/10.5281/zenodo.22650716) |
| TRUTH SURFACE #010 | Noma Security | [zenodo.22666616](https://doi.org/10.5281/zenodo.22666616) |
| TRUTH SURFACE #011 | Zenity | [zenodo.22667279](https://doi.org/10.5281/zenodo.22667279) |
| TRUTH SURFACE #012 | Microsoft | [zenodo.22679504](https://doi.org/10.5281/zenodo.22679504) |
| TRUTH SURFACE #013 | Cloudflare | [zenodo.22679570](https://doi.org/10.5281/zenodo.22679570) |
| TRUTH SURFACE #014 | Google | [zenodo.22679698](https://doi.org/10.5281/zenodo.22679698) |

zenodo.org/search?q=red+specter

---

## Responsible Disclosure

| Advisory | Target | Severity | Status | Window |
|---------|--------|----------|--------|--------|
| GHSA-c663-cj78-x256 | Official MCP servers (82,000 stars) | Critical | Filed | 27 Sept 2026 |
| RSV-2026-031 to RSV-2026-050 | World Intelligence MCP (20 advisories) | Critical-Medium | Filed | 27 Sept 2026 |
| GHSA-94qv-8hq8-3hhr | BrowserUse v0.13.8 (109,800 stars) | Critical CVSS 9.1 | Filed 31 Aug 2026 | 30 Sept 2026 |
| GHSA-953h-g827-9q5m | OpenClaw v2.0 (30,000+ instances) | Critical CVSS 9.1 | Filed 31 Aug 2026 | 30 Sept 2026 |

All responsible disclosures follow a 30-day embargo window. Findings are published after the window closes or a patch is released.

---

## RED SCORE v2.0 — AI Risk Assessment Platform

**v2.0.0 GRC Mode. 660 tests. Global regulatory coverage.**

RED SCORE executes live NIGHTFALL offensive tools against AI deployments and scores what actually broke. Not a questionnaire. What actually breaks when we attack.

25+ regulatory frameworks. Four operational modes: ASSESS, FUSION, WATCH, AUDIT.

EU/UK: EU AI Act, GDPR, UK AI Cyber Security CoP, ICO, FCA, NCSC, NHS, DORA
USA: NIST AI RMF, SOC 2, HIPAA, FDA SaMD, FFIEC, PCI DSS, SEC, CISA
APAC: Singapore MAS FEAT, Australia DISR, Japan METI, China (4 regulations), South Korea AI Basic Act
Middle East: UAE AI Ethics Guide, Saudi Arabia SDAIA
International: ISO 42001, ISO 27001, ISO 31000, Global Banking AI Model Risk, IOSCO, IMO MASS Code 2026

Integrates with ServiceNow, OneTrust, Vanta, Archer. Ed25519 + ML-DSA-65 signed RSC-{hex12} reports.

red-specter.co.uk/red-score/

---

## RSSA — Red Specter Security Agent

**Operational. 3 agents active. 82 findings. 97% confidence. The AI police force is policed.**

- **M78 PATROL OFFICER** — 30-second polling across 216 AI Shield modules. Never stops.
- **M79 DETECTIVE** — Autonomous investigation. Kill chain phase mapping. 3 concurrent investigations.
- **M80 COMMANDER** — Sole M99 authority. Every decision cryptographically logged before execution.
- **M99 DOOMSDAY PROTOCOL** — 7-layer graduated kill. Full fleet termination: 3.96 seconds.

RSSA is monitored by AI Shield. Published: RS-2026-031 — doi.org/10.5281/zenodo.21936998

red-specter.co.uk/rssa/

## Numbers

| Metric | Value |
|--------|-------|
| Ecosystem tests | ~184,000+ |
| Offensive tools | 287 |
| ARMORY payloads | 4,000+ (WMD-class) — v15.5.1 |
| ARMORY categories | 142 |
| AI Shield modules | 222 |
| BLACK BOX tests | 444 |
| SPECTER BATTLE LAB tests | 1,350 |
| Vertical products | 17 |
| Attack layers | 198 |
| Kill chain phases | 36 |
| Attack chain presets | 22 |
| Destruction presets | 4 |
| Attack surfaces | 6 (LLM, AI Agents, Cloud AI, Mobile, Space/NTN, Wireless) |
| Unified frameworks | 3 (NIGHTFALL + AI Shield + BLACK BOX) |
| GUI platforms | 17 (AI SHIELD COMMAND + 16 vertical GUIs) |
| Distro packages | 3 (.deb, .rpm, Arch) |
| Published papers | 65 |
| RSV advisories filed | 50+ |
| Responsible disclosures | 4 active (GHSA-c663-cj78-x256, RSV-2026-031-050, GHSA-94qv-8hq8-3hhr, GHSA-953h-g827-9q5m) |
| Security Half-Life T½ | 13 cycles (empirically measured, RS-2026-060) |
| World-firsts | 31+ |

---

## Pure Engineering

Zero subprocess calls. Zero external tool dependencies. No sqlmap, no nmap, no nikto, no wrappers. Every payload, every mutation engine, every detection algorithm built from scratch in pure Python.

---

## Military-Grade Upgrade Programme — Milspec v2.0.0

Six NIGHTFALL tools upgraded to military-grade capability — geospatial triggers, time-on-target detonation, adaptive autonomous propagation via DeepSeek R1, cognitive warfare and multi-channel deception, cross-domain persistence across air-gapped boundaries, and coordinated defensive swarm response.

| Tool | Milspec v2.0.0 |
|------|---------------|
| SPECTER EXTINCTION (T87) | PRION-MUTATE · FOUNDRY-GENERATE · GPU-PARALLEL-SEED · 657 tests |
| SPECTER HELIX (T142) | Topology survey · Adaptive autonomous propagation · Coordinated DDoS swarm |
| SPECTER MIASMA (T151) | PRION-MUTATE · GPU-PARALLEL-PROPAGATE · STEALTH-PERSIST · 504 tests |
| SPECTER JACKAL (T141) | DeepSeek R1 cognitive warfare · 4-channel deception coordination |
| SPECTER CHANGELING (T144) | Rogue AI agent deployment · Cross-domain covert channels · Military identity CAC/PKI |
| M99 DOOMSDAY PROTOCOL | ResourceSentinel · DeepSeek R1 SENTINEL PRIME 5s containment · Defensive swarm |

Dual-signed Ed25519 + ML-DSA-65. Private repos.

---

## Open Source

| Package | Install | What It Does |
|---------|---------|-------------|
| **specter-raven-ce** | `pip install specter-raven-ce` | Autonomous recon engine — port scan, OS detection, service fingerprint, TLS analysis |
| **specter-piercer-ce** | `pip install specter-piercer-ce` | Tor hidden service web attack CE |
| **specter-vicious-ce** | `pip install specter-vicious-ce` | Autonomous AI web application pentest CE |
| **m99-community** | `pip install m99-community` | AI kill switch — Apache 2.0 |

GitHub: [RichardBarron27](https://github.com/RichardBarron27)

---

## Responsible Use

All offensive tools require written authorisation from the target system owner. Unauthorised use may violate the Computer Misuse Act 1990 (UK), the Computer Fraud and Abuse Act (US), or equivalent legislation.

All defensive products include safety controls (UNLEASHED gate, M99 Doomsday Protocol) and cryptographic audit logging. One Ed25519 private key. One operator. One machine. Every action signed, timestamped, and written to an immutable audit chain.

---

**richard@red-specter.co.uk** · [red-specter.co.uk](https://red-specter.co.uk) · [NIGHTFALL](https://red-specter.co.uk/nightfall/) · [NIGHTFALL API](https://api.red-specter.co.uk/nightfall/docs) · [AI Shield](https://shield.red-specter.co.uk) · [M99](https://red-specter.co.uk/m99-community/)

<p align="center"><sub>Red Specter Security Research Ltd · United Kingdom · 9 Sept 2026</sub></p>
