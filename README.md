# 60x plugins

Connects Claude Code and Codex to the 60x MCP server. Sign-in is OAuth;
no API key is needed.

Logo and composer assets retain the original colours, with separate light and dark theme files.

**Claude Code**

```bash
claude plugin marketplace add 60xAI/ai-brain-plugins
claude plugin install 60x@60x
claude mcp login plugin:60x:60x
```

**Codex**

```bash
codex plugin marketplace add 60xAI/ai-brain-plugins
codex plugin add 60x@60x
codex mcp login 60x
```

Claude (web/desktop) and ChatGPT instructions: https://aibrain.60x.ai/profile/mcp-connections

## Marketplace validation

For each client, check that the marketplace and plugin JSON parse and that
local package and asset paths resolve. Each validation check must pass on its
own and in any order or shard. Declare the fixtures and files each check needs,
including generated files it uses indirectly. Reuse existing fixtures and
helpers where available. When adding or changing a dependency, run the
affected check by itself from a clean checkout.
