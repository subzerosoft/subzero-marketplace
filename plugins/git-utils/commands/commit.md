---
description: Create a well-formatted git commit with conventional commit message
---

# Smart Commit Command

Create a git commit with a properly formatted conventional commit message:

1. Analyze staged changes using `git diff --staged`
2. Determine the appropriate commit type:
   - `feat`: New feature
   - `fix`: Bug fix
   - `docs`: Documentation changes
   - `style`: Code style/formatting
   - `refactor`: Code refactoring
   - `test`: Adding or updating tests
   - `chore`: Maintenance tasks
3. Generate a concise, descriptive commit message
4. Include scope if changes are localized to a specific area
5. Add breaking change footer if applicable

Format: `type(scope): description`
