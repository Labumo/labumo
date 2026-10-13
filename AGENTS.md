# Labumo public repository guidelines

- This repository currently provides a public introduction. Do not publish private
  product code, commercial plans, customer information, credentials, or internal
  infrastructure details.
- The public code scope and license remain undecided. Do not add a license or
  describe the entire product as open source without the owner's decision.
- After the initial repository setup, use a separate worktree, a `codex/` branch,
  and a pull request for each change. Merge and release require human authorization.
- Building or using a public release must not require access to private repositories,
  a private Software Factory release, or the owner's PR Review service.
- For documentation changes, verify facts and local links, and run `git diff --check`.
  The first implementation PR will define code checks; no application tests exist yet.
- Use English for documentation, issues, pull requests, commit messages, release notes,
  and code identifiers. Product localization is a separate concern.
- Public bug reports belong in this repository's Issues. Do not include private
  support conversations or customer data.
