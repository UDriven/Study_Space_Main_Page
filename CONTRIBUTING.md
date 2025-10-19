# Contributing to UDriven Study Space

Thank you for your interest in contributing to UDriven Study Space! We're excited to have you on board. This document will guide you through the contribution process.

## 📋 Table of Contents

- [Code of Conduct](#-code-of-conduct)
- [Getting Started](#-getting-started)
- [How to Contribute](#-how-to-contribute)
- [Development Workflow](#-development-workflow)
- [Pull Request Process](#-pull-request-process)
- [Code Style Guide](#-code-style-guide)
- [Report Bugs](#-report-bugs)
- [Feature Requests](#-feature-requests)
- [Community](#-community)

## ✨ Code of Conduct

This project adheres to the [Contributor Covenant Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code.

## 🚀 Getting Started

1. **Fork** the repository on GitHub
2. **Clone** your forked repository
   ```bash
   git clone https://github.com/your-username/Study_Space_Main_Page.git
   ```
3. Create a **new branch** for your feature or bugfix
   ```bash
   git checkout -b feature/your-feature-name
   # or
   git checkout -b bugfix/issue-number-short-description
   ```

## 💡 How to Contribute

### Report Bugs
- Check if the bug has already been reported in the [Issues](https://github.com/UDriven/Study_Space_Main_Page/issues) section
- If not, create a new issue with a clear title and description
- Include steps to reproduce the issue and expected vs actual behavior

### Suggest Enhancements
- Open an issue with the "enhancement" label
- Clearly describe the feature and why it would be useful
- Include any relevant screenshots or mockups

### Submit Code Changes
1. Follow the [Development Workflow](#-development-workflow)
2. Ensure your code follows our [Code Style Guide](#-code-style-guide)
3. Submit a Pull Request with a clear description of your changes

## 🔄 Development Workflow

1. **Sync** your fork with the main repository
   ```bash
   git remote add upstream https://github.com/UDriven/Study_Space_Main_Page.git
   git fetch upstream
   git checkout main
   git merge upstream/main
   ```

2. **Create a feature branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```

3. **Make your changes** and commit them with a clear message
   ```bash
   git add .
   git commit -m "feat: add new feature"
   ```

4. **Push** your changes to your fork
   ```bash
   git push origin feature/your-feature-name
   ```

## 🔍 Pull Request Process

1. Ensure your code is well-documented and follows the style guide
2. Update the README.md if necessary
3. Run tests if available (coming soon)
4. Submit a Pull Request to the `main` branch
5. Ensure all CI checks pass
6. Address any code review feedback
7. Once approved, your PR will be merged

## 🎨 Code Style Guide

### HTML/CSS
- Use semantic HTML5 elements
- Follow BEM naming convention for CSS classes
- Use Tailwind CSS utility classes when possible
- Keep CSS specificity low

### JavaScript
- Use ES6+ syntax
- Use meaningful variable and function names
- Add JSDoc comments for functions
- Follow the existing code style

### Git Commit Messages
- Use the conventional commits format:
  - `feat:` for new features
  - `fix:` for bug fixes
  - `docs:` for documentation changes
  - `style:` for formatting changes
  - `refactor:` for code changes that neither fix bugs nor add features
  - `perf:` for performance improvements
  - `test:` for adding or modifying tests
  - `chore:` for maintenance tasks

## 🐛 Report Bugs

When reporting bugs, please include:
1. A clear title and description
2. Steps to reproduce
3. Expected vs actual behavior
4. Screenshots if applicable
5. Browser/OS version

## ✨ Feature Requests

We welcome feature requests! Please:
1. Check if a similar feature request already exists
2. Explain why this feature would be valuable
3. Include any relevant examples or mockups

## 🌍 Community

- Join our [Discord/Slack community]() (link to be added)
- Follow us on [Twitter]() (link to be added)
- Check out our [blog]() (link to be added) for updates

## 🙏 Thank You!

Your contributions help make UDriven Study Space better for everyone. We appreciate your time and effort!
