## Contributing

Hi there! We're thrilled that you'd like to contribute to this project. Your help is essential for keeping it great.

Contributions to this project are [released](https://help.github.com/articles/github-terms-of-service/#6-contributions-under-repository-license) to the public under the project's open source license.

Please note that this project is released with a [Contributor Code of Conduct](CODE_OF_CONDUCT.md). By participating in this project you agree to abide by its terms.

## Getting Started

Before you begin:

- Check the project's README for specific setup instructions
- Look at existing issues to see if your contribution is already being discussed
- For significant changes, open an issue first to discuss your proposed changes with maintainers
- Ensure you have the necessary development environment set up

## Submitting a Pull Request

Follow these steps to submit a pull request:

1. **Fork and clone the repository**
   ```bash
   gh repo fork github/.github --clone
   cd .github
   ```

2. **Configure and install dependencies** (if applicable)
   ```bash
   script/bootstrap
   ```
   Note: Some repositories may not require this step. Check the project's README.

3. **Verify tests pass on your machine**
   ```bash
   script/cibuild
   ```

4. **Create a new branch** with a descriptive name
   ```bash
   git checkout -b fix-typo-in-docs
   # or
   git checkout -b add-feature-x
   ```

5. **Make your changes**
   - Write clear, maintainable code
   - Add or update tests as needed
   - Update documentation to reflect your changes
   - Follow the project's existing code style and conventions

6. **Test your changes**
   - Ensure all tests pass: `script/cibuild`
   - Test your changes manually if applicable
   - Check for any linting or formatting issues

7. **Commit your changes**
   - Write a [good commit message](http://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html)
   - Use present tense ("Add feature" not "Added feature")
   - Reference any related issues (e.g., "Fixes #123")

8. **Push to your fork**
   ```bash
   git push origin my-branch-name
   ```

9. **Open a pull request**
   - Provide a clear title and description
   - Explain what changes you made and why
   - Reference any related issues
   - Add screenshots or examples if relevant

10. **Respond to feedback**
    - Address any review comments promptly
    - Make additional commits if changes are requested
    - Ask questions if feedback is unclear

### Tips for Successful Pull Requests

Here are practices that increase the likelihood of your pull request being accepted:

- **Follow code standards** - Adhere to the project's style guide and code quality standards
- **Write tests** - Include tests for new functionality and bug fixes
- **Keep changes focused** - Submit separate pull requests for independent changes
- **Write clear commit messages** - Make it easy to understand what each commit does
- **Update documentation** - Keep README, comments, and docs in sync with code changes
- **Be responsive** - Reply to comments and update your PR based on feedback
- **Be patient** - Maintainers review PRs as time allows; follow up politely if needed

## Reporting Bugs

If you find a bug:

1. **Check existing issues** - Search to see if it's already been reported
2. **Create a detailed report** - Include:
   - Clear description of the bug
   - Steps to reproduce
   - Expected vs. actual behavior
   - Environment details (OS, browser, version, etc.)
   - Screenshots or error messages if applicable
3. **Use issue templates** - Fill out all sections if the project provides templates

## Requesting Features

For feature requests:

1. **Check existing issues** - Someone may have already suggested it
2. **Describe the use case** - Explain the problem you're trying to solve
3. **Propose a solution** - Share your ideas, but be open to alternatives
4. **Be patient** - Maintainers will consider your request based on project priorities

## Code Review Process

After submitting a pull request:

- **Automated checks** - CI/CD pipelines will run tests and checks
- **Maintainer review** - Project maintainers will review your code
- **Discussion** - Be prepared to discuss your approach and make changes
- **Approval and merge** - Once approved, maintainers will merge your PR

## Resources

### GitHub Documentation
- [How to Contribute to Open Source](https://opensource.guide/how-to-contribute/)
- [Using Pull Requests](https://help.github.com/articles/about-pull-requests/)
- [GitHub Help](https://help.github.com)
- [About Issues](https://docs.github.com/en/issues/tracking-your-work-with-issues/about-issues)

### Development Best Practices
- [Conventional Commits](https://www.conventionalcommits.org/)
- [Semantic Versioning](https://semver.org/)
- [Keep a Changelog](https://keepachangelog.com/)

## Questions?

If you have questions about contributing:

- Check the project's documentation and README
- Look for answers in existing issues and discussions
- Open a new issue with the "question" label
- Reach out to maintainers respectfully

Thank you for contributing! 🎉
