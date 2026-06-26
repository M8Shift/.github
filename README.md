# M8Shift

M8Shift builds local-first coordination tools for AI agents working on the same repository.

The core project is a cooperative mutex for AI agents: one shared file, one pen, one turn journal. It lets agents such as Claude, Codex, Gemini, Vibe, or custom assistants take turns, hand off context, review each other’s work, and keep a durable trace of decisions without a central runtime, daemon, server, API key, or vendor lock-in.

M8Shift is designed for maintainers who want several AI perspectives in the same workflow while keeping human arbitration explicit.

## Core principles

- One writer at a time in the shared repository
- Plain files, readable by humans and versionable with Git
- No network calls, no account, no API key for M8Shift itself
- Agents coordinate through shell commands and shared project files
- Optional companions for worktrees, runtime presence, reports, and automation
- Human-maintained direction, agent-to-agent handoff

## Main project

- [`M8Shift`](https://github.com/M8Shift/M8Shift) — a free and open-source single-file relay for cooperative multi-agent work.
