# 60x plugins

Connects Claude Code and Codex to the 60x MCP server. Sign-in is OAuth;
no API key is needed.

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
