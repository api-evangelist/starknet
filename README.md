# Starknet (starknet)

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
