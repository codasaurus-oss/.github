<p align="center">
  <img src="https://raw.githubusercontent.com/codasaurus-oss/codasaurus/main/assets/logo.svg" alt="Codasaurus" width="96" />
</p>

<h1 align="center">Codasaurus</h1>

<p align="center">
  Self-hosted GitHub App that reviews pull requests with deterministic checks first and your own LLM key.
</p>

<p align="center">
  <a href="https://github.com/codasaurus-oss/codasaurus/releases"><img src="https://img.shields.io/github/v/release/codasaurus-oss/codasaurus?label=release" alt="Release" /></a>
  <a href="https://github.com/codasaurus-oss/codasaurus/actions/workflows/ci.yml"><img src="https://github.com/codasaurus-oss/codasaurus/actions/workflows/ci.yml/badge.svg" alt="CI" /></a>
  <a href="https://codasaurus-oss.github.io"><img src="https://img.shields.io/badge/docs-codasaurus--oss.github.io-0ea5e9" alt="Docs" /></a>
  <a href="https://www.rust-lang.org/"><img src="https://img.shields.io/badge/rust-1.90%2B-dea584?logo=rust&logoColor=white" alt="Rust" /></a>
  <a href="https://github.com/codasaurus-oss/codasaurus/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-AGPL--3.0--or--later-blue" alt="License" /></a>
</p>

## Repositories

| Repository | What it is |
| --- | --- |
| [codasaurus](https://github.com/codasaurus-oss/codasaurus) | Review engine, webhook handler, HTTP API, deployment |
| [codasaurus-frontend](https://github.com/codasaurus-oss/codasaurus-frontend) | Svelte dashboard, built into the server image |
| [codasaurus-oss.github.io](https://github.com/codasaurus-oss/codasaurus-oss.github.io) | Documentation site, published at <https://codasaurus-oss.github.io> |

## Using it

```bash
git clone https://github.com/codasaurus-oss/codasaurus.git
cd codasaurus
cp .env.example .env
docker compose up -d
```

Open <http://localhost:3000> and finish the onboarding wizard. Mention `codasaurus` in a pull request comment to run a review.

## Contributing

Read the organization defaults in [.github](https://github.com/codasaurus-oss/.github): code of conduct, security policy, support, issue and pull request templates. Commits must be signed off (`git commit -s`).

## Security

Report vulnerabilities privately per the [security policy](https://github.com/codasaurus-oss/.github/blob/main/SECURITY.md). Do not open a public issue.
