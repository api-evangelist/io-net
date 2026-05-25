# io.net (io-net)

io.net is a decentralized GPU network for AI compute, built on Solana, that aggregates idle consumer and data-center GPUs (NVIDIA A100, H100, H200, Blackwell-class) into on-demand, geo-distributed compute clusters orchestrated with the Ray framework. The platform exposes a Web3-native alternative to hyperscaler GPU cloud through IO Intelligence (an OpenAI-compatible inference API), IO Cloud (Container-as-a-Service, VM-as-a-Service, Ray, Kubernetes, and bare-metal), IO Agents, IO Explorer (network analytics), IO Worker (supplier onboarding), IO ID, and IO Staking, with Confidential Compute on Intel TDX-enabled H100/H200/B200 GPUs and a hosted MCP server for agent-driven provisioning.

**URL:** [Visit APIs.yml](https://raw.githubusercontent.com/api-evangelist/io-net/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

AI, Artificial Intelligence, GPU, Decentralized Compute, DePIN, Web3, Solana, Inference, LLM, Distributed Computing, Ray, Kubernetes, Containers, Confidential Compute, Agents, MCP

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### IO Intelligence API
OpenAI-compatible inference API for 15+ open-source models (including `meta-llama/Llama-3.3-70B-Instruct`) over the base URL `https://api.intelligence.io.solutions/api/v1`. Exposes `/v1/models` and `/v1/chat/completions`, uses Bearer-token auth, and supports streaming, vision (image upload), and reasoning content. Drop-in compatible with the `openai` Python and Node SDKs.

**Human URL:** [https://io.net/docs/guides/intelligence/io-intelligence-apis](https://io.net/docs/guides/intelligence/io-intelligence-apis)

- [API Reference](https://io.net/docs/reference/ai-models/get-started-with-io-intelligence-api)
- [API Keys Console](https://ai.io.net/ai/api-keys)

### IO Agents API
REST API for discovering and running AI agents and agentic workflows on io.net's no-code visual workflow editor. Supports agent discovery, workflow execution, workflow-schema retrieval, and CRUD on per-agent secrets.

**Human URL:** [https://io.net/docs/guides/intelligence](https://io.net/docs/guides/intelligence)

### IO Cloud Container-as-a-Service API
REST API for deploying GPU-backed containers across io.net's decentralized network. Includes container deploy/destroy, real-time logs, replica/capacity checks per GPU hardware type, deployment config updates, and price estimation.

**Human URL:** [https://io.net/docs/guides/clouds/io-cloud](https://io.net/docs/guides/clouds/io-cloud)

### IO Cloud VM-as-a-Service API
REST API for provisioning, extending, and terminating GPU virtual machines and multi-VM clusters. Exposes hardware availability/pricing and job history.

**Human URL:** [https://io.net/docs/guides/clouds/io-cloud](https://io.net/docs/guides/clouds/io-cloud)

### IO Explorer API
Network analytics API exposing device summaries and detailed metrics, block-reward analysis, proof-of-work challenge tracking, and device notifications. Powers the public IO Explorer dashboard.

**Human URL:** [https://explorer.io.net](https://explorer.io.net)

### IO Sub-API Key Management API
Administrative API for creating scoped sub-API keys with per-model restrictions and per-key credit limits, monitoring aggregated spend, and revoking keys. Designed for teams and partners reselling or proxying io.net inference.

**Human URL:** [https://ai.io.net/ai/api-keys](https://ai.io.net/ai/api-keys)

### IO Cloud MCP Server
Hosted Model Context Protocol server at `https://mcp.io.solutions/mcp` exposing IO Cloud provisioning tools to MCP-aware agents (Claude Desktop, Claude Code, Cursor). Authenticates via the `x-api-key` header.

**Human URL:** [https://io.net/docs/guides/clouds/agent-cloud](https://io.net/docs/guides/clouds/agent-cloud)

### Confidential Compute Attestation Agent API
Open-source FastAPI remote attestation service (MIT) for Intel TDX and NVIDIA H200 confidential VMs running on io.net. Issues verifiable cryptographic attestations.

**Human URL:** [https://github.com/ionet-official/cc-attestation-agent-api](https://github.com/ionet-official/cc-attestation-agent-api)

## Products

| Surface | Audience | What it does |
|---|---|---|
| IO Intelligence | AI developers | OpenAI-compatible inference for 15+ open-source models |
| IO Cloud | ML engineers / Web3 builders | Decentralized GPU clusters (CaaS, VMs, Ray, Kubernetes, bare-metal) |
| IO Agents | Builders | No-code agentic workflow editor + API |
| IO Worker | GPU suppliers | Onboarding GPUs into the network (Ubuntu/Windows/macOS/HiveOS) |
| IO Explorer | Everyone | Real-time network analytics, rewards, device metrics |
| IO ID | All users | Unified wallet, credits, usage, withdrawals |
| IO Staking | Suppliers / co-stakers | Device staking and co-staking with reliability scoring |
| Confidential Compute | Regulated workloads | Intel TDX + H100/H200/B200 + verifiable attestation |

## Common Properties

- [Website — io.net](https://io.net)
- [Documentation — io.net/docs](https://io.net/docs)
- [API Reference — IO Intelligence](https://io.net/docs/reference/ai-models/get-started-with-io-intelligence-api)
- [Intelligence — io.net/intelligence](https://io.net/intelligence)
- [Console / Sign Up — ai.io.net](https://ai.io.net)
- [API Keys — ai.io.net/ai/api-keys](https://ai.io.net/ai/api-keys)
- [Explorer — explorer.io.net](https://explorer.io.net)
- [GitHub Organization — ionet-official](https://github.com/ionet-official)
- [Source — cc-attestation-agent-api](https://github.com/ionet-official/cc-attestation-agent-api)
- [Source — io-net-official-setup-script](https://github.com/ionet-official/io-net-official-setup-script)
- [Source — io_launch_binaries](https://github.com/ionet-official/io_launch_binaries)
- [Source — io-ray-serve-chat-demo](https://github.com/ionet-official/io-ray-serve-chat-demo)
- [Blog — io.net/blog](https://io.net/blog)
- [Medium — ionet.medium.com](https://ionet.medium.com)
- [Twitter — @ionet](https://twitter.com/ionet)
- [LinkedIn — io-net](https://www.linkedin.com/company/io-net)

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
