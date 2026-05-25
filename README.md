# Storm Code

Storm Code is a premium AI coding plugin for VS Code built for real development work inside the editor. It helps you plan, write, fix, explain, and ship code without leaving your workspace.

Website: https://standaloneaistorm.com  
Public GitHub: https://github.com/adamgold1/Storm_Code.-PUBLIC  
Releases: https://github.com/adamgold1/Storm_Code.-PUBLIC/releases  
Email: standaloneaistorm.com@gmail.com

<p align="center">
  <img src="src/assets/icons/storm-dark.png" width="128" height="128" alt="Storm Code logo" />
</p>

## What Storm Code Does

- Generates code from natural language instructions.
- Explains selected code and project structure.
- Fixes bugs and improves existing code.
- Helps generate terminal commands and explain terminal output.
- Creates commit messages from real workspace context.
- Works directly inside VS Code as a full AI coding surface.
- Supports multiple model providers and MCP servers.
- Adds Ghost Mode suggested edits for fast inline workflows.

## Storm Agent

Storm Agent is the parallel session system inside Storm Code. It lets you run multiple AI sessions at the same time, each with its own provider, model, tools, state, and optional isolated workspace.

Core capabilities:

- Parallel AI coding sessions.
- Independent session state and provider routing.
- Optional git worktree isolation for risky or separate tasks.
- Session actions: spawn, list, status, stop, and finish.
- Batch tool execution for search, reads, and terminal work.
- Coordinated multi-edit workflows inside a file.
- Persistent session restore after reconnects.

## LocalHub Integration

Storm Code includes a LocalHub-aware commit flow built for grouped code changes and cleaner version control handoff.

- Reads selected pending changes from LocalHub.
- Understands file context and workspace context.
- Generates focused commit messages from the real change set.
- Preserves existing LocalHub summaries when they already exist.
- Falls back safely when LocalHub context is unavailable.

## Voice Input And Speaker Runtime

Storm Code includes local voice tooling for hands-free workflows:

- Microphone input with the local Python runtime.
- Whisper speech-to-text using `faster-whisper` and CTranslate2.
- Energy-based speech detection.
- Background transcription workers.
- Multilingual text-to-speech playback.
- Voice selection, speed control, and cleanup for more natural output.

## MCP And Skills

Storm Code supports MCP servers and reusable Skills:

- Project MCP config through `.stormcode/mcp.json`.
- Compatibility reads for older MCP config paths.
- MCP marketplace with local fallback support.
- Skill discovery for reusable instruction packs.
- Provider-aware tool usage inside AI workflows.

## Main Commands

Storm Code contributes editor, terminal, SCM, and agent commands including:

- `Storm Code: Explain Code`
- `Storm Code: Fix Code`
- `Storm Code: Improve Code`
- `Storm Code: Generate Terminal Command`
- `Generate Commit Message with Storm`
- `Open Agent Manager`
- `Open Storm Agent`
- `Generate Suggested Edits`
- `Apply Current Suggested Edit`
- `Apply All Suggested Edits`

## Get Storm Code

Use the official website or the public release page:

- https://standaloneaistorm.com
- https://github.com/adamgold1/Storm_Code.-PUBLIC/releases

After installation, reload VS Code and open Storm Code from the activity bar.
