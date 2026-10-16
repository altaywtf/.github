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
[uinaf's policy](https://github.com/uinaf/.github#renovate), which sets update
grouping, automerge, and major-update approval; personal overrides go here.
The Renovate app covers every repository but opens no onboarding pull requests,
so a repository gets updates only after it adds `renovate.json`. Forks are skipped.
