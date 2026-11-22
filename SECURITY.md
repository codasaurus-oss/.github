# Security Policy

## Reporting a vulnerability

Email **iam@thelohit.in** with a description, reproduction steps, and the
affected version or commit. Do not open a public issue for a suspected
vulnerability.

You can expect an acknowledgement within 72 hours. Confirmed issues are fixed
on `main` and disclosed after a patched release is available, with credit unless
you ask otherwise.

## Supported versions

Security fixes land on the latest release. Older releases are not maintained.

| Version | Supported |
| --- | --- |
| latest release | yes |
| `main` | yes (pre-release) |
| older tags | no |

## Scope

In scope: the server binary, the dashboard, the Docker image, and the documented
deployment paths.

Out of scope: vulnerabilities in third-party services you connect (GitHub,
OpenRouter, Postgres), and findings that require an already-compromised host.
