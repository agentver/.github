# Documentation
Agentver is an open-source platform for managing AI agent skills. Git-native version control for skills, plugins, configs, scripts, and prompts across 43+ agents.

## What is Agentver?
Think of Agentver as version control for AI agents. Instead of managing code repositories, you manage agent skills — the instructions, configurations, and workflows that make AI coding agents useful. The entire platform is open source. Everything is stored in Git, versioned with semantic tags, and secured with cryptographic integrity checks. You can self-host the platform or use our hosted cloud.

### Key concepts

**Skills**
  - Agent instructions and workflows (SKILL.md entry point)

**Agent Configs**
  - Configuration overrides for specific agents (.cursorrules, CLAUDE.md, etc.)

**Plugins**
  - External tools and MCP integrations

**Scripts**
  - Executable automation (Node.js, Bun, Python, Bash)

**Prompts**
 - Reusable prompt templates with variable substitution

### Quick start

```terminal
$ bun add -g @agentver/cli
$ agentver install github.com/acme/deploy-checker
$ agentver list
```
