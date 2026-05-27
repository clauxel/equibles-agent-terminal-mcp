# Equibles Agent Terminal

Ask market filings like an agent-ready finance terminal.

Equibles Agent Terminal is a paid hosted remote MCP for Equibles. It exposes Streamable HTTP tool calls, bearer-token access, public server-card metadata, usage logs, and receipt-oriented JSON for AI agent workflows.

## Public Endpoints

- Website: https://equiblesagent.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605r27
- MCP endpoint: https://equiblesagent.clauxel.com/mcp
- Server card: https://equiblesagent.clauxel.com/server-card.json
- Registry name: `com.clauxel.equiblesagent/equiblesagent-mcp`

## Access

This is a paid hosted remote MCP. Production calls require a bearer token issued from the product website.

```http
Authorization: Bearer <token>
```

Unauthenticated browser visits to `/mcp` return a clear JSON error instead of internal details.

## Tools

- `resolve_equity_entity`
- `fetch_sec_packet`
- `compare_institutional_holders`
- `export_finance_receipt`

## Quick Start

1. Open the website and choose a plan.
2. Create or request an API token.
3. Add the endpoint to an MCP client that supports Streamable HTTP remote servers.
4. Send JSON-RPC requests with the bearer token.

## Useful Links

- Product page: https://equiblesagent.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605r27
- Pricing: https://equiblesagent.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605r27#pricing
- Server card: https://equiblesagent.clauxel.com/server-card.json
- MCP endpoint: https://equiblesagent.clauxel.com/mcp

## Status

This repository is a public documentation and directory-submission reference for the hosted service. It does not contain the private production source code.
