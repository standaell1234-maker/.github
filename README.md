# .github

*Community health files for the [@GitHub](https://github.com/github) organization*

## Overview

This repository contains default community health files that are automatically applied to all public repositories in the GitHub organization that don't have their own versions of these files. This provides a consistent experience across all GitHub open source projects.

## What are Community Health Files?

Community health files help contributors understand how to interact with your project. When a repository doesn't have its own version of these files, GitHub automatically uses the versions from this `.github` repository.

## Files Included

### Core Community Files

- **CODE_OF_CONDUCT.md** - Defines standards for how to engage in the community (Contributor Covenant v2.1)
- **CONTRIBUTING.md** - Guidelines for contributing to projects, including pull request process
- **SECURITY.md** - Instructions for reporting security vulnerabilities responsibly
- **profile/README.md** - Organization profile that appears on the GitHub organization page

### Configuration Files

- **config/repolinter-ruleset.json** - Automated repository linting rules for validating open source best practices
- **.devcontainer/devcontainer.json** - Development container configuration for GitHub Codespaces

## How It Works

When someone visits a repository in the GitHub organization:

1. GitHub first checks if the repository has its own community health file (e.g., `CODE_OF_CONDUCT.md`)
2. If not found, GitHub automatically uses the version from this `.github` repository
3. The file appears in the repository as if it were there, providing consistent guidance to contributors

This means you only need to maintain these files in one place, and they apply to all repositories that don't override them.

## Customizing for Your Repository

If a specific repository needs different community health files:

1. Create the file directly in that repository (e.g., add a custom `CONTRIBUTING.md`)
2. The repository-specific version will take precedence over the default from this `.github` repository
3. Other files will continue to use the defaults

## Repository Linting

The `config/repolinter-ruleset.json` file defines automated checks that validate repositories against GitHub's open source policies. These rules check for:

- **MIT License** - Ensures repositories use the MIT license (or have approval for alternatives)
- **README file** - Verifies a README exists to document the project
- **CODEOWNERS file** - Confirms maintainers are identified for the project

These rules are enforced via the [repolinter-action](https://github.com/newrelic/repolinter-action) in CI/CD pipelines.

## Development Environment

The `.devcontainer` folder provides configuration for GitHub Codespaces and VS Code Dev Containers, allowing contributors to quickly set up a standardized development environment.

## Learn More

For more information, please see the article on [creating a default community health file for your organization](https://help.github.com/en/articles/creating-a-default-community-health-file-for-your-organization).
