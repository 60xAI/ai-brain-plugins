# 60x AI Brain plugins

Connects Claude Code and Codex to the 60x AI Brain MCP server. Sign-in is OAuth;
no API key is needed.

**Claude Code**

```bash
claude plugin marketplace add 60xAI/ai-brain-plugins
claude plugin install ai-brain@60x
```

Then run `/mcp` in a session and sign in to `ai-brain`.

**Codex**

```bash
codex plugin marketplace add 60xAI/ai-brain-plugins
```

Install AI Brain from `/plugins`, then run `codex mcp login ai-brain`.

Claude (web/desktop) and ChatGPT instructions: https://aibrain.60x.ai/profile/mcp-connections
