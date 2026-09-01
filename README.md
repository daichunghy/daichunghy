# Đái Chung Hy

Vietnam-based open-source maintainer building deterministic contract layers for
coding agents, repository governance, and reproducible research workflows.

I keep one rule across the portfolio: make the boundary explicit, make the
output reproducible, and attach every adoption claim to public evidence.

## Maintainer tooling

The projects below are one portfolio, not unrelated demos:

| Project | Purpose | Start here |
| --- | --- | --- |
| [PatchGate](https://github.com/daichunghy/patchgate) | Checks whether a GitHub pull request has the policy, evidence, ownership, and human boundaries needed before review | [first use](https://github.com/daichunghy/patchgate#try-it-locally) · [beta release](https://github.com/daichunghy/patchgate/releases/tag/v0.1.0-beta.5) |
| [contribkit](https://github.com/daichunghy/contribkit) | Compiles a repository's contribution contract and preflights a local diff before a pull request is opened | [quickstart](https://github.com/daichunghy/contribkit#contribkit) · [npm](https://www.npmjs.com/package/contribkit) |
| [agentsmd](https://github.com/daichunghy/agentsmd) | Keeps AI-agent instruction files wired to one source of truth, with linting, sync, and scoring | [README](https://github.com/daichunghy/agentsmd#agentsmd) · [npm](https://www.npmjs.com/package/%40daichunghy/agentsmd) |
| [OpenSheet-AI](https://github.com/daichunghy/opensheet-ai) | Turns typed spreadsheet operations into validated plans, dry-run receipts, and controlled workbook writes | [quickstart](https://github.com/daichunghy/opensheet-ai/blob/main/docs/QUICKSTART.md) · [npm](https://www.npmjs.com/package/opensheet-ai) |
| [quant-research](https://github.com/daichunghy/quant-research) | Checks research instruments, recodes, coverage, and measurement specifications before analysis | [reproducibility](https://github.com/daichunghy/quant-research/blob/main/docs/REPRODUCIBILITY.md) · [npm](https://www.npmjs.com/package/%40agentbiz%2Fquant-research) |

## Public evidence · 2026-09-01

- Five original public tools are active; the remaining public repositories are
  forks, a smoke-test fixture, or profile/supporting material.
- Four packages are published on npm, all explicitly pre-release.
- [Flecto #145](https://github.com/myselfsiddharth/Flecto/pull/145) was merged
  after maintainer review. It added a GitHub Actions policy pack, fixtures,
  documentation, and a 628-test validation pass; the maintainer recorded me in
  the contributor list.
- I also have active upstream work in
  [nDspec #116](https://github.com/nDspec/nDspec/pull/116) and
  [OpenSSF Scorecard #5192](https://github.com/ossf/scorecard/pull/5192).

These projects are pre-release. I do not claim external adoption, dependent
repositories, 20-contributor community status, or download thresholds unless
the repositories or registries make that evidence visible.

## How to contribute

- Try PatchGate or contribkit against a disposable repository in their documented
  non-blocking paths.
- Report the exact command, runtime, and observed output in the relevant issue.
- Review an open issue or pull request, especially the clean-consumer and
  adapter fixtures linked from each project.

The longer account of the maintainer workflow is in
[How this repo is built](https://github.com/daichunghy/patchgate/discussions/50).
Tests, clean-room checks, release metadata, and public CI decide what can be
claimed; documentation-only work is labeled as such.
