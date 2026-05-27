# Evaluation Guide

Use this page to evaluate whether Equibles Agent Terminal fits a real workflow.

## What To Test

- Equibles
- Equibles Agent Terminal
- Equibles Agent Terminal documentation
- Equibles Agent Terminal remote MCP
- equiblesagent server card

## Expected Evidence

- Open Equibles Agent Terminal and select the buyer plan.
- Create or request a bearer token from the hosted product.
- Add https://equiblesagent.clauxel.com/mcp to a compatible MCP client.
- Run tools/list, then call resolve_equity_entity with public-safe sample data.
- Save the returned receipt or export for human review.

## Risk Checks

- Do not put API keys, tokens, payment details, private logs, or customer records in public issues.
- Use public-safe sample data for examples and directory submissions.
- Treat generated receipts and scores as reviewer evidence, not as a substitute for accountable human approval.

## Buyer Path

Default plan: team.

- https://equiblesagent.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=equiblesagent_public_docs&utm_content=evaluation_checkout
