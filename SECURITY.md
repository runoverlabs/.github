# Security Policy

## Reporting a vulnerability

Please **do not** open a public issue for security problems.

Use GitHub's private vulnerability reporting instead: open the affected
repository, go to the **Security** tab, and choose **Report a vulnerability**.
If the repository doesn't offer that option, open a minimal public issue asking
for a private contact channel, without including any details.

Helpful things to include:

- The affected project and version or commit
- Steps to reproduce, or a proof of concept
- The impact as you understand it

## What to expect

Runover Labs is run by a single developer, so response times are best effort.
I aim to acknowledge reports within about a week, and to keep you updated as a
fix takes shape. Credit is given in the advisory unless you prefer otherwise.

## Supported versions

Only the latest release (or the default branch, for projects without releases)
receives security fixes.

## Scope notes

Some projects here, such as the microsandbox management CLI, exist to contain
untrusted agents. Sandbox escapes, credential leaks across the VM boundary, and
bypasses of egress or filesystem restrictions are treated as high-priority
vulnerabilities. Vulnerabilities in upstream projects (microsandbox, KanDev,
Forgejo) should be reported to those projects directly.
