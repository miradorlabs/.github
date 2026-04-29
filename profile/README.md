# Mirador

**Cross-chain observability for blockchain applications.**

[Mirador](https://mirador.org) correlates transactions across EVM and Solana chains into unified traces. We give developers, operators, and AI agents a single timeline for every cross-chain flow.

## What we build

- **Trace ingestion**: capture blockchain events via lightweight SDKs and correlate them with application context in real time
- **Cross-chain correlation**: automatically detect and match bridge transactions across chains (Ethereum, Polygon, Arbitrum, Base, Optimism, Solana, and more)
- **Safe multisig tracking**: follow Safe message and transaction confirmations from proposal to execution
- **Query API**: REST gateway for traces, events, and chain data with filtering, search, and streaming
- **Automation**: rule-based triggers with webhook, email, and Slack integrations

## Open source SDKs

| Package | Description | Install |
|---------|-------------|---------|
| [`@miradorlabs/nodejs-sdk`](https://github.com/miradorlabs/nodejs-sdk) | Server-side Node.js SDK (gRPC) | `npm install @miradorlabs/nodejs-sdk` |
| [`@miradorlabs/web-sdk`](https://github.com/miradorlabs/web-sdk) | Browser SDK (gRPC-Web) | `npm install @miradorlabs/web-sdk` |
| [`@miradorlabs/cli`](https://github.com/miradorlabs/mirador-cli) | CLI for querying traces and events | `npm install -g @miradorlabs/cli` |

## Links

- [Website](https://mirador.org)
- [Documentation](https://docs.mirador.org)
