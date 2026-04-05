# Contributing

Thank you for considering contributing to this project. Contributions of all kinds are welcome — bug reports, feature suggestions, documentation improvements, and code changes.

---

## Before You Start

**Read the README** to understand what the project does, what it is designed to do, and — equally important — what it is not designed to do. Every project has a defined scope. If you are unsure whether your idea fits, open an issue and ask before writing any code.

**Search for existing issues** before filing a new one. Duplicate reports and PRs slow everyone down.

---

## Reporting Bugs

Open a [GitHub issue](../../issues/new) and include:

- **What you expected to happen**
- **What actually happened**
- **Steps to reproduce** — the exact sequence that triggers the problem
- **Environment** — browser name and version, OS, screen size, or runtime version (whichever is relevant)

A minimal, reproducible example is more valuable than a long description.

---

## Suggesting Features

Open an issue before writing any code. Describe:

- The **problem** you are trying to solve, not just the feature you want
- Why the change fits within the project's stated goals and constraints
- Any tradeoffs or alternatives you considered

Feature requests without a clear user problem are unlikely to move forward.

---

## Submitting a Pull Request

1. **Fork** the repository and create a branch from `main`:
   ```bash
   git checkout -b fix/short-description
   # or
   git checkout -b feat/short-description
   ```

2. **Make your changes.** Keep commits small and focused — one logical change per commit.

3. **Test your changes** manually, across environments where relevant (browsers, Python versions, etc.).

4. **Open a pull request** with a description that explains:
   - *What* changed
   - *Why* it is better
   - Any *tradeoffs* introduced
   - Reference any related issue numbers (e.g., `Closes #42`)

5. **Respond to review feedback.** Resolve all reviewer comments before the PR can be merged. All PRs require at least one maintainer approval.

---

## Commit Messages

Use the imperative mood and keep the subject line under 72 characters:

```
fix: correct off-screen particle culling
feat: add reduced-motion media query support
docs: clarify setup steps in README
style: align CSS token comments
refactor: extract shared utility function
perf: reduce bundle size by removing unused import
chore: update dependencies
```

---

## Code Style

Follow the conventions already present in the file you are editing. When in doubt:

- Prefer clarity over cleverness
- Comments should explain *why*, not *what*
- Keep the dependency footprint small — new runtime dependencies require explicit justification

Project-specific standards (language, framework, linter config) are documented in the README or a `docs/` folder.

---

## What We Generally Won't Accept

- External runtime dependencies added without discussion
- Features that contradict the project's stated philosophy or constraints
- PRs that break existing deployment or build behaviour
- Changes without adequate testing or documentation

---

## Code of Conduct

By participating in this project you agree to abide by the [Code of Conduct](CODE_OF_CONDUCT.md).

---

## License

By submitting a pull request you agree that your contribution will be licensed under the project's existing license.
