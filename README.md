# Blockchain Lab Hackathons

Tracker for blockchain / web3 hackathons Blockchain Lab may enter. One issue per hackathon ([new hackathon](../../issues/new?template=hackathon.yml)), one per entry ([new entry](../../issues/new?template=submission.yml)). Start entries from [`Blockchains/hackathon-entry-template`](https://github.com/Blockchains/hackathon-entry-template).

**Labels:** `status:open` → `status:applied` → `status:building` → `status:submitted` → `status:won` / `status:not-placed` (or `status:closed` if skipped/expired) · `platform:*` · `format:online|in-person`

[Open hackathons](../../issues?q=is%3Aissue+is%3Aopen+label%3Ahackathon) · [All](../../issues?q=is%3Aissue+label%3Ahackathon)

## Seeded 3 Oct 2026 (open or upcoming, verified on organiser pages)

| Hackathon | Dates | Prize | Format | Link |
|---|---|---|---|---|
| Solana — Perps and Prediction Markets | one-week build; deadline 9 Oct 2026 | $100,000 (1st $50k / 2nd $30k / 3rd $20k) | Online | https://hackathons.solana.com/hackathons/perps-and-prediction-markets |
| Monad Metropolis | 1 Sep – 13 Oct 2026 (submission deadline 13 Oct; winners 3 Nov) | $250,000+ | Online | https://www.monad.xyz/metropolis |
| Encode London Hackathon | 23 – 25 Oct 2026 | Prizes TBA (bounties / partner challenges) | In person, London | https://luma.com/encode-london-2026 |
| IEEE ClimateChain Global Hackathon (AI + blockchain) | 5 – 25 Oct 2026 | $3,000 cash (students only) | Online | https://ieee-climatechain-hack.devpost.com/ |
| TUM Blockchain & AI Hackathon — Agentic Payments | 30 – 31 Oct 2026 | €4,000 BSV track (more tracks TBA) | In person, Munich | https://tum.devfolio.co/overview |
| BNB Chain — The Smart Money Era: Set and Earn | 1 Oct – 5 Nov 2026 12:00 UTC | $10,000 in merchandise (first 100 wallets) | Online | https://www.bnbchain.org/en/hackathons/smart-money-era-set-and-earn |
| ETHGlobal Mumbai | 5 – 7 Nov 2026 (submissions by 8 Nov 09:00 IST) | Partner prize pools (largest $20,000) | In person, Mumbai | https://ethglobal.com/events/mumbai |

Not seeded: no currently open DoraHacks or Gitcoin web3 hackathon could be verified on the organiser's own page on 3 Oct 2026 (DoraHacks blocks automated reads; Gitcoin had no hackathon listed).

Live calendar of events and hackathons: **https://blockchains.github.io/events/**

<!-- blocks:start -->
## Use as a building block

> **For AI agents and builders:** read [`AGENTS.md`](AGENTS.md) (setup, commands, structure, rules), [`llms.txt`](llms.txt) (doc map) and the machine-readable [`blocks.json`](blocks.json) ([schema](https://github.com/Blockchains/.github/blob/main/docs/BLOCKS-SCHEMA.md)). How all Blockchains blocks fit together: **[Build with Blocks](https://github.com/Blockchains/.github/blob/main/docs/BUILD-WITH-BLOCKS.md)** · org catalogue: [https://blockchains.github.io/blocks.json](https://blockchains.github.io/blocks.json).

**What it exports**

| Export | Type | Install / access |
|---|---|---|
| `issues API` | http | `gh issue list -R Blockchains/hackathons` |
| `.github/ISSUE_TEMPLATE/` | file | `.github/ISSUE_TEMPLATE/hackathon.yml` |

**Minimal example**

```bash
gh issue list -R Blockchains/hackathons --state open --json number,title,url
```

**Inputs → outputs**

- In: `issue form` (GitHub issue)
- Out: `tracker issues` (GitHub issues); `README table` (Markdown)

**Composes with**

- [Blockchains/hackathon-entry-template](https://github.com/Blockchains/hackathon-entry-template): link the tracker issue from your entry
- [Blockchains/blockchainlab-feeds](https://github.com/Blockchains/blockchainlab-feeds): automated hackathon feed
- [Blockchains/blockchainlab-api](https://github.com/Blockchains/blockchainlab-api): `hackathons` dataset

**Versioning & stability:** `stable`. Issue forms are stable; README table is refreshed by hand.
<!-- blocks:end -->

## Licence

No licence file; this is an issue tracker. Event details belong to their organisers.

## Contributing

Issues and pull requests are welcome. Please read the [contributing guide](https://github.com/Blockchains/.github/blob/main/CONTRIBUTING.md), [code of conduct](https://github.com/Blockchains/.github/blob/main/CODE_OF_CONDUCT.md) and [security policy](https://github.com/Blockchains/.github/blob/main/SECURITY.md) first.

---
Built by Blockchain Lab — [blockchainlab.com](https://blockchainlab.com/?utm_source=github&utm_medium=readme&utm_campaign=hackathons)
