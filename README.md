# Subzero Marketplace

A curated marketplace for Claude Code plugins.

## Installation

Add this marketplace to Claude Code:

```bash
/plugin marketplace add subzerosoft/subzero-marketplace
```

## Available Plugins

| Plugin | Description | Commands |
|--------|-------------|----------|
| `code-reviewer` | Automated code review with best practices analysis | `/review` |
| `git-utils` | Git workflow utilities and shortcuts | `/commit`, `/pr` |

## Installing Plugins

Install a plugin from this marketplace:

```bash
/plugin install code-reviewer@subzero-marketplace
/plugin install git-utils@subzero-marketplace
```

## Creating Plugins

Want to contribute a plugin? See the structure in `plugins/` for examples.

Each plugin needs:
- `.claude-plugin/plugin.json` - Plugin manifest
- `commands/` - Slash commands (`.md` files)
- `skills/` - Agent skills (directories with `SKILL.md`)
- `README.md` - Documentation

## Plugin Structure

```
plugins/your-plugin/
├── .claude-plugin/
│   └── plugin.json
├── commands/
│   └── your-command.md
├── skills/
│   └── your-skill/
│       └── SKILL.md
└── README.md
```
