# 21st — Codex plugin

Self-hosted Codex plugin that wires the remote 21st MCP server and 21st.dev skills so the agent can search, install, generate, and publish UI components from the terminal or via MCP.

## Install

```bash
export API_KEY_21ST="sk_..."
codex plugin marketplace add 21st-dev/codex-plugin
```

Then open `/plugins` in Codex and install `21st`.

## What's inside

- **MCP server `21st`** — remote endpoint `https://21st.dev/api/mcp` (search, get_component, generate, themes, registry, etc.)
- **Skills** — `21st-cli-use`, `21st-ai`, `21st-registry`, `21st-design-sync`, plus Build / Explore / Review workflows

## Auth

```toml
[mcp_servers.21st]
url = "https://21st.dev/api/mcp"
bearer_token_env_var = "API_KEY_21ST"
```

## Upstream

- Repository: https://github.com/21st-dev/codex-plugin
- License: Apache-2.0
