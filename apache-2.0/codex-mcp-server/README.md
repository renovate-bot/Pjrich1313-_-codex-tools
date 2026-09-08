# Codex MCP Server

An open-source Model Context Protocol server that bridges MCP clients (Claude Desktop, Cursor, etc.) with the Codex CLI running on your machine.

Run coding tasks, manage conversation threads, fork sessions, and browse historical rolls — all through standard MCP tooling.

## Prerequisites

- **Node.js 22+** (required for native SQLite bindings)
- **Codex CLI** installed and authenticated — verify with `codex doctor`

## Quick Start

```bash
git clone https://github.com/4dhxm/codex-mcp-server.git
cd codex-mcp-server
npm install
npm run build
```

## Tools

| Tool | Description |
|------|-------------|
| `codex_task` / `codex_run` | Run a coding task in a new thread |
| `codex_start_thread` | Initialize a thread without running a turn |
| `codex_run_turn` / `codex_continue` | Send a follow-up prompt to an existing thread |
| `codex_list_threads` | List active/archived threads from local SQLite |
| `codex_get_thread` | Get metadata and conversation history |
| `codex_fork_thread` | Clone a thread's history into a new session |
| `codex_archive_thread` | Archive a thread |
| `codex_unarchive_thread` | Unarchive a thread |
| `codex_interrupt` / `codex_interrupt_turn` | Abort a running turn |

## Upstream

- Repository: https://github.com/4dhxm/codex-mcp-server
- License: Apache-2.0
