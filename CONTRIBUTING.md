## Contributing

Hi there! We're thrilled that you'd like to contribute to this project. Your help is essential for keeping it great.

Contributions to this project are [released](https://help.github.com/articles/github-terms-of-service/#6-contributions-under-repository-license) to the public under the project's open source license.

Please note that this project is released with a Contributor Code of Conduct. By participating in this project you agree to abide by its terms.

## Table of Contents

- [Getting Started](#getting-started)
- [Types of Contributions](#types-of-contributions)
- [Development Workflow](#development-workflow)
- [Submitting a Pull Request](#submitting-a-pull-request)
- [Code Review Process](#code-review-process)
- [Style Guidelines](#style-guidelines)
- [Resources](#resources)

## Getting Started

Before you begin:

1. **Check existing issues and pull requests** - Someone might already be working on something similar
2. **Read the Code of Conduct** - Understand the community standards
3. **Review the documentation** - Familiarize yourself with the project structure

## Types of Contributions

We welcome many types of contributions:

### 📝 Documentation
- Fix typos or clarify existing documentation
- Add examples or use cases
- Translate documentation
- Write tutorials or blog posts

### 🐛 Bug Reports
- Use the issue template if available
- Include clear steps to reproduce
- Provide system/environment details
- Add screenshots or error messages

### ✨ Feature Requests
- Describe the problem you're trying to solve
- Explain your proposed solution
- Consider alternative approaches
- Discuss potential impacts

### 💻 Code Contributions
- Bug fixes
- New features
- Performance improvements
- Test coverage improvements

## Development Workflow

1. **Fork and clone the repository**
   ```bash
   git clone https://github.com/your-username/repository-name.git
   cd repository-name
   ```

2. **Configure and install dependencies**
   ```bash
   script/bootstrap
   ```

3. **Create a new branch**
   ```bash
   git checkout -b my-branch-name
   ```
   Use descriptive branch names like:
   - `fix/bug-description`
   - `feature/feature-name`
   - `docs/documentation-update`

4. **Make your changes**
   - Write clear, readable code
   - Follow existing code patterns
   - Add or update tests as needed
   - Update documentation if required

5. **Run tests locally**
   ```bash
   script/cibuild
   ```
   Ensure all tests pass before submitting your changes.

6. **Commit your changes**
   - Use clear, descriptive commit messages
   - Reference related issues when applicable
   - Keep commits focused and atomic

## Submitting a Pull Request

### Pre-submission Checklist

Before submitting, ensure:

- [ ] Code follows the project's style guidelines
- [ ] All tests pass locally
- [ ] New tests are added for new functionality
- [ ] Documentation is updated if needed
- [ ] Commit messages are clear and descriptive
- [ ] Branch is up to date with the base branch

### Pull Request Process

1. **Push to your fork**
   ```bash
   git push origin my-branch-name
   ```

2. **Open a pull request**
   - Navigate to the original repository
   - Click "New Pull Request"
   - Select your fork and branch
   - Fill out the pull request template

3. **Craft a great pull request**
   - **Title**: Clear and concise summary (50 characters or less)
   - **Description**:
     - What changes are included
     - Why these changes are needed
     - How to test the changes
     - Link to related issues
   - **Screenshots**: Include for UI changes
   - **Breaking changes**: Clearly document any breaking changes

4. **Wait for review**
   - Be responsive to feedback
   - Make requested changes promptly
   - Keep discussions focused and professional

### Tips for Pull Request Success

Here are things that will increase the likelihood of your pull request being accepted:

- **Follow standards** - Adhere to style guides and code quality standards
- **Write tests** - Ensure adequate test coverage for your changes
- **Stay focused** - Keep changes as focused as possible. If there are multiple independent changes, submit them as separate pull requests
- **Write good commit messages** - Follow [these guidelines](http://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html)
- **Update documentation** - Keep documentation in sync with code changes
- **Be responsive** - Reply to review comments in a timely manner

## Code Review Process

### What to Expect

- **Initial review**: Usually within 2-3 business days
- **Follow-up reviews**: After you address feedback
- **Approval**: At least one maintainer approval required
- **Merge**: Maintainers will merge once approved

### Addressing Feedback

When reviewers request changes:

1. **Understand the feedback** - Ask clarifying questions if needed
2. **Make the changes** - Update your branch with the requested modifications
3. **Respond to comments** - Let reviewers know when you've addressed their feedback
4. **Re-request review** - Once all changes are made

### After Your PR is Merged

- Delete your branch (optional but recommended)
- Update your fork to stay in sync
- Celebrate your contribution! 🎉

## Style Guidelines

### General Principles

- **Readability**: Code is read more often than written
- **Consistency**: Follow existing patterns in the codebase
- **Simplicity**: Prefer simple, clear solutions over clever ones
- **Documentation**: Comment complex logic, not obvious code

### Code Standards

- Use meaningful variable and function names
- Keep functions small and focused
- Avoid deep nesting (max 3-4 levels)
- Handle errors appropriately
- Remove commented-out code and debug statements

### Commit Message Format

```
Short summary (50 chars or less)

More detailed explanation if necessary. Wrap at 72 characters.
Explain the problem this commit solves and why this approach was taken.

- Bullet points are okay
- Use present tense ("Add feature" not "Added feature")
- Reference issues: Fixes #123, Closes #456
```

## Resources

- [How to Contribute to Open Source](https://opensource.guide/how-to-contribute/)
- [Using Pull Requests](https://help.github.com/articles/about-pull-requests/)
- [GitHub Help](https://help.github.com)
