# GitHub defaults

Keep shared templates applicable across personal projects. Build instructions,
licenses, and product-specific constraints belong in their repositories.

Validate Renovate configuration with `npx --yes --package renovate -- renovate-config-validator`.
Run `actionlint` and `zizmor --offline .github/workflows` after workflow edits.
[uinaf/.github](https://github.com/uinaf/.github#renovate) owns the shared
Renovate policy; `renovate-config.json` holds personal overrides, and
repository opt-ins belong in each consumer. Automerge requires enforced
required checks on the target repository.
