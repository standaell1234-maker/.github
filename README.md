# .github

*Community health files for the @GitHub organization*

## Overview

This repository serves as the default location for community health files that apply across all repositories in the @GitHub organization. When a repository doesn't have its own community health files, GitHub will automatically use the files from this repository.

## What Are Community Health Files?

Community health files help establish guidelines and standards for contributors and community members. They provide important information about:

- How to contribute to projects
- Code of conduct expectations
- Security vulnerability reporting
- Support resources

## Files in This Repository

### Core Documentation

- **CODE_OF_CONDUCT.md** - Defines standards for community interaction and behavior expectations
- **CONTRIBUTING.md** - Guidelines for contributing to projects, including pull request process
- **SECURITY.md** - Information about reporting security vulnerabilities
- **profile/README.md** - Organization profile page content displayed on GitHub

## How It Works

When someone views any repository in the @GitHub organization that doesn't have its own community health files, GitHub will:

1. Check if the file exists in the repository
2. If not found, fall back to the file in this `.github` repository
3. Display the content from this centralized location

This approach ensures consistent policies and guidelines across all organization repositories while allowing individual repositories to override with custom versions when needed.

## Usage

### For Repository Maintainers

If you want to use custom community health files for your repository:

1. Create the file in your repository's root or `.github` directory
2. Your custom file will take precedence over the organization default

### For Contributors

When contributing to any repository in the @GitHub organization:

1. Read the CONTRIBUTING.md guidelines
2. Follow the CODE_OF_CONDUCT.md standards
3. Report security issues according to SECURITY.md

## Related Resources

For more information, see:
- [Creating a default community health file for your organization](https://help.github.com/en/articles/creating-a-default-community-health-file-for-your-organization)
- [About community profiles for public repositories](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/about-community-profiles-for-public-repositories)
- [Building a strong community](https://docs.github.com/en/communities)

## Maintenance

This repository is maintained by the GitHub organization team. To suggest changes:

1. Fork this repository
2. Make your changes
3. Submit a pull request with a clear description of the improvements

---

**Note:** Changes to files in this repository will affect all repositories in the organization that don't have their own copies of these files.
