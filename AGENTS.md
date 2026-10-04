# AGENTS.md: hackathons

Instructions for AI coding agents (Grok, Cursor, Claude Code, Codex, Copilot and others) working **in** this repo or **using it as a building block**. Humans: see [README.md](README.md).

## What this is

Blockchain Lab hackathon tracker: one GitHub issue per open blockchain/web3 hackathon (issue forms for hackathons and submissions) plus a README table of verified upcoming events.

- Kind: docs, dataset · stability: `stable` · licence: NOASSERTION
- Machine-readable manifest: [`blocks.json`](blocks.json) (schema: [BLOCKS-SCHEMA](https://github.com/Blockchains/.github/blob/main/docs/BLOCKS-SCHEMA.md))
- How it fits with the other Blockchains repos: [Build with Blocks](https://github.com/Blockchains/.github/blob/main/docs/BUILD-WITH-BLOCKS.md)

## Setup

```bash
gh auth status
```

## Build and test

```bash
# no build; docs + issue forms only
```

Tests hit **live** public networks/APIs (the org rule is no mocks). A failure can be an upstream outage: re-run before changing code.

## Structure

| Path | What |
|---|---|
| `README.md` | event table |
| `.github/ISSUE_TEMPLATE/` | hackathon + submission forms |

## Conventions

- Only events verified on the organiser's own page.

## Extension points

- New field: edit the issue form YAML.

## Do

- Cite the organiser URL.

## Don't

- List unverified events.
- Commit secrets, keys or `.env` files. Run `gitleaks` before pushing; CI and the org policy reject leaks.

## Using it from another project

- **issues API** (http): `gh issue list -R Blockchains/hackathons`
- **.github/ISSUE_TEMPLATE/** (file): `.github/ISSUE_TEMPLATE/hackathon.yml`

See the README section [Use as a building block](README.md#use-as-a-building-block) for a copy-paste example.

## Related blocks

- [Blockchains/hackathon-entry-template](https://github.com/Blockchains/hackathon-entry-template): link the tracker issue from your entry
- [Blockchains/blockchainlab-feeds](https://github.com/Blockchains/blockchainlab-feeds): automated hackathon feed
- [Blockchains/blockchainlab-api](https://github.com/Blockchains/blockchainlab-api): `hackathons` dataset
