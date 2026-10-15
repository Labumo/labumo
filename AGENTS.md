# Labumo public repository guidelines

- This repository currently provides a public introduction. Add documentation,
  demos, and integration examples only when they exist and have been verified.
  Do not publish private product code, commercial plans, customer information,
  credentials, or internal infrastructure details.
- Labumo follows a commercial product model. Partners are intended to receive
  the complete product source under separately agreed commercial terms. Do not
  grant licenses or repository access, or describe the product as open source,
  without the owner's explicit authorization.
- After the initial repository setup, use a separate worktree, a `codex/` branch,
  and a pull request for each change. Merge and release require human authorization.
- Standalone public demos and examples must not require access to private
  repositories, a private Software Factory release, or the owner's PR Review service.
- For documentation changes, verify facts and local links, and run `git diff --check`.
  The first implementation PR will define code checks; no application tests exist yet.
- Use English for documentation, issues, pull requests, commit messages, release notes,
  and code identifiers. Product localization is a separate concern.
- Public bug reports belong in this repository's Issues. Do not include private
  support conversations or customer data.
