# Equibles Agent Terminal

Equibles Agent Terminal is a hosted remote MCP for Equibles.

This repository is a public documentation project for Equibles Agent Terminal. Its structure follows the public documentation pattern used by [MiroFish](https://github.com/clauxel/MiroFish): a short front door, a clear reading order, practical guides, reference pages, and a public-safe boundary.

## Start Here

- Website: https://equiblesagent.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=equiblesagent_public_docs&utm_content=readme_home
- Pricing: https://equiblesagent.clauxel.com/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=equiblesagent_public_docs&utm_content=readme_pricing
- Checkout: https://equiblesagent.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=equiblesagent_public_docs&utm_content=readme_checkout
- Support: support@aigeamy.com

## Remote MCP

- Endpoint: https://equiblesagent.clauxel.com/mcp
- Server card: https://equiblesagent.clauxel.com/server-card.json
- Registry name: `com.clauxel.equiblesagent/equiblesagent-mcp`
- Tools: `resolve_equity_entity`, `fetch_sec_packet`, `compare_institutional_holders`, `export_finance_receipt`

## Reading Order

1. [Quickstart](guide/quickstart.md)
2. [Evaluation guide](guide/evaluation.md)
3. [Checkout and pricing](guide/checkout-and-pricing.md)
4. [Workflow notes](features/workflow.md)
5. [Security model](features/security-model.md)
6. [Public link reference](reference/links.md)

## Audience

AI product teams, operations leads, workflow owners, and technical evaluators.

## Capabilities

- Streamable HTTP MCP endpoint
- Bearer-token access for production calls
- Structured tool-call output
- Receipt-oriented evidence export
- Public server card and registry metadata
- MCP tool: resolve_equity_entity
- MCP tool: fetch_sec_packet
- MCP tool: compare_institutional_holders
- MCP tool: export_finance_receipt

## Public-Safe Boundary

This repository contains documentation only. It does not contain production source code, credentials, payment configuration, Cloudflare configuration, customer records, private analytics, or local machine paths.
