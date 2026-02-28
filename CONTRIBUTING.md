# Contributing to FOSSHack Jabalpur 2026

Thank you for your interest in contributing. This document outlines the process for submitting contributions to this repository.

---

## Getting Started

### 1. Fork the Repository

Click the **Fork** button at the top right of this repository page on GitHub. This creates a personal copy of the repository under your account.

### 2. Clone Your Fork

```bash
git clone https://github.com/YOUR-USERNAME/FOSS-Hack-Jabalpur-2026.git
cd FOSS-Hack-Jabalpur-2026
```

### 3. Create a New Branch

Create a descriptive branch for your contribution. Do not work directly on the `main` branch.

```bash
git checkout -b feature/your-feature-name
```

Branch naming conventions:

| Type | Format | Example |
|---|---|---|
| New feature or content | `feature/description` | `feature/add-project-submission` |
| Bug fix | `fix/description` | `fix/broken-link-in-readme` |
| Documentation update | `docs/description` | `docs/update-timeline` |

---

## Making Changes

### 4. Make Your Changes

Edit the relevant files in your local copy. Ensure your changes are focused and address a single concern per pull request.

### 5. Commit Your Changes

Write clear, descriptive commit messages. Follow this format:

```
type: short summary (max 72 characters)

Optional longer description explaining what changed and why.
```

Accepted types:

- `feat` — new feature or content
- `fix` — bug fix or correction
- `docs` — documentation changes
- `style` — formatting only (no logic changes)
- `chore` — maintenance tasks

**Examples:**

```
docs: add project submission instructions to README
feat: create problem statement for education category
fix: correct Demo Day date in EVENT_TIMELINE.md
```

### 6. Push Your Branch

```bash
git push origin feature/your-feature-name
```

---

## Submitting a Pull Request

### 7. Open a Pull Request

1. Go to your forked repository on GitHub
2. Click **Compare & pull request**
3. Provide a clear title and description of your changes
4. Reference any related issues using `Closes #issue-number` if applicable
5. Submit the pull request

### Pull Request Guidelines

- Keep pull requests focused — one change per PR
- Ensure your branch is up to date with the base branch before submitting
- Do not include unrelated changes in the same PR
- Respond promptly to reviewer feedback

---

## Code Quality Expectations

- All documentation must be written in clear, professional English
- Markdown files must render correctly — test locally before submitting
- Avoid introducing broken links
- Do not commit binary files, build artifacts, or personal credentials
- Follow the formatting conventions already present in the file you are editing

---

## Review Process

1. A maintainer will review your pull request within a reasonable timeframe
2. Feedback may be provided as review comments — address them and push updated commits
3. Once approved, your pull request will be merged
4. Maintainers reserve the right to close pull requests that do not meet the contribution standards

---

## Questions

If you have questions about contributing, contact us at **fosshack@ggits.org** or open a GitHub Issue.
