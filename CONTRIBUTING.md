# Contributing to Bitstack Analytics

We love your input! We want to make contributing to Bitstack Analytics as easy and transparent as possible, whether it's:

- Reporting a bug
- Discussing the current state of the code
- Submitting a fix
- Proposing new features
- Becoming a maintainer

## Development Process

We use GitHub to host code, to track issues and feature requests, as well as accept pull requests.

### Pull Requests

1. Fork the repo and create your branch from `master`
2. If you've added code that should be tested, add tests
3. If you've changed APIs, update the documentation
4. Ensure the test suite passes
5. Make sure your code lints
6. Issue that pull request!

### Development Setup

1. Install Clarity CLI

```bash
npm install -g @stacks/cli
```

2. Clone your fork

```bash
git clone https://github.com/your-username/analytics-contract.git
```

3. Set up development environment

```bash
cd analytics-contract
npm install
```

4. Run tests

```bash
clarity-cli test ./tests
```

### Coding Style

- Use 2 spaces for indentation
- Keep lines under 80 characters
- Comment complex logic
- Follow Clarity best practices

## Bug Reports

We use GitHub issues to track public bugs. Report a bug by opening a new issue.

### Write bug reports with detail:

1. Summary of the problem
2. Steps to reproduce
3. What you expected would happen
4. What actually happens
5. Notes (possibly including why you think this might be happening)

## Feature Requests

We use GitHub issues to track feature requests. When proposing a feature:

1. Explain in detail how it would work
2. Keep the scope as narrow as possible
3. Remember that this is a volunteer-driven project

## Documentation

Documentation improvements are always welcome. Please follow these guidelines:

1. Use Markdown format
2. Include code examples where appropriate
3. Follow the existing documentation structure
4. Test all code examples


## License

By contributing, you agree that your contributions will be licensed under its MIT License.
