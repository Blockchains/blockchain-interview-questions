# AGENTS.md: blockchain-interview-questions

Instructions for AI coding agents (Grok, Cursor, Claude Code, Codex, Copilot and others) working **in** this repo or **using it as a building block**. Humans: see [README.md](README.md).

## What this is

54 blockchain and smart-contract interview questions with concise answers, each linked to a runnable lab, a free tool or an explainer.

- Kind: docs, dataset · stability: `stable` · licence: MIT AND CC-BY-4.0
- Machine-readable manifest: [`blocks.json`](blocks.json) (schema: [BLOCKS-SCHEMA](https://github.com/Blockchains/.github/blob/main/docs/BLOCKS-SCHEMA.md))
- How it fits with the other Blockchains repos: [Build with Blocks](https://github.com/Blockchains/.github/blob/main/docs/BUILD-WITH-BLOCKS.md)

## Setup

```bash
# nothing to install
```

## Build and test

```bash
# CI link-checks README.md (.github/workflows/links.yml)
```

Tests hit **live** public networks/APIs (the org rule is no mocks). A failure can be an upstream outage: re-run before changing code.

## Structure

| Path | What |
|---|---|
| `README.md` | the content |
| `.github/workflows/links.yml` | link checker |
| `LICENSE` | MIT (code) / CC BY 4.0 (text) |

## Conventions

- Every item links to a primary doc plus a runnable lab or tool.
- UTM-tagged links to blockchainlab.com are intentional.

## Extension points

- Add an item in the right section with the same link pattern.

## Do

- Verify every link.

## Don't

- Remove or rename anchors other repos link to.
- Commit secrets, keys or `.env` files. Run `gitleaks` before pushing; CI and the org policy reject leaks.

## Using it from another project

- **README.md** (file): `https://raw.githubusercontent.com/Blockchains/blockchain-interview-questions/main/README.md`

See the README section [Use as a building block](README.md#use-as-a-building-block) for a copy-paste example.

## Related blocks

- [Blockchains/blockchainlab-labs](https://github.com/Blockchains/blockchainlab-labs): hands-on labs linked from each item
- [Blockchains/blockchainlab-tools](https://github.com/Blockchains/blockchainlab-tools): tools linked from each item
- [Blockchains/blockchain-dev-roadmap](https://github.com/Blockchains/blockchain-dev-roadmap): companion guide
