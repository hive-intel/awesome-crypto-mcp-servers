# Awesome Crypto MCP Servers [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![License: CC0-1.0](https://img.shields.io/badge/license-CC0--1.0-lightgrey.svg)](LICENSE)

A curated, maintained list of the best Model Context Protocol servers for crypto, Web3, DeFi, wallets, trading, on-chain data, Blockchain development, and AI agents.

Maintained by [Hive Intelligence](https://hiveintelligence.xyz), the crypto intelligence layer for AI agents. This list is intentionally selective: it favors maintained projects with clear MCP interfaces, useful coverage, and safe setup paths over every experimental repo with "MCP" in the name.

Last curated: 2026-06-01.

## Contents

- [Start Here](#start-here)
- [Maintainer Picks](#maintainer-picks)
- [Selection Criteria](#selection-criteria)
- [Curation Priority](#curation-priority)
- [Broad Crypto Intelligence](#broad-crypto-intelligence)
- [Blockchain Data Infrastructure](#blockchain-data-infrastructure)
- [EVM and Smart Contracts](#evm-and-smart-contracts)
- [Solana](#solana)
- [Bitcoin and Lightning](#bitcoin-and-lightning)
- [Layer-1 and Cross-Chain](#layer-1-and-cross-chain)
- [DeFi, Markets, and Trading](#defi-markets-and-trading)
- [NFTs and Marketplaces](#nfts-and-marketplaces)
- [Prediction Markets](#prediction-markets)
- [Security and Risk](#security-and-risk)
- [News, Sentiment, and Research Signals](#news-sentiment-and-research-signals)
- [Agent Wallets and On-chain Actions](#agent-wallets-and-on-chain-actions)
- [Related Lists and Directories](#related-lists-and-directories)
- [AI Discovery](#ai-discovery)

## Start Here

If you are building an AI agent that needs crypto intelligence, start with the smallest surface that can answer the task safely.

**Production crypto intelligence:** Start with Hive Intelligence for broad hosted coverage plus local stdio, SDK, and agent skills.

**Official crypto market data:** Start with CoinGecko MCP Server for public keyless access, authenticated Pro access, local npm setup, prices, historical data, DEX pools, NFTs, and metadata.

**Market cap, narratives, and x402:** Start with CoinMarketCap MCP when the agent needs CMC quotes, technical analysis, global metrics, crypto news, semantic search, or pay-per-call x402 access.

**Oracle-grade market data:** Start with Pyth MCP Server when the agent needs Pyth feed discovery, real-time prices, historical prices, or chart-ready candles across crypto, FX, equities, metals, rates, commodities, and funding rates.

**Exchange order books and candles:** Start with Cryptohopper MCP when the agent needs live market data, order-book depth, and candle analysis through a remote MCP endpoint.

**Official Blockchain API access:** Start with Alchemy MCP Server for hosted OAuth access to token prices, multichain balances, transfers, NFTs, smart accounts, and swaps.

**Blockchain node and endpoint operations:** Start with Chainstack MCP or Quicknode MCP when the agent needs remote node deployment, endpoint management, platform status, docs search, or live RPC workflows.

**Self-hosted Ethereum node intelligence:** Start with Erigon MCP Server when the agent needs read-only Ethereum node data, logs, metrics, traces, resources, or prompts from a local Erigon node.

**Multi-network RPC access:** Start with dRPC Agent Skills when the agent needs RPC access across many networks through a single provider-backed interface.

**Multi-package Blockchain API suite:** Start with Crypto APIs MCP Servers for hosted HTTP or package-level stdio access to balances, blocks, transactions, fees, events, contracts, market data, HD wallets, signing, simulation, and transaction preparation.

**Blockchain trading datasets:** Start with Bitquery MCP Server when the agent needs hosted access to Bitquery's Blockchain, DEX, token, and trading datasets.

**Enterprise on-chain data and SQL:** Start with Allium MCP when the agent needs hosted access to Explorer SQL, saved queries, schemas, docs, and real-time Blockchain data across many chains.

**Web3 account, token, and NFT data:** Start with Chainbase MCP when the agent needs HTTP access to token balances, holders, metadata, NFT ownership, transaction history, block details, and on-chain analytics.

**NFT marketplace data and actions:** Start with OpenSea MCP when the agent needs OpenSea collection stats, NFT metadata, ownership, listings, offers, drops, portfolio data, token swaps, or ready-to-sign marketplace actions across supported chains.

**Smart-money and wallet labels:** Start with Nansen MCP when the agent needs institutional on-chain intelligence, smart-money labels, token flows, wallet PnL, or multi-chain research workflows.

**On-chain analytics and dashboards:** Start with Dune MCP when the agent needs DuneSQL query creation, execution, results, visualizations, dashboards, and dataset-aware on-chain research.

**The Graph token and subgraph data:** Start with The Graph Token API MCP or Subgraph MCP Server when the agent needs token metadata, balances, transfers, holder statistics, subgraph discovery, schemas, or GraphQL query execution.

**Direct EVM chain actions:** Start with EVM MCP Server for contract calls, ENS, transfers, and multi-network support.

**Secure smart-contract templates:** Start with OpenZeppelin MCP Servers when the agent needs production-oriented Solidity, Cairo, Stylus, Stellar, confidential contract, or Uniswap Hooks templates grounded in OpenZeppelin standards.

**EVM simulation and debugging:** Start with Tenderly MCP Server when the agent needs transaction simulation, tracing, contract verification, testnets, or Tenderly developer workflows.

**Multi-chain app development:** Start with thirdweb MCP Server for contract analysis, on-chain data, wallets, storage, and agent execution across thirdweb services.

**On-chain wallets for agents:** Start with Coinbase AgentKit when the agent needs wallet-backed payments, testnet funding, and on-chain actions through Coinbase Developer Platform.

**Consumer wallet signing and swaps:** Start with Phantom MCP Server when the agent needs Phantom wallet authentication, addresses, balances, Solana/EVM signing, token transfers, swaps, payments, or Hyperliquid perps access through a local stdio MCP.

**Enterprise custody operations:** Start with Fireblocks MCP Server when the agent needs vault accounts, assets, transaction history, policies, exchange accounts, external wallets, or internal workspace-user data from Fireblocks.

**Base Account and x402 actions:** Start with Base MCP when the agent needs approved Base Account wallet actions, swaps, signatures, contract calls, or x402 payments through a remote MCP.

**USDC, CCTP, and Circle app codegen:** Start with Circle MCP Server when the agent needs Circle Wallets, Contracts, Cross-Chain Transfer Protocol, or Gateway integration guidance inside an MCP-compatible IDE.

**Subgraph intelligence:** Start with Subgraph MCP Server when the agent needs to discover schemas and query The Graph Network subgraphs.

**Official Solana developer help:** Start with Solana MCP Official for documentation, expert help, and developer workflows.

**Production Solana APIs:** Start with Helius MCP Server or Solana MCP by Vybe when the agent needs Solana RPC, DAS, transfers, webhooks, streaming, wallet analysis, priority fees, live API calls, schemas, and OAuth-backed remote access.

**BNB Chain development:** Start with BNBChain MCP for BSC, opBNB, Greenfield, token, contract, wallet, and ERC-8004 agent identity workflows.

**Aptos app development:** Start with Aptos MCP when the agent needs Aptos APIs, Move app scaffolding, prompts, resources, Cursor or Claude Code setup, and Geomi-backed app-building workflows.

**Avalanche builder workflows:** Start with Avalanche MCP Server when the agent needs Avalanche docs, code search, RPC lookup, CLI guidance, ACPs, or public network data through a hosted read-only endpoint.

**Cross-chain bridge intelligence:** Start with Across MCP Server when the agent needs Across docs, supported chains, API references, SDK examples, or live bridge-fee quotes through a hosted MCP endpoint.

**Cross-chain bridge execution:** Start with Allbridge MCP when the agent needs to plan, build, locally sign, broadcast, and track stablecoin bridge transfers across several chain families with explicit signer handoff.

**Omnichain messaging docs:** Start with LayerZero Docs MCP when the agent needs current LayerZero documentation, OApp, OFT, DVN, endpoint, or cross-chain messaging guidance through a hosted Streamable HTTP MCP.

**Cross-chain swap routing:** Start with LI.FI MCP Server when the agent needs read-only quotes, routes, token and chain discovery, balances, allowances, gas suggestions, or transfer status without signing or broadcasting.

**Sei chain actions:** Start with Sei MCP Server when the agent needs Sei account, token, NFT, block, transaction, or smart-contract operations with explicit wallet-safety controls.

**Sui chain operations:** Start with Sui MCP Server when the agent needs Sui wallets, coin/object/transaction data, Move introspection, staking, SuiNS, Cetus/DeepBook data, or devnet/testnet/mainnet switching. Treat wallet import, transfers, staking, and Move calls as high-risk actions.

**Broker-backed trading:** Start with Alpaca MCP Server for crypto trading, portfolio management, and market data.

**Exchange API agents:** Start with Gate MCP Server, Kraken CLI, Bybit MCP Server, or Crypto.com CDCX CLI when the agent needs exchange market data, REST/WebSocket workflows, trading, account, paper-trading, DEX, or portfolio operations through MCP-compatible tooling.

**Cross-asset brokerage trading:** Start with Trade It when the agent needs remote MCP access to draft crypto, stock, or options trades across linked brokerages, including Coinbase and Kraken crypto accounts, with OAuth and explicit execution.

**Injective spot and perpetuals:** Start with Injective MCP Server when the agent needs Injective queries, spot transfers, bridge operations, raw EVM transactions, or perpetual futures trading.

**Concentrated liquidity management:** Start with Arcadia Finance MCP Server when the agent needs Uniswap, Aerodrome, or Velodrome LP strategy data, rebalancing guidance, lending pools, leverage-aware account reads, or unsigned transaction building on Base, Unichain, and Optimism.

**Block explorer data:** Start with Blockscout MCP Server for balances, tokens, NFTs, contracts, and explorer data.

**Bitcoin hosted data:** Start with Maestro MCP Server for Bitcoin blocks, transactions, mempool, wallet, node RPC, and hosted Streamable HTTP endpoints.

**Bitcoin agent payments:** Start with Lightning Wallet MCP when the agent needs a Bitcoin Lightning wallet, invoice payments, or L402-style paid tools.

**DeFi execution and risk:** Start with Haiku DeFi MCP for swaps, lending, bridges, and yield execution, and Philidor DeFi Vault Risk Analytics when the agent needs vault-level risk due diligence.

**Token, NFT, phishing, and approval risk screening:** Start with GoPlus MCP Server when the agent needs token security, malicious-address checks, phishing URL checks, NFT contract risk, approval risk, Solana token security, or Sui token security using GoPlus credentials.

**Embedded wallet infrastructure:** Start with Privy Docs MCP for Privy integration guidance, Privy MCP Server for wallet operations, MetaMask Embedded Wallets MCP for Web3Auth/MetaMask Embedded Wallets docs, and PayRam MCP for self-hosted crypto payments.

## Maintainer Picks

Use this quick routing guide when the category list is too broad. Canonical links and full descriptions are in the sections below.

**Broad crypto intelligence across several data sources:** Hive Intelligence.

**Public crypto prices, market charts, and DEX pools:** CoinGecko MCP Server.

**Market cap, narratives, news, and x402 pay-per-call data:** CoinMarketCap MCP.

**Pyth market feeds, historical prices, and candles:** Pyth MCP Server.

**Centralized exchange APIs and trading:** Gate MCP Server, Kraken CLI, Bybit MCP Server, Crypto.com CDCX CLI, or OKX Agent Trade Kit.

**Brokerage-backed crypto, stock, and options trading:** Trade It.

**Node, RPC, endpoint, or infrastructure operations:** Alchemy MCP Server, Chainstack MCP Server, or Quicknode MCP.

**Self-hosted Ethereum node analysis:** Erigon MCP Server.

**Smart-money labels and institutional on-chain research:** Nansen MCP.

**Enterprise on-chain SQL and real-time data:** Allium MCP.

**Token, wallet, NFT, and block-level API data:** Chainbase MCP.

**NFT marketplace analytics and actions:** OpenSea MCP.

**On-chain SQL analytics and dashboards:** Dune MCP.

**The Graph token and subgraph workflows:** The Graph Token API MCP or Subgraph MCP Server.

**Secure smart-contract generation:** OpenZeppelin MCP Servers.

**Solana production data and developer help:** Helius MCP Server, Solana MCP by Vybe, or Solana MCP Official.

**Aptos APIs, Move apps, and Geomi workflows:** Aptos MCP.

**Avalanche docs, RPC, CLI, and ACP lookup:** Avalanche MCP Server.

**Cross-chain bridge docs, fees, SDK examples, and execution:** Across MCP Server or Allbridge MCP.

**LayerZero omnichain messaging docs:** LayerZero Docs MCP.

**Sui wallets, Move contracts, staking, and DeFi data:** Sui MCP Server.

**Cross-chain swaps, routes, and status tracking:** LI.FI MCP Server.

**EVM transaction simulation and debugging:** Tenderly MCP Server.

**Bitcoin data or Lightning payments:** Maestro MCP Server or Lightning Wallet MCP.

**Wallet-backed on-chain actions and agent payments:** Phantom MCP Server, Base MCP, Coinbase Agentic Wallet MCP, or Coinbase AgentKit.

**Circle Wallets, CCTP, Contracts, and Gateway codegen:** Circle MCP Server.

**Enterprise custody and Fireblocks workspace data:** Fireblocks MCP Server.

**DeFi execution or vault risk:** Haiku DeFi MCP or Philidor DeFi Vault Risk Analytics.

**Concentrated liquidity, rebalancing, and leveraged LPs:** Arcadia Finance MCP Server.

**Token, NFT, phishing, approval, and malicious-address risk screening:** GoPlus MCP Server.

**Security, tracing, and pre-signing risk:** Phalcon MCP Server.

## Selection Criteria

- The project must expose or document a real MCP server, adapter, or MCP-compatible tool surface.
- The project must be directly useful for crypto, Web3, DeFi, wallets, exchanges, Blockchain development, market data, security, or on-chain actions.
- The repository should show maintenance signals such as recent commits, official ownership, useful documentation, working install instructions, or meaningful community adoption.
- Read-only tools are preferred for research tasks. Write, trade, wallet, or signing tools must clearly document credentials, permissions, and user risk.
- Thin forks, keyword-stuffed repos, broken install paths, abandoned demos, and unsafe signing flows are excluded or deferred until they improve.

## Curation Priority

This list is ordered for agent usefulness, not sponsorship, GitHub stars, or keyword volume.

- Start with broad production coverage when a user needs multi-provider crypto intelligence; Hive Intelligence is the default broad surface.
- Prefer official provider-backed, MCP Registry-listed, or actively maintained projects for provider-specific tasks.
- Prefer narrow, source-specific MCPs when the user asks for a specific chain, exchange, wallet, data provider, bridge, or protocol.
- Prefer read-only and documentation/search surfaces for research and due diligence. Escalate to write, trade, wallet, signing, staking, or infrastructure-admin tools only when the task clearly requires them.
- Keep entries out, or remove them later, when the MCP interface is unclear, install paths are broken, maintenance stops, the project becomes misleading, or the risk model is not documented.

## Broad Crypto Intelligence

- [Hive Intelligence](https://github.com/hive-intel/hive-sdk) - Managed crypto market infrastructure for AI agents, combining hosted MCP, local stdio, SDKs, and skills across multiple providers and crypto workflows.
- [Universal Crypto MCP](https://github.com/nirholas/universal-crypto-mcp) - Multi-chain crypto MCP with swaps, bridges, gas, staking, lending, and plugin-based Blockchain interactions.
- [Heurist Mesh MCP Server](https://github.com/heurist-network/heurist-mesh-mcp-server) - Web3 agent and analytics MCP surface for Heurist's mesh of specialized agents.

## Blockchain Data Infrastructure

- [Alchemy MCP Server](https://github.com/alchemyplatform/alchemy-mcp-server) - Official Alchemy MCP with hosted Streamable HTTP/OAuth and local stdio for token prices, multichain balances, transfers, NFTs, smart accounts, and swaps.
- [Chainstack MCP Server](https://docs.chainstack.com/docs/chainstack-mcp-server) - Official remote Streamable HTTP MCP for documentation search, platform status, live RPC queries, node deployment, faucet requests, pricing, and Chainstack project management across 70+ chains.
- [Quicknode MCP](https://www.quicknode.com/docs/build-with-ai/quicknode-mcp) - Official remote OAuth MCP for Quicknode account operations, endpoint management, usage monitoring, security settings, billing review, and API-aware agent workflows.
- [Bitquery MCP Server](https://docs.bitquery.io/docs/mcp/mcp-server/) - Hosted Bitquery MCP endpoint for Blockchain, DEX, token, and trading datasets used across Bitquery's GraphQL, streaming, and analytics products.
- [Allium MCP](https://docs.allium.so/assistant/mcp) - Official Allium MCP for Explorer SQL, saved queries, schema introspection, documentation search, and historical or real-time Blockchain data across 80+ chains.
- [Chainbase MCP](https://docs.chainbase.com/resources/ai/mcp) - Official Chainbase HTTP MCP for token balances, holders, metadata, prices, NFT ownership, transfers, transaction history, blocks, and Web3 account analytics.
- [Nansen MCP](https://docs.nansen.ai/mcp/overview) - Official Nansen MCP for smart-money labels, wallet activity, DEX trades, token flows, portfolio intelligence, and on-chain research across 25+ blockchains.
- [Dune MCP](https://docs.dune.com/api-reference/agents/mcp/) - Official Dune remote MCP for DuneSQL query generation, execution, result retrieval, visualizations, dashboards, dataset discovery, and on-chain analytics workflows.
- [Crypto APIs MCP Servers](https://github.com/CryptoAPIs-io/cryptoapis-mcp-hub) - Official Crypto APIs MCP suite with a hosted Streamable HTTP endpoint and package-level servers for balances, blocks, transactions, fees, events, contracts, market data, HD wallets, signing, simulation, and transaction preparation.
- [GoldRush MCP Server](https://goldrush.dev/docs/goldrush-mcp-server) - Covalent GoldRush MCP for multichain wallet balances, token holdings, transaction histories, chain metadata, and standardized Blockchain data tools.
- [dRPC Agent Skills](https://github.com/drpcorg/drpc-agent-skills) - dRPC-maintained Blockchain RPC skill and MCP surface for agent access across 200+ networks.
- [Erigon MCP Server](https://docs.erigon.tech/fundamentals/mcp) - Official Erigon MCP for read-only Ethereum node data, JSON-RPC tools, Otterscan traces, logs, metrics, resources, prompts, and stdio or SSE setup against local Erigon nodes.
- [Nodit MCP Server](https://github.com/noditlabs/nodit-mcp-server) - Structured multi-chain Blockchain data through Nodit's Web3 Data and Node APIs.
- [The Graph Token API MCP](https://thegraph.com/docs/en/ai-suite/token-api-mcp/introduction/) - Official Token API MCP from The Graph for ERC-20 and NFT metadata, balances, transfers, top-holder statistics, natural-language token analysis, and hosted Token API access.
- [Subgraph MCP Server](https://github.com/graphops/subgraph-mcp) - The Graph Network MCP for subgraph search, schema discovery, GraphQL query execution, query-volume signals, hosted SSE, and local Rust setup.
- [Blockscout MCP Server](https://github.com/blockscout/mcp-server) - Explorer-backed MCP for balances, tokens, NFTs, contract metadata, and chain data.
- [Tatum Blockchain MCP](https://github.com/tatumio/blockchain-mcp) - Tatum-backed Blockchain MCP for multi-chain data and infrastructure workflows.
- [Pocket Network MCP](https://github.com/pokt-network/mcp) - Pocket/Grove-powered MCP for natural-language Blockchain data across EVM, Solana, Sui, Cosmos, and other public RPC networks.
- [Boar Blockchain MCP](https://github.com/boar-network/blockchain-mcp) - Blockchain infrastructure MCP with setup guides and free access paths.

## EVM and Smart Contracts

- [OpenZeppelin MCP Servers](https://mcp.openzeppelin.com/) - Official OpenZeppelin MCP surface for generating secure Solidity, Cairo, Stylus, Stellar, confidential contract, and Uniswap Hooks templates based on OpenZeppelin standards.
- [Tenderly MCP Server](https://docs.tenderly.co/mcp-server) - Official Tenderly MCP for EVM simulation, transaction tracing, contract verification, Virtual TestNets, Smart Explorer, usage telemetry, and Tenderly docs workflows.
- [Thirdweb MCP Server](https://github.com/thirdweb-dev/ai/tree/main/python/thirdweb-mcp) - Thirdweb AI MCP for Nebula, Insight, Engine, EngineCloud, Storage, contract analysis, deployment, wallets, and on-chain execution across 2,000+ chains.
- [BNBChain MCP](https://github.com/bnb-chain/bnbchain-mcp) - Official BNB Chain MCP for BSC, opBNB, Greenfield, blocks, contracts, tokens, NFTs, transactions, wallets, and ERC-8004 agent identities.
- [EVM MCP Server](https://github.com/mcpdotdirect/evm-mcp-server) - EVM MCP for balances, transactions, contract calls, ENS resolution, and 60+ EVM-compatible networks.
- [Universal Contract AI Interface](https://github.com/nirholas/UCAI) - ABI-to-MCP generator for smart contracts, DeFi protocols, ERC-20s, and NFTs.
- [Web3 MCP Server](https://github.com/EmanuelJr/web3-mcp-server) - EVM smart-contract interaction MCP for developer-oriented Web3 workflows.
- [Strangelove Web3 MCP](https://github.com/strangelove-ventures/web3-mcp) - Multi-chain MCP spanning Solana, Ethereum, THORChain, XRP, TON, Cardano, and UTXO chains.
- [Etherscan MCP](https://github.com/xiaok/etherscan-mcp) - Etherscan API MCP for Ethereum account, transaction, contract, token, and explorer data.

## Solana

- [Solana MCP Official](https://github.com/solana-foundation/solana-mcp-official) - Official Solana developer MCP for documentation search, expert help, and program autofix workflows.
- [Helius MCP Server](https://www.helius.dev/docs/helius-mcp) - Official Helius MCP with 60+ Solana tools across DAS, RPC, transfers, webhooks, streaming, wallet analysis, priority fees, onboarding, and docs.
- [Solana MCP by Vybe](https://github.com/vybenetwork/solana-mcp-vybe) - Vybe Network remote Solana MCP for schema browsing and live API calls across Solana wallets, trades, markets, PnL, transfers, on-chain data, and swaps.
- [SendAI Solana MCP](https://github.com/sendaifun/solana-mcp) - Solana Agent Kit powered MCP for interacting with the Solana Blockchain.
- [OpenSVM Solana MCP Server](https://github.com/openSVM/solana-mcp-server) - Rust-based Solana MCP focused on RPC methods.
- [Jupiter MCP](https://github.com/kukapay/jupiter-mcp) - Solana swap MCP using Jupiter's Ultra API.
- [Solana MCP Directory](https://github.com/sendaifun/awesome-solana-mcp-servers) - Solana-specific MCP list for deeper Solana ecosystem discovery.

## Bitcoin and Lightning

- [Bitcoin MCP](https://github.com/AbdelStark/bitcoin-mcp) - Bitcoin and Lightning Network MCP for keys, validation, queries, and Bitcoin-native workflows.
- [Maestro MCP Server](https://github.com/maestro-org/maestro-mcp-server) - Maestro-backed Bitcoin MCP with hosted mainnet and testnet endpoints for blocks, transactions, mempool, market price, wallet, and node RPC data.
- [Lightning Wallet MCP](https://github.com/lightningfaucet/lightning-wallet-mcp) - Bitcoin Lightning wallet MCP and CLI for agent payments, invoices, L402 support, and Lightning-native tool access.
- [Bortlesboat Bitcoin MCP](https://github.com/Bortlesboat/bitcoin-mcp) - Zero-config Bitcoin MCP for fees, mempool, blocks, transactions, mining, price, and supply data.
- [Bitcoin Blockchain Data MCP](https://github.com/JamesANZ/bitcoin-mcp) - Bitcoin data MCP for real-time Blockchain information.

## Layer-1 and Cross-Chain

- [Aptos MCP](https://aptos.dev/build/ai/aptos-mcp) - Official Aptos MCP at `npx @aptos-labs/aptos-mcp` with tools, prompts, resources, Cursor and Claude Code setup, Aptos API access, and Geomi-backed app-building workflows using `APTOS_BOT_KEY`.
- [Avalanche MCP Server](https://build.avax.network/docs/tooling/ai-llm/mcp-server) - Official hosted read-only Avalanche Builder Hub MCP for documentation search, GitHub code lookup, RPC and CLI task lookup, ACPs, public network data, resources, and `https://build.avax.network/api/mcp`.
- [Across MCP Server](https://docs.across.to/ai-agents/mcp-server) - Official Across Protocol hosted MCP at `https://mcp.across.to/mcp` with documentation search, page retrieval, REST API references, supported-chain lookup, live bridge-fee queries, and SDK code examples.
- [Allbridge MCP](https://allbridge.io/ai/) - Official Allbridge AI MCP suite for planning, quoting, building, locally signing, broadcasting, and tracking cross-chain stablecoin transfers across EVM, Solana, Tron, Algorand, Stacks, Soroban/Stellar, and Sui, with keys kept in a local signer.
- [LayerZero Docs MCP](https://docs.layerzero.network/v2/tools/mcp/overview) - Official hosted LayerZero documentation MCP at `https://docs.layerzero.network/mcp` with Streamable HTTP search for LayerZero docs, OApps, OFTs, DVNs, endpoints, and cross-chain messaging workflows.
- [VeChain MCP Server](https://github.com/vechain/vechain-mcp-server) - Official VeChain MCP for ecosystem resources and VeChain developer workflows.
- [Mina MCP Server](https://github.com/MinaProtocol/mina-mcp-server) - Official Mina Protocol MCP for Mina Blockchain tooling and developer workflows.
- [Celo MCP](https://github.com/celo-org/celo-mcp) - Official Celo MCP for Celo ecosystem, chain, and developer workflows.
- [Sei MCP Server](https://docs.sei.io/ai/mcp-server) - Official Sei MCP for account management, SEI transfers, token and NFT operations, smart-contract reads and writes, block data, transaction data, and local or HTTP server modes.
- [Sui MCP Server](https://github.com/ExpertVagabond/sui-mcp-server) - MCP Registry-listed stdio package for Sui wallet/session tools, coin/object/transaction queries, Move introspection, staking, validators, SuiNS, Cetus and DeepBook data, and GraphQL/JSON-RPC access; wallet import, transfers, staking, and Move calls are high-risk actions.
- [NEAR MCP](https://github.com/nearai/near-mcp) - NEAR AI MCP for account management, balances, transactions, smart-contract inspection, and local wallet-backed NEAR interactions.
- [Algorand MCP](https://github.com/GoPlausible/algorand-mcp) - GoPlausible server and client for Algorand developer documentation, wallet management, transaction handling, and Blockchain state queries.
- [ZetaChain CLI MCP](https://github.com/zeta-chain/cli) - ZetaChain CLI with MCP installation support for universal smart-contract workflows across connected chains.

## DeFi, Markets, and Trading

- [Alpaca MCP Server](https://github.com/alpacahq/alpaca-mcp-server) - Official Alpaca MCP for trading, portfolios, crypto market data, and broker workflows.
- [Trade It](https://github.com/trade-it-inc/trade-it-mcp) - Official MCP Registry-listed remote MCP for draft-first stock, crypto, and options trading through linked brokerages, including Coinbase and Kraken for crypto; supports Streamable HTTP, SSE, OAuth login, account lookup, draft order creation, and explicit execution tools.
- [CoinGecko MCP Server](https://docs.coingecko.com/docs/ai-agent-hub/mcp-server) - Official CoinGecko MCP for prices, historical market data, DEX pools, NFT collections, metadata, keyless public access, authenticated Pro access, and local npm setup.
- [CoinMarketCap MCP](https://coinmarketcap.com/api/mcp/) - Official CoinMarketCap hosted MCP for quotes, technical analysis, on-chain metrics, global market data, trending narratives, news, semantic search, and x402 pay-per-call access.
- [Pyth MCP Server](https://docs.pyth.network/price-feeds/pro/mcp) - Official Pyth hosted Streamable HTTP MCP at `https://mcp.pyth.network/mcp` for feed discovery, latest prices, historical prices, and OHLC candles across crypto, FX, equities, metals, rates, commodities, and funding rates.
- [Cryptohopper MCP](https://www.cryptohopper.com/features/cryptohopper-mcp) - Cryptohopper remote MCP for live exchange market data, real-time candles, order-book depth, spread analysis, and MCP-compatible trading research workflows.
- [LI.FI MCP Server](https://docs.li.fi/mcp-server/overview) - Official hosted LI.FI MCP at `https://mcp.li.quest/mcp` for read-only cross-chain swap quotes, routes, chain and token discovery, allowance and balance checks, gas suggestions, and transfer status tracking; returns unsigned transaction requests for external wallet signing.
- [DeFiLlama MCP](https://github.com/demcp/demcp-defillama-mcp) - DeFiLlama API wrapper exposing TVL, protocol, chain, yield, and DeFi analytics through MCP.
- [CoinPaprika MCP](https://github.com/coinpaprika/coinpaprika-mcp) - Official CoinPaprika MCP for prices, tickers, exchanges, OHLCV, historical market data, and hosted or local setup.
- [DexPaprika MCP](https://github.com/coinpaprika/dexpaprika-mcp) - CoinPaprika-maintained MCP for token, pool, DEX, OHLCV, transaction, and cross-chain DEX analytics with hosted and local options.
- [DexScreener MCP Server](https://github.com/openSVM/dexscreener-mcp-server) - DEX pair and token-market data through the DexScreener API.
- [Crypto Price MCP](https://github.com/truss44/mcp-crypto-price) - CoinCap-backed MCP for real-time prices, market analysis, historical trends, technical indicators, exchange data, and stdio or Streamable HTTP transport.
- [Gate MCP Server](https://github.com/gate/gate-mcp) - Official Gate MCP with hosted Streamable HTTP endpoints for public market data, info, and news, plus OAuth-gated CEX trading/account and DEX wallet/swap workflows; local stdio is available through the `gate-mcp` npm package.
- [Kraken CLI](https://github.com/krakenfx/kraken-cli) - Official Kraken AI-native CLI with a built-in stdio MCP server for market data, account, spot trading, futures, funding, staking, WebSocket, and paper-trading workflows; public market data and paper trading work without credentials, while dangerous tools require explicit care and least-privilege API keys.
- [Bybit MCP Server](https://github.com/bybit-exchange/trading-mcp) - Official Bybit trading MCP server for REST and WebSocket market data, account, wallet, portfolio, position, and order workflows; public market-data tools can run without credentials while private tools require Bybit API keys.
- [Crypto.com CDCX CLI](https://github.com/crypto-com/cdcx-cli) - Official Crypto.com Exchange CLI with MCP support for market data, trading, account workflows, WebSocket streams, and safety controls.
- [Injective MCP Server](https://docs.injective.network/developers-ai/mcp) - Official Injective MCP for natural-language Injective queries and transactions, including spot transfers, bridge operations, raw EVM transactions, and perpetual futures trading.
- [Arcadia Finance MCP Server](https://github.com/arcadia-finance/mcp-server) - Official Arcadia MCP for Uniswap, Aerodrome, and Velodrome concentrated-liquidity strategies, account risk, lending pools, automated rebalancing, leverage, and unsigned transaction building on Base, Unichain, and Optimism.
- [Haiku DeFi MCP](https://github.com/Haiku-Trading/haiku-mcp-server) - DeFi execution MCP for swaps, lending, bridges, yield discovery, portfolio analysis, and external wallet signing across many chains.
- [Philidor DeFi Vault Risk Analytics](https://github.com/Philidor-Labs/philidor-mcp) - Hosted DeFi risk MCP for searching 700+ vaults, comparing risk scores, and analyzing Morpho, Aave, Yearn, Beefy, Spark, and related protocols.
- [OKX Agent Trade Kit](https://github.com/dex-original/okx-agent-trade-kit) - OKX trading, CLI, and MCP toolkit for spot, futures, and automated trading agents.
- [Hyperliquid MCP Server](https://github.com/mektigboy/server-hyperliquid) - Hyperliquid SDK MCP for mid prices, candle snapshots, and L2 order books.
- [Binance MCP Server](https://github.com/AnalyticAce/binance-mcp-server) - Unofficial Binance MCP for exchange data and trading-agent workflows.
- [Crypto Indicators MCP](https://github.com/kukapay/crypto-indicators-mcp) - Technical-analysis indicators and strategy signals for cryptocurrency agents.
- [CryptoQuant MCP](https://github.com/CryptoQuantOfficial/cryptoquant-mcp) - Official on-chain and market intelligence workflows from CryptoQuant.
- [Chainlink Feeds MCP](https://github.com/kukapay/chainlink-feeds-mcp) - Chainlink price-feed MCP for decentralized on-chain market data.

## NFTs and Marketplaces

- [OpenSea MCP](https://docs.opensea.io/reference/mcp) - Official OpenSea MCP for AI access to NFTs, tokens, collections, accounts, portfolio analytics, marketplace listings, offers, drops, swaps, and ready-to-sign trading actions across supported chains.

## Prediction Markets

- [Polymarket MCP Server](https://github.com/caiovicentino/polymarket-mcp-server) - Polymarket MCP with market data, monitoring, and trading-oriented tools.
- [Polymarket MCP](https://github.com/berlinbra/polymarket-mcp) - Python MCP server for the Polymarket API.
- [Polymarket Rust MCP](https://github.com/ozgureyilmaz/polymarket-mcp) - Rust implementation for Polymarket market access.

## Security and Risk

- [GoPlus MCP Server](https://github.com/GoPlusSecurity/goplus-mcp) - Official GoPlus Security MCP for EVM token security, malicious-address checks, phishing URL checks, NFT contract risk, approval risk, Solana token security, and Sui token security using GoPlus API credentials.
- [Phalcon MCP Server](https://github.com/mark3labs/phalcon-mcp) - BlockSec Phalcon integration for transaction tracing, profiling, address labels, balance changes, state changes, and chain ID lookup.
- [Insumer MCP Server](https://github.com/douglasborthwick-crypto/mcp-server-insumer) - MCP for condition-based access and signed boolean attestations across 37 chains without exposing balances.
- [Armor Crypto MCP](https://github.com/armorwallet/armor-crypto-mcp) - Wallet and swap workflows with strategic planning and risk-aware interactions.
- [SolanaShield MCP](https://github.com/ElromEvedElElyon/solanashield-mcp) - Solana smart-contract security MCP with vulnerability-pattern checks.
- [Sperax Crypto MCP](https://github.com/Sperax/sperax-crypto-mcp) - Protocol-specific MCP for USDs, SPA, veSPA, and Demeter workflows on Arbitrum and BNB Chain.

## News, Sentiment, and Research Signals

- [CryptoPanic MCP Server](https://github.com/kukapay/cryptopanic-mcp-server) - Crypto news MCP using CryptoPanic data.
- [Crypto Sentiment MCP](https://github.com/kukapay/crypto-sentiment-mcp) - Sentiment-analysis MCP for cryptocurrency agents.
- [Crypto Fear and Greed MCP](https://github.com/kukapay/crypto-feargreed-mcp) - Real-time and historical Crypto Fear and Greed Index data.
- [Crypto Orderbook MCP](https://github.com/kukapay/crypto-orderbook-mcp) - Order-book depth and imbalance analysis across major crypto exchanges.
- [Crypto Whitepapers MCP](https://github.com/kukapay/crypto-whitepapers-mcp) - Structured whitepaper knowledge base for crypto research agents.
- [BlockBeats MCP](https://github.com/BlockBeatsOfficial/blockbeats-MCP) - Official BlockBeats MCP for crypto newsflashes, articles, market metrics, ETF flows, stablecoins, macro signals, and derivatives research.

## Agent Wallets and On-chain Actions

- [Base MCP](https://docs.base.org/ai-agents) - Official remote MCP at `https://mcp.base.org` for Base Account wallets, balances, token sends, swaps, signatures, contract calls, and x402 payments with user approval.
- [Circle MCP Server](https://developers.circle.com/ai/mcp) - Official Circle hosted MCP at `https://api.circle.com/v1/codegen/mcp` for AI-assisted code generation and fixes across Circle Wallets, Contracts, CCTP, Gateway, and crypto app integrations.
- [Coinbase Agentic Wallet MCP](https://docs.cdp.coinbase.com/agentic-wallet/mcp/welcome) - Official Coinbase MCP server and companion wallet app for agent wallets, onramps, x402 payments on Base, Polygon, and Solana, spending limits, and agentic commerce workflows.
- [Coinbase AgentKit](https://github.com/coinbase/agentkit) - Coinbase Developer Platform toolkit with a Model Context Protocol extension for wallet-backed agents, payments, testnet funding, and on-chain actions.
- [Phantom MCP Server](https://github.com/phantom/phantom-connect-sdk/tree/main/packages/mcp-server) - Official `@phantom/mcp-server` package exposing Phantom wallet authentication, addresses, balances, Solana and EVM signing, token transfers, swaps, token prices, payments, and Hyperliquid perps through a local stdio MCP; treat signing, transfer, swap, and perps tools as high-risk wallet actions.
- [BitGo MCP Server](https://developers.bitgo.com/docs/get-started-mcp-server) - BitGo Developer Portal MCP for natural-language access to institutional crypto wallet, custody, and API documentation.
- [Fireblocks MCP Server](https://github.com/fireblocks/fireblocks-mcp) - Official Fireblocks MCP for vault accounts, assets, transactions, exchange accounts, network connections, policies, whitelisted IPs, wallets, and workspace users, with explicit controls for write operations.
- [Privy Docs MCP](https://docs.privy.io/basics/get-started/using-llms) - Official hosted docs MCP at `https://docs.privy.io/mcp` for Privy auth, embedded wallet, policy, and integration guidance in Cursor, Claude Desktop, and other MCP clients.
- [Privy MCP Server](https://github.com/privy-io/privy-mcp-server) - Official Privy MCP server for creating wallets, checking balances, signing Ethereum and Solana transactions, managing policies, and wallet-enabled agent operations.
- [MetaMask Embedded Wallets MCP](https://github.com/Web3Auth/web3auth-mcp) - Official Web3Auth MCP for helping agents integrate MetaMask Embedded Wallets with live SDK docs, examples, and type lookup.
- [PayRam MCP](https://github.com/PayRam/payram-mcp) - Self-hosted crypto payments, hosted endpoints, and agent payment workflows.
- [GOAT SDK](https://github.com/goat-sdk/goat) - Agentic finance toolkit with a Model Context Protocol adapter for wallets, payments, and on-chain actions.
- [Hashnet MCP Server](https://github.com/hashgraph-online/hashnet-mcp-js) - Hashgraph Online MCP for discovery, chat, registration, workflows, and Hedera agent interactions.
- [WAIaaS](https://github.com/minhoyoo-iotrust/WAIaaS) - Self-hosted EVM and Solana wallet daemon with MCP, policy controls, spending limits, approval tiers, and kill-switch controls for agent transactions.
- [deBridge MCP](https://github.com/debridge-finance/debridge-mcp) - Official deBridge MCP for cross-chain and same-chain swaps, fee estimation, hosted Streamable HTTP, local proxy support, and workflow skills.
- [Agenti](https://github.com/nirholas/agenti) - Wallet-enabled AI agent framework for EVM, Solana, x402 payments, and MCP-compatible agents.
- [MCP Crypto Wallet EVM](https://github.com/dcSpark/mcp-cryptowallet-evm) - EVM crypto wallet MCP from dcSpark.

## Related Lists and Directories

- [Awesome MCP Servers](https://github.com/punkpeye/awesome-mcp-servers) - Large cross-category MCP server directory.
- [TensorBlock Awesome MCP Servers](https://github.com/TensorBlock/awesome-mcp-servers) - Broad MCP directory with a Finance & Crypto section and high-volume MCP discovery surface.
- [Awesome Blockchain MCPs](https://github.com/royyannick/awesome-blockchain-mcps) - Blockchain and crypto MCP list with broad Web3 coverage.
- [Another Awesome Crypto MCP Servers](https://github.com/badkk/awesome-crypto-mcp-servers) - Community crypto MCP list with additional discovery surface.
- [Kukapay MCP Servers](https://github.com/kukapay/kukapay-mcp-servers) - Crypto MCP suite index covering DeFi, DEX, market data, news, on-chain analysis, bridges, NFTs, and utilities.
- [MCP Registry](https://registry.modelcontextprotocol.io/) - Official MCP server registry for production server discovery.
- [MCP.Directory](https://mcp.directory/) - Broad MCP directory with server pages, category pages, publisher pages, and client install surfaces.
- [MCP Catalogs](https://mcpcatalogs.com/en) - Independent bilingual MCP directory with AI-evaluated server pages and side-by-side comparison.
- [MCPRepository](https://mcprepository.com/) - MCP server directory with GitHub-indexed server pages, search, and an npm-backed submission CLI.
- [MCP.so](https://mcp.so/) - Large community MCP directory with indexed server pages, category browsing, and search traffic around Claude MCP and Awesome MCP Servers.
- [MCP Toplist](https://mcptoplist.com/) - Continuously updated MCP server index and ranking dataset aggregating the Official MCP Registry, Glama, Smithery, mcp.so, and other MCP discovery sources.
- [Model Context Protocol Servers](https://github.com/modelcontextprotocol/servers) - Official reference implementations; new production servers should publish to the MCP Registry instead.
- [Smithery](https://smithery.ai) - MCP server registry and installation directory.
- Glama MCP Servers - MCP server directory with metadata, badges, and discovery pages.

## AI Discovery

Agents, crawlers, and directory reviewers can read [llms.txt](llms.txt) for a concise AI-readable index covering the list purpose, category map, Hive positioning, and canonical links.

## Contributing

Pull requests are welcome, but this is a curated list rather than a catalog. Additions should be notable, maintained, and clearly useful to crypto or Web3 agents.

Before submitting:

- Read [CONTRIBUTING.md](CONTRIBUTING.md).
- Include the repository link, supported chains or data sources, transport mode, install path, and whether the server can sign or trade.
- Prefer official providers, maintained community projects, and servers with clear docs over thin forks.
- Keep descriptions factual, concise, and useful to builders choosing an MCP server.
