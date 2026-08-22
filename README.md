# Starknet (starknet)

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

Starknet is a permissionless Ethereum Layer 2 validity rollup developed by StarkWare, powered by STARK proofs and the Cairo smart contract language. Developers interact with Starknet via a versioned Starknet JSON-RPC (served by Pathfinder, Juno, and Papyrus full nodes as well as Infura / Alchemy / Blast / Nethermind providers), the Cairo toolchain (Scarb, Starknet Foundry, Cairo compiler, cairo-vm), client SDKs (starknet.js, starknet.py, starknet-rs), the StarkGate canonical bridge between Ethereum and Starknet, and Voyager / Starkscan block explorers.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/starknet/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/starknet/refs/heads/main/apis.yml)

## Tags

- Layer 2
- Ethereum
- Validity Rollup
- ZK
- Cairo
- STARK
- JSON-RPC
- Bridge

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-29

## APIs

### Starknet JSON-RPC Specification

Versioned JSON-RPC specification implemented by Starknet full nodes (Pathfinder, Juno, Papyrus) and infrastructure providers. Defines read methods (starknet_* for blocks, transactions, classes, state, storage, events), trace methods, and write methods for invoking, deploying accounts, and declaring classes.

- **Human URL:** [https://github.com/starkware-libs/starknet-specs](https://github.com/starkware-libs/starknet-specs)
- **Base URL:** `https://github.com/starkware-libs/starknet-specs`

#### Tags

- JSON-RPC
- Spec
- OpenRPC

#### Properties

- [Documentation](https://github.com/starkware-libs/starknet-specs)
- [Repository](https://github.com/starkware-libs/starknet-specs)
- [AsyncAPI](https://raw.githubusercontent.com/api-evangelist/starknet/refs/heads/main/asyncapi/starknet-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/starknet.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/starknet.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Starknet Mainnet RPC (Public Providers)

Starknet Mainnet (chain ID SN_MAIN) is reached via the Starknet JSON-RPC at hosted providers — Infura, Alchemy, Blast, Nethermind Voyager, Lava, Chainstack — or via self-hosted Pathfinder / Juno full nodes.

- **Human URL:** [https://docs.starknet.io/quick-start/environment-setup](https://docs.starknet.io/quick-start/environment-setup)
- **Base URL:** `https://starknet-mainnet.public.blastapi.io`

#### Tags

- JSON-RPC
- Mainnet
- Providers

#### Properties

- [Documentation](https://docs.starknet.io/quick-start/environment-setup)
- [Postman Collection](collections/starknet.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/starknet.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Starknet Sepolia RPC (Public Providers)

Public JSON-RPC endpoint for Starknet Sepolia testnet (chain ID SN_SEPOLIA) for development and integration testing.

- **Human URL:** [https://docs.starknet.io/quick-start/environment-setup](https://docs.starknet.io/quick-start/environment-setup)
- **Base URL:** `https://starknet-sepolia.public.blastapi.io`

#### Tags

- JSON-RPC
- Testnet
- Sepolia

#### Properties

- [Documentation](https://docs.starknet.io/quick-start/environment-setup)
- [Postman Collection](collections/starknet.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/starknet.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### StarkGate Bridge

Canonical L1<->L2 bridge for ETH and ERC-20 tokens between Ethereum and Starknet, operated by StarkWare. Bridge contracts are open-source.

- **Human URL:** [https://starkgate.starknet.io](https://starkgate.starknet.io)
- **Base URL:** `https://starkgate.starknet.io`

#### Tags

- Bridge
- Cross-Chain
- Canonical

#### Properties

- [Documentation](https://docs.starknet.io/quick-start/bridging-tokens)
- [App](https://starkgate.starknet.io)
- [Repository](https://github.com/starknet-io/starkgate-contracts)
- [Postman Collection](collections/starknet.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/starknet.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### starknet.js SDK

JavaScript / TypeScript SDK for Starknet — providers, accounts, contract classes, ABI parsing, transaction signing, and integration with browser wallets via the wallet API (get-starknet).

- **Human URL:** [https://www.starknetjs.com](https://www.starknetjs.com)
- **Base URL:** `https://github.com/starknet-io/starknet.js`

#### Tags

- SDK
- JavaScript
- TypeScript

#### Properties

- [Documentation](https://www.starknetjs.com)
- [Repository](https://github.com/starknet-io/starknet.js)
- [Postman Collection](collections/starknet.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/starknet.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### starknet.py SDK

Python SDK for Starknet maintained by Software Mansion, covering account / contract interaction, Cairo ABI handling, and the Starknet JSON-RPC.

- **Human URL:** [https://starknetpy.readthedocs.io](https://starknetpy.readthedocs.io)
- **Base URL:** `https://github.com/software-mansion/starknet.py`

#### Tags

- SDK
- Python

#### Properties

- [Documentation](https://starknetpy.readthedocs.io)
- [Repository](https://github.com/software-mansion/starknet.py)
- [Postman Collection](collections/starknet.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/starknet.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### starknet-rs SDK

Rust SDK for Starknet with high-performance providers, accounts, contract bindings, ABI codegen, and Cairo serialization.

- **Human URL:** [https://github.com/xJonathanLEI/starknet-rs](https://github.com/xJonathanLEI/starknet-rs)
- **Base URL:** `https://github.com/xJonathanLEI/starknet-rs`

#### Tags

- SDK
- Rust

#### Properties

- [Repository](https://github.com/xJonathanLEI/starknet-rs)
- [Postman Collection](collections/starknet.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/starknet.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cairo Language

Cairo is StarkWare's Turing-complete language for creating provable programs and the canonical smart contract language for Starknet. Distributed as the Cairo compiler (Rust) and the Scarb package manager.

- **Human URL:** [https://book.cairo-lang.org](https://book.cairo-lang.org)
- **Base URL:** `https://github.com/starkware-libs/cairo`

#### Tags

- Cairo
- Language
- Smart Contracts

#### Properties

- [Documentation](https://book.cairo-lang.org)
- [Repository](https://github.com/starkware-libs/cairo)
- [Package Manager](https://docs.swmansion.com/scarb)
- [Postman Collection](collections/starknet.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/starknet.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Pathfinder Full Node

Rust implementation of a Starknet full node from Equilibrium that serves the Starknet JSON-RPC, syncs from Ethereum L1 data, and verifies state transitions.

- **Human URL:** [https://github.com/eqlabs/pathfinder](https://github.com/eqlabs/pathfinder)
- **Base URL:** `https://github.com/eqlabs/pathfinder`

#### Tags

- Node
- JSON-RPC
- Rust

#### Properties

- [Repository](https://github.com/eqlabs/pathfinder)
- [Postman Collection](collections/starknet.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/starknet.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Juno Full Node

Go implementation of a Starknet full node from Nethermind that serves the Starknet JSON-RPC and acts as a sequencer / RPC backend.

- **Human URL:** [https://github.com/NethermindEth/juno](https://github.com/NethermindEth/juno)
- **Base URL:** `https://github.com/NethermindEth/juno`

#### Tags

- Node
- JSON-RPC
- Go

#### Properties

- [Repository](https://github.com/NethermindEth/juno)
- [Postman Collection](collections/starknet.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/starknet.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Voyager Block Explorer

Nethermind-built block explorer for Starknet Mainnet and Sepolia with a public REST API for blocks, transactions, contracts, classes, events, and tokens.

- **Human URL:** [https://voyager.online](https://voyager.online)
- **Base URL:** `https://api.voyager.online/beta`

#### Tags

- Block Explorer
- Voyager
- API

#### Properties

- [Website](https://voyager.online)
- [Postman Collection](collections/starknet.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/starknet.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Starkscan Block Explorer

Block explorer for Starknet Mainnet, Sepolia, and Sepolia Integration with a public REST API for blocks, transactions, events, classes, and NFTs.

- **Human URL:** [https://starkscan.co](https://starkscan.co)
- **Base URL:** `https://api.starkscan.co/api`

#### Tags

- Block Explorer
- Starkscan
- API

#### Properties

- [Website](https://starkscan.co)
- [Postman Collection](collections/starknet.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/starknet.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.starknet.io)
- [Documentation](https://docs.starknet.io)
- [Foundation](https://www.starknet.io/foundation)
- [Git Hub Stark Ware](https://github.com/starkware-libs)
- [Git Hub Starknet](https://github.com/starknet-io)
- [Specs](https://github.com/starkware-libs/starknet-specs)
- [Bridge](https://starkgate.starknet.io)
- [Community](https://community.starknet.io)
- [Twitter](https://x.com/Starknet)
- [Discord](https://discord.gg/starknet-community)
- [Telegram](https://t.me/sncorestars)
- [Blog](https://www.starknet.io/blog)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
