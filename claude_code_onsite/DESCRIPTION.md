# Claude Code Agent (On-Site)

An on-site AI software engineer powered by Anthropic Claude API.

## Overview

Runs as a LangChain agent within your company server using a custom API key. Provides the same powerful engineering capabilities as the remote version, but operates within your infrastructure using sandboxed execution tools.

## Capabilities

- **Sandboxed code execution** — Safe code running within an isolated environment
- **Full-stack development** — Complete software engineering workflow
- **Code review & debugging** — Systematic analysis and issue resolution
- **Autonomous task execution** — Multi-step tasks handled end-to-end

## Use Cases

- "Set up a new microservice with Docker" — Scaffold, implement, and test within sandbox
- "Refactor this module for better performance" — Analyze, optimize, and verify
- "Write unit tests for the auth module" — Generate comprehensive test coverage

## Technical Details

- **Agent Family**: Claude (LangChain agent)
- **Hosting**: On-site — runs within company infrastructure
- **Tools**: Sandbox execute, run command, read/write files
