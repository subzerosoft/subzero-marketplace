---
name: code-reviewer
description: Automatically reviews code changes for quality, security, and best practices when the user commits or modifies files
allowed-tools: Read, Grep, Glob
---

# Code Review Skill

When reviewing code, apply these standards:

## Code Quality
- Functions should be small and focused (single responsibility)
- Variable names should be descriptive and consistent
- Avoid deep nesting (max 3 levels)
- DRY - Don't Repeat Yourself

## Security Checks
- No hardcoded secrets or credentials
- Proper input validation and sanitization
- Safe handling of user data
- Secure authentication patterns

## Performance
- Avoid N+1 queries
- Efficient data structures
- Proper async/await usage
- Resource cleanup (close connections, etc.)

## Language-Specific
- Follow language idioms and conventions
- Use appropriate typing where available
- Proper error handling patterns
