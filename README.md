## Sidharth Nayyar

Forward deployed engineer. I work with customers directly and ship the production code that gets them live.

**Now** — building [WebAbility.io](https://webability.io), an accessibility platform: an AI widget, a scanning engine, and agents for WCAG 2.2 / ADA / Section 508 / EAA. It runs on **1,697 live sites** for **758 customers**, inside codebases I do not control.

**Before** — Principal Forward Deployed Engineer at Ares, a legal-AI product built on Claude. I was in the room with **25 law firms**, scoping the ask and shipping it that week. Live case volume grew from 128 to ~1,200 over the contract while I owned the agent loop, the evaluation harness, and per-case cost controls.

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

Taking a vague customer problem, finding the smallest version that is genuinely useful, and having it in production that week. Agent and tool design — deciding what becomes a tool, and writing the description well enough that the model picks the right one. Making software behave in environments I don't own.

**[sidharthnayyar.com](https://sidharthnayyar.com)** · [LinkedIn](https://linkedin.com/in/sidharth-nayyar-a13515171) · sidharth15nayyar@gmail.com
