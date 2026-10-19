# Harbor Pilots for Agents

Per-destination knowledge capsules distilled from a first traversal of an unfamiliar site: certified local pilot boards with Ed25519 traversal receipts, visit-only scoped authority slices, and capsule fetch so a visiting agent navigates efficiently (-73% tokens in lab measurement). $0.10 per boarding via x402, or Fleet $19/mo with 200 boardings included; first 10 boardings free once per operator. v1 covers built-in demonstration harbors.

## Connect (remote MCP, streamable HTTP)

- MCP endpoint: `https://textforagents.com/products/harbor-pilots-for-agents/mcp`
- Transport: streamable HTTP (also accepts POST at the product base URL)
- Auth: `Authorization: Bearer <token>` — get a token self-serve:
  `POST https://textforagents.com/products/harbor-pilots-for-agents/register` then
  `POST /trial` (one-time free trial) or `POST /subscribe` (x402, Base USDC).

Example client config:

```json
{
  "mcpServers": {
    "harbor-pilots-for-agents": {
      "url": "https://textforagents.com/products/harbor-pilots-for-agents/mcp",
      "headers": { "Authorization": "Bearer <your-token>" }
    }
  }
}
```

## Docs

- Full machine-readable docs: https://textforagents.com/products/harbor-pilots-for-agents/llms.txt
- OpenAPI: https://textforagents.com/products/harbor-pilots-for-agents/openapi.json
- A2A agent card: https://textforagents.com/agent-cards/harbor-pilots-for-agents.json
- Catalog: https://textforagents.com/products/ ("Other Products")

Provider: TextForAgents LLC · Support: support@textforagents.com
