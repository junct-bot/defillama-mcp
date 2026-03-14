# Defillama MCP Server

MCP server for Defillama. Agent-ready API for Defillama.

Hosted at [defillama.mcp.junct.dev/mcp](https://defillama.mcp.junct.dev/mcp). Free to use. No auth. No API key required.

Part of [Junct](https://junct.dev) — the agent-readiness layer for the crypto stack.

## Quick Start

Add to your MCP client config (Claude Desktop, Cursor, Windsurf):

```json
{
  "mcpServers": {
    "defillama": {
      "url": "https://defillama.mcp.junct.dev/mcp",
      "transport": "streamable-http"
    }
  }
}
```

## About

This MCP server is **deterministically generated** from the Defillama API specification. Every tool maps 1:1 to a real API endpoint — no hallucinated endpoints, no phantom tools.

- **Protocol:** Defillama
- **Endpoint:** `https://defillama.mcp.junct.dev/mcp`
- **Transport:** Streamable HTTP
- **Auth:** None required
- **Documentation:** [defillama.mcp.junct.dev/llms.txt](https://defillama.mcp.junct.dev/llms.txt)
- **Server card:** [defillama.mcp.junct.dev/.well-known/mcp/server.json](https://defillama.mcp.junct.dev/.well-known/mcp/server.json)

## Links

- [Junct Dashboard](https://junct.dev/servers/defillama)
- [llms.txt](https://defillama.mcp.junct.dev/llms.txt)
- [agents.md](https://defillama.mcp.junct.dev/agents.md)
- [OpenAPI spec](https://defillama.mcp.junct.dev/openapi.json)

## Keywords

Defillama, MCP server, DeFi, AI agent, agent-ready API, crypto tools, Model Context Protocol, hosted MCP
