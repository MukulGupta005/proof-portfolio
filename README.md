# Mukul Gupta: Work Portfolio

One page with links to my public, checkable work, plus a summary of the private evaluation work I cannot publish.

- GitHub: [MukulGupta005](https://github.com/MukulGupta005)
- All my public pull requests: [author:MukulGupta005](https://github.com/pulls?q=is%3Apr+author%3AMukulGupta005)

## Open-source contributions

| Project | Pull request | What it does | Status |
|---|---|---|---|
| [arcee-ai/mergekit](https://github.com/arcee-ai/mergekit) | [#726](https://github.com/arcee-ai/mergekit/pull/726) | Replaces a dead Multi-SLERP reference URL that was written into every generated model card, and adds `examples/multislerp.yml` (closes [#561](https://github.com/arcee-ai/mergekit/issues/561)) | Open; CLA signed, all checks passing |
| [EddieHubCommunity/BioDrop](https://github.com/EddieHubCommunity/BioDrop) | [#10323](https://github.com/EddieHubCommunity/BioDrop/pull/10323) | Added my profile data | Merged (2024) |

## Evaluation task authoring for AI coding agents (private, under NDA)

Since July 2026 I have built and reviewed software-engineering evaluation tasks used to test AI coding models. The task repositories belong to the client and are private, so no code, task names or screenshots are published here.

What the work involves:

- Reading unfamiliar open-source codebases in **Rust, Python, C++, C# and Go** and finding a realistic change site
- Writing **fail-to-pass and pass-to-pass tests** (pytest, cargo test, GoogleTest, xUnit) that fail on the original code and pass on the fix
- Building **reproducible Docker test environments** with digest-pinned base images and offline test runners
- Calibrating verifiers with **oracle** (must score 1) and **no-op** (must score 0) runs so the task cannot be gamed
- Fixing CI failures and reviewer feedback until each task passed quality review

## Skills

- **Languages:** JavaScript/TypeScript, Python, Java, SQL (PostgreSQL), plus reading-level Rust, C++, C#, Go
- **Backend:** Node.js, Next.js, Spring Boot, Supabase, REST APIs, JWT auth
- **Tooling:** Docker, Linux/Bash, Git/GitHub CLI, pytest
