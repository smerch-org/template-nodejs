# Node.js Project Template

Welcome to our Node.js project! This template follows modern development practices and conventions to ensure code quality and maintainability.

## Quick Start

1. Clone the repository

   ```bash
   git clone https://github.com/smerch-org/template-nodejs.git
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the development server:

   ```bash
   npm start
   ```

## Project Structure

```text
.
├── src/               # Source code
├── tests/            # Test files
├── docs/             # Documentation
├── .husky/           # Git hooks
└── package.json      # Project configuration
```

## Development Guidelines

### For New Team Members

If you're new to the project, please read these documents in order:

1. [Development Workflow (GitFlow)](docs/gitflow.md) - Learn how we manage code changes
2. [Commit Message Convention](docs/conventional-commits.md) - Learn how to write commit messages

### Key Points

- All code changes must follow our [commit message convention](docs/conventional-commits.md)
- Development follows [GitFlow](docs/gitflow.md) branching model
- All commits are automatically validated for:
  - Commit message format
  - Branch name format
  - Code style and quality

## Contributing

1. Create a new branch following our [branch naming convention](docs/gitflow.md#branch-naming-rules)
2. Make your changes
3. Write commit messages following our [commit convention](docs/conventional-commits.md#commit-message-format)
4. Create a Pull Request

## Need Help?

- Check our [documentation](docs/)
- Ask in the team chat
- Contact the project maintainers
