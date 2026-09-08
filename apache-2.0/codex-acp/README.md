# ACP adapter for Codex CLI

Use OpenAI Codex from Agent Client Protocol clients.

`codex-acp` is a stdio ACP agent server. It starts the Codex App Server, translates ACP requests into Codex operations, and maps Codex events back into the client.

## Features

- ChatGPT, API key, and client-provided custom gateway authentication.
- Model, reasoning effort, fast mode, approval, and sandbox mode configuration.
- Text prompts, embedded context, images, resource links, and additional workspace directories.
- Shell command, file change, permission request, MCP tool call, terminal output, reasoning, plan, web search, image generation, image view, token usage, and review events.
- Native ACP subagent sessions (after capability negotiation) with separate child histories and root-routed permissions.
- Background terminal tasks with task status and targeted stop support.
- Session-scoped long-running goals through the provider-neutral goal extension.
- Client-provided MCP servers over command-based stdio config and HTTP transport.
- Slash commands: `/status`, `/mcp`, `/skills`, `/goal`, `/review`, `/review-branch`, `/review-commit`, `/compact`, and `/logout`, as well as configured skills.

## Installation

```bash
npx -y @agentclientprotocol/codex-acp
```

Or install globally:

```bash
npm install -g @agentclientprotocol/codex-acp
codex-acp --version
```

## Upstream

- Repository: https://github.com/agentclientprotocol/codex-acp
- License: Apache-2.0
- npm: `@agentclientprotocol/codex-acp`
