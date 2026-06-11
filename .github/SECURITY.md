# Security Policy

## Supported versions

The tap always serves the formula for the **latest released version** of
`gplay`. Older formula revisions are not maintained.

## Reporting a vulnerability

**Please do not open a public GitHub issue for security reports.**

Report privately through **GitHub Private Vulnerability Reporting** —
[open an advisory](https://github.com/PollyGlot/homebrew-tap/security/advisories/new).
It keeps the report private and in the repo with proper coordination. If you
can't use GitHub advisories, reach the maintainer privately via their
[GitHub profile](https://github.com/PollyGlot).

Please include:

- The formula affected (e.g. `Formula/gplay.rb`) and its version.
- A description of the vulnerability and its impact.
- Reproduction steps or a proof-of-concept.
- Any suggested remediation.

You'll get an acknowledgement within **72 hours** and a status update within
**7 days**. Coordinated disclosure is the default; we'll agree on a public
disclosure date together once a fix is ready.

## Scope

In-scope:

- The formulae in `Formula/` — in particular a download URL or `sha256`
  that does not match the official release artifacts published on
  [google-play-cli releases](https://github.com/PollyGlot/google-play-cli/releases).
- The release automation that updates this tap.

Out of scope (please file with the relevant project instead):

- The `gplay` binary itself — report via the
  [google-play-cli security policy](https://github.com/PollyGlot/google-play-cli/security/policy).
- Homebrew itself — report to [Homebrew/brew](https://github.com/Homebrew/brew/security/policy).

## Credit

Reporters who follow this policy will be credited (by handle of their choice)
in the fix's commit or release notes, unless they prefer to remain anonymous.
