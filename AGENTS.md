# GitHub defaults

Keep shared templates applicable across personal projects. Build instructions,
licenses, and product-specific constraints belong in their repositories.

Validate Renovate configuration with `npx --yes --package renovate -- renovate-config-validator`.
Run `actionlint` and `zizmor --offline .github/workflows` after workflow edits.
Keep dependency policies in `renovate-config.json`; repository opt-ins belong
in each consumer. Do not add automerge without enforced required checks.
