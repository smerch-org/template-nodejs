# Conventional Commits Documentation

This project follows the [Conventional Commits](https://www.conventionalcommits.org/) specification for commit messages. This helps maintain a clear and consistent commit history, making it easier to understand the purpose of each change.

## Commit Message Format

Each commit message consists of a **type**, an optional **scope**, and a **description**:

```text
<type>(<scope>): <description>
```

### Types

- **feat**: A new feature
- **fix**: A bug fix
- **docs**: Documentation only changes
- **style**: Changes that do not affect the meaning of the code (white-space, formatting, etc)
- **refactor**: A code change that neither fixes a bug nor adds a feature
- **perf**: A code change that improves performance
- **test**: Adding missing tests or correcting existing tests
- **build**: Changes that affect the build system or external dependencies
- **ci**: Changes to CI configuration files and scripts
- **chore**: Changes to the build process or auxiliary tools and libraries
- **revert**: Reverts a previous commit

### Scopes

The scope is optional and can be anything specifying the place of the commit change. For example:

- `feat(api)`: New API feature
- `fix(ui)`: UI bug fix
- `docs(readme)`: Documentation changes in README

### Description

The description should be:

- Written in the imperative mood ("Add feature" not "Added feature")
- Start with a capital letter
- Not end with a period
- Be concise but descriptive

## Examples

```text
feat(auth): add OAuth2 authentication
fix(api): handle null response from external service
docs(readme): update installation instructions
style: format code according to ESLint rules
refactor(utils): extract common functions into separate module
```

## Validation

Commit messages are automatically validated using [Husky](https://github.com/typicode/husky) and [commitlint](https://github.com/conventional-changelog/commitlint). If your commit message doesn't follow the convention, the commit will be rejected
