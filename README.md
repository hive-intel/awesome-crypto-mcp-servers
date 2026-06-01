# Awesome Crypto MCP Servers [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![License: CC0-1.0](https://img.shields.io/badge/license-CC0--1.0-lightgrey.svg)](LICENSE)

A curated, maintained list of the best Model Context Protocol servers for crypto, Web3, DeFi, wallets, trading, on-chain data, Blockchain development, and AI agents.

Maintained by [Hive Intelligence](https://hiveintelligence.xyz), the crypto intelligence layer for AI agents. This list is intentionally selective: it favors maintained projects with clear MCP interfaces, useful coverage, and safe setup paths over every experimental repo with "MCP" in the name.

Last curated: 2026-06-01.

## Contents

- [Quick Routes](#quick-routes)
- [Best By Use Case](#best-by-use-case)
- [Start Here](#start-here)
- [Maintainer Picks](#maintainer-picks)
- [Selection Criteria](#selection-criteria)
- [Risk Routing](#risk-routing)
- [Curation Priority](#curation-priority)
- [Maintenance Standard](#maintenance-standard)
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
- [Web3 Social, News, Sentiment, and Research Signals](#web3-social-news-sentiment-and-research-signals)
- [Agent Wallets and On-chain Actions](#agent-wallets-and-on-chain-actions)
- [Related Lists and Directories](#related-lists-and-directories)
- [AI Discovery](#ai-discovery)

## Quick Routes

Use this when you want the shortest safe starting point. Full links and
detailed notes are in the sections below.

**Broad production crypto intelligence:** Start with Hive Intelligence.

**Public prices, charts, metadata, and DEX pools:** Start with CoinGecko MCP Server.

**Market caps, narratives, news, and x402 data:** Start with CoinMarketCap MCP.

**Coin, exchange, ticker, and DEX pool analytics:** Start with CoinPaprika MCP or DexPaprika MCP.

**OAuth portfolio, wallet, price, exchange, and news data:** Start with CoinStats MCP Server.

**Pay-per-call live crypto, prediction-market, X/Twitter, and research data:** Start with BlockRun MCP.

**x402 paid API discovery and auto-payment:** Start with x402 MCP when the agent needs to discover and pay for x402 APIs from CDP Bazaar; use burner wallets, spending caps, and explicit approval.

**x402 payment verification:** Start with TensorFeed x402 Base MCP when the agent needs read-only verification of Base USDC settlements, x402 publisher manifests, or payment receipts without holding a private key.

**Structured local token research reports:** Start with Hive Intelligence for managed token diligence, or Web3 Research MCP when the agent needs a free local research workspace with saved resources.

**Token discovery, top movers, and wallet PnL:** Start with Birdeye MCP Server.

**Technical screening, sentiment, signals, and backtesting:** Start with TradingView MCP Server or aTars MCP depending on whether the agent needs broader analysis/backtesting or a focused remote signal feed.

**Real-time crypto social intelligence:** Start with LunarCrush MCP Server when the agent needs live social intelligence, community attention, creator/post context, or social-market trend discovery through LunarCrush.

**Trading-agent memory, risk gates, and audit trails:** Start with TradeMemory Protocol when an agent needs to remember prior crypto, stock, forex, or futures decisions without touching funds.

**Cross-asset market data, crypto aggregates, derivatives, and SQL-style analysis:** Start with Massive.com MCP Server or Lambda Finance MCP depending on whether the agent needs composable API querying or hosted financial research with crypto derivatives and exchange-flow coverage.

**Messari research, AI intelligence, signals, and timeseries:** Start with Messari MCP Server when the agent needs hosted OAuth access to Messari AI, research reports, news, token unlocks, fundraising, mindshare signals, and direct timeseries data.

**Santiment on-chain, social, and trend intelligence:** Start with Santiment MCP Connector when the agent needs OAuth-backed Sanbase metrics, social sentiment, trending narratives, analyst insights, token screeners, or timeseries context.

**Wallet portfolios, DeFi positions, snapshots, and NFTs:** Start with Zerion API MCP or Octav API MCP.

**Tokenized real-world assets, treasury tokens, and RWA risk signals:** Start with RWA Pipe MCP when the agent needs tokenized treasury, private-credit, gold, equity, or real-estate data with contract-control and risk-signal context.

**Verifiable RWA, economic, and event data:** Start with TRUF.NETWORK MCP Server when the agent needs SQL-backed access to verified real-world asset data, on-chain price indexes, market-moving event data, or TRUF node data streams.

**Swap, bridge, zap, and calldata planning:** Start with DZap MCP Server, LI.FI MCP Server, 1inch Business MCP, or CoW MCP depending on the route and execution model.

**OKX OnchainOS token, wallet, DEX, and smart-money workflows:** Start with OKX OnchainOS Skills/MCP when the agent needs OKX-maintained token discovery, wallet portfolio reads, DEX swaps, security scans, smart-money signals, DeFi actions, or transaction simulation/broadcasting across 20+ chains.

**Node, RPC, endpoint, and infrastructure operations:** Start with Alchemy MCP Server, Chainstack MCP Server, Quicknode MCP, or GetBlock MCP Server.

**Solana production APIs and execution:** Start with Helius MCP Server, Solana MCP by Vybe, or TradeRouter MCP.

**TON address, transaction, jetton, and trend analysis:** Start with TON Blockchain MCP.

**TON wallet operations and agentic TON apps:** Start with TON AgentKit MCP when the agent needs official `@ton/mcp` wallet operations, transfers, swaps, NFTs, DNS, or local/HTTP/serverless TON agent setup.

**Tari wallet, node, and local AI integration:** Start with Tari MCP Servers when the agent needs local Minotari wallet balances, transaction history, address info, transfer preparation, burn transactions, coin splits, node status, peers, blocks, mempool, or sync status.

**Polkadot, Kusama, and system parachain data:** Start with Polkadot MCP.

**Starknet RPC, state, and trace reads:** Start with Starknet MCP Server.

**Hedera build-only transactions and mirror-node reads:** Start with Hedera MCP.

**Wallet-backed payments, signing, swaps, x402, ramps, or custody:** Start with Phantom MCP Server, Base MCP, Coinbase Agentic Wallet MCP, Cobo Agentic Wallet MCP, MoonPay CLI MCP, Polygon LLM Wallet MCP Server, Tether WDK MCP Toolkit, Coinbase AgentKit, GOAT SDK, Adamik MCP Server, BitGo MCP Server, or Fireblocks MCP Server.

**Crypto commerce, gift cards, eSIMs, and top-ups:** Start with Bitrefill eCommerce MCP or CryptoRefills MCP depending on the merchant catalog, hosted endpoint, and checkout model.

**Trading, exchange APIs, brokerage, bots, quant strategies, or prediction markets:** Start with Gate for AI, Gate MCP Server, Bitget Agent Hub, Kraken CLI, Bybit MCP Server, CCXT MCP Server, Hummingbot MCP Server, Trade It, QuantConnect MCP Server, or PMXT.

**Bitcoin, Stacks, sBTC, x402, and Lightning wallet workflows:** Start with AIBTC MCP Server, Alby Bitcoin Payments MCP Server, or LNbits MCP Server depending on the wallet stack.

**Token, wallet, phishing, approval, and transaction risk:** Start with GoPlus MCP Server or Phalcon MCP Server.

## Best By Use Case

Use this map when you are comparing crypto MCP servers by the job an agent
needs to do. Hive stays first for broad production crypto intelligence; the
narrower rows point to focused provider MCPs when a task needs a specific data
source, chain, wallet, venue, or risk model.

**Broad crypto intelligence:** Start with Hive Intelligence. Compare Universal Crypto MCP and Heurist Mesh MCP Server only when the agent needs a different broad architecture.

**Public prices, charts, feeds, and market metadata:** Start with CoinGecko MCP Server, CoinMarketCap MCP, CoinPaprika MCP, or Pyth MCP Server. Compare Messari MCP Server, Santiment MCP Connector, CoinStats MCP Server, Crypto.com Market Data MCP, Massive.com MCP Server, Lambda Finance MCP, AkTools MCP Server, Cryptohopper MCP, altFINS MCP Server, and TradingView MCP Server.

**Technical analysis, screening, sentiment, and backtesting:** Start with TradingView MCP Server when the agent needs analysis-only TradingView-style research. Compare aTars MCP for a registry-backed remote signal and sentiment feed, or altFINS MCP Server when an API-key-backed crypto analytics platform is preferable.

**Real-time social intelligence and attention signals:** Start with LunarCrush MCP Server when the agent needs hosted or stdio access to LunarCrush social intelligence, creator/post context, social-market trend discovery, or API-backed attention signals. Compare Santiment MCP Connector when the task needs Sanbase metrics plus on-chain/social timeseries.

**Trading-agent memory and audit trails:** Start with TradeMemory Protocol when a crypto-capable trading agent needs pre-trade memory, risk gates, strategy reflection, or tamper-evident decision exports without handing over exchange credentials.

**AI-powered crypto research, news, signals, and timeseries:** Start with Messari MCP Server when the agent needs hosted OAuth access to Messari AI, deep research, market data, on-chain metrics, token unlocks, fundraising, news, social mindshare, sentiment, or direct timeseries data.

**On-chain, social sentiment, and narrative validation:** Start with Santiment MCP Connector when the agent needs OAuth-backed Santiment metrics, exchange-flow context, social volume, weighted sentiment, trending stories, analyst insights, or token screening.

**Token discovery, wallet PnL, and portfolio intelligence:** Start with Birdeye MCP Server, Zerion API MCP, Octav API MCP, or CoinStats MCP Server. Compare Nansen MCP, Moralis Cortex MCP, and Chainbase MCP.

**DeFi TVL, protocol, chain, and yield analytics:** Start with DeFiLlama MCP when the agent needs public DeFiLlama protocol TVL, chain TVL, token prices, pool, or yield data. Compare Token Terminal for financial fundamentals and Dune for SQL-backed custom analysis.

**Tokenized RWA and treasury intelligence:** Start with RWA Pipe MCP when the agent needs tokenized treasury, private-credit, commodity, equity, or real-estate tokens, wallet RWA holdings, whale flows, contract-control profiles, or issuer/category comparisons. Treat contract scans and admin-token workflows as higher risk than read-only market lookups.

**Verifiable economic data and RWA streams:** Start with TRUF.NETWORK MCP Server when the agent needs natural-language-to-SQL access to verified RWA data, event-driven market data, on-chain price indexes, or TRUF.NETWORK data streams. Treat local node/database access as infrastructure-sensitive.

**DEX token, pool, and trading activity:** Start with DexPaprika MCP when the agent needs token details, liquidity pools, DEXes, pool OHLCV, recent transactions, or cross-chain DEX analytics. Compare Birdeye MCP Server for broader token discovery and safety signals.

**Swap, bridge, zap, and route construction:** Start with DZap MCP Server or LI.FI MCP Server when the agent needs cross-chain routes, token discovery, balances, allowances, or execution-ready transaction data. Compare 1inch Business MCP for 1inch APIs and CoW MCP for CoW Protocol order flows.

**OKX OnchainOS token, wallet, DEX, and smart-money workflows:** Start with OKX OnchainOS Skills/MCP when the agent needs OKX-maintained wallet lifecycle, token discovery, market data, DEX swaps, transaction simulation/broadcasting, smart-money signals, security scans, DeFi product actions, or agent payments across 20+ chains. Treat OKX API credentials, swaps, broadcasts, deposits, withdrawals, and payment actions as high-risk.

**On-chain analytics, SQL, and financial metrics:** Start with Dune MCP, Token Terminal MCP, or CryptoQuant MCP. Compare Glassnode MCP Server, Allium MCP, and Bitquery MCP Server.

**RPC, nodes, endpoints, and infrastructure operations:** Start with Alchemy MCP Server or Chainstack MCP Server. Compare Quicknode MCP, GetBlock MCP Server, and Tatum Blockchain MCP.

**Solana data, development, and execution:** Start with Helius MCP Server or Solana MCP by Vybe. Compare Solana MCP Official and TradeRouter MCP. Treat swaps, order tools, and private-key flows as high-risk.

**TON address, transaction, and jetton analytics:** Start with TON Blockchain MCP when the agent needs TON address analysis, transaction details, hot trends, trading-pattern analysis, TON prices, or jetton prices through TON API. Treat its beta warning and financial-advice caveat seriously.

**TON wallet operations and agentic TON apps:** Start with TON AgentKit MCP when the agent needs official `@ton/mcp` wallet operations, token transfers, swaps, NFT workflows, DNS, jettons, pools, transaction lookup, or stdio/HTTP/serverless TON agent setup. Treat wallet creation, recovery phrases, transfers, swaps, deployments, and account credentials as high-risk.

**Tari wallet and node workflows:** Start with Tari MCP Servers when the agent needs local Minotari wallet balances, transaction history, address info, transfers, burn transactions, coin splits, node/network information, blocks, mempool, peers, or sync status. Use read-only mode by default; control operations require explicit enablement, confirmation, and audit logging.

**Wallets, signing, payments, swaps, ramps, and custody:** Start with Phantom MCP Server, Base MCP, Coinbase Agentic Wallet MCP, Cobo Agentic Wallet MCP, MoonPay CLI MCP, Polygon LLM Wallet MCP Server, or Tether WDK MCP Toolkit. Compare Coinbase AgentKit, GOAT SDK, Adamik MCP Server, BitGo MCP Server, VaultPilot MCP, and Fireblocks MCP Server. Require explicit user confirmation for write, payment, ramp, trading, or custody actions.

**Crypto commerce, gift cards, mobile top-ups, and eSIMs:** Start with Bitrefill eCommerce MCP when the agent needs Bitrefill product search, details, hosted OAuth, or purchase workflows. Compare CryptoRefills MCP when the task needs CryptoRefills catalog, pricing, payments, and agentic commerce flows. Treat checkout, invoice, payment, account, and order actions as high-risk.

**Trading, exchange APIs, bots, and prediction markets:** Start with Gate MCP Server, Bitget Agent Hub, or Kraken CLI. Compare Bybit MCP Server, CCXT MCP Server, Hummingbot MCP Server, Trade It, and PMXT. Separate read-only data from account, order, bot deployment, brokerage, and prediction-market execution.

**Quant strategy research, backtesting, optimization, and live deployment:** Start with QuantConnect MCP Server when the agent needs to create or update QuantConnect projects, run compiles, backtests, optimizations, and live algorithm workflows, including crypto-capable strategies. Treat broker authorization, live deployment, liquidation, and project writes as high-risk.

**Pay-per-call agent data and x402-funded research:** Start with BlockRun MCP when the agent needs crypto prices, prediction-market data, DEX data, X/Twitter intelligence, web research, or model calls behind one funded wallet.

**x402 paid API discovery and routing:** Start with x402 MCP when the agent needs automatic x402 payment handling across CDP Bazaar endpoints. Compare BlockRun MCP or CoinMarketCap MCP when the task needs crypto-specific data rather than a general paid-API router. Use a fresh funded wallet, `MAX_PRICE_USD`, and explicit payment approval.

**x402 settlement verification and publisher manifests:** Start with TensorFeed x402 Base MCP when the agent needs to independently verify Base USDC payment receipts, inspect `/.well-known/x402` manifests, or check x402 publisher health without signing or broadcasting transactions.

**Token research reports and source collection:** Start with Hive Intelligence when the agent needs managed provider-backed token diligence. Compare Web3 Research MCP when the task is a local research dossier with a plan, web/news search, saved resources, CoinGecko data, DeFiLlama protocol data, and progress tracking.

**Token, wallet, approval, phishing, and transaction risk:** Start with GoPlus MCP Server or Phalcon MCP Server. Compare Tenderly MCP Server, VaultPilot MCP, and Philidor DeFi Vault Risk Analytics before signing, approving, swapping, bridging, staking, or recommending risky assets.

**Smart contracts, app development, and chain docs:** Start with OpenZeppelin MCP Servers or Tenderly MCP Server. Compare thirdweb MCP Server, Aptos MCP, Avalanche MCP Server, and LayerZero Docs MCP.

**Starknet RPC and trace inspection:** Start with Starknet MCP Server when the agent needs Starknet JSON-RPC reads, blocks, transactions, state, events, traces, fee estimates, or network switching against a user-provided Starknet RPC endpoint.

## Start Here

If you are building an AI agent that needs crypto intelligence, start with the smallest surface that can answer the task safely.

**Production crypto intelligence:** Start with Hive Intelligence for broad hosted coverage plus local stdio, SDK, and agent skills.

**Official crypto market data:** Start with CoinGecko MCP Server for public keyless access, authenticated Pro access, local npm setup, prices, historical data, DEX pools, NFTs, and metadata.

**Market cap, narratives, and x402:** Start with CoinMarketCap MCP when the agent needs CMC quotes, technical analysis, global metrics, crypto news, semantic search, or pay-per-call x402 access.

**CoinPaprika market data:** Start with CoinPaprika MCP when the agent needs source-specific coin, ticker, exchange, OHLCV, contract, search, or historical market-data workflows through CoinPaprika's hosted or local MCP.

**DexPaprika DEX analytics:** Start with DexPaprika MCP when the agent needs no-key token, pool, DEX, OHLCV, transaction, or cross-chain DEX analytics across supported networks.

**CoinStats account and market data:** Start with CoinStats MCP Server when the agent needs OAuth-backed CoinStats account data, portfolio coins, P/L, wallet balances, transactions, prices, charts, exchange comparisons, or crypto news; use the npm stdio fallback only for developer-key/headless integrations.

**Wallet-funded live data and research:** Start with BlockRun MCP when the agent needs pay-per-call crypto, prediction-market, DEX, X/Twitter, web research, or model access without juggling multiple API subscriptions.

**x402 API payment router:** Start with x402 MCP when the agent needs to discover CDP Bazaar x402 endpoints and automatically handle USDC micropayments from a controlled Base wallet. Keep `X402_PRIVATE_KEY` on a burner wallet and set a strict per-call cap.

**Keyless exchange market data:** Start with Crypto.com Market Data MCP when the agent needs free live prices, market caps, trading volumes, and market trend data without managing API keys.

**Crypto screeners and technical analysis:** Start with altFINS MCP Server when the agent needs crypto screeners, technical indicators, curated technical analysis, signal feeds, news, calendar events, OHLCV, or portfolio analytics from an API-key-backed analytics platform.

**TradingView-style analysis and backtesting:** Start with TradingView MCP Server when the agent needs multi-exchange crypto screening, technical indicators, sentiment/news confluence, candlestick patterns, or strategy backtests without order execution.

**Registry-backed signal and sentiment feed:** Start with aTars MCP when the agent needs a free remote MCP for technical-indicator-based crypto signals, daily sentiment scoring, and rolling sentiment trends. Treat outputs as research signals, not financial advice or trade execution.

**LunarCrush real-time social intelligence:** Start with LunarCrush MCP Server when the agent needs API-key-backed access to LunarCrush's remote MCP for social intelligence and community attention signals, or the `@lunarcrush/mcp-server` stdio proxy for desktop clients.

**Oracle-grade market data:** Start with Pyth MCP Server when the agent needs Pyth feed discovery, real-time prices, historical prices, or chart-ready candles across crypto, FX, equities, metals, rates, commodities, and funding rates.

**Cross-asset financial market data:** Start with Massive.com MCP Server when the agent needs crypto, stock, options, forex, futures, news, reference data, or technical-analysis functions through a single API-key-backed search/call/query MCP. Use Lambda Finance MCP when the task is hosted financial research that needs crypto derivatives, funding/open-interest context, exchange flows, whale transfers, or wallet tracking alongside broader market data.

**Messari crypto intelligence and timeseries:** Start with Messari MCP Server when the agent needs hosted OAuth access to Messari AI, research reports, news, token unlocks, fundraising, social signals, market data, on-chain metrics, or direct timeseries queries.

**Santiment social and on-chain intelligence:** Start with Santiment MCP Connector when the agent needs hosted OAuth access to Santiment metrics, asset screening, analyst insights, trending stories, combined social trends, or sentiment-backed token research.

**Tokenized real-world assets:** Start with RWA Pipe MCP when the agent needs tokenized treasury, private-credit, commodity, equity, real-estate, or stablecoin data with TVL, APY, issuer, chain, holder, whale-flow, risk-signal, and contract-control context.

**Verifiable RWA and economic data streams:** Start with TRUF.NETWORK MCP Server when the agent needs a local MCP for natural-language SQL over verified RWA data, market-moving event data, on-chain price data points, or TRUF.NETWORK node-backed streams.

**DeFi swap, bridge, and zap routing:** Start with DZap MCP Server when the agent needs a hosted public MCP for swaps, bridges, zaps, token and pool data, wallet balances, price/sentiment/news tools, or DZap documentation search. Treat calldata, execution links, and transaction preparation as high-risk.

**Exchange order books and candles:** Start with Cryptohopper MCP when the agent needs live market data, order-book depth, and candle analysis through a remote MCP endpoint.

**Algorithmic trading research and backtesting:** Start with QuantConnect MCP Server when the agent needs QuantConnect project management, docs/API search, code edits, compiles, backtests, optimization, or live algorithm deployment for crypto-capable quantitative strategies.

**Token discovery and on-chain market analytics:** Start with Birdeye MCP Server when the agent needs trending tokens, new launches, top movers, hot pools, DEX liquidity data, token metadata, safety signals, OHLCV, wallet net worth, or wallet PnL across supported networks.

**Official Blockchain API access:** Start with Alchemy MCP Server for hosted OAuth access to token prices, multichain balances, transfers, NFTs, smart accounts, and swaps.

**Blockchain node and endpoint operations:** Start with Chainstack MCP or Quicknode MCP when the agent needs remote node deployment, endpoint management, platform status, docs search, or live RPC workflows.

**Open-source RPC-backed chain reads:** Start with GetBlock MCP Server when the agent needs Ethereum or Solana balances, transactions, latest blocks, gas prices, account information, or JSON-RPC access through GetBlock credentials.

**Self-hosted Ethereum node intelligence:** Start with Erigon MCP Server when the agent needs read-only Ethereum node data, logs, metrics, traces, resources, or prompts from a local Erigon node.

**Multi-network RPC access:** Start with dRPC Agent Skills when the agent needs RPC access across many networks through a single provider-backed interface.

**Multi-package Blockchain API suite:** Start with Crypto APIs MCP Servers for hosted HTTP or package-level stdio access to balances, blocks, transactions, fees, events, contracts, market data, HD wallets, signing, simulation, and transaction preparation.

**Multi-chain Blockchain API coverage:** Start with Tatum Blockchain MCP when the agent needs one npm-installed MCP for balances, transactions, token metadata, fee estimation, address activity, exchange rates, and Tatum API access across many networks.

**Blockchain trading datasets:** Start with Bitquery MCP Server when the agent needs hosted access to Bitquery's Blockchain, DEX, token, and trading datasets.

**Enterprise on-chain data and SQL:** Start with Allium MCP when the agent needs hosted access to Explorer SQL, saved queries, schemas, docs, and real-time Blockchain data across many chains.

**Web3 account, token, and NFT data:** Start with Chainbase MCP when the agent needs HTTP access to token balances, holders, metadata, NFT ownership, transaction history, block details, and on-chain analytics.

**Natural-language Web3 data layer:** Start with Moralis Cortex MCP when the agent needs Moralis-grounded wallet activity, token metrics, NFT ownership, transfers, transactions, dapp usage, or structured on-chain answers through a hosted Cortex API or self-hosted npm MCP.

**Wallet portfolios and DeFi positions:** Start with Zerion API MCP when the agent needs normalized wallet balances, labeled transaction history, DeFi positions, NFT holdings, collection metadata, or PnL across EVM chains and Solana. Use Octav API MCP when the agent needs portfolio, NAV, transaction history, historical snapshots, airdrop, or Polymarket position views across several wallets.

**NFT marketplace data and actions:** Start with OpenSea MCP when the agent needs OpenSea collection stats, NFT metadata, ownership, listings, offers, drops, portfolio data, token swaps, or ready-to-sign marketplace actions across supported chains.

**Smart-money and wallet labels:** Start with Nansen MCP when the agent needs institutional on-chain intelligence, smart-money labels, token flows, wallet PnL, or multi-chain research workflows.

**Institutional on-chain metrics:** Start with Glassnode MCP Server when the agent needs asset and metric discovery, metric metadata, single or bulk Glassnode metric retrieval, market intelligence, or 30-day public-access analytics with optional API-key authentication.

**CryptoQuant on-chain signals:** Start with CryptoQuant MCP when the agent needs MVRV, SOPR, exchange flows, funding rates, whale activity, metric descriptions, endpoint discovery, or API-key-backed CryptoQuant data.

**DeFiLlama protocol and yield data:** Start with DeFiLlama MCP when the agent needs public protocol TVL, chain TVL, token prices, liquidity pools, or yield analytics from DeFiLlama. Treat it as a community wrapper around public DeFiLlama APIs.

**On-chain analytics and dashboards:** Start with Dune MCP when the agent needs DuneSQL query creation, execution, results, visualizations, dashboards, and dataset-aware on-chain research.

**On-chain fundamentals and financial metrics:** Start with Token Terminal MCP when the agent needs project, product, chain, sector, market, methodology, or financial-metric data through a hosted OAuth remote MCP.

**The Graph token and subgraph data:** Start with The Graph Token API MCP or Subgraph MCP Server when the agent needs token metadata, balances, transfers, holder statistics, subgraph discovery, schemas, or GraphQL query execution.

**Direct EVM chain actions:** Start with EVM MCP Server for contract calls, ENS, transfers, and multi-network support.

**Secure smart-contract templates:** Start with OpenZeppelin MCP Servers when the agent needs production-oriented Solidity, Cairo, Stylus, Stellar, confidential contract, or Uniswap Hooks templates grounded in OpenZeppelin standards.

**EVM simulation and debugging:** Start with Tenderly MCP Server when the agent needs transaction simulation, tracing, contract verification, testnets, or Tenderly developer workflows.

**Multi-chain app development:** Start with thirdweb MCP Server for contract analysis, on-chain data, wallets, storage, and agent execution across thirdweb services.

**On-chain wallets for agents:** Start with Coinbase AgentKit when the agent needs wallet-backed payments, testnet funding, and on-chain actions through Coinbase Developer Platform.

**Multi-chain account, transfer, and staking operations:** Start with Adamik MCP Server when the agent needs API-key-backed balances, transaction history, native or token transfers, staking, unstaking, rewards, swaps, or bridges across many chains. Treat transfers, staking, swaps, and bridges as high-risk actions.

**Consumer wallet signing and swaps:** Start with Phantom MCP Server when the agent needs Phantom wallet authentication, addresses, balances, Solana/EVM signing, token transfers, swaps, payments, or Hyperliquid perps access through a local stdio MCP.

**Institutional custody integration docs:** Start with BitGo MCP Server when the agent needs docs-grounded help for BitGo wallets, policies, webhooks, staking, trading, or API integration. It is a documentation MCP, not a custody-execution MCP.

**Enterprise custody operations:** Start with Fireblocks MCP Server when the agent needs vault accounts, assets, transaction history, policies, exchange accounts, external wallets, or internal workspace-user data from Fireblocks.

**Base Account and x402 actions:** Start with Base MCP when the agent needs approved Base Account wallet actions, swaps, signatures, contract calls, or x402 payments through a remote MCP.

**Cobo MPC agent wallets and Pact controls:** Start with Cobo Agentic Wallet MCP when the agent needs a stdio MCP for MPC-backed wallets, owner-approved Pacts, balances, addresses, transfers, smart-contract calls, message signing, transaction records, pending approvals, and audit logs. Treat invitation onboarding, API keys, Pact approval, transfers, contract calls, signing, recovery, and mainnet activity as high-risk.

**MoonPay agent wallets, ramps, and swaps:** Start with MoonPay CLI MCP when the agent needs MoonPay's local MCP surface for non-custodial wallets, balances, swaps, bridges, transfers, fiat on/off ramps, token search, market data, or Open Wallet Standard-aligned agent workflows. Treat login, KYC, local wallet storage, swaps, bridges, transfers, DCA, limit orders, and fiat transactions as high-risk.

**Polygon x402 wallet and paid-API flows:** Start with Polygon LLM Wallet MCP Server when the agent needs encrypted Polygon wallets, spending limits, x402 buyer/seller tools, payment history, or dynamic paid-API registration. It is documented by Polygon's Agentic Payments docs; prefer Polygon Amoy/testnet and keep mainnet usage small and explicitly approved.

**Crypto commerce and gift-card purchases:** Start with Bitrefill eCommerce MCP for hosted OAuth-backed product search, product details, and purchase workflows across Bitrefill's crypto-commerce catalog. Use CryptoRefills MCP when the agent needs CryptoRefills gift cards, mobile top-ups, eSIMs, catalog, pricing, or checkout-preparation workflows. Treat checkout, invoices, payments, account data, and order placement as high-risk.

**USDC, CCTP, and Circle app codegen:** Start with Circle MCP Server when the agent needs Circle Wallets, Contracts, Cross-Chain Transfer Protocol, or Gateway integration guidance inside an MCP-compatible IDE.

**Subgraph intelligence:** Start with Subgraph MCP Server when the agent needs to discover schemas and query The Graph Network subgraphs.

**Official Solana developer help:** Start with Solana MCP Official for documentation, expert help, and developer workflows.

**Production Solana APIs:** Start with Helius MCP Server or Solana MCP by Vybe when the agent needs Solana RPC, DAS, transfers, webhooks, streaming, wallet analysis, priority fees, live API calls, schemas, and OAuth-backed remote access.

**Solana swap and order execution:** Start with TradeRouter MCP when the agent needs Solana swaps, limit orders, trailing orders, TWAP, DCA, combo orders, holdings, or token market-cap checks through a local non-custodial MCP. Treat private-key, signing, and order tools as high-risk actions.

**TON Blockchain analysis:** Start with TON Blockchain MCP when the agent needs TON address analysis, transaction details, hot trends, trading-pattern analysis, TON prices, or jetton prices through a local Python MCP using TON API credentials.

**TON wallet operations and app agents:** Start with TON AgentKit MCP when the agent needs official `@ton/mcp` setup for wallet operations, transfers, swaps, NFTs, DNS, jettons, pools, transaction lookup, or stdio/HTTP/serverless deployment. Treat wallet creation, recovery phrases, transfers, swaps, deployments, and credentials as high-risk.

**Tari wallet and node workflows:** Start with Tari MCP Servers when the agent needs local Minotari wallet balance/history reads, address info, transfers, burn transactions, coin splits, node status, peers, blocks, mempool, or sync status. Keep read-only mode as the default and treat control mode as high-risk.

**BNB Chain development:** Start with BNBChain MCP for BSC, opBNB, Greenfield, token, contract, wallet, and ERC-8004 agent identity workflows.

**Aptos app development:** Start with Aptos MCP when the agent needs Aptos APIs, Move app scaffolding, prompts, resources, Cursor or Claude Code setup, and Geomi-backed app-building workflows.

**Avalanche builder workflows:** Start with Avalanche MCP Server when the agent needs Avalanche docs, code search, RPC lookup, CLI guidance, ACPs, or public network data through a hosted read-only endpoint.

**Rootstock wallet, contract, and attestation workflows:** Start with Rootstock MCP Server when the agent needs RBTC balances, ERC-20 transfers, Rootstock contract deployment, verification, reads, transaction history, or Rootstock Attestation Service workflows. Treat wallet import, transfers, deployment, and attestations as high-risk actions.

**Starknet RPC and traces:** Start with Starknet MCP Server when the agent needs Starknet blocks, transactions, state, storage, classes, events, traces, simulation, fee estimates, or node info through the Starknet JSON-RPC API. Treat private provider RPC URLs as secrets.

**Cross-chain bridge intelligence:** Start with Across MCP Server when the agent needs Across docs, supported chains, API references, SDK examples, or live bridge-fee quotes through a hosted MCP endpoint.

**Cross-chain bridge execution:** Start with Allbridge MCP when the agent needs to plan, build, locally sign, broadcast, and track stablecoin bridge transfers across several chain families with explicit signer handoff.

**Omnichain messaging docs:** Start with LayerZero Docs MCP when the agent needs current LayerZero documentation, OApp, OFT, DVN, endpoint, or cross-chain messaging guidance through a hosted Streamable HTTP MCP.

**Cross-chain swap routing:** Start with LI.FI MCP Server when the agent needs read-only quotes, routes, token and chain discovery, balances, allowances, gas suggestions, or transfer status without signing or broadcasting.

**Sei chain actions:** Start with Sei MCP Server when the agent needs Sei account, token, NFT, block, transaction, or smart-contract operations with explicit wallet-safety controls.

**Sui chain operations:** Start with Sui MCP Server when the agent needs Sui wallets, coin/object/transaction data, Move introspection, staking, SuiNS, Cetus/DeepBook data, or devnet/testnet/mainnet switching. Treat wallet import, transfers, staking, and Move calls as high-risk actions.

**Polkadot ecosystem operations:** Start with Polkadot MCP when the agent needs live Polkadot, Kusama, Westend, Paseo, or system-parachain data, account diagnostics, governance, fellowship, staking, or optional signer-backed transactions.

**Hedera build-only workflows:** Start with Hedera MCP when the agent needs Hedera Mirror Node reads or unsigned frozen transactions across Account, HTS, HCS, EVM, File, Schedule, Network, and analytics tools without giving the MCP server private keys.

**Broker-backed trading:** Start with Alpaca MCP Server for crypto trading, portfolio management, and market data.

**Hyperliquid perps trading:** Start with Hyperliquid MCP Server by Caio when the agent needs Hyperliquid account, order, leverage, margin, WebSocket, or execution workflows; use the lighter Hyperliquid SDK MCP only for read-only mids, candles, and order books.

**Exchange API agents:** Start with Gate MCP Server, Bitget Agent Hub, Kraken CLI, Bybit MCP Server, or Crypto.com CDCX CLI when the agent needs exchange market data, REST/WebSocket workflows, trading, account, paper-trading, DEX, or portfolio operations through MCP-compatible tooling.

**OKX on-chain app agents:** Start with OKX OnchainOS Skills/MCP when the agent needs an OKX-maintained skill and MCP surface for token research, wallet analysis, DEX swaps, smart-money signals, security checks, DeFi product actions, x402/payment workflows, or transaction simulation and broadcasting. Treat built-in sandbox keys as testing-only, and keep production API credentials, swaps, broadcasts, deposits, withdrawals, and payments under explicit user control.

**Automated trading bots and executors:** Start with Hummingbot MCP Server when the agent needs to connect to a Hummingbot API, configure exchange connectors, inspect portfolio state, manage controllers, deploy or monitor bots, create executors, explore DEX pools, or query GeckoTerminal data. Treat connector credentials, bot deployment, executor creation, leverage, private keys, and live orders as high-risk.

**DEX aggregation and 1inch APIs:** Start with 1inch Business MCP when the agent needs 1inch documentation, examples, portfolio or balance data, orderbook access, spot prices, classic swaps, Fusion intent swaps, cross-chain swaps, or authenticated 1inch Business API calls.

**CoW Protocol swaps:** Start with CoW MCP when the agent needs CoW quotes, token lookup, wallet trade history, externally signed orders, or signed cancellations without giving the MCP server custody of private keys.

**Cross-asset brokerage trading:** Start with Trade It when the agent needs remote MCP access to draft crypto, stock, or options trades across linked brokerages, including Coinbase and Kraken crypto accounts, with OAuth and explicit execution.

**Prediction-market data and trading:** Start with PMXT when the agent needs a hosted or local MCP for prediction-market search, events, order books, price history, cross-venue comparison, or trading across Polymarket, Kalshi, Limitless, and related venues. Treat order creation, cancellation, private keys, and exchange credentials as high-risk actions.

**Injective spot and perpetuals:** Start with Injective MCP Server when the agent needs Injective queries, spot transfers, bridge operations, raw EVM transactions, or perpetual futures trading.

**Concentrated liquidity management:** Start with Arcadia Finance MCP Server when the agent needs Uniswap, Aerodrome, or Velodrome LP strategy data, rebalancing guidance, lending pools, leverage-aware account reads, or unsigned transaction building on Base, Unichain, and Optimism.

**Block explorer data:** Start with Blockscout MCP Server for balances, tokens, NFTs, contracts, and explorer data.

**Bitcoin hosted data:** Start with Maestro MCP Server for Bitcoin blocks, transactions, mempool, wallet, node RPC, and hosted Streamable HTTP endpoints.

**Bitcoin-native agent wallets:** Start with AIBTC MCP Server when the agent needs Bitcoin L1, Stacks, sBTC, NFTs, DeFi yield, or x402 payments through a local wallet-aware MCP. Treat wallet creation, mnemonic export, transfers, DeFi, and x402 payment tools as high-risk actions.

**Bitcoin agent payments:** Start with Alby Bitcoin Payments MCP Server, LNbits MCP Server, or Lightning Wallet MCP when the agent needs a Bitcoin Lightning wallet, Nostr Wallet Connect, LNbits instance access, invoices, LNURL, L402, or Lightning-native paid tools.

**DeFi execution and risk:** Start with Haiku DeFi MCP for swaps, lending, bridges, and yield execution, VaultPilot MCP when hardware-wallet verification is the central constraint, and Philidor DeFi Vault Risk Analytics when the agent needs vault-level risk due diligence.

**Token, NFT, phishing, and approval risk screening:** Start with GoPlus MCP Server when the agent needs token security, malicious-address checks, phishing URL checks, NFT contract risk, approval risk, Solana token security, or Sui token security using GoPlus credentials.

**Farcaster social graph and mini apps:** Start with Neynar MCP when the agent needs Farcaster users, casts, feeds, social graphs, Mini Apps, notifications, signers, or on-chain/social intersections through Neynar's hosted docs MCP.

**Embedded wallet infrastructure:** Start with Privy Docs MCP for Privy integration guidance, Privy MCP Server for wallet operations, MetaMask Embedded Wallets MCP for Web3Auth/MetaMask Embedded Wallets docs, and PayRam MCP for self-hosted crypto payments.

## Maintainer Picks

Use this quick routing guide when the category list is too broad. Canonical links and full descriptions are in the sections below.

**Broad crypto intelligence across several data sources:** Hive Intelligence.

**Public crypto prices, market charts, and DEX pools:** CoinGecko MCP Server.

**Market cap, narratives, news, and x402 pay-per-call data:** CoinMarketCap MCP.

**CoinPaprika prices, tickers, exchanges, contracts, OHLCV, and search:** CoinPaprika MCP.

**DexPaprika token, pool, DEX, OHLCV, and transaction analytics:** DexPaprika MCP.

**CoinStats OAuth portfolios, wallets, prices, exchanges, and news:** CoinStats MCP Server.

**Wallet-funded live data, research, prediction markets, and model calls:** BlockRun MCP.

**x402 paid API discovery and micropayments:** x402 MCP.

**x402 receipt and settlement verification:** TensorFeed x402 Base MCP.

**Local token research plans and saved resources:** Web3 Research MCP.

**Keyless Crypto.com prices, market caps, volumes, and trends:** Crypto.com Market Data MCP.

**Crypto screeners, technical indicators, signals, news, and portfolio analytics:** altFINS MCP Server.

**TradingView-style screeners, technicals, sentiment, and backtesting:** TradingView MCP Server.

**Real-time crypto social intelligence and attention signals:** LunarCrush MCP Server.

**Remote crypto signals and sentiment scoring:** aTars MCP.

**Trading-agent memory and audit trail:** TradeMemory Protocol.

**Pyth market feeds, historical prices, and candles:** Pyth MCP Server.

**Cross-asset market data, crypto aggregates, derivatives, and SQL-style analysis:** Massive.com MCP Server or Lambda Finance MCP.

**Messari AI research, news, signals, token unlocks, and timeseries:** Messari MCP Server.

**A-share, Hong Kong, US stock, and crypto data:** AkTools MCP Server.

**Tokenized real-world assets, treasury tokens, and RWA risk signals:** RWA Pipe MCP.

**DeFi swaps, bridges, zaps, and execution-ready route planning:** DZap MCP Server or LI.FI MCP Server.

**Token discovery, DEX analytics, wallet PnL, and safety signals:** Birdeye MCP Server.

**Centralized exchange APIs and trading:** Gate for AI, Gate MCP Server, Bitget Agent Hub, Kraken CLI, Bybit MCP Server, CCXT MCP Server, Crypto.com CDCX CLI, Hummingbot MCP Server, or OKX Agent Trade Kit.

**OKX on-chain token, wallet, DEX, smart-money, and DeFi workflows:** OKX OnchainOS Skills/MCP.

**Quant strategy development, backtesting, and live deployment:** QuantConnect MCP Server.

**Hyperliquid perps account, order, leverage, margin, and WebSocket workflows:** Hyperliquid MCP Server by Caio.

**DEX aggregation, 1inch APIs, and swap workflows:** 1inch Business MCP.

**CoW Protocol quote, order, and cancellation flows:** CoW MCP.

**Brokerage-backed crypto, stock, and options trading:** Trade It.

**Prediction-market search, pricing, routing, and trading:** PMXT.

**Node, RPC, endpoint, or infrastructure operations:** Alchemy MCP Server, Chainstack MCP Server, Quicknode MCP, or GetBlock MCP Server.

**Self-hosted Ethereum node analysis:** Erigon MCP Server.

**Smart-money labels and institutional on-chain research:** Nansen MCP.

**On-chain metrics, asset discovery, and market intelligence:** Glassnode MCP Server.

**CryptoQuant metrics, endpoint discovery, and whale or leverage signals:** CryptoQuant MCP.

**DeFi TVL, chain, protocol, pool, and yield snapshots:** DeFiLlama MCP.

**Enterprise on-chain SQL and real-time data:** Allium MCP.

**Token, wallet, NFT, and block-level API data:** Chainbase MCP.

**Natural-language Moralis Web3 data:** Moralis Cortex MCP.

**Wallet portfolios, DeFi positions, historical snapshots, NFTs, and PnL:** Zerion API MCP or Octav API MCP.

**Broad multi-chain API access and fee estimation:** Tatum Blockchain MCP.

**NFT marketplace analytics and actions:** OpenSea MCP.

**On-chain SQL analytics and dashboards:** Dune MCP.

**On-chain fundamentals and financial metrics:** Token Terminal MCP.

**The Graph token and subgraph workflows:** The Graph Token API MCP or Subgraph MCP Server.

**Secure smart-contract generation:** OpenZeppelin MCP Servers.

**Solana production data and developer help:** Helius MCP Server, Solana MCP by Vybe, or Solana MCP Official.

**Solana swaps and advanced order execution:** TradeRouter MCP.

**TON address, transaction, jetton, and trend analysis:** TON Blockchain MCP.

**TON wallet operations and agentic apps:** TON AgentKit MCP.

**Tari wallet and node workflows:** Tari MCP Servers.

**Aptos APIs, Move apps, and Geomi workflows:** Aptos MCP.

**Avalanche docs, RPC, CLI, and ACP lookup:** Avalanche MCP Server.

**Rootstock wallets, contracts, transfers, and attestations:** Rootstock MCP Server.

**Starknet JSON-RPC reads, state, and traces:** Starknet MCP Server.

**Cross-chain bridge docs, fees, SDK examples, and execution:** Across MCP Server or Allbridge MCP.

**LayerZero omnichain messaging docs:** LayerZero Docs MCP.

**Sui wallets, Move contracts, staking, and DeFi data:** Sui MCP Server.

**Polkadot, Kusama, and system parachain workflows:** Polkadot MCP.

**Hedera Mirror Node reads and unsigned transaction building:** Hedera MCP.

**Cross-chain swaps, routes, and status tracking:** LI.FI MCP Server.

**EVM transaction simulation and debugging:** Tenderly MCP Server.

**Bitcoin data or Lightning payments:** Maestro MCP Server for Bitcoin data, and Alby Bitcoin Payments MCP Server, LNbits MCP Server, or Lightning Wallet MCP for Lightning payments.

**Bitcoin L1, Stacks, sBTC, NFTs, DeFi yield, and x402 wallet workflows:** AIBTC MCP Server.

**Wallet-backed on-chain actions and agent payments:** Phantom MCP Server, Base MCP, Coinbase Agentic Wallet MCP, Cobo Agentic Wallet MCP, MoonPay CLI MCP, Polygon LLM Wallet MCP Server, Tether WDK MCP Toolkit, Coinbase AgentKit, or GOAT SDK.

**Read-only x402 settlement verification:** TensorFeed x402 Base MCP.

**Crypto commerce, gift cards, eSIMs, and top-ups:** Bitrefill eCommerce MCP or CryptoRefills MCP.

**Multi-chain account, transfer, staking, and bridge operations:** Adamik MCP Server.

**Circle Wallets, CCTP, Contracts, and Gateway codegen:** Circle MCP Server.

**Institutional custody docs and workspace data:** BitGo MCP Server for BitGo docs-grounded integration help; Fireblocks MCP Server for Fireblocks workspace data and custody operations.

**DeFi execution, hardware-wallet verification, or vault risk:** Haiku DeFi MCP, VaultPilot MCP, or Philidor DeFi Vault Risk Analytics.

**Concentrated liquidity, rebalancing, and leveraged LPs:** Arcadia Finance MCP Server.

**Token, NFT, phishing, approval, and malicious-address risk screening:** GoPlus MCP Server.

**Security, tracing, and pre-signing risk:** Phalcon MCP Server or VaultPilot MCP.

**Farcaster user, cast, feed, Mini App, and social graph workflows:** Neynar MCP.

## Selection Criteria

- The project must expose or document a real MCP server, adapter, or MCP-compatible tool surface.
- The project must be directly useful for crypto, Web3, DeFi, wallets, exchanges, Blockchain development, market data, security, or on-chain actions.
- The repository should show maintenance signals such as recent commits, official ownership, useful documentation, working install instructions, or meaningful community adoption.
- Read-only tools are preferred for research tasks. Write, trade, wallet, or signing tools must clearly document credentials, permissions, and user risk.
- Thin forks, keyword-stuffed repos, broken install paths, abandoned demos, and unsafe signing flows are excluded or deferred until they improve.

## Risk Routing

Use the lowest-risk MCP that can complete the task. Crypto agents should start with read-only data surfaces, move to authenticated account tools only when the user needs a specific provider, and use wallet or trading tools only after explicit confirmation.

**Read-only data:** Prefer market, analytics, docs, RPC, search, dashboard, and risk-screening MCPs for research, due diligence, monitoring, and comparison tasks.

**API-key or OAuth data:** Use provider-scoped MCPs when the task needs account-specific data, premium datasets, hosted dashboards, billing, endpoint management, or source-specific provenance. Keep scopes narrow and report the provider used.

**Wallet, signing, transfers, swaps, staking, deployments, attestations, and trading:** Treat these as high-risk actions. Require explicit user intent, confirm chain, asset, address, amount, account, venue, and transaction type, and prefer draft, simulation, unsigned transaction, or user-approved flows where available.

**Secrets and custody:** Do not paste seed phrases, private keys, API keys, bearer tokens, or recovery material into prompts, issues, screenshots, or examples. Prefer dedicated test wallets, least-privilege API keys, spending limits, policy controls, and local signing when a server requires credentials.

## Curation Priority

This list is ordered for agent usefulness, not sponsorship, GitHub stars, or keyword volume.

- Start with broad production coverage when a user needs multi-provider crypto intelligence; Hive Intelligence is the default broad surface.
- Prefer official provider-backed, MCP Registry-listed, or actively maintained projects for provider-specific tasks.
- Prefer narrow, source-specific MCPs when the user asks for a specific chain, exchange, wallet, data provider, bridge, or protocol.
- Prefer read-only and documentation/search surfaces for research and due diligence. Escalate to write, trade, wallet, signing, staking, or infrastructure-admin tools only when the task clearly requires them.
- Keep entries out, or remove them later, when the MCP interface is unclear, install paths are broken, maintenance stops, the project becomes misleading, or the risk model is not documented.

## Maintenance Standard

This is a curated list, not an add-only catalog. Entries should stay useful to an agent choosing a crypto MCP server today.

- Recheck links and basic Markdown quality in CI, including `README.md`, `llms.txt`, `CONTRIBUTING.md`, and `SUBMISSIONS.md`.
- Prefer primary docs, official repos, MCP Registry entries, or maintained package pages over thin mirrors and stale forks.
- Keep descriptions use-case oriented: what the server helps an agent do, what credentials it needs, and where the risk boundary is.
- Remove or downgrade entries when a repo is archived, install paths break, docs disappear, the MCP interface is unclear, or the project becomes unsafe.
- Use [SUBMISSIONS.md](SUBMISSIONS.md) to track external directory status so stale Hive listings and duplicate outreach do not drift out of sight.

## Broad Crypto Intelligence

- [Hive Intelligence](https://github.com/hive-intel/hive-sdk) - Managed crypto market infrastructure for AI agents, combining hosted MCP, local stdio, SDKs, and skills across multiple providers and crypto workflows.
- [Universal Crypto MCP](https://github.com/nirholas/universal-crypto-mcp) - Multi-chain crypto MCP with swaps, bridges, gas, staking, lending, and plugin-based Blockchain interactions.
- [Heurist Mesh MCP Server](https://github.com/heurist-network/heurist-mesh-mcp-server) - Web3 agent and analytics MCP surface for Heurist's mesh of specialized agents.

## Blockchain Data Infrastructure

- [Alchemy MCP Server](https://github.com/alchemyplatform/alchemy-mcp-server) - Official Alchemy MCP with hosted Streamable HTTP/OAuth and local stdio for token prices, multichain balances, transfers, NFTs, smart accounts, and swaps.
- [Chainstack MCP Server](https://docs.chainstack.com/docs/chainstack-mcp-server) - Official remote Streamable HTTP MCP for documentation search, platform status, live RPC queries, node deployment, faucet requests, pricing, and Chainstack project management across 70+ chains.
- [Quicknode MCP](https://www.quicknode.com/docs/build-with-ai/quicknode-mcp) - Official remote OAuth MCP for Quicknode account operations, endpoint management, usage monitoring, security settings, billing review, and API-aware agent workflows.
- [GetBlock MCP Server](https://github.com/GetBlock-io/mcp-server) - Official open-source GetBlock MCP for Ethereum and Solana balances, transactions, latest blocks, gas prices, account information, JSON-RPC access, Node.js or Docker setup, and token-based GetBlock API authentication.
- [Bitquery MCP Server](https://docs.bitquery.io/docs/mcp/mcp-server/) - Hosted Bitquery MCP endpoint for Blockchain, DEX, token, and trading datasets used across Bitquery's GraphQL, streaming, and analytics products.
- [Allium MCP](https://docs.allium.so/assistant/mcp) - Official Allium MCP for Explorer SQL, saved queries, schema introspection, documentation search, and historical or real-time Blockchain data across 80+ chains.
- [Chainbase MCP](https://docs.chainbase.com/resources/ai/mcp) - Official Chainbase HTTP MCP for token balances, holders, metadata, prices, NFT ownership, transfers, transaction history, blocks, and Web3 account analytics.
- [Moralis Cortex MCP](https://www.jsdelivr.com/package/npm/@moralisweb3/api-mcp-server) - Official Moralis AI-native Web3 data layer with a hosted Cortex API and self-hosted `@moralisweb3/api-mcp-server` package for wallet activity, token metrics, NFT ownership, transfers, transactions, dapp usage, and structured on-chain answers using `MORALIS_API_KEY`.
- [Zerion API MCP](https://zerion.io/blog/zerion-for-api-ai-agents-mcp-skills/) - Official hosted Zerion MCP at `https://developers.zerion.io/mcp` for AI access to normalized wallet balances, prices, labeled transaction history, DeFi positions across 8,000+ protocols, NFT holdings, collection metadata, PnL, and documentation-backed API workflows across EVM chains and Solana.
- [Octav API MCP](https://github.com/Octav-Labs/octav-api-mcp) - Official Octav MCP package for portfolio data, wallet holdings, DeFi positions, NAV, transaction history, historical snapshots, token distribution, airdrop checks, and Polymarket position tracking across 20+ blockchains using an Octav API key.
- [CoinStats MCP Server](https://github.com/CoinStatsHQ/coinstats-mcp) - Official hosted CoinStats Streamable HTTP MCP at `https://mcp.coinstats.app/mcp` with OAuth 2.1 and Dynamic Client Registration for prices, charts, 100,000+ coins, portfolio coins, P/L, wallet balances, transactions across 120+ blockchains, 200+ exchange comparisons, and crypto news; npm stdio fallback is available as `@coinstats/coinstats-mcp` with `COINSTATS_API_KEY`.
- [Nansen MCP](https://docs.nansen.ai/mcp/overview) - Official Nansen MCP for smart-money labels, wallet activity, DEX trades, token flows, portfolio intelligence, and on-chain research across 25+ blockchains.
- [Glassnode MCP Server](https://docs.glassnode.com/guides-and-tutorials/glassnode-mcp-server) - Official beta Glassnode MCP at `https://mcp.glassnode.com` for asset and metric discovery, metric metadata, single or bulk on-chain metric retrieval, market intelligence, public 30-day access, and API-key authenticated analytics.
- [CryptoQuant MCP](https://github.com/CryptoQuantOfficial/cryptoquant-mcp) - Official `cryptoquant-mcp` npm server for CryptoQuant on-chain analytics, 245+ endpoint discovery, metric descriptions, raw API queries, MVRV, SOPR, exchange flows, funding rates, whale activity, and API-key-backed market intelligence.
- [Dune MCP](https://docs.dune.com/api-reference/agents/mcp/) - Official Dune remote MCP for DuneSQL query generation, execution, result retrieval, visualizations, dashboards, dataset discovery, and on-chain analytics workflows.
- [Token Terminal MCP](https://tokenterminal.com/docs/mcp/introduction) - Official hosted remote MCP at `https://mcp.tokenterminal.com/mcp` for Token Terminal on-chain datasets, projects, products, chains, market sectors, financial metrics, methodologies, time series, breakdowns, chart creation, and OAuth 2.1 authenticated access.
- [Crypto APIs MCP Servers](https://github.com/CryptoAPIs-io/cryptoapis-mcp-hub) - Official Crypto APIs MCP suite with a hosted Streamable HTTP endpoint and package-level servers for balances, blocks, transactions, fees, events, contracts, market data, HD wallets, signing, simulation, and transaction preparation.
- [GoldRush MCP Server](https://goldrush.dev/docs/goldrush-mcp-server) - Covalent GoldRush MCP for multichain wallet balances, token holdings, transaction histories, chain metadata, and standardized Blockchain data tools.
- [dRPC Agent Skills](https://github.com/drpcorg/drpc-agent-skills) - dRPC-maintained Blockchain RPC skill and MCP surface for agent access across 200+ networks.
- [Erigon MCP Server](https://docs.erigon.tech/fundamentals/mcp) - Official Erigon MCP for read-only Ethereum node data, JSON-RPC tools, Otterscan traces, logs, metrics, resources, prompts, and stdio or SSE setup against local Erigon nodes.
- [Nodit MCP Server](https://github.com/noditlabs/nodit-mcp-server) - Structured multi-chain Blockchain data through Nodit's Web3 Data and Node APIs.
- [The Graph Token API MCP](https://thegraph.com/docs/en/ai-suite/token-api-mcp/introduction/) - Official Token API MCP from The Graph for ERC-20 and NFT metadata, balances, transfers, top-holder statistics, natural-language token analysis, and hosted Token API access.
- [Subgraph MCP Server](https://github.com/graphops/subgraph-mcp) - The Graph Network MCP for subgraph search, schema discovery, GraphQL query execution, query-volume signals, hosted SSE, and local Rust setup.
- [Blockscout MCP Server](https://github.com/blockscout/mcp-server) - Explorer-backed MCP for balances, tokens, NFTs, contract metadata, and chain data.
- [Tatum Blockchain MCP](https://github.com/tatumio/blockchain-mcp) - Official Tatum MCP package for balances, transactions, token metadata, fee estimation, address activity, exchange rates, and Tatum Blockchain API access across 130+ networks using a Tatum API key.
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
- [TradeRouter MCP](https://github.com/TradeRouter/trade-router-mcp) - MCP Registry-listed `@traderouter/trade-router-mcp` package for non-custodial Solana swaps, limit orders, trailing orders, TWAP, DCA, combo orders, holdings, and token market-cap checks across Raydium, PumpSwap, Orca, and Meteora; private-key, signing, submission, and order tools are high-risk and should use a dedicated wallet plus explicit user control.
- [OpenSVM Solana MCP Server](https://github.com/openSVM/solana-mcp-server) - Rust-based Solana MCP focused on RPC methods.
- [Jupiter MCP](https://github.com/kukapay/jupiter-mcp) - Solana swap MCP using Jupiter's Ultra API.
- [Solana MCP Directory](https://github.com/sendaifun/awesome-solana-mcp-servers) - Solana-specific MCP list for deeper Solana ecosystem discovery.

## Bitcoin and Lightning

- [Bitcoin MCP](https://github.com/AbdelStark/bitcoin-mcp) - Bitcoin and Lightning Network MCP for keys, validation, queries, and Bitcoin-native workflows.
- [Maestro MCP Server](https://github.com/maestro-org/maestro-mcp-server) - Maestro-backed Bitcoin MCP with hosted mainnet and testnet endpoints for blocks, transactions, mempool, market price, wallet, and node RPC data.
- [AIBTC MCP Server](https://github.com/aibtcdev/aibtc-mcp-server) - Bitcoin-native MCP for BTC/STX wallets, Bitcoin L1 reads and transfers, Stacks L2, sBTC, NFTs, DeFi yield, and x402 payments; wallet creation, mnemonic export, transfers, DeFi, and paid-call tools are high-risk.
- [Alby Bitcoin Payments MCP Server](https://github.com/getAlby/mcp) - Official Alby MCP for connecting Lightning wallets to agents through Nostr Wallet Connect, hosted Streamable HTTP or SSE, local stdio, LNURL, L402, invoices, and bearer-authenticated NWC secrets.
- [LNbits MCP Server](https://github.com/lnbits/LNbits-MCP-Server) - Official LNbits MCP for Lightning wallet balances, invoices, payments, Lightning addresses, LNURLp links, TPoS, SatsPay, watch-only wallets, node info, and user management; API keys, payment tools, and admin tools require explicit user control.
- [Lightning Wallet MCP](https://github.com/lightningfaucet/lightning-wallet-mcp) - Bitcoin Lightning wallet MCP and CLI for agent payments, invoices, L402 support, and Lightning-native tool access.
- [Bortlesboat Bitcoin MCP](https://github.com/Bortlesboat/bitcoin-mcp) - Zero-config Bitcoin MCP for fees, mempool, blocks, transactions, mining, price, and supply data.
- [Bitcoin Blockchain Data MCP](https://github.com/JamesANZ/bitcoin-mcp) - Bitcoin data MCP for real-time Blockchain information.

## Layer-1 and Cross-Chain

- [Aptos MCP](https://aptos.dev/build/ai/aptos-mcp) - Official Aptos MCP at `npx @aptos-labs/aptos-mcp` with tools, prompts, resources, Cursor and Claude Code setup, Aptos API access, and Geomi-backed app-building workflows using `APTOS_BOT_KEY`.
- [Avalanche MCP Server](https://build.avax.network/docs/tooling/ai-llm/mcp-server) - Official hosted read-only Avalanche Builder Hub MCP for documentation search, GitHub code lookup, RPC and CLI task lookup, ACPs, public network data, resources, and `https://build.avax.network/api/mcp`.
- [Rootstock MCP Server](https://github.com/rsksmart/rsk-mcp-server) - Official `@rsksmart/rsk-mcp-server` package for Rootstock wallet management, RBTC and ERC-20 balances, transfers, transaction status, contract deployment, contract verification, contract reads, transaction history, and Rootstock Attestation Service workflows; wallet import, transfers, deployments, and attestations are high-risk actions.
- [Starknet MCP Server](https://github.com/starkware-libs/starknet-specs/tree/master/mcp) - StarkWare-maintained Starknet specifications repo MCP exposing Starknet JSON-RPC v0.10.2 methods for blocks, transactions, state, storage, classes, events, traces, simulation, fee estimates, node info, and network switching against a user-provided Starknet RPC endpoint; treat private provider RPC URLs as secrets.
- [TON Blockchain MCP](https://github.com/devonmojito/ton-blockchain-mcp) - MIT-licensed Python MCP for TON address analysis, transaction details, hot trends, trading-pattern analysis, TON price, and jetton prices using TON API credentials; beta software, not financial advice.
- [TON AgentKit MCP](https://docs.ton.org/overview/ai/mcp) - Official TON `@ton/mcp` server for TON AgentKit wallet operations, token transfers, swaps, NFT inspection and transfers, DNS, jettons, pools, transaction lookup, stdio, Streamable HTTP, and serverless deployment; wallet creation, recovery phrases, transfers, swaps, deployments, and credentials are high-risk.
- [Tari MCP Servers](https://github.com/tari-project/tari) - Official Tari protocol repo with Minotari wallet and node MCP servers for local AI-agent access to wallet balances, transaction history, address info, transfers, burn transactions, coin splits, node/network information, blocks, mempool, peers, and sync status; defaults should stay read-only, while control operations require explicit enablement, confirmation, and audit logging.
- [Across MCP Server](https://docs.across.to/ai-agents/mcp-server) - Official Across Protocol hosted MCP at `https://mcp.across.to/mcp` with documentation search, page retrieval, REST API references, supported-chain lookup, live bridge-fee queries, and SDK code examples.
- [Allbridge MCP](https://allbridge.io/ai/) - Official Allbridge AI MCP suite for planning, quoting, building, locally signing, broadcasting, and tracking cross-chain stablecoin transfers across EVM, Solana, Tron, Algorand, Stacks, Soroban/Stellar, and Sui, with keys kept in a local signer.
- [LayerZero Docs MCP](https://docs.layerzero.network/v2/tools/mcp/overview) - Official hosted LayerZero documentation MCP at `https://docs.layerzero.network/mcp` with Streamable HTTP search for LayerZero docs, OApps, OFTs, DVNs, endpoints, and cross-chain messaging workflows.
- [VeChain MCP Server](https://github.com/vechain/vechain-mcp-server) - Official VeChain MCP for ecosystem resources and VeChain developer workflows.
- [Mina MCP Server](https://github.com/MinaProtocol/mina-mcp-server) - Official Mina Protocol MCP for Mina Blockchain tooling and developer workflows.
- [Celo MCP](https://github.com/celo-org/celo-mcp) - Official Celo MCP for Celo ecosystem, chain, and developer workflows.
- [Sei MCP Server](https://docs.sei.io/ai/mcp-server) - Official Sei MCP for account management, SEI transfers, token and NFT operations, smart-contract reads and writes, block data, transaction data, and local or HTTP server modes.
- [Sui MCP Server](https://github.com/ExpertVagabond/sui-mcp-server) - MCP Registry-listed stdio package for Sui wallet/session tools, coin/object/transaction queries, Move introspection, staking, validators, SuiNS, Cetus and DeepBook data, and GraphQL/JSON-RPC access; wallet import, transfers, staking, and Move calls are high-risk actions.
- [Polkadot MCP](https://github.com/shawntabrizi/polkadot-mcp) - Rust stdio MCP for Polkadot, Kusama, Westend, Paseo, and system parachains, with live account, fellowship, governance, staking, and chain-state tools; read-only by default, with transaction tools only when `POLKADOT_SIGNER_URI` is explicitly configured.
- [Hedera MCP](https://github.com/ExpertVagabond/hedera-mcp) - MCP Registry-listed `@purplesquirrel/hedera-mcp` package for Hedera Mirror Node reads and 73 build-only tools across Account, HTS, HCS, EVM, File, Schedule, Network, and analytics; write tools return unsigned frozen transactions for external signing and never hold private keys.
- [NEAR MCP](https://github.com/nearai/near-mcp) - NEAR AI MCP for account management, balances, transactions, smart-contract inspection, and local wallet-backed NEAR interactions.
- [Algorand MCP](https://github.com/GoPlausible/algorand-mcp) - GoPlausible server and client for Algorand developer documentation, wallet management, transaction handling, and Blockchain state queries.
- [ZetaChain CLI MCP](https://github.com/zeta-chain/cli) - ZetaChain CLI with MCP installation support for universal smart-contract workflows across connected chains.

## DeFi, Markets, and Trading

- [Alpaca MCP Server](https://github.com/alpacahq/alpaca-mcp-server) - Official Alpaca MCP for trading, portfolios, crypto market data, and broker workflows.
- [Trade It](https://github.com/trade-it-inc/trade-it-mcp) - Official MCP Registry-listed remote MCP for draft-first stock, crypto, and options trading through linked brokerages, including Coinbase and Kraken for crypto; supports Streamable HTTP, SSE, OAuth login, account lookup, draft order creation, and explicit execution tools.
- [QuantConnect MCP Server](https://www.quantconnect.com/mcp) - Official QuantConnect MCP for AI-assisted project management, docs/API search, code editing, compiles, backtests, optimization, and live algorithm deployment across QuantConnect strategies, including crypto-capable workflows; project writes, broker authorization, live deployment, stops, liquidations, and account API tokens are high-risk.
- [CoinGecko MCP Server](https://docs.coingecko.com/docs/ai-agent-hub/mcp-server) - Official CoinGecko MCP for prices, historical market data, DEX pools, NFT collections, metadata, keyless public access, authenticated Pro access, and local npm setup.
- [CoinMarketCap MCP](https://coinmarketcap.com/api/mcp/) - Official CoinMarketCap hosted MCP for quotes, technical analysis, on-chain metrics, global market data, trending narratives, news, semantic search, and x402 pay-per-call access.
- [BlockRun MCP](https://github.com/BlockRunAI/blockrun-mcp) - MIT-licensed MCP for pay-per-call live data across crypto prices, DEX data, prediction markets, X/Twitter intelligence, web research, and model calls using an x402-funded local wallet.
- [Crypto.com Market Data MCP](https://mcp.crypto.com/docs) - Official Crypto.com hosted MCP for keyless live cryptocurrency prices, market caps, trading volumes, market trends, ChatGPT setup, and Claude setup.
- [altFINS MCP Server](https://altfins.com/crypto-market-and-analytical-data-api/documentation/mcp-server/) - Official altFINS Streamable HTTP MCP for crypto screeners, technical analysis, OHLCV, historical indicators, signal feeds, news, calendar events, and portfolio data using altFINS API-key authentication.
- [TradingView MCP Server](https://github.com/atilaahmettaner/tradingview-mcp) - MIT-licensed Python/PyPI MCP for TradingView-style crypto and stock screening, Binance/KuCoin/Bybit+ market coverage, 30+ technical-analysis tools, candlestick patterns, Reddit/news sentiment, Yahoo Finance prices, and strategy backtesting; analysis-only and does not execute trades.
- [LunarCrush MCP Server](https://github.com/lunarcrush/mcp-server) - Official LunarCrush MCP with preferred remote Streamable HTTP endpoint `https://lunarcrush.ai/mcp`, SSE endpoint, and `@lunarcrush/mcp-server` stdio proxy for API-key-backed real-time social intelligence, community attention, creator/post context, and crypto social-market trend discovery.
- [aTars MCP](https://github.com/aarna-ai/atars-fts-mcp) - Official MCP Registry-listed remote MCP from aarna for cryptocurrency trading signals and sentiment analysis, including technical-indicator-based buy/sell signals, daily sentiment scoring, and rolling sentiment trends; use as a research signal feed, not financial advice or trade execution.
- [TradeMemory Protocol](https://github.com/mnemox-ai/tradememory-protocol) - MCP-native memory and audit layer for AI trading agents across crypto, stocks, forex, and futures, with outcome-weighted recall, risk gates, strategy reflection, and SHA-256 decision records; it records and recalls decisions but does not execute trades or access wallets.
- [Pyth MCP Server](https://docs.pyth.network/price-feeds/pro/mcp) - Official Pyth hosted Streamable HTTP MCP at `https://mcp.pyth.network/mcp` for feed discovery, latest prices, historical prices, and OHLC candles across crypto, FX, equities, metals, rates, commodities, and funding rates.
- [Massive.com MCP Server](https://github.com/massive-com/mcp_massive) - Official experimental Massive.com MCP for crypto, stock, options, forex, futures, news, reference data, market snapshots, technical functions, and in-memory SQLite analysis through three composable search, call, and query tools using a Massive.com API key.
- [Lambda Finance MCP](https://www.lambdafin.com/financial-mcp-server) - Hosted Streamable HTTP financial MCP for real-time market research across stocks, options, futures, crypto, bonds, macro, filings, and related datasets, including crypto derivatives, funding/open-interest context, exchange flows, whale transfers, and wallet tracking. Requires a Lambda Finance account/API key or OAuth flow.
- [Messari MCP Server](https://docs.messari.io/mcp-server/hosted) - Official hosted Messari MCP at `https://mcp.messari.io/mcp` for AI-powered crypto research, natural-language data queries, deep research jobs, Messari timeseries catalog and data, market data, on-chain metrics, fundraising, token unlocks, news, research reports, and X/Twitter mindshare signals through OAuth-backed Messari API-key authentication; legacy local stdio is available as `@messari/sdk-ts-mcp`.
- [Santiment MCP Connector](https://academy.santiment.net/mcp-connector/) - Official hosted Santiment MCP at `https://api.santiment.net/mcp` for OAuth-backed Sanbase market intelligence, including metric and asset discovery, timeseries data, asset screening, analyst insights, trending stories, combined social trends, on-chain metrics, exchange flows, development activity, social volume, and weighted sentiment.
- [AkTools MCP Server](https://github.com/aahl/mcp-aktools) - MIT-licensed AkShare-backed MCP for A-share, Hong Kong, US stock, and crypto market data, including historical crypto prices, related news, OKX long/short ratios, OKX taker volume, and Binance AI reports; use its `trading_suggest` style outputs as research signals, not financial advice.
- [RWA Pipe MCP](https://github.com/rwapipe/mcp) - Tokenized real-world asset MCP for AI agents that need RWA token discovery, treasury comparisons, TVL, APY, issuer and chain filters, wallet holdings, whale flows, risk signals, and contract-control intelligence across tokenized treasuries, private credit, commodities, equities, stablecoins, and real estate. Requires `RWAPIPE_API_KEY`; contract scans and admin-oriented tooling require stronger user control.
- [TRUF.NETWORK MCP Server](https://docs.truf.network/ai-toolkit) - Official TRUF.NETWORK MCP for natural-language-to-SQL access to verified real-world asset data, event-driven market data, on-chain price indexes, and TRUF node data streams; setup runs against TRUF.NETWORK node/database infrastructure and is tested with Claude Desktop.
- [Cryptohopper MCP](https://www.cryptohopper.com/features/cryptohopper-mcp) - Cryptohopper remote MCP for live exchange market data, real-time candles, order-book depth, spread analysis, and MCP-compatible trading research workflows.
- [Birdeye MCP Server](https://docs.birdeye.so/docs/birdeye-ai) - Official beta Birdeye MCP at `https://mcp.birdeye.so/mcp` for real-time market data, token discovery, new listings, top movers, DEX liquidity, token metadata, safety signals, OHLCV, wallet net worth, wallet PnL, and authenticated production access through a Birdeye API key.
- [1inch Business MCP](https://business.1inch.com/1inch-mcp) - Official 1inch MCP for docs search, code examples, 1inch Business API access, portfolio and balance data, orderbook flows, spot prices, classic swaps, Fusion intent swaps, and cross-chain swaps; protected tools use API key or OAuth and require explicit transaction controls.
- [DZap MCP Server](https://docs.dzap.io/ai/mcp) - Official DZap MCP documentation for 17 DeFi, NLP, and analytics tools covering prices, trends, sentiment, wallet balances, DeFi positions, token and pool data, swaps, bridges, zaps, and DZap docs search; treat calldata, execution links, and transaction preparation as high-risk.
- [LI.FI MCP Server](https://docs.li.fi/mcp-server/overview) - Official hosted LI.FI MCP at `https://mcp.li.quest/mcp` for read-only cross-chain swap quotes, routes, chain and token discovery, allowance and balance checks, gas suggestions, and transfer status tracking; returns unsigned transaction requests for external wallet signing.
- [CoW MCP](https://github.com/krzysu/cow-mcp) - Hosted and local MCP for CoW Protocol quotes, supported chain and token lookup, wallet trade history, EIP-712 order and cancellation payloads, external wallet signing, and order submission; treat approvals, signed orders, cancellations, and host-wallet broadcasts as high-risk actions.
- [DeFiLlama MCP](https://github.com/demcp/demcp-defillama-mcp) - Community DeFiLlama API wrapper exposing protocol TVL, chain TVL, token prices, pools, yield data, and public DeFi analytics through MCP; useful for TVL and yield research, not an official DeFiLlama server.
- [CoinPaprika MCP](https://github.com/coinpaprika/coinpaprika-mcp) - Official `@coinpaprika/mcp` server with 30 tools for prices, tickers, 8,000+ coins, 200+ exchanges, OHLCV, contracts, search, historical market data, hosted access, local setup, and free-tier features without an API key.
- [DexPaprika MCP](https://github.com/coinpaprika/dexpaprika-mcp) - CoinPaprika-maintained `dexpaprika-mcp` server with 14 tools for token, pool, DEX, OHLCV, transaction, and cross-chain DEX analytics across 33 networks, hosted and local options, and no API keys required.
- [DexScreener MCP Server](https://github.com/openSVM/dexscreener-mcp-server) - DEX pair and token-market data through the DexScreener API.
- [Crypto Price MCP](https://github.com/truss44/mcp-crypto-price) - CoinCap-backed MCP for real-time prices, market analysis, historical trends, technical indicators, exchange data, and stdio or Streamable HTTP transport.
- [Gate for AI](https://github.com/gate/gate-for-ai) - Official Gate AI-native crypto infrastructure repo covering Gate MCP endpoints and skills for CEX market data and trading, DEX wallets and swaps, coin info, on-chain data, news, sentiment, and installer workflows for Claude Code, Codex, Cursor, and OpenClaw; trading, wallet, transfer, swap, and account tools require explicit user control.
- [Gate MCP Server](https://github.com/gate/gate-mcp) - Official Gate MCP with hosted Streamable HTTP endpoints for public market data, info, and news, plus OAuth-gated CEX trading/account and DEX wallet/swap workflows; local stdio is available through the `gate-mcp` npm package.
- [Bitget Agent Hub](https://github.com/Bitget-AI/agent_hub) - Official Bitget Agent Hub with `bitget-mcp-server`, CLI, and skills for spot, futures, account, margin, copy trading, convert, Earn, P2P, and broker workflows; default modules expose 36 tools while `--modules all` exposes the full 58-tool surface, and account, order, leverage, transfer, Earn, P2P, broker, and API-key permissions are high-risk.
- [Kraken CLI](https://github.com/krakenfx/kraken-cli) - Official Kraken AI-native CLI with a built-in stdio MCP server for market data, account, spot trading, futures, funding, staking, WebSocket, and paper-trading workflows; public market data and paper trading work without credentials, while dangerous tools require explicit care and least-privilege API keys.
- [Bybit MCP Server](https://github.com/bybit-exchange/trading-mcp) - Official Bybit trading MCP server for REST and WebSocket market data, account, wallet, portfolio, position, and order workflows; public market-data tools can run without credentials while private tools require Bybit API keys.
- [CCXT MCP Server](https://github.com/lazy-dinosaur/ccxt-mcp) - CCXT-backed local MCP package for market data, order books, OHLCV, balances, orders, trading history, performance analysis, position sizing, and multi-exchange trading across 100+ crypto exchanges; private exchange API keys and order-placement tools are high-risk.
- [Crypto.com CDCX CLI](https://github.com/crypto-com/cdcx-cli) - Official Crypto.com Exchange CLI with MCP support for market data, trading, account workflows, WebSocket streams, and safety controls.
- [Hummingbot MCP Server](https://github.com/hummingbot/mcp) - Official Hummingbot MCP for connecting AI agents to a Hummingbot API across multi-exchange crypto trading, connector setup, portfolio overview, market data, controller and bot management, executors, DEX pool exploration, Gateway operations, and GeckoTerminal data; connector credentials, private keys, bot deployment, leverage, executor creation, and live orders are high-risk.
- [Injective MCP Server](https://docs.injective.network/developers-ai/mcp) - Official Injective MCP for natural-language Injective queries and transactions, including spot transfers, bridge operations, raw EVM transactions, and perpetual futures trading.
- [Arcadia Finance MCP Server](https://github.com/arcadia-finance/mcp-server) - Official Arcadia MCP for Uniswap, Aerodrome, and Velodrome concentrated-liquidity strategies, account risk, lending pools, automated rebalancing, leverage, and unsigned transaction building on Base, Unichain, and Optimism.
- [Haiku DeFi MCP](https://github.com/Haiku-Trading/haiku-mcp-server) - DeFi execution MCP for swaps, lending, bridges, yield discovery, portfolio analysis, and external wallet signing across many chains.
- [Philidor DeFi Vault Risk Analytics](https://github.com/Philidor-Labs/philidor-mcp) - Hosted DeFi risk MCP for searching 700+ vaults, comparing risk scores, and analyzing Morpho, Aave, Yearn, Beefy, Spark, and related protocols.
- [OKX OnchainOS Skills/MCP](https://github.com/okx/onchainos-skills) - Official OKX `onchainos` skills and CLI whose CLI doubles as a native MCP server for wallet lifecycle, portfolio reads, token discovery, market data, DEX swaps, transaction simulation and broadcasting, smart-money signals, security scans, DeFi product actions, and x402/payment workflows across 20+ chains; OKX API credentials, swaps, broadcasts, deposits, withdrawals, and payments are high-risk.
- [OKX Agent Trade Kit](https://github.com/dex-original/okx-agent-trade-kit) - Community OKX trading, CLI, and MCP toolkit for spot, futures, and automated trading agents.
- [Hyperliquid MCP Server](https://github.com/mektigboy/server-hyperliquid) - Hyperliquid SDK MCP for mid prices, candle snapshots, and L2 order books.
- [Hyperliquid MCP Server by Caio](https://github.com/caiovicentino/hyperliquid-mcp-server) - Hyperliquid DEX MCP with account state, positions, orders, fills, leverage, margin, TWAP, WebSocket subscriptions, and trading tools; private keys, leverage, margin, and order execution are high-risk.
- [Binance MCP Server](https://github.com/AnalyticAce/binance-mcp-server) - Unofficial Binance MCP for exchange data and trading-agent workflows.
- [Crypto Indicators MCP](https://github.com/kukapay/crypto-indicators-mcp) - Technical-analysis indicators and strategy signals for cryptocurrency agents.
- [Chainlink Feeds MCP](https://github.com/kukapay/chainlink-feeds-mcp) - Chainlink price-feed MCP for decentralized on-chain market data.

## NFTs and Marketplaces

- [OpenSea MCP](https://docs.opensea.io/reference/mcp) - Official OpenSea MCP for AI access to NFTs, tokens, collections, accounts, portfolio analytics, marketplace listings, offers, drops, swaps, and ready-to-sign trading actions across supported chains.

## Prediction Markets

- [PMXT](https://github.com/pmxt-dev/pmxt) - Open-source unified prediction-market API with hosted MCP at `https://api.pmxt.dev/mcp` and local `@pmxt/mcp` setup for market search, events, order books, price history, cross-venue comparison, and trading across Polymarket, Kalshi, Limitless, and related venues; treat order creation, cancellation, private keys, and exchange credentials as high-risk actions requiring explicit confirmation.
- [Polymarket MCP Server](https://github.com/caiovicentino/polymarket-mcp-server) - Polymarket MCP with market data, monitoring, and trading-oriented tools.
- [Polymarket MCP](https://github.com/berlinbra/polymarket-mcp) - Python MCP server for the Polymarket API.
- [Polymarket Rust MCP](https://github.com/ozgureyilmaz/polymarket-mcp) - Rust implementation for Polymarket market access.

## Security and Risk

- [GoPlus MCP Server](https://github.com/GoPlusSecurity/goplus-mcp) - Official GoPlus Security MCP for EVM token security, malicious-address checks, phishing URL checks, NFT contract risk, approval risk, Solana token security, and Sui token security using GoPlus API credentials.
- [Phalcon MCP Server](https://github.com/mark3labs/phalcon-mcp) - BlockSec Phalcon integration for transaction tracing, profiling, address labels, balance changes, state changes, and chain ID lookup.
- [VaultPilot MCP](https://github.com/szhygulin/vaultpilot-mcp) - Hardware-wallet-verified DeFi MCP for portfolio reads and Ledger-approved prepares, sends, swaps, staking, lending, LP management, bridges, approvals, and verification artifacts across EVM, TRON, Solana, Bitcoin, and Litecoin; signing, blind-signing, approvals, bridges, and broadcasts are high-risk and require explicit device confirmation.
- [Insumer MCP Server](https://github.com/douglasborthwick-crypto/mcp-server-insumer) - MCP for condition-based access and signed boolean attestations across 37 chains without exposing balances.
- [Armor Crypto MCP](https://github.com/armorwallet/armor-crypto-mcp) - Wallet and swap workflows with strategic planning and risk-aware interactions.
- [SolanaShield MCP](https://github.com/ElromEvedElElyon/solanashield-mcp) - Solana smart-contract security MCP with vulnerability-pattern checks.
- [Sperax Crypto MCP](https://github.com/Sperax/sperax-crypto-mcp) - Protocol-specific MCP for USDs, SPA, veSPA, and Demeter workflows on Arbitrum and BNB Chain.

## Web3 Social, News, Sentiment, and Research Signals

- [Neynar MCP](https://docs.neynar.com/docs/neynar-farcaster-with-cursor) - Official Neynar hosted MCP at `https://docs.neynar.com/mcp` for Farcaster development workflows, users, casts, feeds, social graphs, Mini Apps, notifications, signers, on-chain/social data, and API-backed agent setup in Cursor, VS Code, Claude Code, and Claude.
- [LunarCrush MCP Server](https://lunarcrush.com/products/lunarcrush-mcpserver) - Official LunarCrush MCP for connecting agents to real-time social intelligence through remote Streamable HTTP, SSE, or stdio proxy setup with a LunarCrush API key.
- [Web3 Research MCP](https://github.com/aaronjmars/web3-research-mcp) - Local npm MCP for structured cryptocurrency token research plans, web/news/image/video search, source collection, saved research resources, status tracking, CoinGecko market data, exchange listings, and DeFiLlama protocol lookups; use it for research dossiers and verify claims against primary sources before acting.
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
- [Cobo Agentic Wallet MCP](https://github.com/CoboGlobal/cobo-agentic-wallet) - Official Cobo Agentic Wallet repo with Python and TypeScript SDKs, a stdio MCP server, and scoped Pact controls for MPC-backed wallets, balances, addresses, transfers, smart-contract calls, message signing, transaction records, pending approvals, and audit logs; invitation onboarding, API keys, Pact approval, transfers, contract calls, signing, recovery, and mainnet activity are high-risk.
- [MoonPay CLI MCP](https://support.moonpay.com/en/articles/592667-connect-moonpay-to-any-mcp-compatible-ai) - Official MoonPay CLI local MCP server (`mp mcp`) for non-custodial wallets, balances, swaps, bridges, transfers, fiat on/off ramps, token search, market data, and Open Wallet Standard-aligned agent workflows; treat login, KYC, local wallet storage, swaps, bridges, transfers, DCA, limit orders, and fiat transactions as high-risk.
- [Polygon LLM Wallet MCP Server](https://github.com/0xPolygon/apk-mcp-llm-wallet) - Polygon-documented `llm-wallet-mcp` package for encrypted Polygon and Polygon Amoy wallets, balances, per-transaction and daily spending limits, x402 buyer and seller flows, payment history, and dynamic paid-API tool registration; development-stage package, prefer testnet, and treat wallet import, mainnet funds, and automatic micropayments as high-risk.
- [Tether WDK MCP Toolkit](https://docs.wdk.tether.io/ai/mcp-toolkit) - Official Wallet Development Kit MCP toolkit from Tether for building self-custodial wallet MCP servers across EVM chains, Bitcoin, Solana, Spark, TON, and Tron, with 35 built-in tools for wallets, pricing, indexer queries, swaps, bridges, lending, and fiat on/off-ramps; beta package, local seed handling, and all write operations require explicit human confirmation before broadcasting.
- [Bitrefill eCommerce MCP](https://docs.bitrefill.com/docs/ecommerce-mcp) - Official hosted Bitrefill MCP at `https://api.bitrefill.com/mcp` for ChatGPT, Claude, Cursor, and other MCP clients to search products, inspect product details, and buy from Bitrefill's crypto-commerce catalog; use the [sample implementation](https://github.com/bitrefill/bitrefill-mcp-server) for self-hosted or forked API-key experiments. Treat invoices, account data, purchases, eSIMs, and payments as high-risk actions.
- [CryptoRefills MCP](https://www.cryptorefills.com/insights/cryptorefills-mcp) - Official CryptoRefills MCP integration at `https://api.cryptorefills.com/mcp/http` for AI-agent commerce flows across gift cards, mobile top-ups, eSIMs, catalog, pricing, checkout preparation, and payments. Keep final payment confirmation under explicit user control.
- [Coinbase AgentKit](https://github.com/coinbase/agentkit) - Coinbase Developer Platform toolkit with a Model Context Protocol extension for wallet-backed agents, payments, testnet funding, and on-chain actions.
- [x402 MCP](https://github.com/x402node/x402-mcp) - MCP server for discovering x402-paid APIs from CDP Bazaar and automatically handling USDC micropayments on Base through the `x402node-mcp` package; use a fresh burner wallet, set `MAX_PRICE_USD`, and treat `X402_PRIVATE_KEY` as a spend-capable secret.
- [TensorFeed x402 Base MCP](https://github.com/RipperMercs/tensorfeed-x402-base-mcp) - Read-only Base mainnet MCP for verifying x402 USDC settlements, parsing publisher `/.well-known/x402` manifests, probing x402 endpoints, decoding payment payloads, and checking TensorFeed/AFTA publisher health; it does not hold private keys, sign, or broadcast transactions.
- [Adamik MCP Server](https://github.com/AdamikHQ/adamik-mcp-server) - Official `@adamik/mcp-server` package for API-key-backed balances, transaction history, native and token transfers, staking, unstaking, rewards, swaps, and bridge workflows across 60+ blockchains; treat transfer, staking, swap, bridge, and premium operations as high-risk actions requiring explicit user control.
- [Phantom MCP Server](https://github.com/phantom/phantom-connect-sdk/tree/main/packages/mcp-server) - Official `@phantom/mcp-server` package exposing Phantom wallet authentication, addresses, balances, Solana and EVM signing, token transfers, swaps, token prices, payments, and Hyperliquid perps through a local stdio MCP; treat signing, transfer, swap, and perps tools as high-risk wallet actions.
- [BitGo MCP Server](https://developers.bitgo.com/docs/get-started-mcp-server) - BitGo Developer Portal MCP for natural-language access to institutional crypto wallet, custody, and API documentation.
- [Fireblocks MCP Server](https://github.com/fireblocks/fireblocks-mcp) - Official Fireblocks MCP for vault accounts, assets, transactions, exchange accounts, network connections, policies, whitelisted IPs, wallets, and workspace users, with explicit controls for write operations.
- [Privy Docs MCP](https://docs.privy.io/basics/get-started/using-llms) - Official hosted docs MCP at `https://docs.privy.io/mcp` for Privy auth, embedded wallet, policy, and integration guidance in Cursor, Claude Desktop, and other MCP clients.
- [Privy MCP Server](https://github.com/privy-io/privy-mcp-server) - Official Privy MCP server for creating wallets, checking balances, signing Ethereum and Solana transactions, managing policies, and wallet-enabled agent operations.
- [MetaMask Embedded Wallets MCP](https://github.com/Web3Auth/web3auth-mcp) - Official Web3Auth MCP for helping agents integrate MetaMask Embedded Wallets with live SDK docs, examples, and type lookup.
- [PayRam MCP](https://github.com/PayRam/payram-mcp) - Self-hosted crypto payments, hosted endpoints, and agent payment workflows.
- [GOAT SDK](https://github.com/goat-sdk/goat) - Large agentic finance toolkit with a Model Context Protocol adapter, 200+ on-chain tools, wallet integrations, payments, DeFi, prediction markets, tokenization, and framework adapters across TypeScript and Python.
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
- [Awesome Lists](https://github.com/szabgab/awesome-lists) - General index of awesome lists across domains.
- [Ecosyste.ms Awesome](https://awesome.ecosyste.ms/) - Open API index for awesome lists and downstream software ecosystem discovery.
- [MCP Registry](https://registry.modelcontextprotocol.io/) - Official MCP server registry for production server discovery.
- [AgentNDX](https://agentndx.ai/) - Curated, quality-scored MCP, A2A, and x402 registry with a free server index, programmatic API, and MCP-native discovery endpoint.
- PulseMCP (`pulsemcp[.]com`) - Large MCP server directory, newsletter, API, and partner registry surface that ingests from the Official MCP Registry.
- [MCP.Directory](https://mcp.directory/) - Broad MCP directory with server pages, category pages, publisher pages, and client install surfaces.
- [MCPfinder](https://www.mcpfinder.org/) - Reviewed MCP server directory with reliability checks, category pages, comparison coverage, and a public submit flow.
- [MCPfinder.dev](https://mcpfinder.dev/) - Agent-facing MCP discovery server that searches the Official MCP Registry, Glama, and Smithery, then generates install-ready client config.
- [MCP Directory App](https://mcpdirectory.app/browse) - Verified open-source MCP server browser with one-click install positioning and compatibility checks.
- [MCP Catalogs](https://mcpcatalogs.com/en) - Independent bilingual MCP directory with AI-evaluated server pages and side-by-side comparison.
- [MCPRepository](https://mcprepository.com/) - MCP server directory with GitHub-indexed server pages, search, and an npm-backed submission CLI.
- [MCPpedia](https://mcppedia.org/) - Open MCP catalog with server scoring, security signals, community submissions, API access, and daily official-registry sync.
- [MCP Showcase](https://mcpshowcase.com/p/mcp-server-directory) - Interactive MCP server directory and playground pages for testing and presenting MCP endpoints.
- [MCP Server Spot](https://www.mcpserverspot.com/) - Modern MCP server directory with category pages, server detail pages, structured metadata, and a public submit flow.
- [MCP Bundles](https://www.mcpbundles.com/) - MCP marketplace and bundling directory with provider pages, publish flow, and SKILL.md-oriented discovery.
- [MCP.so](https://mcp.so/) - Large community MCP directory with indexed server pages, category browsing, and search traffic around Claude MCP and Awesome MCP Servers.
- [FindMCP](https://findmcp.dev/) - Large web MCP directory with category pages, server search, and an MCP installer companion CLI.
- [MCPList.ai](https://www.mcplist.ai/) - Broad MCP directory with verified/community server browsing, function categories, comparison content, and a contact-based contribution path.
- ServeMCP (`servemcp[.]com`) - Broad MCP directory with granular crypto, DeFi, Solana, risk, exchange, and trading categories.
- MCP Server Directory (`mcpserverdirectory[.]org`) - MCP resource directory with a public submit form and indexed server pages.
- [MCP Server Info](https://www.mcpserver.info/) - MCP directory with server detail pages, source links, and category browsing.
- [MCP Server Registry](https://model-context-protocol-server.com/) - Searchable MCP server registry powered by the Model Context Protocol ecosystem.
- [MCP Toplist](https://mcptoplist.com/) - Continuously updated MCP server index and ranking dataset aggregating the Official MCP Registry, Glama, Smithery, mcp.so, and other MCP discovery sources.
- [MCP Atlas](https://www.mcp-atlas.com/) - Provenance-first MCP ecosystem index aggregating the Official MCP Registry, Smithery, Glama, PulseMCP, and GitHub/community sources.
- [toolidx](https://toolidx.dev/) - Agent-first MCP verification directory with structured server records, OpenAPI, `llms.txt`, and quality metadata.
- [Qorua](https://www.qorua.com/) - Early-access MCP registry focused on capability search, trust scores, and USDC pay-per-call settlement.
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
