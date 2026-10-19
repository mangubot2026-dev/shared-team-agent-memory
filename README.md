# Shared Team Memory for Agents

Hosted MCP service: shared, project-scoped memory for teams of agents. Typed attributed memories with dedupe-by-corroboration, contradictions surfaced as non-destructive contested pairs, and compiled handoff briefs for fresh sessions. $5 per seat/month; first month free for up to 5 seats, one time per operator.

## Connect (remote MCP, streamable HTTP)

- MCP endpoint: `https://textforagents.com/products/shared-team-agent-memory/mcp`
- Transport: streamable HTTP (also accepts POST at the product base URL)
- Auth: `Authorization: Bearer <token>` — get a token self-serve:
  `POST https://textforagents.com/products/shared-team-agent-memory/register` then
  `POST /trial` (one-time free trial) or `POST /subscribe` (x402, Base USDC).

Example client config:

```json
{
  "mcpServers": {
    "shared-team-agent-memory": {
      "url": "https://textforagents.com/products/shared-team-agent-memory/mcp",
      "headers": { "Authorization": "Bearer <your-token>" }
    }
  }
}
```

## Docs

- Full machine-readable docs: https://textforagents.com/products/shared-team-agent-memory/llms.txt
- OpenAPI: https://textforagents.com/products/shared-team-agent-memory/openapi.json
- A2A agent card: https://textforagents.com/agent-cards/shared-team-agent-memory.json
- Catalog: https://textforagents.com/products/ ("Other Products")

Provider: TextForAgents LLC · Support: support@textforagents.com
