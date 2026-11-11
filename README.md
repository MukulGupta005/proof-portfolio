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

### Why there are no repository links for this work

- **The repositories belong to the client, not to me.** Each task was built in a private repository inside the client's GitHub organisation. My access was removed when each batch finished, so the repositories no longer open even for me.
- **The work is under NDA.** I agreed not to publish task code, task IDs, repository names or the open-source projects the tasks were built on.
- **Benchmark tasks must stay out of public view.** These tasks are used to test AI models. If a task appears publicly, it can end up in training data and stops being a fair test, so the task files carry a "never publish" marker.

My GitHub profile still counts these commits as "contributions in private repositories" (most of the green squares from July to November 2026). A written confirmation of this work can be requested from the client.

### Tasks completed

**Repository-level code-change tasks (October 2026): 9 tasks**

Each task: pick a realistic change in a real open-source codebase, write the before/after code states, the task prompt and the reference solution, write fail-to-pass and pass-to-pass tests, build the Docker test environment, and iterate on CI and reviewer feedback until it passes quality review.

| # | Language | Task type | Difficulty tier |
|---|---|---|---|
| 1 | Rust | Edge-case fix | Trivial |
| 2 | Rust | Performance | Trivial |
| 3 | Rust | Portability | Very Hard |
| 4 | Python | Performance | Very Easy |
| 5 | Python | Test repair | Hard |
| 6 | Python | Refactor | Very Hard |
| 7 | C++ | Refactor | Trivial |
| 8 | C# | Portability | Hard |
| 9 | Go | Refactor | Hard |

**Terminal-environment tasks for AI agents (October 2026): 2 tasks**

Full task packages in Harbor format: instructions, Docker environment, reference solution, and pytest verifier calibrated with oracle and no-op runs.

| # | Category | Subject |
|---|---|---|
| 1 | Operations / Compliance | Data erasure across PostgreSQL and Redis |
| 2 | Hardware / RTL | Hardware-design (RTL) filter task |

**Terminal-environment tasks for AI agents (July–August 2026)**

Harbor-format tasks across data processing, data querying and databases, data science and reporting, ML infrastructure, systems operations, and mathematical reasoning; for example, a log-parsing task with a JSON report and a verifier that checks the computed values rather than file existence.

## Skills

- **Languages:** JavaScript/TypeScript, Python, Java, SQL (PostgreSQL), plus reading-level Rust, C++, C#, Go
- **Backend:** Node.js, Next.js, Spring Boot, Supabase, REST APIs, JWT auth
- **Tooling:** Docker, Linux/Bash, Git/GitHub CLI, pytest
