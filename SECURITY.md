# Security Policy

## Project identity

Claude LB is an unofficial derivative of
[KarpelesLab/teamclaude](https://github.com/KarpelesLab/teamclaude). It is not
affiliated with or endorsed by KarpelesLab or Anthropic.

- **Claude LB source:** https://github.com/liubozh/claude-lb
- **Official TeamClaude source:** https://github.com/KarpelesLab/teamclaude
- **Official TeamClaude npm package:** `@karpeleslab/teamclaude`

Claude LB is currently distributed from source only. It has no npm package and
is not distributed as a downloadable binary archive.

## Reporting a vulnerability

For a vulnerability introduced by Claude LB or affecting this derivative, use
[private vulnerability reporting](https://github.com/liubozh/claude-lb/security/advisories/new).
Do not disclose exploitable details in a public issue.

For a vulnerability that also affects the original TeamClaude project, report
it to the upstream maintainers through their
[private vulnerability reporting](https://github.com/KarpelesLab/teamclaude/security/advisories/new)
channel. Include the affected version, reproduction steps, and impact.

## Supported versions

Only the current `master` branch is supported. There are no Claude LB release
artifacts or published packages at this time.

## Supply-chain guidance

- Clone Claude LB only from the canonical repository above.
- Review upstream synchronization pull requests before merging them.
- Treat repositories or archives claiming to be official Claude LB builds with
  caution.
- Verify that npm installations using the `@karpeleslab` scope come from the
  official TeamClaude project, not Claude LB.
