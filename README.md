# GitHub defaults

Shared issue forms, pull request template, and security policy for altaywtf repositories.
Repository-specific setup and contribution instructions stay with each project.

## Dependency updates

Repositories opt in with `renovate.json`:

```json
{
  "extends": ["github>altaywtf/.github:renovate-config"]
}
```

The [personal preset](renovate-config.json) extends
[uinaf’s maintained policy](https://github.com/uinaf/renovate-config).
Major updates require dashboard approval. Native automerge is a repository-level
opt-in that requires enforced checks. Contribution forks and archived projects
are excluded from the Renovate installation.
