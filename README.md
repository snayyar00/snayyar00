## Sidharth Nayyar

Forward deployed engineer. I build AI agents and the evaluation around them, I work with the people who use them, and I ship the production code. Lately that means voice agents, MCP servers, and agentic pipelines on Anthropic models.

Based in Canada · open to relocating · [sidharthnayyar.com](https://sidharthnayyar.com)

### Recent work

#### **[callcheck](https://github.com/snayyar00/callcheck)**: onboarding a voice AI customer from their past calls

Takes a company's past support calls and answers four questions: what callers want, what an agent can automate first, what that saves, and how callers' experience looks today, so the improvement after go-live can be measured. Tested on held-out public data: it finds the back-office systems an agent needs with 87% recall, and measures response times within 0.21 s on 90% of turns in real phone calls. The README lists where it still fails.

#### **Legal AI: Ares** (2025 to 2026, contract)

Principal Forward Deployed Engineer. Built the agentic core on Anthropic models: chat and tool orchestration, a drafting pipeline, a medical-chronology engine that turns 10,000-page record sets into a timeline, citation grounding that binds every extracted fact to its source page, and per-case cost caps. On calls with the firms, shipping their feedback the same week. Case volume went from 128 to roughly 1,200 across 25 firms.

#### **Accessibility AI: [WebAbility.io](https://webability.io)** (2023 to present)

My own company. An AI widget, a scanning engine, and agents for WCAG 2.2, ADA, Section 508 and EAA. Runs on **1,697 live sites** for **758 customers**, inside React, Vue and AngularJS apps behind other people's CSPs and CDNs, so every release has to be safe in all of them at once.

**[@webability/mcp](https://www.npmjs.com/package/@webability/mcp)** ([source](https://github.com/snayyar00/webability-mcp)) is a hosted MCP server with 15 tools for Cursor, Claude Code and Copilot: scan a URL or HTML, get framework-aware fixes, verify they landed. Live on [Smithery](https://smithery.ai/servers/webability/accessibility).

```bash
npx @webability/mcp
```

Also on npm: [`cli`](https://www.npmjs.com/package/@webability/cli) · [`core`](https://www.npmjs.com/package/@webability/core) · [`eslint-plugin`](https://www.npmjs.com/package/@webability/eslint-plugin) · [`playwright`](https://www.npmjs.com/package/@webability/playwright) · [`jest`](https://www.npmjs.com/package/@webability/jest) · [`cypress`](https://www.npmjs.com/package/@webability/cypress) · [`react-native`](https://www.npmjs.com/package/@webability/react-native) · [`mobile`](https://www.npmjs.com/package/@webability/mobile)

#### **ERP and financial data: ICAO** (Montreal, 2024 to present)

Helped lead a finance and procurement migration from Unit 4 to Oracle Fusion Cloud, from integration approach to cutover. Built the monthly overhead and journal pipeline in Python over the Oracle Fusion warehouse on Azure Synapse, reconciled to the live general ledger.

### Stack

- **AI**: Anthropic tool use and agentic loops · MCP · voice and turn-taking evaluation · retrieval with citation grounding · vision extraction · cost control
- **Languages**: Python · TypeScript · JavaScript · SQL
- **Web**: React · Next.js · Node · Vue · AngularJS
- **Data and cloud**: Azure Synapse · Cloudflare Workers · Azure · AWS · Docker · MySQL · GitHub Actions
- **Testing**: pytest · Jest · Cypress · Playwright

B.Sc. Computer Science, Simon Fraser University · AWS Certified Cloud Practitioner · PMP

**[sidharthnayyar.com](https://sidharthnayyar.com)** · [LinkedIn](https://linkedin.com/in/sidharth-nayyar-a13515171) · sidharth15nayyar@gmail.com
