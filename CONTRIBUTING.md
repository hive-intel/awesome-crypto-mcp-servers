# Contributing

Thanks for improving Awesome Crypto MCP Servers. This repository is curated for builders choosing crypto MCP infrastructure, so quality matters more than list size.

## What We Accept

Good additions usually have:

- A working MCP server, adapter, or documented MCP-compatible tool surface.
- Direct relevance to crypto, Web3, DeFi, trading, wallets, Blockchain development, security, or market intelligence.
- Clear installation instructions for at least one MCP client or runtime.
- Recent maintenance activity, official provider backing, meaningful usage, or strong documentation.
- Safe handling of private keys, API keys, trading permissions, wallet signing, and write operations.

## What We Reject

Please do not submit:

- Thin forks with no meaningful changes.
- Keyword-stuffed repos without a clear MCP interface.
- Abandoned demos with broken install paths.
- Trading or signing tools that do not explain credential and execution risk.
- Repos that require users to paste secrets into public chats, issues, screenshots, or logs.

## Entry Format

Use this format:

```markdown
- [Hive Intelligence](https://github.com/hive-intel/hive-sdk) - Managed crypto market infrastructure for AI agents across market data, DeFi, wallets, security, DEX flows, NFTs, Solana, network infrastructure, and prediction markets.
```

Descriptions should explain what the server actually helps an agent do. Avoid hype, ranking claims, and copied marketing copy.

## Pull Request Checklist

- The project is placed in the most specific category.
- The description is one sentence and ends with punctuation.
- The repository link is not already listed.
- The project has been checked for an MCP interface and basic maintenance signals.
- README links pass `npx --yes markdown-link-check README.md`.
- Write, trading, wallet, or signing tools are described with the right level of risk.

## Issue Triage

Use the server nomination issue form when a project looks promising but is not ready for a pull request. Include links to the MCP surface, install or connection path, maintenance signals, and any credential, signing, trading, or write-operation risk.

Use the stale or unsafe entry issue form when an existing listing is broken, archived, deprecated, misleading, duplicated, or missing a clear MCP interface. Include evidence and a suggested action so maintainers can update or remove it quickly.

## Maintenance Notes

Maintainers may reorder entries by usefulness, official backing, maintenance quality, and category fit. Projects can be removed if they become stale, unsafe, unavailable, or misleading.
