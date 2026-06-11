# Agent Instructions

## Mission

Maintain this repository as a public documentation shell for a private market-data dashboard implementation.

## Boundaries

- Do not copy private implementation source code into this repository.
- Do not commit `.env` files, API keys, OAuth tokens, webhook secrets, broker credentials, databases, local watchlists, Discord payloads, trading logs, or generated runtime artifacts.
- Do not include local absolute paths or private machine configuration.
- Keep public wording humble: market-data analytics, financial-data exploration, dashboarding, prototype modeling, and validation discipline.
- Do not describe the private project as a production trading system, autonomous broker, professional quant platform, or institutional-grade engine.

## Public-Safe Update Rules

Before pushing changes:

1. Run a path-only secret scan for credential-shaped content.
2. Confirm all examples use public, mock, or synthetic data.
3. Confirm links point only to public-safe surfaces.
4. Keep implementation repo visibility private.
