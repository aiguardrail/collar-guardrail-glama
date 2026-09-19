# Collar Guardrail — Glama Verification

Public verification repository for the Collar Guardrail MCP server
listing on [Glama](https://glama.ai).

The server implementation is proprietary and hosted at the endpoint
below. This repository contains only the public manifest required for
directory verification.

## Hosted MCP Endpoint

| Field | Value |
| :--- | :--- |
| **URL** | `https://api.collarguardrail.com/mcp-http/mcp` |
| **Transport** | Streamable HTTP |
| **Protocol** | MCP 2025-06-18 |
| **Authentication** | None required (fixed Tier 1) |

## Available Tools

- `evaluate_trade` — pre-trade risk check (allow / warn / deny)
- `check_token_safety` — honeypot detection (auto-DENY on danger)
- `simulate_balance` — ERC-20 balance simulation
- `get_supported_assets` — official asset registry
- `verify_audit_trail` — hash-chain verification

## Discovery Files

- MCP Server Card: https://api.collarguardrail.com/.well-known/mcp/server-card.json
- Agent Card: https://api.collarguardrail.com/.well-known/agent-card.json
- x402: https://api.collarguardrail.com/.well-known/x402.json

## Documentation

- Agent docs: https://collarguardrail.com/agent-docs.html
- Terminal UI: https://collarguardrail.com

## Registry Listings

- Official MCP Registry: `io.github.aiguardrail/backend`
- PyPI: [langchain-collar](https://pypi.org/project/langchain-collar/)

## License

MIT — see [LICENSE](./LICENSE).
