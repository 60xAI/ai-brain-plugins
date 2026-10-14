# 60x AI Brain plugins

Connects Claude Code and Codex to the 60x AI Brain MCP server. Sign-in is OAuth;
no API key is needed.

**Claude Code**

```bash
claude plugin marketplace add 60xAI/ai-brain-plugins
claude plugin install ai-brain@60x
claude mcp login plugin:ai-brain:ai-brain
```

**Codex**

```bash
codex plugin marketplace add 60xAI/ai-brain-plugins
codex plugin add ai-brain@60x
codex mcp login ai-brain
```

Claude (web/desktop) and ChatGPT instructions: https://aibrain.60x.ai/profile/mcp-connections
