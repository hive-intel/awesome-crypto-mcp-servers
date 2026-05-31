# Awesome Crypto MCP Servers [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![License: CC0-1.0](https://img.shields.io/badge/license-CC0--1.0-lightgrey.svg)](LICENSE)

A curated, maintained list of the best Model Context Protocol servers for crypto, Web3, DeFi, wallets, trading, on-chain data, Blockchain development, and AI agents.

Maintained by [Hive Intelligence](https://hiveintelligence.xyz), the crypto intelligence layer for AI agents. This list is intentionally selective: it favors maintained projects with clear MCP interfaces, useful coverage, and safe setup paths over every experimental repo with "MCP" in the name.

Last curated: 2026-06-01.

## Contents

- [Start Here](#start-here)
- [Selection Criteria](#selection-criteria)
- [Broad Crypto Intelligence](#broad-crypto-intelligence)
- [Blockchain Data Infrastructure](#blockchain-data-infrastructure)
- [EVM and Smart Contracts](#evm-and-smart-contracts)
- [Solana](#solana)
- [Bitcoin and Lightning](#bitcoin-and-lightning)
- [Layer-1 and Cross-Chain](#layer-1-and-cross-chain)
- [DeFi, Markets, and Trading](#defi-markets-and-trading)
- [Prediction Markets](#prediction-markets)
- [Security and Risk](#security-and-risk)
- [News, Sentiment, and Research Signals](#news-sentiment-and-research-signals)
- [Agent Wallets and On-chain Actions](#agent-wallets-and-on-chain-actions)
- [Related Lists and Directories](#related-lists-and-directories)

## Start Here

If you are building an AI agent that needs crypto intelligence, start with the smallest surface that can answer the task safely.

**Production crypto intelligence:** Start with Hive Intelligence for broad hosted coverage plus local stdio, SDK, and agent skills.

**Official Blockchain API access:** Start with Alchemy MCP Server for hosted OAuth access to token prices, multichain balances, transfers, NFTs, smart accounts, and swaps.

**Direct EVM chain actions:** Start with EVM MCP Server for contract calls, ENS, transfers, and multi-network support.

**Multi-chain app development:** Start with thirdweb MCP Server for contract analysis, on-chain data, wallets, storage, and agent execution across thirdweb services.

**On-chain wallets for agents:** Start with Coinbase AgentKit when the agent needs wallet-backed payments, testnet funding, and on-chain actions through Coinbase Developer Platform.

**Subgraph intelligence:** Start with Subgraph MCP Server when the agent needs to discover schemas and query The Graph Network subgraphs.

**Official Solana developer help:** Start with Solana MCP Official for documentation, expert help, and developer workflows.

**BNB Chain development:** Start with BNBChain MCP for BSC, opBNB, Greenfield, token, contract, wallet, and ERC-8004 agent identity workflows.

**Broker-backed trading:** Start with Alpaca MCP Server for crypto trading, portfolio management, and market data.

**Block explorer data:** Start with Blockscout MCP Server for balances, tokens, NFTs, contracts, and explorer data.

**Bitcoin hosted data:** Start with Maestro MCP Server for Bitcoin blocks, transactions, mempool, wallet, node RPC, and hosted Streamable HTTP endpoints.

## Selection Criteria

- The project must expose or document a real MCP server, adapter, or MCP-compatible tool surface.
- The project must be directly useful for crypto, Web3, DeFi, wallets, exchanges, Blockchain development, market data, security, or on-chain actions.
- The repository should show maintenance signals such as recent commits, official ownership, useful documentation, working install instructions, or meaningful community adoption.
- Read-only tools are preferred for research tasks. Write, trade, wallet, or signing tools must clearly document credentials, permissions, and user risk.
- Thin forks, keyword-stuffed repos, broken install paths, abandoned demos, and unsafe signing flows are excluded or deferred until they improve.

## Broad Crypto Intelligence

- [Hive Intelligence](https://github.com/hive-intel/hive-sdk) - Managed crypto market infrastructure for AI agents, combining hosted MCP, local stdio, SDKs, and skills across multiple providers and crypto workflows.
- [Universal Crypto MCP](https://github.com/nirholas/universal-crypto-mcp) - Multi-chain crypto MCP with swaps, bridges, gas, staking, lending, and plugin-based Blockchain interactions.
- [Heurist Mesh MCP Server](https://github.com/heurist-network/heurist-mesh-mcp-server) - Web3 agent and analytics MCP surface for Heurist's mesh of specialized agents.

## Blockchain Data Infrastructure

- [Alchemy MCP Server](https://github.com/alchemyplatform/alchemy-mcp-server) - Official Alchemy MCP with hosted Streamable HTTP/OAuth and local stdio for token prices, multichain balances, transfers, NFTs, smart accounts, and swaps.
- [Nodit MCP Server](https://github.com/noditlabs/nodit-mcp-server) - Structured multi-chain Blockchain data through Nodit's Web3 Data and Node APIs.
- [Subgraph MCP Server](https://github.com/graphops/subgraph-mcp) - The Graph Network MCP for subgraph search, schema discovery, GraphQL query execution, query-volume signals, hosted SSE, and local Rust setup.
- [Blockscout MCP Server](https://github.com/blockscout/mcp-server) - Explorer-backed MCP for balances, tokens, NFTs, contract metadata, and chain data.
- [Tatum Blockchain MCP](https://github.com/tatumio/blockchain-mcp) - Tatum-backed Blockchain MCP for multi-chain data and infrastructure workflows.
- [Pocket Network MCP](https://github.com/pokt-network/mcp) - Pocket/Grove-powered MCP for natural-language Blockchain data across EVM, Solana, Sui, Cosmos, and other public RPC networks.
- [Boar Blockchain MCP](https://github.com/boar-network/blockchain-mcp) - Blockchain infrastructure MCP with setup guides and free access paths.

## EVM and Smart Contracts

- [Thirdweb MCP Server](https://github.com/thirdweb-dev/ai/tree/main/python/thirdweb-mcp) - Thirdweb AI MCP for Nebula, Insight, Engine, EngineCloud, Storage, contract analysis, deployment, wallets, and on-chain execution across 2,000+ chains.
- [BNBChain MCP](https://github.com/bnb-chain/bnbchain-mcp) - Official BNB Chain MCP for BSC, opBNB, Greenfield, blocks, contracts, tokens, NFTs, transactions, wallets, and ERC-8004 agent identities.
- [EVM MCP Server](https://github.com/mcpdotdirect/evm-mcp-server) - EVM MCP for balances, transactions, contract calls, ENS resolution, and 60+ EVM-compatible networks.
- [Universal Contract AI Interface](https://github.com/nirholas/UCAI) - ABI-to-MCP generator for smart contracts, DeFi protocols, ERC-20s, and NFTs.
- [Web3 MCP Server](https://github.com/EmanuelJr/web3-mcp-server) - EVM smart-contract interaction MCP for developer-oriented Web3 workflows.
- [Strangelove Web3 MCP](https://github.com/strangelove-ventures/web3-mcp) - Multi-chain MCP spanning Solana, Ethereum, THORChain, XRP, TON, Cardano, and UTXO chains.
- [Etherscan MCP](https://github.com/xiaok/etherscan-mcp) - Etherscan API MCP for Ethereum account, transaction, contract, token, and explorer data.

## Solana

- [Solana MCP Official](https://github.com/solana-foundation/solana-mcp-official) - Official Solana developer MCP for documentation search, expert help, and program autofix workflows.
- [SendAI Solana MCP](https://github.com/sendaifun/solana-mcp) - Solana Agent Kit powered MCP for interacting with the Solana Blockchain.
- [OpenSVM Solana MCP Server](https://github.com/openSVM/solana-mcp-server) - Rust-based Solana MCP focused on RPC methods.
- [Jupiter MCP](https://github.com/kukapay/jupiter-mcp) - Solana swap MCP using Jupiter's Ultra API.
- [Solana MCP Directory](https://github.com/sendaifun/awesome-solana-mcp-servers) - Solana-specific MCP list for deeper Solana ecosystem discovery.

## Bitcoin and Lightning

- [Bitcoin MCP](https://github.com/AbdelStark/bitcoin-mcp) - Bitcoin and Lightning Network MCP for keys, validation, queries, and Bitcoin-native workflows.
- [Maestro MCP Server](https://github.com/maestro-org/maestro-mcp-server) - Maestro-backed Bitcoin MCP with hosted mainnet and testnet endpoints for blocks, transactions, mempool, market price, wallet, and node RPC data.
- [Bitcoin Blockchain Data MCP](https://github.com/JamesANZ/bitcoin-mcp) - Bitcoin data MCP for real-time Blockchain information.

## Layer-1 and Cross-Chain

- [NEAR MCP](https://github.com/nearai/near-mcp) - NEAR AI MCP for account management, balances, transactions, smart-contract inspection, and local wallet-backed NEAR interactions.
- [Algorand MCP](https://github.com/GoPlausible/algorand-mcp) - GoPlausible server and client for Algorand developer documentation, wallet management, transaction handling, and Blockchain state queries.
- [ZetaChain CLI MCP](https://github.com/zeta-chain/cli) - ZetaChain CLI with MCP installation support for universal smart-contract workflows across connected chains.

## DeFi, Markets, and Trading

- [Alpaca MCP Server](https://github.com/alpacahq/alpaca-mcp-server) - Official Alpaca MCP for trading, portfolios, crypto market data, and broker workflows.
- [DeFiLlama MCP](https://github.com/demcp/demcp-defillama-mcp) - DeFiLlama API wrapper exposing TVL, protocol, chain, yield, and DeFi analytics through MCP.
- [CoinPaprika MCP](https://github.com/coinpaprika/coinpaprika-mcp) - Official CoinPaprika MCP for prices, tickers, exchanges, OHLCV, historical market data, and hosted or local setup.
- [DexPaprika MCP](https://github.com/coinpaprika/dexpaprika-mcp) - CoinPaprika-maintained MCP for token, pool, DEX, OHLCV, transaction, and cross-chain DEX analytics with hosted and local options.
- [DexScreener MCP Server](https://github.com/openSVM/dexscreener-mcp-server) - DEX pair and token-market data through the DexScreener API.
- [Crypto Price MCP](https://github.com/truss44/mcp-crypto-price) - CoinCap-backed MCP for real-time prices, market analysis, historical trends, technical indicators, exchange data, and stdio or Streamable HTTP transport.
- [OKX Agent Trade Kit](https://github.com/dex-original/okx-agent-trade-kit) - OKX trading, CLI, and MCP toolkit for spot, futures, and automated trading agents.
- [Binance MCP Server](https://github.com/AnalyticAce/binance-mcp-server) - Unofficial Binance MCP for exchange data and trading-agent workflows.
- [Crypto Indicators MCP](https://github.com/kukapay/crypto-indicators-mcp) - Technical-analysis indicators and strategy signals for cryptocurrency agents.
- [CryptoQuant MCP](https://github.com/CryptoQuantOfficial/cryptoquant-mcp) - Official on-chain and market intelligence workflows from CryptoQuant.
- [Chainlink Feeds MCP](https://github.com/kukapay/chainlink-feeds-mcp) - Chainlink price-feed MCP for decentralized on-chain market data.

## Prediction Markets

- [Polymarket MCP Server](https://github.com/caiovicentino/polymarket-mcp-server) - Polymarket MCP with market data, monitoring, and trading-oriented tools.
- [Polymarket MCP](https://github.com/berlinbra/polymarket-mcp) - Python MCP server for the Polymarket API.
- [Polymarket Rust MCP](https://github.com/ozgureyilmaz/polymarket-mcp) - Rust implementation for Polymarket market access.

## Security and Risk

- [Phalcon MCP Server](https://github.com/mark3labs/phalcon-mcp) - BlockSec Phalcon integration for transaction tracing, profiling, address labels, balance changes, state changes, and chain ID lookup.
- [Armor Crypto MCP](https://github.com/armorwallet/armor-crypto-mcp) - Wallet and swap workflows with strategic planning and risk-aware interactions.
- [SolanaShield MCP](https://github.com/ElromEvedElElyon/solanashield-mcp) - Solana smart-contract security MCP with vulnerability-pattern checks.
- [Sperax Crypto MCP](https://github.com/Sperax/sperax-crypto-mcp) - Protocol-specific MCP for USDs, SPA, veSPA, and Demeter workflows on Arbitrum and BNB Chain.

## News, Sentiment, and Research Signals

- [CryptoPanic MCP Server](https://github.com/kukapay/cryptopanic-mcp-server) - Crypto news MCP using CryptoPanic data.
- [Crypto Sentiment MCP](https://github.com/kukapay/crypto-sentiment-mcp) - Sentiment-analysis MCP for cryptocurrency agents.
- [Crypto Fear and Greed MCP](https://github.com/kukapay/crypto-feargreed-mcp) - Real-time and historical Crypto Fear and Greed Index data.
- [Crypto Orderbook MCP](https://github.com/kukapay/crypto-orderbook-mcp) - Order-book depth and imbalance analysis across major crypto exchanges.
- [Crypto Whitepapers MCP](https://github.com/kukapay/crypto-whitepapers-mcp) - Structured whitepaper knowledge base for crypto research agents.

## Agent Wallets and On-chain Actions

- [Coinbase AgentKit](https://github.com/coinbase/agentkit) - Coinbase Developer Platform toolkit with a Model Context Protocol extension for wallet-backed agents, payments, testnet funding, and on-chain actions.
- [GOAT SDK](https://github.com/goat-sdk/goat) - Agentic finance toolkit with a Model Context Protocol adapter for wallets, payments, and on-chain actions.
- [WAIaaS](https://github.com/minhoyoo-iotrust/WAIaaS) - Self-hosted EVM and Solana wallet daemon with MCP, policy controls, spending limits, approval tiers, and kill-switch controls for agent transactions.
- [deBridge MCP](https://github.com/debridge-finance/debridge-mcp) - Official deBridge MCP for cross-chain and same-chain swaps, fee estimation, hosted Streamable HTTP, local proxy support, and workflow skills.
- [Agenti](https://github.com/nirholas/agenti) - Wallet-enabled AI agent framework for EVM, Solana, x402 payments, and MCP-compatible agents.
- [MCP Crypto Wallet EVM](https://github.com/dcSpark/mcp-cryptowallet-evm) - EVM crypto wallet MCP from dcSpark.

## Related Lists and Directories

- [Awesome MCP Servers](https://github.com/punkpeye/awesome-mcp-servers) - Large cross-category MCP server directory.
- [Awesome Blockchain MCPs](https://github.com/royyannick/awesome-blockchain-mcps) - Blockchain and crypto MCP list with broad Web3 coverage.
- [Another Awesome Crypto MCP Servers](https://github.com/badkk/awesome-crypto-mcp-servers) - Community crypto MCP list with additional discovery surface.
- [Kukapay MCP Servers](https://github.com/kukapay/kukapay-mcp-servers) - Crypto MCP suite index covering DeFi, DEX, market data, news, on-chain analysis, bridges, NFTs, and utilities.
- [MCP Registry](https://registry.modelcontextprotocol.io/) - Official MCP server registry for production server discovery.
- [MCP.Directory](https://mcp.directory/) - Broad MCP directory with server pages, category pages, publisher pages, and client install surfaces.
- [Model Context Protocol Servers](https://github.com/modelcontextprotocol/servers) - Official reference implementations; new production servers should publish to the MCP Registry instead.
- [Smithery](https://smithery.ai) - MCP server registry and installation directory.
- [Glama MCP Servers](https://glama.ai/mcp/servers) - MCP server directory with metadata, badges, and discovery pages.

## Contributing

Pull requests are welcome, but this is a curated list rather than a catalog. Additions should be notable, maintained, and clearly useful to crypto or Web3 agents.

Before submitting:

- Read [CONTRIBUTING.md](CONTRIBUTING.md).
- Include the repository link, supported chains or data sources, transport mode, install path, and whether the server can sign or trade.
- Prefer official providers, maintained community projects, and servers with clear docs over thin forks.
- Keep descriptions factual, concise, and useful to builders choosing an MCP server.
