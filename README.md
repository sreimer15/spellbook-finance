# SpellBook Finance plugin

SpellBook Finance gives an agent market facts and seller tools for Magic: The Gathering, Pokémon and Riftbound cards.

This repository connects an agent to the SpellBook Finance MCP server at `https://api.spellbook-finance.com/mcp`.
Public research tools answer with no account.
Workspace tools sign in through OAuth 2.1 with PKCE.

Full tool reference: https://spellbook-finance.com/agent/mcp.md

## Install

Perplexity: open Plugins, choose Add custom, and import `https://github.com/sreimer15/spellbook-finance`.

Gemini CLI:

```
gemini extensions install https://github.com/sreimer15/spellbook-finance
```

Claude Code:

```
claude mcp add --transport http spellbook-finance https://api.spellbook-finance.com/mcp
```

Any other MCP client: add a remote Streamable HTTP server with the URL `https://api.spellbook-finance.com/mcp`.

## Try

1. What Magic cards are moving this week?
2. Find me cheap Magic booster boxes that are worth opening.
3. Compare the available price snapshots for Disa the Restless, and tell me what seller, stock, shipping, and checkout details are missing.
4. Help me start a card store.

## Boundaries

SpellBook Finance never buys cards, holds money, or ships anything.
Tools that publish or change marketplace listings are annotated destructive and require a preview first.

## Support

support@spellbook-finance.com, https://spellbook-finance.com/support, https://discord.gg/BbbepYdsJ2

Privacy: https://spellbook-finance.com/privacy
Terms: https://spellbook-finance.com/terms
