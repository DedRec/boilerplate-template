# Boilerplate Best Practices (Source-Verified)

This file records the specific sources used to shape the template.

## 1) Use a GitHub template repository

- Claim: A template repository lets you generate new repositories with the same structure and files.
- Source: GitHub Docs - Creating a template repository.
- URL: https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-template-repository
- Notes:
  - Template-generated branches have unrelated histories.
  - Template repositories cannot include Git LFS files.

## 2) Keep a useful README in the repository root

- Claim: README should explain what the project does, why it is useful, and how to get started.
- Source: GitHub Docs - About the repository README file.
- URL: https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes

## 3) Commit a shared .gitignore

- Claim: Put `.gitignore` in repo root and commit it so clone users share ignore rules.
- Source: GitHub Docs - Ignoring files.
- URL: https://docs.github.com/en/get-started/git-basics/ignoring-files
- Notes:
  - GitHub maintains language/OS examples in github/gitignore.

## 4) Standardize editor behavior with EditorConfig

- Claim: `.editorconfig` helps keep coding style consistent across editors/IDEs.
- Source: EditorConfig official site.
- URL: https://editorconfig.org/

## 5) Keep deploy-varying config in environment variables

- Claim: Config that changes by deploy should be separated from code and stored in env vars.
- Source: The Twelve-Factor App - Config.
- URL: https://12factor.net/config

## 6) Maintain a human-readable changelog

- Claim: Keep a curated changelog for notable changes and use an Unreleased section.
- Source: Keep a Changelog.
- URL: https://keepachangelog.com/en/1.1.0/

## 7) Use Semantic Versioning

- Claim: Use MAJOR.MINOR.PATCH and bump according to compatibility impact.
- Source: Semantic Versioning 2.0.0.
- URL: https://semver.org/

## 8) Use conventional commit structure (recommended)

- Claim: Conventional Commits improves commit clarity and supports changelog/version automation.
- Source: Conventional Commits 1.0.0.
- URL: https://www.conventionalcommits.org/en/v1.0.0/
