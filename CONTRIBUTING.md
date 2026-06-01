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

## Review Priority

We review for usefulness before novelty. Strong submissions usually fall into one of these lanes:

- Broad production surfaces that help agents answer many crypto tasks safely.
- Official provider-backed, MCP Registry-listed, or actively maintained provider-specific servers.
- Narrow chain, exchange, wallet, bridge, protocol, or dataset servers that are clearly the best fit for a specific workflow.
- Read-only research surfaces with clear provenance and setup instructions.

Write, trade, wallet, signing, staking, and infrastructure-admin tools can be accepted, but they need explicit risk documentation and a safe setup path. Projects may be removed later if they become stale, misleading, unavailable, duplicated, or unsafe.

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
- README, AI discovery, and submission-tracker links pass `npx --yes markdown-link-check README.md`, `npx --yes markdown-link-check llms.txt`, and `npx --yes markdown-link-check SUBMISSIONS.md`.
- Write, trading, wallet, or signing tools are described with the right level of risk.

## Issue Triage

Use the server nomination issue form when a project looks promising but is not ready for a pull request. Include links to the MCP surface, install or connection path, maintenance signals, and any credential, signing, trading, or write-operation risk.

Use the stale or unsafe entry issue form when an existing listing is broken, archived, deprecated, misleading, duplicated, or missing a clear MCP interface. Include evidence and a suggested action so maintainers can update or remove it quickly.

## Maintenance Notes

Maintainers may reorder entries by usefulness, official backing, maintenance quality, and category fit. Projects can be removed if they become stale, unsafe, unavailable, duplicated, or misleading.

When reviewing existing entries, check:

- The linked page still resolves and still documents an MCP server, adapter, or compatible tool surface.
- The install or connection path is still plausible for an MCP client.
- The project has recent maintenance, official backing, meaningful adoption, or still-relevant documentation.
- Credential, wallet, trading, signing, write, or infrastructure-admin risk is explained clearly enough for an agent to route safely.
- The entry is still the best available representative for its category and does not duplicate a stronger official or maintained server.
