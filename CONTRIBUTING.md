# Contributing to FOSSHack Jabalpur 2026

Thank you for your interest in contributing to the FOSSHack Jabalpur 2026 repository. This document provides guidelines for contributing project documentation, updates, and improvements to this repository.

---

## Table of Contents

- [Getting Started](#getting-started)
- [How to Fork the Repository](#how-to-fork-the-repository)
- [Creating a Branch](#creating-a-branch)
- [Making Changes](#making-changes)
- [Commit Message Standards](#commit-message-standards)
- [Submitting a Pull Request](#submitting-a-pull-request)
- [Code Quality Expectations](#code-quality-expectations)
- [Review Process](#review-process)

---

## Getting Started

Before contributing, ensure you have:

- A GitHub account.
- Git installed on your local machine.
- Familiarity with basic Git workflows (clone, branch, commit, push, pull request).

If you are new to Git and GitHub, the [GitHub documentation](https://docs.github.com/en/get-started) is a good starting point.

---

## How to Fork the Repository

1. Navigate to the [FOSSHack Jabalpur 2026 repository](https://github.com/opensource-society/FOSS-Hack-Jabalpur-2026) on GitHub.
2. Click the **Fork** button in the top-right corner of the page.
3. This creates a copy of the repository under your GitHub account.
4. Clone your fork to your local machine:

```bash
git clone https://github.com/<your-username>/FOSS-Hack-Jabalpur-2026.git
cd FOSS-Hack-Jabalpur-2026
```

5. Add the upstream remote to keep your fork up to date:

```bash
git remote add upstream https://github.com/opensource-society/FOSS-Hack-Jabalpur-2026.git
```

---

## Creating a Branch

Always create a new branch for your changes. Do not work directly on the `main` branch.

Use the following naming conventions for branches:

| Type | Branch Naming Pattern | Example |
|---|---|---|
| Adding a new project | `add/<project-name>` | `add/weather-dashboard` |
| Fixing documentation | `fix/<description>` | `fix/typo-in-readme` |
| General updates | `update/<description>` | `update/event-timeline` |

To create and switch to a new branch:

```bash
git checkout -b add/your-project-name
```

---

## Making Changes

- Keep changes focused and minimal. Each pull request should address a single concern.
- Follow the existing file and directory structure of the repository.
- Ensure all Markdown files are properly formatted and render correctly.
- Do not include build artifacts, compiled files, or unrelated content.

---

## Commit Message Standards

Write clear, descriptive commit messages. Use the following format:

```
<Type>: <Short description>

[Optional body explaining why the change was made]
```

**Accepted types:**

| Type | Use Case |
|---|---|
| `Add` | Adding new files or content |
| `Fix` | Fixing errors or broken content |
| `Update` | Updating existing content |
| `Remove` | Removing outdated content |
| `Docs` | Documentation-only changes |

**Examples:**

```
Add: project documentation for open-source CLI tool
Fix: broken link in JUDGING_CRITERIA.md
Update: event timeline with confirmed Demo Day venue
Docs: improve CONTRIBUTING.md formatting
```

Avoid vague messages such as:
- `update`
- `fix stuff`
- `changes`
- `final version`

---

## Submitting a Pull Request

1. Push your branch to your fork:

```bash
git push origin add/your-project-name
```

2. Navigate to your fork on GitHub and click **Compare & pull request**.
3. Ensure the base repository is `opensource-society/FOSS-Hack-Jabalpur-2026` and the base branch is `main`.
4. Provide a clear title and description for your pull request, explaining what was changed and why.
5. Reference any related issues using `Closes #<issue-number>` if applicable.
6. Submit the pull request.

---

## Code Quality Expectations

All contributions to this repository must meet the following standards:

- **Markdown formatting** — Use proper headings, lists, tables, and code blocks.
- **Spelling and grammar** — Proofread before submitting. Avoid abbreviations and informal language.
- **Accuracy** — Ensure all project details, links, and references are correct and up to date.
- **Attribution** — If referencing or reproducing any third-party content, provide proper attribution.
- **Licensing** — All submitted projects must include a valid FOSS license from the options listed in the [LICENSES/](LICENSES/) folder.

---

## Review Process

After submitting a pull request:

1. A maintainer will review your submission within a reasonable timeframe.
2. You may receive requests for changes. Address them promptly and push updates to your branch.
3. Once approved, your pull request will be merged into the `main` branch.
4. Repeated or intentional policy violations may result in your contribution being rejected.

All contributions are subject to the [Code of Conduct](CODE_OF_CONDUCT.md).

---

*For questions or clarifications, contact the organizing team at fosshack@ggits.org.*
