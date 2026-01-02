# Code Reviewer Plugin

Automated code review with best practices analysis for Claude Code.

## Features

- `/review` command for on-demand code reviews
- Automatic code review skill that activates when reviewing changes
- Security vulnerability detection
- Performance optimization suggestions

## Installation

```bash
/plugin install code-reviewer@subzero-marketplace
```

## Usage

Run a code review on any file:
```
/review src/main.ts
```

The skill will also automatically activate when you ask Claude to review code changes.
