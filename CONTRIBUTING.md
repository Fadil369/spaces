# Contributing to GitHub Copilot Spaces Documentation

Thank you for your interest in contributing to this project! This document provides guidelines and instructions for contributing.

## Table of Contents

1. [Code of Conduct](#code-of-conduct)
2. [Getting Started](#getting-started)
3. [How to Contribute](#how-to-contribute)
4. [Development Workflow](#development-workflow)
5. [Style Guidelines](#style-guidelines)
6. [Submitting Changes](#submitting-changes)
7. [Issue Guidelines](#issue-guidelines)

## Code of Conduct

This project adheres to a Code of Conduct that all contributors are expected to follow. Please read [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) before contributing.

## Getting Started

### Prerequisites

- A GitHub account
- Git installed on your local machine
- Familiarity with Markdown (for documentation)
- Understanding of GitHub workflow (issues, pull requests, etc.)

### Setting Up Your Development Environment

1. **Fork the Repository**
   
   Click the "Fork" button at the top right of the repository page.

2. **Clone Your Fork**
   
   ```bash
   git clone https://github.com/YOUR-USERNAME/spaces.git
   cd spaces
   ```

3. **Add Upstream Remote**
   
   ```bash
   git remote add upstream https://github.com/Fadil369/spaces.git
   ```

4. **Verify Remotes**
   
   ```bash
   git remote -v
   ```

## How to Contribute

There are many ways to contribute to this project:

### 1. Documentation Improvements

- Fix typos or grammatical errors
- Clarify confusing sections
- Add missing information
- Update outdated content
- Create new guides or tutorials

### 2. Issue Templates

- Improve existing templates
- Create new templates for different use cases
- Add helpful examples

### 3. Process Documentation

- Enhance project management guidelines
- Share best practices
- Document workflows
- Add case studies or examples

### 4. Copilot Instructions

- Improve Copilot Space instructions
- Add new tips and tricks
- Document common patterns
- Share successful use cases

### 5. Issue Reporting

- Report documentation bugs
- Suggest enhancements
- Ask questions for clarification
- Provide feedback

## Development Workflow

### 1. Find or Create an Issue

- Check existing issues for work to do
- Create a new issue if needed
- Comment on the issue to express interest
- Wait for approval before starting major work

### 2. Create a Branch

Create a descriptive branch for your work:

```bash
git checkout -b docs/improve-copilot-instructions
```

Branch naming conventions:
- `docs/*` - Documentation updates
- `feature/*` - New features or content
- `fix/*` - Bug fixes or corrections
- `enhance/*` - Enhancements to existing content

### 3. Make Your Changes

- Make focused, logical commits
- Write clear commit messages
- Test your changes (validate Markdown, check links)
- Update related documentation

### 4. Keep Your Branch Updated

Regularly sync with the upstream repository:

```bash
git fetch upstream
git rebase upstream/main
```

### 5. Submit a Pull Request

See [Submitting Changes](#submitting-changes) section below.

## Style Guidelines

### Markdown Style

1. **Headers**
   - Use ATX-style headers (`#` syntax)
   - Include a blank line before and after headers
   - Use sentence case for headers

2. **Lists**
   - Use `-` for unordered lists
   - Use `1.` for ordered lists
   - Indent nested lists with 2 or 3 spaces

3. **Code Blocks**
   - Use fenced code blocks with language specification
   - Example: ````markdown ```bash ````

4. **Links**
   - Use descriptive link text
   - Prefer relative links for internal documents
   - Example: `[Contributing Guidelines](CONTRIBUTING.md)`

5. **Emphasis**
   - Use `**bold**` for strong emphasis
   - Use `*italic*` for mild emphasis
   - Use `code` for inline code or commands

### Writing Style

1. **Clarity**
   - Write in clear, simple language
   - Use active voice
   - Be concise but thorough
   - Define technical terms

2. **Structure**
   - Use headings to organize content
   - Include a table of contents for long documents
   - Use bullet points for lists
   - Add examples where helpful

3. **Consistency**
   - Follow existing patterns in the documentation
   - Use consistent terminology
   - Match the tone of existing content

4. **Accessibility**
   - Write for a global audience
   - Avoid idioms and colloquialisms
   - Use inclusive language
   - Provide context for acronyms

### Documentation Standards

1. **README Files**
   - Include a clear project description
   - Add a table of contents
   - Provide quick start instructions
   - Link to detailed documentation

2. **Code Examples**
   - Ensure examples are correct and tested
   - Include explanatory comments
   - Show expected output when relevant
   - Keep examples focused and minimal

3. **Screenshots**
   - Use screenshots sparingly
   - Ensure screenshots are current
   - Provide alt text descriptions
   - Keep file sizes reasonable

## Submitting Changes

### Pull Request Process

1. **Prepare Your PR**
   
   - Ensure your branch is up to date
   - Test your changes
   - Review your own code first
   - Update relevant documentation

2. **Create the Pull Request**
   
   - Go to the repository on GitHub
   - Click "New Pull Request"
   - Select your branch
   - Fill out the PR template completely

3. **PR Title Format**
   
   Use a clear, descriptive title:
   - `docs: improve Copilot instructions clarity`
   - `fix: correct typo in project management guide`
   - `feat: add new issue template for questions`

4. **PR Description**
   
   Include:
   - Summary of changes
   - Related issue numbers (e.g., "Closes #123")
   - Motivation for the changes
   - How to test/verify the changes
   - Screenshots (if applicable)

5. **Request Review**
   
   - Request review from maintainers
   - Be patient and responsive
   - Address feedback constructively

### PR Review Process

- Maintainers will review your PR
- You may be asked to make changes
- Address feedback in new commits
- Once approved, maintainers will merge

### After Merge

- Delete your branch (locally and remotely)
- Update your fork's main branch
- Celebrate your contribution! 🎉

## Issue Guidelines

### Creating Issues

1. **Search First**
   - Check if a similar issue already exists
   - Comment on existing issues instead of creating duplicates

2. **Use Templates**
   - Select the appropriate issue template
   - Fill out all sections completely
   - Provide as much detail as possible

3. **Be Specific**
   - Use a clear, descriptive title
   - Provide context and background
   - Include steps to reproduce (for bugs)
   - Suggest solutions (when possible)

4. **Add Labels**
   - Add appropriate labels
   - Use priority labels when relevant
   - Tag with component/area labels

### Working on Issues

1. **Claim Issues**
   - Comment on the issue to express interest
   - Wait for assignment before starting
   - Ask questions if anything is unclear

2. **Keep Updated**
   - Provide progress updates
   - Ask for help if stuck
   - Communicate if you can't complete the work

3. **Link to Issues**
   - Reference issues in commits: `docs: improve guide (see #123)`
   - Link PRs to issues: `Closes #123`

## Communication

### Where to Ask Questions

- **GitHub Issues**: For bugs, features, and documentation issues
- **Pull Request Comments**: For questions about specific changes
- **Issue Comments**: For general questions about an issue

### Response Times

- We aim to respond to issues within 2-3 business days
- Pull requests are typically reviewed within a week
- Urgent issues may be prioritized

## Recognition

Contributors are recognized in several ways:
- Listed in GitHub contributors
- Mentioned in release notes (for significant contributions)
- Acknowledged in documentation updates

## Additional Resources

- [GitHub Docs - Contributing to Projects](https://docs.github.com/en/get-started/quickstart/contributing-to-projects)
- [Markdown Guide](https://www.markdownguide.org/)
- [Conventional Commits](https://www.conventionalcommits.org/)

## License

By contributing, you agree that your contributions will be licensed under the same license as the project.

## Questions?

If you have questions about contributing, please open an issue with the "question" label.

---

Thank you for contributing to GitHub Copilot Spaces Documentation!
