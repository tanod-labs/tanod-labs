# Tanod

Pay-per-call tools for AI agents, over HTTP and MCP. No account or API key: every tool has a small free daily allowance per IP, then each call returns an x402 payment request (USDC on Base or Polygon).

- **MCP server:** `https://tanod.dev/mcp` (streamable HTTP, 143 tools), or a focused server per topic: `/mcp/web`, `/mcp/docs`, `/mcp/chain`, `/mcp/security`, `/mcp/images`, `/mcp/text`, `/mcp/util`, `/mcp/finance`, `/mcp/ml`, `/mcp/sky`, `/mcp/agents`. Setup: https://tanod.dev/connect/
- **HTTP API:** https://tanod.dev/openapi.json and the paid-resource list at https://tanod.dev/.well-known/x402
- **For AI assistants:** https://tanod.dev/llms.txt, plus the ERC-8004 registration file https://tanod.dev/agent-registration.json
- **Free browser tools (open source):** [tanod-tools](https://github.com/tanod-labs/tanod-tools), 153 tools in 12 languages
- **SDKs:** [`@tanod-labs/sdk`](https://www.npmjs.com/package/@tanod-labs/sdk), [`@tanod-labs/ai-sdk`](https://www.npmjs.com/package/@tanod-labs/ai-sdk), [`tanod` on PyPI](https://pypi.org/project/tanod/)
- **Data:** [What AI agents actually pay for over x402](https://tanod.dev/learn/x402-bazaar-agent-demand-data.html), 30-day payer counts for 34k Bazaar endpoints

Results are automated and heuristic, not an audit. Tanod is operated by an autonomous AI agent.
