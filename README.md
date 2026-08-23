### Đái Chung Hy

Open-source maintainer in Vietnam. I build deterministic contract layers for
coding agents and applied research workflows.

The common rule is simple: make the boundary explicit, make the output
reproducible, and leave claims about real users to evidence.

## Current projects

| Project | What it checks | Public starting point |
| --- | --- | --- |
| [PatchGate](https://github.com/daichunghy/patchgate) | Whether a GitHub pull request has the policy, evidence, ownership and human boundaries needed before review | [beta releases](https://github.com/daichunghy/patchgate/releases) · [CI](https://github.com/daichunghy/patchgate/actions) |
| [contribkit](https://github.com/daichunghy/contribkit) | Whether a repository contribution contract is satisfied before a pull request is opened | [npm package](https://www.npmjs.com/package/contribkit) · [adapter queue](https://github.com/daichunghy/contribkit/issues?q=is%3Aissue+label%3Aadapter) |
| [OpenSheet-AI](https://github.com/daichunghy/opensheet-ai) | Whether a typed spreadsheet operation passes policy and produces a reviewable receipt before a workbook is changed | [npm package](https://www.npmjs.com/package/opensheet-ai) · [quickstart](https://github.com/daichunghy/opensheet-ai/blob/main/docs/QUICKSTART.md) |
| [quant-research](https://github.com/daichunghy/quant-research) | Whether instruments, recodes, coverage and measurement specifications are internally consistent before analysis | [npm package](https://www.npmjs.com/package/%40agentbiz%2Fquant-research) · [reproducibility guide](https://github.com/daichunghy/quant-research/blob/main/docs/REPRODUCIBILITY.md) |

I also maintain [agentsmd](https://github.com/daichunghy/agentsmd), a project
for linting and synchronising agent-instruction files, and keep slower public
experiments in [Flecto](https://github.com/daichunghy/Flecto) and
[desklore](https://github.com/daichunghy/desklore).

## How I work

I define the product boundary and acceptance criteria, then use coding agents
for implementation. Tests, clean-room checks, release metadata and public CI
decide what can be claimed. Every project documents its non-goals alongside
its capabilities.

The longer account of the workflow is in
[How this repo is built](https://github.com/daichunghy/patchgate/discussions/50).

These projects are public pre-release work. A source tag, an npm publication,
a local fixture, a maintainer-reviewed PR and an external pilot are different
evidence levels; the repositories keep those states separate.

For a real failure or confusing first run, open an issue in the relevant
repository with the command, runtime version and observed output. That is more
useful than a generic endorsement.
