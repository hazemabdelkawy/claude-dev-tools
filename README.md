# claude-dev-tools

Claude Code plugin marketplace with development productivity tools.

## Plugins

### dev-assistant
Development analytics and session management plugin.

**Install:**
```bash
claude plugin marketplace add https://github.com/hazemabdelkawy/claude-dev-tools
claude plugin install dev-assistant@claude-dev-tools
```

Or configure in your project's `.claude/settings.json`:
```json
{
  "extraKnownMarketplaces": {
    "claude-dev-tools": {
      "source": {
        "source": "github",
        "repo": "hazemabdelkawy/claude-dev-tools"
      }
    }
  },
  "enabledPlugins": {
    "dev-assistant@claude-dev-tools": true
  }
}
```
