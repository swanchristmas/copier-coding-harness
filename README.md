# copier-coding-harness

This repository is retired. [`v0.4.4`](https://github.com/agentic-tend/copier-coding-harness/tree/v0.4.4) is the last usable Copier template revision. It remains available for historical, pinned use; `main` no longer provides a template, and no successor tag is planned.

## Replacement

The generic scaffold was replaced by an observed-need model:

- [`bootstrap-project-context`](https://github.com/agentic-tend/skills/tree/main/bootstrap-project-context) inspects a repository and applies only justified local agent context.
- [`clarifying-contracts`](https://github.com/agentic-tend/skills/tree/main/clarifying-contracts) resolves user-owned semantic ambiguity before implementation.
- [`software-engineering`](https://github.com/agentic-tend/skills/tree/main/software-engineering) owns reusable implementation, testing, and delivery taste without loading it into non-software tasks.
- [`structure-documentation`](https://github.com/agentic-tend/skills/tree/main/structure-documentation) owns reusable persistent-prose behavior.
- [Context ownership](https://github.com/agentic-tend/.github/blob/main/docs/context-ownership.md) defines the boundaries among global defaults, repository context, skills, decisions, mechanical enforcement, and generators.
- [Agentic tooling](https://github.com/agentic-tend/.github/blob/main/docs/agentic-tooling.md) preserves the motivation and semantic model, while the [development routing model](https://github.com/agentic-tend/.github/blob/main/docs/development.md) preserves the human-facing uncertainty workflow.

## Existing consumers

This retirement does not modify downstream repositories. Existing projects retain their generated context until their maintainers migrate them separately. Historical Copier use should remain pinned to `v0.4.4`; do not copy or update from `main`.

Repository archival is a separate maintainer action after the replacement repositories are published.
