## Sidharth Nayyar

Forward deployed engineer. I work with customers directly and ship the production code that gets them live.

**Now** — building [WebAbility.io](https://webability.io), an accessibility platform: an AI widget, a scanning engine, and agents for WCAG 2.2 / ADA / Section 508 / EAA. It runs on **1,697 live sites** for **758 customers**, inside codebases I do not control.

**Before** — Principal Forward Deployed Engineer at Ares, legal AI on Anthropic models. I built the agentic core: chat and tool orchestration, a drafting pipeline, a medical-chronology engine that turns 10,000-page record sets into a timeline, citation grounding that binds every extracted fact to its source page, and per-case cost caps. On calls with the firms, shipping their feedback the same week. Case volume went from 128 to roughly 1,200 across 25 firms.

### Things you can actually run

**[@webability/mcp](https://www.npmjs.com/package/@webability/mcp)** — a hosted MCP server, 15 tools, for Cursor / Claude Code / Copilot. Scan a URL or HTML, get framework-aware fixes, verify they landed.
Live on Smithery: **[smithery.ai/servers/webability/accessibility](https://smithery.ai/servers/webability/accessibility)**

```bash
npx @webability/mcp
```

The rest of the developer surface, all published:

| Package | What it does |
|---|---|
| [`@webability/cli`](https://www.npmjs.com/package/@webability/cli) | Scan and fix from the terminal or CI |
| [`@webability/core`](https://www.npmjs.com/package/@webability/core) | The detection engine |
| [`@webability/eslint-plugin`](https://www.npmjs.com/package/@webability/eslint-plugin) | Catch issues at lint time |
| [`@webability/playwright`](https://www.npmjs.com/package/@webability/playwright) · [`jest`](https://www.npmjs.com/package/@webability/jest) · [`cypress`](https://www.npmjs.com/package/@webability/cypress) | Assert accessibility in your existing tests |
| [`@webability/react-native`](https://www.npmjs.com/package/@webability/react-native) · [`mobile`](https://www.npmjs.com/package/@webability/mobile) | The same checks on mobile |

### What I'm good at

Agent and tool design — deciding what becomes a tool, and writing the description well enough that the model picks the right one. Shipping into environments I don't own. Working directly with the people who use the thing.

**[sidharthnayyar.com](https://sidharthnayyar.com)** · [LinkedIn](https://linkedin.com/in/sidharth-nayyar-a13515171) · sidharth15nayyar@gmail.com
