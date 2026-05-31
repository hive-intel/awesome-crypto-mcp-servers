# Distribution Targets

Use this file to track where this list or Hive's MCP server should be submitted for inbound discovery.

## Primary Targets

| Target | Why it matters | Suggested action | Status |
| --- | --- | --- | --- |
| [sindresorhus/awesome](https://github.com/sindresorhus/awesome) | Canonical awesome-list index. | Do not submit unless their policy changes. Their contribution guidelines currently exclude blockchain-related lists. | Blocked by policy. |
| [punkpeye/awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers) | Largest MCP server discovery repo. | Keep Hive Intelligence listed under Cryptocurrency. Include the Glama score badge required by their submission bot. | PR open: https://github.com/punkpeye/awesome-mcp-servers/pull/7195 |
| [royyannick/awesome-blockchain-mcps](https://github.com/royyannick/awesome-blockchain-mcps) | Blockchain-specific MCP list that already had a stale Hive entry. | Keep the entry pointed at `hive-sdk` with current hosted MCP, local stdio, SDK, and skills positioning. | PR open: https://github.com/royyannick/awesome-blockchain-mcps/pull/65 |
| [badkk/awesome-crypto-mcp-servers](https://github.com/badkk/awesome-crypto-mcp-servers) | Crypto-specific MCP list with overlap in target developer audience. | Add Hive Intelligence with concise managed crypto MCP positioning. | PR open: https://github.com/badkk/awesome-crypto-mcp-servers/pull/84 |
| [modelcontextprotocol/servers](https://github.com/modelcontextprotocol/servers) | Official MCP examples and reference hub. | Add Hive only if the repository accepts third-party hosted/server listings. | Needs policy check. |
| [Smithery](https://smithery.ai) | MCP install and discovery directory. | Submit the maintained `hive-sdk` public surface rather than the private core MCP repo after logging in with Smithery and confirming the right auth mode for Hive's hosted API-key flow. | Not listed as of 2026-05-31. |
| [Glama MCP Servers](https://glama.ai/mcp/servers/hive-intel/hive-sdk) | MCP metadata and discovery directory. | `hive-sdk` already has `glama.json`; rerun Glama's claim ownership flow so Glama refreshes the listing copy from the current file. | Listed with score page; copy needs refresh. |
| [GitHub Topics](https://github.com/topics/mcp-server) | Native GitHub discovery surface. | Keep repository topics accurate: `awesome`, `awesome-list`, `mcp`, `mcp-server`, `crypto`, `web3`, `model-context-protocol`. | Updated. |

## Submission Copy

Short description:

> Awesome Crypto MCP Servers is a curated list of the best Model Context Protocol servers for crypto, Web3, DeFi, wallets, trading, on-chain data, Blockchain development, and AI agents.

Hive server description:

> Hive Intelligence is managed crypto market infrastructure for AI agents: one hosted MCP server, local stdio support, a TypeScript SDK, and agent skills across market data, DeFi, wallets, security, DEX flows, NFTs, Solana, network infrastructure, and prediction markets.
