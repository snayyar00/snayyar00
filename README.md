## Sidharth Nayyar

Forward deployed engineer. I work with the people who use the software, and I ship the production code. Most of what I do sits in one of three places: **AI agents and tool design**, **enterprise data and ERP**, or **web platforms that run inside codebases I don't own**.

Based in Canada · open to relocating · [sidharthnayyar.com](https://sidharthnayyar.com)

### What I've been working on

#### **ERP and financial data — ICAO** (Montreal, 2024 – present)

Helped lead a finance and procurement migration from Unit 4 to Oracle Fusion Cloud: integration approach, data migration, testing, cutover, hypercare. Built the monthly overhead and journal pipeline in Python over the Oracle Fusion warehouse on Azure Synapse — account mapping, journal generation, reconciliation to the live general ledger. Executive dashboards with row-level security, and an Azure Function service for project risk forecasting.

#### **Legal AI — Ares** (2025 – 2026, contract)

Principal Forward Deployed Engineer. Built the agentic core on Anthropic models: chat and tool orchestration, a drafting pipeline, a medical-chronology engine that turns 10,000-page record sets into a timeline, citation grounding that binds every extracted fact to its source page, and per-case cost caps. On calls with the firms, shipping their feedback the same week. Case volume went from 128 to roughly 1,200 across 25 firms.

#### **Accessibility platform — [WebAbility.io](https://webability.io)** (2023 – present)

My own company. An AI widget, a scanning engine, and agents for WCAG 2.2 / ADA / Section 508 / EAA. Runs on **1,697 live sites** for **758 customers** — React, Vue and AngularJS, behind other people's CSPs and CDNs, so every release has to be safe in all of them at once.

### Published packages

**[@webability/mcp](https://www.npmjs.com/package/@webability/mcp)** — a hosted MCP server, 15 tools, for Cursor / Claude Code / Copilot. Scan a URL or HTML, get framework-aware fixes, verify they landed.
Live on Smithery: **[smithery.ai/servers/webability/accessibility](https://smithery.ai/servers/webability/accessibility)**

```bash
npx @webability/mcp
```

The rest, all on npm:

| Package | What it does |
|---|---|
| [`@webability/cli`](https://www.npmjs.com/package/@webability/cli) | Scan and fix from the terminal or CI |
| [`@webability/core`](https://www.npmjs.com/package/@webability/core) | The detection engine |
| [`@webability/eslint-plugin`](https://www.npmjs.com/package/@webability/eslint-plugin) | Catch issues at lint time |
| [`@webability/playwright`](https://www.npmjs.com/package/@webability/playwright) · [`jest`](https://www.npmjs.com/package/@webability/jest) · [`cypress`](https://www.npmjs.com/package/@webability/cypress) | Assert accessibility in your existing tests |
| [`@webability/react-native`](https://www.npmjs.com/package/@webability/react-native) · [`mobile`](https://www.npmjs.com/package/@webability/mobile) | The same checks on mobile |

### Stack

- **Languages** — Python · TypeScript · JavaScript · SQL · PowerShell
- **Web** — React · Next.js · Node · Vue · AngularJS
- **AI** — Anthropic tool use and agentic loops · MCP · retrieval with citation grounding · vision extraction · cost control
- **Data & cloud** — Azure Synapse · Cloudflare Workers · Azure · AWS · Docker · MySQL · GitHub Actions
- **Enterprise** — Oracle Fusion Cloud ERP · Power Apps · Power Automate · Power BI · SharePoint · Jira Cloud Assets
- **Testing** — Jest · Cypress · Playwright · Lighthouse CI

B.Sc. Computer Science, Simon Fraser University · AWS Certified Cloud Practitioner · PMP

**[sidharthnayyar.com](https://sidharthnayyar.com)** · [LinkedIn](https://linkedin.com/in/sidharth-nayyar-a13515171) · sidharth15nayyar@gmail.com
