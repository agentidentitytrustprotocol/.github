# Security Policy

## Reporting a vulnerability

Please report security issues privately via
[GitHub Security Advisories](https://github.com/agentidentitytrustprotocol/aitp-rs/security/advisories/new)
on the relevant repository, or by email to **security@zer07labs.com**. Do not
open a public issue for a suspected vulnerability.

We aim to acknowledge reports within 3 business days.

## Supply chain

Release artifacts are published with build provenance — npm `--provenance` and
PyPI PEP 740 attestations for the NAPI/wheel binaries. The spec repository pins
third-party GitHub Actions to commit SHAs; the other repositories reference
them by version tag. Cross-repo automation runs as the
`aitp-deps-bot` GitHub App (short-lived installation tokens) — no PATs.
