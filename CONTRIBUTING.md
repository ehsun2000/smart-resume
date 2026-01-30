# Contributing Guide

## How to Contribute

1. Create an issue first
2. Fork this repository
3. Create a branch from the issue
4. Make your changes
5. Submit a pull request

## Branch Naming Convention

Format: `type/issue-number-short-description`

**Types:**
- `feature/` - New features (e.g., `feature/123-user-login`)
- `bugfix/` - Bug fixes (e.g., `bugfix/456-fix-null-pointer`)
- `hotfix/` - Urgent production fixes (e.g., `hotfix/789-security-patch`)
- `refactor/` - Code refactoring (e.g., `refactor/101-optimize-query`)
- `docs/` - Documentation only (e.g., `docs/202-update-readme`)

**Rules:**
- Always include issue number
- Use lowercase and hyphens
- Keep description short and clear

## Commit Message Convention

Format: `<type>(<scope>): <subject>`

**Types:**
- `feat` - New feature
- `fix` - Bug fix
- `docs` - Documentation changes
- `style` - Code style changes (formatting, no logic change)
- `refactor` - Code refactoring
- `test` - Adding or updating tests
- `chore` - Build process or auxiliary tool changes

**Examples:**
- `feat(auth): add JWT authentication`
- `fix(user): resolve null pointer exception in getUserById`
- `docs(readme): update installation instructions`
- `refactor(service): simplify error handling logic`

**Rules:**
- Use present tense ("add" not "added")
- Don't capitalize first letter
- No period at the end
- Keep subject line under 50 characters
- Add detailed description in commit body if needed

## Code Style

- Follow Java conventions
- Run `./mvnw verify` before commit
