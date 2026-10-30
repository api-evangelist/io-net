# io.net

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

io.net is a decentralized GPU network for AI compute, built on Solana, that aggregates idle consumer and data-center GPUs (NVIDIA A100, H100, H200, and Blackwell-class) into on-demand, geo-distributed compute clusters orchestrated with the Ray framework. The platform exposes a Web3-native alternative to hyperscaler GPU cloud through several developer-facing surfaces: IO Intelligence (an OpenAI-compatible inference API for 15+ open-source models including Llama 3.3 70B), IO Cloud (Container-as-a-Service and VM-as-a-Service APIs for deploying GPU containers, Ray clusters, Kubernetes clusters, and bare-metal instances), IO Agents (agent and agentic-workflow APIs), IO Explorer (a network analytics API for devices, clusters, and block rewards), IO Worker (the supplier-side onboarding stack), IO ID (the account/wallet hub), and IO Staking. Confidential Compute on Intel TDX-enabled H100/H200/B200 GPUs and a remote attestation service for Intel TDX and NVIDIA H200 confidential VMs round out the security surface. The IO token is an SPL token on Solana used for settlement, staking, and rewards; fiat and USDC payments are accepted and converted to IO. io.net also publishes an MCP server at mcp.io.solutions for agent-driven cluster provisioning. The platform's tagline is "the open-source AI infrastructure platform" and its commercial pitch is AI compute at 50–70% below comparable hyperscaler rates.

**Areas:** Artificial Intelligence · GPU · Decentralized Compute · DePIN · Web3 · Solana · Inference · LLM · Distributed Computing · Ray · Kubernetes · Containers

## io.net on APIs.io

Everything profiled for io.net is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/io-net/](https://apis.io/providers/io-net/)** — or go straight to one of the APIs or properties below.

### APIs (8)

- [IO Intelligence API](https://apis.io/apis/io-net/io-intelligence-api/) — OpenAI-compatible inference API for open-source AI models hosted on io.net's decentralized GPU network. Exposes /v1/models and /v1/chat/completions over the…
- [IO Agents API](https://apis.io/apis/io-net/io-agents-api/) — REST API for discovering, configuring, and running AI agents and agentic workflows on io.net's no-code workflow editor. Supports agent discovery, workflow…
- [IO Cloud Container-as-a-Service API](https://apis.io/apis/io-net/io-cloud-caas-api/) — Container-as-a-Service REST API for deploying GPU-backed containers across io.net's decentralized network. Operations include container deployment and…
- [IO Cloud VM-as-a-Service API](https://apis.io/apis/io-net/io-cloud-vmaas-api/) — VM-as-a-Service REST API for provisioning, extending, and terminating GPU virtual machines on io.net. Surfaces hardware availability and pricing, supports…
- [IO Explorer API](https://apis.io/apis/io-net/io-explorer-api/) — Network analytics API exposing device summaries and detailed metrics, block-reward analysis, proof-of-work challenge tracking, and device notifications.…
- [IO Sub-API Key Management API](https://apis.io/apis/io-net/io-sub-api-key-api/) — Administrative API for creating scoped sub-API keys with per-model restrictions and per-key credit limits, tracking usage and aggregated spend, and revoking…
- [IO Cloud MCP Server](https://apis.io/apis/io-net/io-cloud-mcp-server/) — Hosted Model Context Protocol server at https://mcp.io.solutions/mcp that exposes IO Cloud provisioning and management tools to MCP-aware agents (Claude…
- [Confidential Compute Attestation Agent API](https://apis.io/apis/io-net/cc-attestation-agent-api/) — Open-source FastAPI remote attestation service for Intel TDX and NVIDIA H200 confidential VMs operating on the io.net network. Issues verifiable…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [Io Net Domain Security](https://apis.io/security/io-net/io-net-domain-security/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://io.net)
- [Documentation](https://io.net/docs)
- [Getting started](https://io.net/docs)
- [API reference](https://io.net/docs/reference/ai-models/get-started-with-io-intelligence-api)
- [Blog](https://io.net/blog)
- [Terms of service](https://io.net/terms)
- [Privacy policy](https://io.net/privacy)
- [GitHub](https://github.com/ionet-official)

## API Evangelist rating

**Kin Score 35.9** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 62.5 |
| Contract quality | 0.0 |
| Contract governance | 0.0 |
| Operational transparency | 28.9 |
| Developer ergonomics | 57.1 |
| Access clarity | 34.2 |

**Agent readiness 2.5** — human-only

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | — |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 18.2** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/io-net/](https://apis.io/providers/io-net/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for io.net: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/io-net/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
