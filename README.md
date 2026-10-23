## Hi, I'm Sidharth

Forward deployed engineer. I work with the people who use the software, and I ship the production code.

Based in Canada · open to relocating · [sidharthnayyar.com](https://sidharthnayyar.com) · [LinkedIn](https://linkedin.com/in/sidharth-nayyar-a13515171)

### AI agents in production: Ares, legal AI (2025 to 2026)

Case volume went from 128 to roughly 1,200 across 25 law firms while I ran engineering, on calls and on site with the firms, shipping their feedback the same week.

- **Agentic core.** Tool orchestration, a drafting pipeline, and a medical-chronology engine that turns record sets of up to 10,000 pages into a timeline a paralegal used to spend days on. Per-case cost caps keep a large file from breaking the price.
- **Citation grounding.** Every extracted fact is bound to the page it came from, and the agent abstains instead of citing something it cannot find. A lawyer will not file what they cannot verify.
- **Retrieval.** Moved the retrieval layer across three vector stores, with an A/B harness to compare strategies before switching. Legal research over case law and the web, with grounded citations.
- **Voice intake agent.** Answers personal-injury firms' inbound calls: a 14-step call flow, rules-based lead scoring in under 500 ms to decide a live transfer, and a suite of 50 simulated callers to test it before it touched a real call.
- **Enterprise plumbing.** Connectors into SharePoint, NetDocuments, Box and Dropbox that keep each firm's permissions, and a document pipeline that resumes after failure instead of restarting.

### AI that ships into code I don't own: [WebAbility.io](https://webability.io) (2023 to present)

My own company. Accessibility for **1,697 live sites** and **758 customers**, running inside React, Vue and AngularJS apps behind other people's CSPs and CDNs.

- **Screen-reader agents.** An agent walks a page by its accessibility tree and drives real VoiceOver and NVDA on CI runners, recording what a blind user would hear.
- **Fixes, not reports.** The model layer returns code-level fixes in HTML, JSX and CSS.
- **Speed.** Cut the widget's first-interaction time from 1,393 ms to 174 ms, because it runs on other companies' pages and counts against their Core Web Vitals.
- **Tools for coding agents.** [`@webability/mcp`](https://www.npmjs.com/package/@webability/mcp) is a hosted MCP server with 15 tools: scan a URL or HTML, get framework-aware fixes, verify they landed.

[![npm](https://img.shields.io/npm/dm/@webability/mcp?label=%40webability%2Fmcp&color=2a78d6)](https://www.npmjs.com/package/@webability/mcp)
[![npm](https://img.shields.io/npm/dm/@webability/core?label=%40webability%2Fcore&color=2a78d6)](https://www.npmjs.com/package/@webability/core)
[![npm](https://img.shields.io/npm/dm/@webability/cli?label=%40webability%2Fcli&color=2a78d6)](https://www.npmjs.com/package/@webability/cli)
[![Smithery](https://img.shields.io/badge/Smithery-live-1baf7a)](https://smithery.ai/servers/webability/accessibility)

```bash
npx @webability/mcp
```

Source: [snayyar00/webability-mcp](https://github.com/snayyar00/webability-mcp)

### Enterprise data: ICAO (Montreal, 2024 to present)

Helped lead a finance and procurement migration to Oracle Fusion Cloud, and built the monthly journal pipeline in Python on Azure Synapse, reconciled to the live general ledger.

### Stack

- **AI:** agentic loops and tool use · MCP · RAG with citation grounding · voice agents · evals and simulation · cost control
- **Code:** Python · TypeScript · SQL · React · Next.js · Node · FastAPI
- **Data and infra:** Postgres · vector search · Cloudflare Workers · AWS · Azure · Docker · GitHub Actions

B.Sc. Computer Science, Simon Fraser University · sidharth15nayyar@gmail.com
