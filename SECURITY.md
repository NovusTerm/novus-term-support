# Security Policy

We take the security of NovusTerm seriously. Thank you for helping keep it and
its users safe.

## Reporting a vulnerability

**Do not report security vulnerabilities through public GitHub issues,
discussions, or pull requests.** A public report exposes users before a fix
exists.

Use **either** of these private channels — whichever you prefer:

1. **GitHub private vulnerability reporting** (preferred) —
   [open a private advisory](https://github.com/NovusTerm/novus-term-support/security/advisories/new).
   It is private between you and the maintainer.
2. **Email** — **security@novusterm.com**. If you want to encrypt, say so in a
   first plaintext message and we will exchange keys.

## What to include

- The version of NovusTerm and your operating system.
- What the vulnerability is, and what an attacker could achieve with it.
- Step-by-step reproduction, a proof of concept, or a crash trace if you have one.
- Anything you think we would otherwise miss.

**Please redact secrets from anything you send.** Terminal output routinely
contains API keys and tokens.

## What happens next

| Stage | Target |
|---|---|
| We acknowledge your report | within **72 hours** |
| We confirm the issue and give you an assessment | within **7 days** |
| We ship a fix, or explain why we will not | as fast as severity warrants |

We practise **coordinated disclosure**: we will agree a disclosure date with you,
credit you in the advisory and the changelog unless you ask us not to, and we
will not take legal action against good-faith research that respects these rules.

## Scope

**In scope** — the NovusTerm desktop application, its auto-updater and update
feed, its licensing/activation flow, and the signed release artifacts published
in [`novus-term-releases`](https://github.com/NovusTerm/novus-term-releases).

**Out of scope** — vulnerabilities in third-party dependencies that we merely
consume (report those upstream, then tell us), issues requiring an already fully
compromised machine, and social engineering.

## Supported versions

Security updates are provided for the **latest released version**. Update before
reporting; the issue may already be fixed.
