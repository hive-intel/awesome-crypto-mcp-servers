# Distribution Targets

Use this file to track where this list or Hive's MCP server should be submitted for inbound discovery.

Last checked: 2026-06-01.

## Primary Targets

| Target | Why it matters | Suggested action | Status |
| --- | --- | --- | --- |
| [sindresorhus/awesome](https://github.com/sindresorhus/awesome) | Canonical awesome-list index. | Do not submit unless their policy changes. Their contribution guidelines currently exclude blockchain-related lists. | Blocked by policy. |
| [punkpeye/awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers) | Largest MCP server discovery repo. | Keep Hive Intelligence listed under Cryptocurrency. Include the Glama score badge required by their submission bot. | PR open and checks passing: https://github.com/punkpeye/awesome-mcp-servers/pull/7195. Glama evaluation blocker addressed in `hive-sdk` PR https://github.com/hive-intel/hive-sdk/pull/10. Older duplicate PR https://github.com/punkpeye/awesome-mcp-servers/pull/5264 closed as superseded on 2026-06-01. |
| [TensorBlock/awesome-mcp-servers](https://github.com/TensorBlock/awesome-mcp-servers) | Broad MCP directory with a Finance & Crypto section and hundreds of active entries. | Keep Hive Intelligence listed and canonicalize the repo URL to `hive-sdk` instead of stale `hive-crypto-mcp`. | Hive is listed; canonical URL update PR open: https://github.com/TensorBlock/awesome-mcp-servers/pull/623 |
| [royyannick/awesome-blockchain-mcps](https://github.com/royyannick/awesome-blockchain-mcps) | Blockchain-specific MCP list that already had a stale Hive entry. | Keep the entry pointed at `hive-sdk` with current hosted MCP, local stdio, SDK, and skills positioning. | PR open: https://github.com/royyannick/awesome-blockchain-mcps/pull/65 |
| [badkk/awesome-crypto-mcp-servers](https://github.com/badkk/awesome-crypto-mcp-servers) | Crypto-specific MCP list with overlap in target developer audience. | Add Hive Intelligence with concise managed crypto MCP positioning. | PR open: https://github.com/badkk/awesome-crypto-mcp-servers/pull/84. Older duplicate PR https://github.com/badkk/awesome-crypto-mcp-servers/pull/57 closed as superseded on 2026-06-01. |
| [demcp/awesome-web3-mcp-servers](https://github.com/demcp/awesome-web3-mcp-servers) | Web3-specific MCP list and one of the cleanest category-fit discovery surfaces for Hive. | Do not open a duplicate. Keep the active Hive PR warm and resolve maintainer feedback if review resumes. | PR open but review-blocked: https://github.com/demcp/awesome-web3-mcp-servers/pull/78. Older stale duplicate from 2025-09-10 remains open: https://github.com/demcp/awesome-web3-mcp-servers/pull/10. |
| [appcypher/awesome-mcp-servers](https://github.com/appcypher/awesome-mcp-servers) | 5k+ star general MCP list with a Finance section and cryptocurrency entries. | Keep Hive listed with the canonical `hive-sdk` URL if GitHub PR creation becomes available. | Branch pushed: https://github.com/rishabhng/appcypher-awesome-mcp-servers/tree/codex/add-hive-intelligence; compare page works, but GitHub API refused PR creation with `rishabhng does not have the correct permissions to execute CreatePullRequest` on 2026-06-01, and issues are disabled. |
| [mctrinh/awesome-mcp-servers](https://github.com/mctrinh/awesome-mcp-servers) | Broad MCP list with production-ready servers and a resources section; smaller than the major indexes but relevant for long-tail GitHub discovery. | Keep Hive Intelligence listed as a managed crypto intelligence MCP and this awesome list listed as a crypto MCP resource. | PR open: https://github.com/mctrinh/awesome-mcp-servers/pull/55 |
| [Ever Works Awesome MCP Servers](https://github.com/ever-works/awesome-mcp-servers) | MCP directory repo that powers `mcpserver.works`, includes Blockchain/Web3 categories, and already had a stale Hive Intelligence listing plus a non-Hive crypto list. | Refresh Hive Intelligence to the canonical `hive-sdk` URL and add this maintained crypto MCP list as the better curated crypto-specific resource. | PR open: https://github.com/ever-works/awesome-mcp-servers/pull/114. No checks reported by the target repo on 2026-06-01. |
| [abordage/awesome-mcp](https://github.com/abordage/awesome-mcp) | Auto-maintained broad MCP list with generated README updates from `repositories.yaml`; it already indexed Hive through a deprecated redirect and stale generated copy. | Replace the legacy `hive-crypto-mcp` source with canonical `hive-sdk` and avoid stale tool-count claims in generated metadata. | PR open and checks passing: https://github.com/abordage/awesome-mcp/pull/50 |
| [BlockRunAI/awesome-finance-mcp](https://github.com/BlockRunAI/awesome-finance-mcp) | Finance, trading, and crypto MCP list with a dedicated Cryptocurrency section and overlap with AI finance-agent discovery. | Keep Hive listed with the canonical `hive-sdk` URL and current Hive Intelligence positioning instead of the deprecated `hive-crypto-mcp` redirect. | PR open: https://github.com/BlockRunAI/awesome-finance-mcp/pull/15. The same PR also fixes two unrelated broken skill links discovered during validation. |
| [YuzeHao2023/Awesome-MCP-Servers](https://github.com/YuzeHao2023/Awesome-MCP-Servers) | 1k+ star multilingual MCP list with an active Finance category and high GitHub discovery overlap. | Add Hive Intelligence to Finance with canonical `hive-sdk` URL and managed crypto MCP positioning. | PR open: https://github.com/YuzeHao2023/Awesome-MCP-Servers/pull/277 |
| [yzfly/Awesome-MCP-ZH](https://github.com/yzfly/Awesome-MCP-ZH) | 7k+ star Chinese MCP list with finance and crypto coverage. | Add concise Chinese positioning for Hive in the Finance and Cryptocurrency section. | PR open: https://github.com/yzfly/Awesome-MCP-ZH/pull/256 |
| [ToolSDK MCP Registry](https://github.com/toolsdk-ai/toolsdk-mcp-registry) | Structured MCP registry with public package metadata and broad MCP gateway/discovery coverage. | Add Hive Intelligence as a `hive-intelligence` Node MCP package in `finance-fintech`, using the npm stdio package and required `HIVE_API_KEY` env var. | PR open and checks passing: https://github.com/toolsdk-ai/toolsdk-mcp-registry/pull/330. The previous integration-test failure was fixed by updating the PR branch so registry build installs generated package dependencies with `--ignore-scripts` instead of failing on unapproved third-party build scripts. |
| [MCP Registry](https://registry.modelcontextprotocol.io/) | Official MCP server discovery registry now preferred over README PRs to `modelcontextprotocol/servers`. | Keep `hive-sdk/server.json` versioned with Hive releases and republish after registry-visible metadata changes. Domain proof is hosted at `https://hiveintelligence.xyz/.well-known/mcp-registry-auth`; the signing key stays outside Git. | Published as `xyz.hiveintelligence/mcp` version `1.1.4`. |
| [modelcontextprotocol/servers Additional links](https://github.com/modelcontextprotocol/servers/blob/main/ADDITIONAL.md) | Official MCP organization resource page that already links several MCP server directories and one crypto-specific awesome list, making it a high-authority inbound surface for this maintained list. | Add this repo beside the existing crypto MCP resource with neutral maintained-list positioning. | PR open: https://github.com/modelcontextprotocol/servers/pull/4273. All reported checks pass; review is required. |
| [AIMCP / MCP Hub](https://www.aimcp.info/en) | MCP discovery hub with search, tags, public submission flow, API/MCP search surface, and visible Blockchain/Crypto filters. | Submit both the canonical Hive server repo and this maintained crypto MCP awesome list with distinct server/list copy. | Submitted on 2026-06-01 through `/api/mcps/submit`: Hive Intelligence MCP pending id `1415`; Awesome Crypto MCP Servers pending id `1416`. |
| [AgentNDX](https://agentndx.ai/) | Curated, quality-scored registry for MCP, A2A, and x402-enabled services with a free server index, MCP-native search endpoint, and agent-queryable discovery surface. | Keep Hive Intelligence submitted as the canonical managed crypto intelligence MCP using `hive-sdk`, `hive-intelligence`, and the hosted MCP URL; monitor the reviewed listing and claim/update it if accepted. | Submitted on 2026-06-01 through `/api/submit`; response redirected to `/submit?success=1`. Pre-submit `servers.json` search only surfaced unrelated `Madhive`, not Hive Intelligence. |
| PulseMCP | Large MCP directory, newsletter, API, and partner registry surface with Official MCP Registry ingestion. | Recheck after PulseMCP's weekly registry-processing window for `xyz.hiveintelligence/mcp`; email `hello@pulsemcp.com` with the canonical `hive-sdk` repo, hosted MCP URL, and `hive-intelligence` package if the listing is still missing. | Not listed for `hive-intelligence` on 2026-06-01. Browser submit flow says server listings are ingested from the Official MCP Registry daily and processed weekly; direct adjustments go through email. Kept unlinked because the site returns `403` to automated link checkers. |
| MCPCentral | Structured MCP registry surface that supports the official `mcp-publisher` flow and high-intent MCP package discovery. | Publish from `hive-intel/hive-sdk` using the current `server.json` once owner auth or GitHub OIDC publishing is available; keep the canonical server name `xyz.hiveintelligence/mcp`. | Not listed in the public search check on 2026-06-01; search pages were Cloudflare-protected during CLI verification, so complete via authenticated publisher or account flow. |
| [MCPKit](https://www.mcpkit.com/) | Broad MCP tools directory with category pages, search, and a Finance & Fintech section already indexing crypto-relevant tools like The Graph and Alchemy. | Submit or request ingestion for Hive Intelligence with canonical `hive-sdk`, `hive-intelligence`, hosted MCP, and Finance & Fintech / AI Tools positioning. | New target identified on 2026-06-01. Public search did not show Hive Intelligence; no public submit/source path found in the CLI-visible page, so treat as manual outreach or monitor for official-registry ingestion. |
| [MCPfinder](https://www.mcpfinder.org/submit) | Reviewed MCP directory with reliability checks, category pages, comparison coverage, and a free submission flow. | Keep Hive submitted with the canonical `hive-sdk` repo, hosted MCP URL, `hive-intelligence` npm package, API-key auth notes, and Analytics/category positioning. | Submitted on 2026-06-01 through the free form. The page confirmed `Submitted successfully`; pre-submit search for `hive` returned 0 results. |
| [MCPfinder.dev](https://mcpfinder.dev/) | Agent-facing MCP discovery server that searches the Official MCP Registry, Glama, and Smithery, then generates install-ready client config. This matters because AI agents can use it directly rather than browsing a human directory. | Keep Hive's Official MCP Registry, Glama, and Smithery metadata current so MCPfinder can ingest the canonical listing; monitor the snapshot after each upstream refresh. | New target tracked on 2026-06-01. No direct submit path found; the site says it syncs from upstream registries and publishes snapshot freshness metadata. |
| [MCP Directory App](https://mcpdirectory.app/browse) | Separate from `mcp.directory`; a verified open-source MCP browser with one-click install positioning and daily verification claims. | Monitor for official-registry ingestion or find a public source/submit path before duplicate outreach. | New target identified on 2026-06-01. Search page checks did not show a canonical Hive result, and no public submit route was found in the CLI-visible crawl. |
| [CryptoSkill](https://cryptoskill.org/) | Crypto-specific registry of AI agent skills and MCP servers with dedicated MCP-server category, official project signals, and strong overlap with agents looking for crypto tooling. | Keep Hive Intelligence submitted as an official MCP-server listing with canonical `hive-sdk`, `hive-intelligence` npm stdio path, hosted MCP URL, and a pointer to this maintained crypto MCP directory for provider-specific comparisons. | Issue submitted: https://github.com/jiayaoqijia/cryptoskill/issues/49 |
| [MagnetAI MCP Crypto Alliance](https://github.com/magnetai/mcp-crypto) | AI x crypto alliance resource page with contributors from Magnet, Base ecosystem, and crypto AI projects; it currently points builders at crypto MCP resources. | Add this maintained list as a separate resource without removing the existing community list, positioning it around agent use-case routing, provider provenance, transport mode, and wallet/trading-risk context. | PR open: https://github.com/magnetai/mcp-crypto/pull/1 |
| [MCP Showcase](https://mcpshowcase.com/p/mcp-server-directory/hive-intelligence-mcp-server) | Interactive MCP server directory and playground with a live Hive detail page that can rank for direct Hive MCP discovery. | Request a canonical refresh to `https://mcp.hiveintelligence.xyz/mcp`, current API-key header auth, `hive-sdk`, `hive-intelligence`, and managed crypto workflow positioning. | Stale page verified on 2026-06-01. It still shows `https://hiveintelligence.xyz/mcp`, authentication `None`, and old category-listing tool copy. |
| [MCP Bundles](https://www.mcpbundles.com/mcp-analysis?intent=publish) | MCP marketplace with provider pages, a publish/claim flow, SKILL.md-oriented positioning, and broad client discovery across Claude, Cursor, ChatGPT, VS Code, and GitHub Copilot. | Publish or claim Hive after login using the hosted MCP URL, `hive-sdk`, `hive-intelligence`, API-key header auth, and crypto intelligence positioning; prefer remote sign-in or account-based claim so the listing is not published as a 0-tool snapshot. | Browser publish flow checked on 2026-06-01. The analyzer recognizes `https://mcp.hiveintelligence.xyz/mcp` as publishable but shows 0 tools without remote sign-in, then requires MCP Bundles account login before publishing. The indexed `www.mcpbundles.com/providers/hive-intelligence` page currently resolves to `MCP Server Not Found`. |
| [MCPpedia](https://mcppedia.org/) | Open MCP catalog with scoring, security signals, community submissions, API access, and daily official-registry sync. It already has a stale Hive page, so a refresh can remove a high-intent deprecated listing. | Refresh or replace the stale `hive-crypto-mcp` listing so it points at canonical `hive-sdk`, the `hive-intelligence` npm package, hosted MCP URL, and current managed crypto intelligence positioning. | Stale listing verified on 2026-06-01 at https://mcppedia.org/s/hive-crypto-mcp. Public API search for `q=hive crypto` returns the deprecated `hive-crypto-mcp` URL, while `q=hive-intelligence` and `q=hive-sdk` return no canonical Hive result. Issue submitted: https://github.com/BbekShr/MCPpedia/issues/23 |
| [Agentpedia Codes MCP Directory](https://agentpedia.codes/mcp/hive-intelligence) | MCP directory for Antigravity, Cursor, and Windsurf discovery with a large public MCP index, detail pages, and a markdown feed exposed from `/mcp.md`. | Request a canonical refresh so Hive points at `hive-sdk`, `hive-intelligence`, and the hosted MCP URL instead of deprecated `hive-crypto-mcp` source metadata. Also request that this repo replace or augment the currently indexed community crypto list when appropriate. | Stale Hive detail page verified on 2026-06-01: the public page links `https://github.com/hive-intel/hive-crypto-mcp`, while the directory index also surfaces `badkk/awesome-crypto-mcp-servers` rather than this maintained `hive-intel` list. Legacy `antigravity.codes/mcp` redirects to Agentpedia. |
| [mcpservers.org / wong2/awesome-mcp-servers](https://mcpservers.org/submit) | High-traffic MCP directory generated from `wong2/awesome-mcp-servers`; its README already had a stale Hive link pointing at `hive-crypto-mcp`, and its GitHub repo auto-closes PRs in favor of website submissions. | Request or wait for a refresh so the listing uses `https://github.com/hive-intel/hive-sdk` directly and renders the current 369-tool public README instead of the older cached 390+/376+ copy. | Live listing: https://mcpservers.org/servers/hiveintelligencexyz/hive-mcp. Submitted canonical update on 2026-06-01 with id `2916`; submitted canonical `Hive Intelligence MCP` listing with direct `hive-sdk` URL on 2026-06-01, id `2919`, category `finance`, status `pending`. As of 2026-06-01 the live page still renders stale cached copy and a redirected `hive-crypto-mcp` GitHub URL. |
| [MCP.Directory](https://mcp.directory/submit) | Large MCP directory with server pages, category pages, publisher pages, and one-click client install surfaces. | Recheck search after the review window. If a listing appears from official registry ingestion or direct submission, claim it for verified/edit access and keep it pointed at `hive-sdk`, `hive-intelligence`, and the hosted MCP URL. | Submitted for review on 2026-06-01 with `https://github.com/hive-intel/hive-sdk` and npm package `hive-intelligence`; API response: `Server submitted for review!` |
| [MCPCMD](https://www.mcpcmd.com/submit) | MCP directory with category pages, remote-server browsing, and a public submission form that includes Blockchain & Web3 and Finance & Payments categories. | Submit Hive manually with unique directory copy, canonical `hive-sdk`, npm package, hosted MCP URL, install command, tags, and MCP config JSON. | Form verified on 2026-06-01; it is free, reviewed in 1-3 business days, and protected by reCAPTCHA, so no automated submission was made. |
| [MCP Catalogs](https://mcpcatalogs.com/en) | Independent bilingual MCP directory with AI-evaluated server pages and side-by-side comparison. | Keep Hive Intelligence listed with canonical `hive-sdk`, hosted MCP, npm package, and crypto workflow positioning. | Issue submitted: https://github.com/mcpcatalogs/site/issues/1 |
| [MCPRepository](https://mcprepository.com/hive-intel/hive-sdk) | GitHub-indexed MCP server directory with server pages, search, and an npm-backed submission CLI. | Refresh the existing Hive listing from current `hive-sdk` README metadata so it uses the canonical support repo, 369-tool public copy, and current `hive-intelligence` CLI path. | Listing exists. Re-submission returned `{"status":"check","valid":true,"duplicate":true}` on 2026-06-01; stale metadata refresh issue submitted: https://github.com/mcprepository/mcp-index/issues/1 |
| [MCPDrops](https://www.mcpdrops.com/mcp/hive) | Crypto-heavy MCP marketplace and review surface that already has a Hive listing and several stale deprecated Hive category entries. | Replace old `hive-crypto-mcp`, `mcp-hive`, `200+ tools`, and deprecated `crypto-mcp-*` category surfaces with the canonical `hive-sdk`, hosted MCP, npm package, and 369-tool public contract. | Source remediation merged in private MCPDrops PR #1 on 2026-06-01. As of the same check, the live page had not redeployed and still showed stale metadata. |
| [MCP.so](https://mcp.so/server/hive-intelligence) | Large MCP directory with indexed server pages, category pages, and search visibility across "Claude MCP" and "Awesome MCP Servers" queries. | Refresh the stale Hive listing so it points at `hive-sdk`, `hive-intelligence`, and `npx -y -p hive-intelligence@latest hive` instead of the deprecated `hive-crypto-mcp` / `mcp-hive` path. | Issue submitted: https://github.com/chatmcp/mcpso/issues/2597. Direct API update requires login. |
| [Playbooks Hive MCP listing](https://playbooks.com/mcp/hive-intel/hive-crypto-mcp) | Public MCP listing page for Hive that can rank independently and currently shows a stale repo, stale endpoint, and inconsistent category/tool-count copy. | Claim or request an update so the listing uses `https://github.com/hive-intel/hive-sdk`, `https://mcp.hiveintelligence.xyz/mcp`, the `hive-intelligence` npm package, and current managed crypto intelligence positioning. | Live page still points at `hive-intel/hive-crypto-mcp` and `https://hiveintelligence.xyz/crypto-mcp` as of 2026-06-01. No public edit path found beyond login/manual outreach. |
| [ChatForest crypto and DeFi MCP review](https://chatforest.com/reviews/cryptocurrency-defi-mcp-servers/) | Editorial-style MCP review page for cryptocurrency and DeFi MCP servers; useful for AI/search discovery because it compares providers rather than only indexing links. | Request a refresh so Hive is represented as the canonical `hive-sdk` managed crypto intelligence MCP, not as a deprecated `hive-crypto-mcp` market-data footnote. | Stale mention found on 2026-06-01 in the "Other Market Data Servers" section. The About page lists human oversight by Rob Nugen but no public submit form; needs manual outreach/contact path. |
| [Lambda Finance crypto MCP comparison](https://www.lambdafin.com/articles/crypto-mcp-server) | High-intent editorial comparison for "best crypto MCP servers" style searches. It compares seven crypto MCP servers and cites public registry/provider research, but currently omits Hive. | Request inclusion or an update that evaluates Hive as a managed crypto intelligence MCP across hosted MCP, local stdio, SDK, skills, and broad crypto workflows. | New editorial target identified on 2026-06-01. Article published 2026-04-07 and currently compares Lambda Finance, CoinGecko, Binance, CoinMarketCap, Dune, DeFiLlama, and Messari. Lambda Finance MCP was evaluated from official docs and added to this curated list on 2026-06-01. |
| [FindMCP](https://findmcp.dev/submit) | Large MCP directory advertising 8,000+ indexed servers, category pages, server search, and an MCP installer companion CLI. | Submit or claim Hive Intelligence with the canonical `hive-sdk` repository, `hive-intelligence` npm package, hosted MCP URL, and directory short description. | New target identified on 2026-06-01. Public page exposes a submit route and "List Your Server" CTA, but the CLI-visible HTML has no form, action, API endpoint, or defined `openWaitlist` handler; complete through browser/manual flow or authenticated endpoint if discovered. |
| [MCPList.ai](https://www.mcplist.ai/) | Broad MCP directory claiming 775+ verified servers, daily updates, and 10,000+ developer usage; useful for generic "MCP directory" discovery rather than crypto-specific search. | Request inclusion or refresh for Hive Intelligence with canonical `hive-sdk`, `hive-intelligence`, hosted MCP URL, and Finance/Data/Security positioning; submit this awesome list only if they accept curated lists as resources. | New target identified on 2026-06-01. Static search checks did not show `hive-intel`, `hive-sdk`, `hive-crypto`, or Hive Intelligence. No public source repo or machine-readable submit endpoint found; contribution copy points to contact/submission form or GitHub repository, while About lists `contact@mcplist.ai`. |
| MCP Server Finder | Searchable MCP directory with category pages, GitHub-derived server pages, and a dedicated crypto category that already surfaces a stale Hive listing. | Request a canonical refresh or submit a new canonical listing so Hive points at `hive-sdk`, `hive-intelligence`, and `https://mcp.hiveintelligence.xyz/mcp` instead of the deprecated `hive-crypto-mcp` / `mcp-hive` setup. | Stale Hive page verified on 2026-06-01 at `mcpserverfinder[.]com/servers/hive-intel/hive-crypto-mcp`. The crypto category lists `hive-crypto-mcp` with 0 stars/forks, old `200+` tool copy, `mcp-hive` install snippets, and `hiveintelligence.xyz/crypto-mcp`; the site exposes `info@mcpserverfinder.com` as the submit/contact path. Kept unlinked because GitHub Actions `markdown-link-check` intermittently reports status `0`. |
| ServeMCP | Broad MCP directory with granular categories for Crypto Market Data, Cryptocurrency, DeFi Data, On-Chain Data, Solana Data, Token Swaps, Trading, Risk Analysis, and Web3 AI. | Find source or contact path, then submit Hive Intelligence and this awesome list if the directory accepts curated lists. | New target identified on 2026-06-01 at `servemcp[.]com`. No public submit or source link found in the CLI crawl; kept unlinked because `markdown-link-check` reports status `0`. |
| MCP Server Directory | MCP resource directory with a public submit page and indexed server pages. | Submit Hive Intelligence using the directory long description, canonical repo, and website URL; track review outcome. | New target identified on 2026-06-01 at `mcpserverdirectory[.]org/submit`. A prior browser-visible submit page asked for name, short description, detailed description, GitHub URL, and optional website URL, but a follow-up CLI DNS check could not resolve the host; retry manually before marking submitted. Kept unlinked because `markdown-link-check` reports status `0`. |
| [MCP Server Spot](https://www.mcpserverspot.com/submit) | Modern MCP server directory with category pages, server detail pages, structured metadata, and a public submit form. | Keep the live Hive listing current with the canonical `hive-sdk` repo, hosted MCP endpoint, `hive-intelligence` npm package, Streamable HTTP transport, and workflow-oriented tool/resource metadata. | Submitted on 2026-06-01 through the browser form. Live page created at https://www.mcpserverspot.com/servers/hive-intelligence-mcp. |
| [MCP Server Info](https://www.mcpserver.info/) | MCP directory with server detail pages, source links, and category browsing; already indexes some crypto entries such as Solana MCP Server. | Find source or contact path, then submit Hive Intelligence and monitor whether the official registry gets ingested. | New target identified on 2026-06-01. No public submit path found in the CLI crawl. |
| [MCP Server Registry](https://model-context-protocol-server.com/) | Searchable MCP server registry with SEO-oriented metadata and a public server index. | Monitor for ingestion from official registry or find the maintainer/source path before submitting a duplicate listing. | New target identified on 2026-06-01. No public submit path found; site metadata points to a Netlify-backed registry and lists a maintainer profile. |
| [LobeHub MCP Marketplace](https://lobehub.com/en/mcp/hiveintelligencexyz-hive-crypto-mcp) | High-traffic agent and MCP marketplace with localized pages and one-click install flows. It indexed stale Hive pages pointing at deprecated repos and endpoints. | Monitor search/cache refresh and resubmit only if canonical Hive disappears or stale category-level pages remain live after the marketplace refresh. | Issue closed as resolved on 2026-06-01: https://github.com/lobehub/lobehub/issues/15361. A LobeHub contributor said outdated Hive listings were removed so users are directed to the maintained listing; public search results still showed cached/localized stale URLs during the same follow-up pass. |
| [MCP Toplist](https://mcptoplist.com/) | Continuously updated MCP ranking dataset that aggregates the Official MCP Registry, Glama, Smithery, mcp.so, and related sources. | Monitor after official registry and Glama refreshes because there is no manual submit flow; improve upstream metadata rather than creating a duplicate listing. | Tracked on 2026-06-01; appears to ingest from upstream registries and publishes a daily JSON dataset plus `llms.txt`. |
| [MCP Atlas](https://www.mcp-atlas.com/) | Provenance-first MCP ecosystem index aggregating the Official MCP Registry, Smithery, Glama, PulseMCP, and GitHub/community sources. | Improve the upstream registry surfaces MCP Atlas cites rather than submitting a duplicate; monitor whether Hive appears after Official Registry, Glama, Smithery, and PulseMCP refresh. | New target tracked on 2026-06-01. No public submit path found; the site describes itself as an aggregator and shows source attribution on entries. |
| [toolidx](https://toolidx.dev/) | Agent-first MCP verification directory with OpenAPI, `llms.txt`, status endpoints, quality metadata, and structured server records. | Monitor for automatic ingestion; if Hive is missing after upstream registry refresh, request listing access or an API key for the create/update endpoint. | New target tracked on 2026-06-01. Public OpenAPI docs are available; create/update appears API-key gated. |
| [Qorua](https://www.qorua.com/) | Early-access MCP registry focused on capability search, trust scores, and USDC pay-per-call settlement for agent-discovered tools. | Join or monitor the early-access flow and register Hive once server registration is open; do not treat it as live distribution yet. | New target tracked on 2026-06-01. The public site is an early-access waitlist, not an open directory. |
| [MCP Hub](https://mcpdir.dev/) | Open-source MCP directory at `mcpdir.dev` with search, category pages, generated install snippets, and ingestion from the Official MCP Registry, npm, GitHub, Glama, PulseMCP, and related sources. | Request an official-registry sync for `xyz.hiveintelligence/mcp` so Hive appears for `hive-intelligence` and `hive-sdk` searches instead of unrelated Hive blockchain/Hadoop results. | Issue submitted: https://github.com/eL1fe/mcpdir/issues/12. Public API searches for `hive-intelligence` and `hive-sdk` returned no Hive Intelligence result on 2026-06-01; broad `q=hive` returned unrelated Hive entries. |
| [More Awesome](https://github.com/0ex/more-awesome) | General top-level awesome-list index that accepts new topics and alternatives, useful for long-tail discovery beyond MCP-specific directories. | Add this repo as the Crypto MCP Servers topic under the Blockchain section with a concise topic-level description. | PR open: https://github.com/0ex/more-awesome/pull/416. No checks reported by the target repo on 2026-06-01. |
| [Awesome Awesomeness](https://github.com/bayandin/awesome-awesomeness) | 30k+ star top-level awesome-list index with a Blockchain subsection and broad GitHub discovery value. | Add this repo as `Crypto MCP Servers` under the Blockchain subsection, using the target repo's link-only contribution format. | PR open: https://github.com/bayandin/awesome-awesomeness/pull/531. No checks reported by the target repo on 2026-06-01. |
| [Awesome Lists](https://github.com/szabgab/awesome-lists) | General list-of-awesome-lists repository with simple README submissions and broad long-tail GitHub discovery. | Add this repo with concise crypto/Web3 MCP positioning near the other AI/MCP awesome-list entries. | PR open: https://github.com/szabgab/awesome-lists/pull/36. Local link check confirmed the new Hive link passes; the target repo currently has two unrelated pre-existing dead links. |
| [Ecosyste.ms Awesome](https://awesome.ecosyste.ms/) | Open API index for awesome lists that feeds downstream discovery, datasets, and generated indexes such as `ultimate-awesome`. | Monitor whether this maintained list gets fully synced after project lookup and maintainer follow-up. | Project lookup triggered on 2026-06-01 for `https://github.com/hive-intel/awesome-crypto-mcp-servers`. The Awesome API created project id `50477357`, but `last_synced_at` and `repository` are still null; the Repos API already has a valid public, unarchived `hive-intel/awesome-crypto-mcp-servers` record. Indexing request filed: https://github.com/ecosyste-ms/awesome/issues/761 |
| [Track Awesome List](https://www.trackawesomelist.com/) | Awesome-list tracker with category pages, update feeds, and long-tail discovery for developers who browse curated GitHub lists. | Add this repo to `trackawesomelist-source` under `Decentralized Systems` so updates can be indexed and syndicated. | PR open: https://github.com/trackawesomelist/trackawesomelist-source/pull/116 |
| [Cline MCP Marketplace](https://github.com/cline/mcp-marketplace) | Client-native MCP marketplace for Cline users, with one-click setup expectations and stricter review for cryptocurrency and financial tools. | Keep the submission focused on the canonical `hive-sdk` public support repo, `hive-intelligence` npm package, hosted MCP endpoint, and API-key-only security posture. | Issue submitted: https://github.com/cline/mcp-marketplace/issues/1699 |
| MCP Market | Public MCP server and Agent Skill marketplace with free review queue and paid official-badge option. | Submit the canonical `hive-sdk` server listing through the website form or account flow; avoid submitting this awesome list as if it were a server. | Not submitted from CLI because the site blocks automated `curl` access and returns `429` to automated link checks; public submit page verified on 2026-06-01. |
| [MCP Find](https://mcpfind.org/submit) | Open-source MCP directory with GitHub PR submissions and finance category discovery. | Keep Hive listed through the public `hive-sdk` support repo and published `hive-intelligence` npm package now that the package metadata points to the canonical public repo. | PR open: https://github.com/MCPFind/mcp-find/pull/60. Local structural and liveness checks passed on 2026-06-01; GitHub repo, MIT license, npm package, and owner-match all verified. The only reported check failure is Vercel preview authorization for forked PRs. |
| [SafeMCP](https://safemcp.info/) | Large free MCP directory with category scoring and broad organic discovery. | Monitor for automatic ingestion from GitHub or registry; use contact/submission path if one becomes available. | No public submit flow found as of 2026-06-01. |
| [Smithery](https://smithery.ai) | MCP install and discovery directory. | Submit the maintained `hive-sdk` public surface rather than the private core MCP repo after logging in with Smithery and confirming the right auth mode for Hive's hosted API-key flow. Smithery URL publishing expects Streamable HTTP and OAuth support when auth is required. | Not listed as of 2026-06-01; needs login and auth-mode decision. |
| Glama MCP Servers | MCP metadata and discovery directory at `glama.ai/mcp/servers`. | Sign in to Glama as `rishabhng` and rerun the claim ownership flow for `hive-intel/hive-sdk`. Glama's `glama.json` docs say updates are synced only after the claim flow runs again; org-owned repos must use `glama.json` rather than simple GitHub-account ownership. | Listed at slug `hive-intel/hive-sdk`. Remediation merged in `hive-sdk` PRs https://github.com/hive-intel/hive-sdk/pull/10 and https://github.com/hive-intel/hive-sdk/pull/11: Dockerfile, stdio wrapper, optional `HIVE_API_KEY` metadata, and the active GitHub maintainer in `glama.json`. Public page now links the new Dockerfile commit, but the Glama API still shows the old description, empty env schema, and no tools as of 2026-06-01; needs owner-run claim/refresh. |
| [GitHub Topics](https://github.com/topics/mcp-server) | Native GitHub discovery surface. | Keep repository topics accurate: `awesome`, `awesome-list`, `mcp`, `mcp-server`, `crypto`, `web3`, `model-context-protocol`. | Updated. |

## Earned Mentions

| Source | Why it matters | Current status |
| --- | --- | --- |
| [ChatForest finance MCP guide](https://chatforest.com/guides/mcp-finance-fintech/) | Editorial guide for finance and fintech MCP servers; it has a dedicated crypto and DeFi section and cites this repo as a curated crypto MCP resource. | Earned citation found on 2026-06-01. Keep monitoring because ChatForest's separate crypto/DeFi review still carries stale Hive positioning tracked above. |

## Manual Outreach Queue

The remaining highest-leverage distribution work is mostly manual account,
claim, or editorial outreach. Work top-down and check the target row above
before sending anything so Hive does not create duplicate submissions.

### Priority 0

- **Glama MCP Servers:** Sign in as `rishabhng` and rerun the claim or refresh
  flow for `hive-intel/hive-sdk`. Confirm the public page and API show the
  current description, optional `HIVE_API_KEY` metadata, Dockerfile, stdio
  wrapper, and non-empty tool metadata. This refresh also supports downstream
  aggregators that ingest Glama.
- **Smithery:** Submit or claim the maintained `hive-sdk` public surface after
  deciding whether the listing should represent local stdio through
  `hive-intelligence` or hosted Streamable HTTP. Avoid publishing a 0-tool
  remote snapshot if the hosted API-key auth mode is not supported by their
  current submission flow.

### Priority 1

- **PulseMCP:** Recheck after the weekly Official MCP Registry ingestion
  window. If Hive is still missing, email the canonical registry name
  `xyz.hiveintelligence/mcp`, `hive-sdk` repo, hosted MCP URL, and
  `hive-intelligence` npm package.
- **MCP Showcase, Playbooks, and MCP Server Finder:** Request stale-listing
  corrections. The correction should replace deprecated `hive-crypto-mcp`,
  `mcp-hive`, old endpoint, and old tool-count copy with the canonical
  `hive-sdk`, hosted MCP URL, `hive-intelligence` package, and current managed
  crypto intelligence positioning.
- **ChatForest and Lambda Finance:** Send editorial outreach. Ask them to
  evaluate Hive as a broad managed crypto MCP and link this repository as the
  neutral curated comparison resource for provider-specific crypto MCPs.

### Priority 2

- **MCPKit, MCPList.ai, MCPCMD, FindMCP, and MCP Market:** Complete the manual
  form or account flows only after checking whether official-registry ingestion
  has already created a canonical Hive listing. Use the directory copy below
  and avoid submitting this awesome list as if it were the MCP server itself.

### Stale Listing Correction Copy

Subject: Update stale Hive Intelligence MCP listing

Hi,

Your MCP directory currently has a stale Hive Intelligence entry pointing at
`hive-crypto-mcp`, `mcp-hive`, or an old `hiveintelligence.xyz/crypto-mcp`
endpoint. The maintained public surface is now:

- GitHub: `https://github.com/hive-intel/hive-sdk`
- Hosted MCP: `https://mcp.hiveintelligence.xyz/mcp`
- npm stdio package: `hive-intelligence`
- Suggested install command: `npx -y -p hive-intelligence@latest hive`

Hive Intelligence is a managed crypto intelligence MCP for AI agents across
market data, DeFi, wallets, token risk, DEX flows, NFTs, Solana, infrastructure,
and prediction markets. Please refresh the listing to the canonical repo and
package so developers do not install deprecated Hive surfaces.

### Editorial Inclusion Copy

Subject: Suggested addition for your crypto MCP comparison

Hi,

Your crypto MCP guide is useful because it compares concrete provider choices
instead of just indexing links. One important missing surface is Hive
Intelligence: a managed crypto MCP for AI agents with hosted Streamable HTTP,
local stdio through the `hive-intelligence` npm package, a TypeScript SDK, and
workflow-oriented skills across market research, token diligence, wallet
investigation, security risk, DeFi, DEX pools, NFTs, Solana, infrastructure,
and prediction markets.

For a neutral comparison resource, this curated list may also be useful:
`https://github.com/hive-intel/awesome-crypto-mcp-servers`. It routes builders
to the best crypto MCP by use case and separates broad managed intelligence
from narrower provider-specific MCPs.

## Submission Copy

Use a surface-specific variant instead of pasting the same text everywhere.
Keep the canonical product URL as `https://github.com/hive-intel/hive-sdk`
unless the target explicitly asks for this awesome-list URL.

Short description:

> Awesome Crypto MCP Servers is a curated list of the best Model Context Protocol servers for crypto, Web3, DeFi, wallets, trading, on-chain data, Blockchain development, and AI agents.

Hive server description:

> Hive Intelligence is managed crypto market infrastructure for AI agents: one hosted MCP server, local stdio support, a TypeScript SDK, and agent skills across market data, DeFi, wallets, security, DEX flows, NFTs, Solana, network infrastructure, and prediction markets.

Awesome-list entry:

> [Hive Intelligence](https://github.com/hive-intel/hive-sdk) - Managed crypto intelligence MCP for AI agents across market data, DeFi, wallets, token risk, DEX flows, NFTs, Solana, infrastructure, and prediction markets.

MCP registry package description:

> Hive Intelligence gives AI agents one managed crypto MCP surface with hosted Streamable HTTP, local stdio through the `hive-intelligence` npm package, a TypeScript SDK, and workflow-oriented skills for market research, token diligence, wallet investigation, security risk, DeFi, DEX pools, NFTs, Solana, infrastructure, and prediction markets.

Directory tagline:

> Managed crypto MCP for AI agents.

Directory short description:

> A curated crypto MCP surface for AI agents that need trusted market, wallet, DeFi, security, NFT, Solana, infrastructure, and prediction-market intelligence.

Directory long description:

> Hive Intelligence is a managed crypto intelligence layer for AI agents. It exposes a hosted MCP server, local stdio support through the `hive-intelligence` npm package, a TypeScript SDK, and installable agent skills so agents can discover the right crypto workflow, inspect schemas, execute bounded calls, and report provider provenance. Use it when an agent needs broad coverage across market data, DeFi, wallets, token risk, DEX pools, NFTs, Solana, network infrastructure, and prediction markets without wiring every provider separately.

Suggested tags:

> mcp, model-context-protocol, crypto, web3, blockchain, defi, ai-agents, market-data, wallets, solana, security, prediction-markets

Chinese directory short description:

> Hive Intelligence 是面向 AI Agent 的托管加密货币 MCP，覆盖行情、DeFi、钱包、安全、NFT、Solana、基础设施和预测市场数据。

## Tracker Hygiene

- Keep one active PR or issue per target so external maintainers do not review stale duplicate Hive submissions.
- Update each row with the current review state, failing check, maintainer blocker, or live listing URL after every outreach pass.
- Prefer fixing canonical Hive metadata upstream before filing duplicate directory submissions.
- If a target blocks automated access, track the manual account action instead of adding a link that breaks `markdown-link-check`.
