# Security policy

ByteCoop Alpha 0.3 is a **local prototype, not a production-ready multi-user service**. Do not deploy it on a publicly reachable host.

## Report a vulnerability

Please **do not** post an exploit, private user data, credentials or proof-of-concept payloads in a public issue.

Use GitHub's **Report a vulnerability** / private vulnerability reporting workflow if available under the repository Security tab. If it is not enabled, open a public issue asking the maintainer to establish a private contact channel **without sharing any sensitive details**.

We do not currently offer a bug bounty or guaranteed response window.

## Basic safeguards for local testers

- Keep the server bound to a loopback address; do not expose or port-forward it.
- Do not publish `.bitlane/`, `credentials.json`, `pgdata/`, `.env` files, session artifacts, backups or provider keys.
- Inspect exactly what context will be sent to third-party model providers.
- Leave live calls disabled until limits and permissions are set.
- Require explicit human authorization for paid provider calls.
- Treat model output, retrieved project memories and user documents as untrusted input.
- Do not allow unsandboxed agent-generated shell commands to run autonomously.

Public source visibility and passing tests are **not a security certification**. A comprehensive independent assessment has not been completed.
