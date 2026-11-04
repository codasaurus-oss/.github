<p align="center">
  <img src="https://raw.githubusercontent.com/codasaurus-oss/codasaurus/main/assets/logo.svg" alt="Codasaurus" width="96" />
</p>

<h1 align="center">Codasaurus</h1>

<p align="center">
  Self-hosted GitHub App that reviews PRs with practical, deterministic checks first.
</p>

<p align="center">
  <a href="https://github.com/codasaurus-oss/codasaurus/releases"><img src="https://img.shields.io/github/v/release/codasaurus-oss/codasaurus?label=release" alt="Release" /></a>
  <a href="https://github.com/codasaurus-oss/codasaurus/actions/workflows/ci.yml"><img src="https://github.com/codasaurus-oss/codasaurus/actions/workflows/ci.yml/badge.svg" alt="CI" /></a>
  <a href="https://www.rust-lang.org/"><img src="https://img.shields.io/badge/rust-1.88%2B-dea584?logo=rust&logoColor=white" alt="Rust" /></a>
  <a href="https://github.com/codasaurus-oss/codasaurus/blob/main/docs/database.md"><img src="https://img.shields.io/badge/db-PostgreSQL-4169E1?logo=postgresql&logoColor=white" alt="PostgreSQL" /></a>
  <a href="https://github.com/codasaurus-oss/codasaurus/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-AGPL--3.0--or--later-blue" alt="License" /></a>
</p>

<p align="center">
  <a href="https://github.com/codasaurus-oss/codasaurus/blob/main/docs/setup-onboarding.md">Onboarding</a>
  ·
  <a href="https://github.com/codasaurus-oss/codasaurus/blob/main/docs/commands.md">Commands</a>
  ·
  <a href="https://github.com/codasaurus-oss/codasaurus/blob/main/docs/configuration.md">Configuration</a>
  ·
  <a href="https://github.com/codasaurus-oss/codasaurus/blob/main/docs/run-for-free.md">Run for free</a>
</p>

---

## Why Codasaurus

- Catches hallucinated imports and phantom dependencies
- Flags lockfile drift, secrets, vulnerabilities, and IaC risks
- Works great offline and supports optional BYOK LLM
- Self-hosted, no seat pricing

---

## Quick start

```bash
git clone https://github.com/codasaurus-oss/codasaurus.git
cd codasaurus
cp .env.example .env   # optional
docker compose up
```

Then open [http://localhost:3000](http://localhost:3000) and finish onboarding.

---

## On PRs

Use `@codasaurus` in comments:

```text
@codasaurus review
@codasaurus security
@codasaurus describe
@codasaurus impact
@codasaurus help
```

See full command list: [docs/commands.md](https://github.com/codasaurus-oss/codasaurus/blob/main/docs/commands.md).

---

## Learn more

- [Documentation index](https://github.com/codasaurus-oss/codasaurus/blob/main/docs/README.md)
- [Contributing](https://github.com/codasaurus-oss/codasaurus/blob/main/CONTRIBUTING.md)
- [Security policy](https://github.com/codasaurus-oss/codasaurus/blob/main/SECURITY.md)
- [Changelog](https://github.com/codasaurus-oss/codasaurus/blob/main/CHANGELOG.md)

[AGPL-3.0-or-later](https://github.com/codasaurus-oss/codasaurus/blob/main/LICENSE) · Copyright (C) 2026 [Lohit Kolluri](https://github.com/lohitkolluri)
