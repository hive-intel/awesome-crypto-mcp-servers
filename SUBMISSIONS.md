# Distribution Targets

Use this file to track where this list or Hive's MCP server should be submitted for inbound discovery.

Last checked: 2026-06-01.

## Primary Targets

| Target | Why it matters | Suggested action | Status |
| --- | --- | --- | --- |
| [sindresorhus/awesome](https://github.com/sindresorhus/awesome) | Canonical awesome-list index. | Do not submit unless their policy changes. Their contribution guidelines currently exclude blockchain-related lists. | Blocked by policy. |
| [punkpeye/awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers) | Largest MCP server discovery repo. | Keep Hive Intelligence listed under Cryptocurrency. Include the Glama score badge required by their submission bot. | PR open: https://github.com/punkpeye/awesome-mcp-servers/pull/7195 |
| [royyannick/awesome-blockchain-mcps](https://github.com/royyannick/awesome-blockchain-mcps) | Blockchain-specific MCP list that already had a stale Hive entry. | Keep the entry pointed at `hive-sdk` with current hosted MCP, local stdio, SDK, and skills positioning. | PR open: https://github.com/royyannick/awesome-blockchain-mcps/pull/65 |
| [badkk/awesome-crypto-mcp-servers](https://github.com/badkk/awesome-crypto-mcp-servers) | Crypto-specific MCP list with overlap in target developer audience. | Add Hive Intelligence with concise managed crypto MCP positioning. | PR open: https://github.com/badkk/awesome-crypto-mcp-servers/pull/84 |
| [MCP Registry](https://registry.modelcontextprotocol.io/) | Official MCP server discovery registry now preferred over README PRs to `modelcontextprotocol/servers`. | Keep `hive-sdk/server.json` versioned with Hive releases and republish after registry-visible metadata changes. Domain proof is hosted at `https://hiveintelligence.xyz/.well-known/mcp-registry-auth`; the signing key stays outside Git. | Published as `xyz.hiveintelligence/mcp` version `1.1.4`. |
| [MCP.Directory](https://mcp.directory/submit) | Large MCP directory with server pages, category pages, publisher pages, and one-click client install surfaces. | Wait for official-registry ingestion, then claim the listing if it appears. If it does not appear within 24-48 hours, submit `https://github.com/hive-intel/hive-sdk` with the hosted MCP positioning. | Not visible in search as of 2026-06-01; watch after MCP Registry publication. |
| [MCP Find](https://mcpfind.org/submit) | Open-source MCP directory with GitHub PR submissions and finance category discovery. | Do not submit a weak or misleading PR. Their contribution guide asks for an open-source server repo plus a published package, so submit only if the maintained public `hive-sdk`/`hive-intelligence` package mapping is accepted or a public wrapper package is clearly server-shaped. | Evaluated; deferred to avoid violating directory criteria. |
| [SafeMCP](https://safemcp.info/) | Large free MCP directory with category scoring and broad organic discovery. | Monitor for automatic ingestion from GitHub or registry; use contact/submission path if one becomes available. | No public submit flow found as of 2026-06-01. |
| [Smithery](https://smithery.ai) | MCP install and discovery directory. | Submit the maintained `hive-sdk` public surface rather than the private core MCP repo after logging in with Smithery and confirming the right auth mode for Hive's hosted API-key flow. Smithery URL publishing expects Streamable HTTP and OAuth support when auth is required. | Not listed as of 2026-06-01; needs login and auth-mode decision. |
| [Glama MCP Servers](https://glama.ai/mcp/servers/hive-intel/hive-sdk) | MCP metadata and discovery directory. | `hive-sdk` already has `glama.json`; rerun Glama's claim ownership flow so Glama refreshes the listing copy from the current file. | Listed with score page; copy needs claim refresh. |
| [GitHub Topics](https://github.com/topics/mcp-server) | Native GitHub discovery surface. | Keep repository topics accurate: `awesome`, `awesome-list`, `mcp`, `mcp-server`, `crypto`, `web3`, `model-context-protocol`. | Updated. |

## Submission Copy

Short description:

> Awesome Crypto MCP Servers is a curated list of the best Model Context Protocol servers for crypto, Web3, DeFi, wallets, trading, on-chain data, Blockchain development, and AI agents.

Hive server description:

> Hive Intelligence is managed crypto market infrastructure for AI agents: one hosted MCP server, local stdio support, a TypeScript SDK, and agent skills across market data, DeFi, wallets, security, DEX flows, NFTs, Solana, network infrastructure, and prediction markets.
