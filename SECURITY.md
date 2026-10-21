# Security policy

## Reporting a vulnerability

Report it privately. Open a security advisory on the affected repository:
`https://github.com/oci-ai-architects/<repo>/security/advisories/new`

Please don't open a public issue for a vulnerability. Include the repository, the version or commit, steps to reproduce, and what an attacker could do with it.

## What counts

Anything in these repositories that could leak credentials, run code the user didn't intend, or give access to someone's OCI tenancy. Examples: an unsafe default in a Terraform stack, a skill that echoes secrets into logs, a workflow that runs untrusted input.

## Keeping secrets out

Never commit API keys, tokens, private keys, tenancy OCIDs tied to a real account, or `.env` files. Secret scanning and push protection are on for new repositories in this organization. If you find a committed secret, rotate it first, then tell us.
