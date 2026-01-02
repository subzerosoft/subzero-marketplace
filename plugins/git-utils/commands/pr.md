---
description: Create a GitHub pull request with auto-generated description
---

# Create Pull Request Command

Create a GitHub pull request with an automatically generated description:

1. Get the current branch and compare against main/master
2. Analyze all commits in the branch
3. Generate a PR title from the branch name or commits
4. Create a comprehensive description including:
   - Summary of changes
   - List of modified files
   - Testing notes
   - Any breaking changes
5. Use `gh pr create` to open the PR
