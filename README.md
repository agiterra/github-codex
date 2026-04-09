# github-codex

Codex CLI plugin for GitHub webhook tools — register PR webhooks via Wire.

## Usage

Install via Codex CLI:

```
codex plugin install agiterra/github-codex
```

## Configuration

| Env var | Default | Description |
|---|---|---|
| `GITHUB_TOKEN` | required | GitHub personal access token |
| `WIRE_URL` | `http://localhost:9800` | Wire broker URL |
| `WIRE_AGENT_ID` | required | Agent identifier (for webhook routing) |

## What it does

Exposes MCP tools for registering and managing GitHub webhooks that route PR and workflow events through The Wire message broker.

## Source

- Tools: [@agiterra/github-tools](https://github.com/agiterra/github-tools)
- Claude Code adapter: [@agiterra/github-claude-code](https://github.com/agiterra/github-claude-code)
