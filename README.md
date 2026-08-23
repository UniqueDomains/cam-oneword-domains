# Available .CAM One-Word Domains (17,796)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-17%2C796%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .cam one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **17,796 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 17,796 domains · **Median ask:** $321.28 · **High-demand under $2,500:** 39

**Last updated:** 2026-08-23
**Canonical page:** `https://unique.domains/domains/tld/cam`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/cam?utm_source=github&utm_medium=referral&utm_campaign=repo_cam_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./cam.csv">CSV</a> / <a href="./cam.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_cam_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_cam_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .CAM search](https://unique.domains/domains/tld/cam?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_cam_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .CAM search](https://unique.domains/domains/tld/cam?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_cam_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_cam_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .CAM one-word domain catalog.

### Files

- `cam.csv`, public CSV extract (1,000 rows)
- `cam.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/cam-oneword-domains/main/cam.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain    | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                  |
| --------- | --------- | --------- | ------------- | -------------- | ------ | ------ | -------------------------- |
| jot.cam   | available | $8.99     | $17.49        | high           | low    | 3      | namesilo                   |
| agile.cam | resell    | $5,520    | $29.99        | high           | medium | 5      | Spaceship, Inc.            |
| add.cam   | premium   | $854      | $16.52        | high           | low    | 3      | namesilo                   |
| LLP.cam   | available | $8.99     | $17.49        | high           | low    | 3      | namesilo                   |
| city.cam  | resell    | —         | —             | high           | medium | 4      | Dynadot LLC                |
| bce.cam   | premium   | $500      | —             | medium         | low    | 3      | name.com                   |
| arid.cam  | available | $2.98     | $22.98        | low            | low    | 4      | namecheap                  |
| firm.cam  | resell    | —         | —             | high           | low    | 4      | Dynadot LLC                |
| dad.cam   | premium   | $1,875    | —             | high           | low    | 3      | name.com                   |
| been.cam  | available | $8.99     | $17.49        | medium         | low    | 4      | namesilo                   |
| join.cam  | resell    | —         | —             | high           | medium | 4      | Porkbun, LLC               |
| dry.cam   | premium   | $500      | $29.99        | high           | low    | 3      | name.com                   |
| boer.cam  | available | $2.98     | $22.98        | low            | low    | 4      | namecheap                  |
| loft.cam  | resell    | —         | —             | medium         | low    | 4      | Spaceship, Inc.            |
| dvd.cam   | premium   | $1,875    | —             | high           | low    | 3      | name.com                   |
| fill.cam  | available | $8.99     | $17.49        | medium         | low    | 4      | namesilo                   |
| need.cam  | resell    | —         | —             | high           | low    | 4      | Dynadot LLC                |
| ego.cam   | premium   | $1,875    | —             | medium         | low    | 3      | name.com                   |
| fond.cam  | available | $8.99     | $17.49        | high           | low    | 4      | namesilo                   |
| ride.cam  | resell    | —         | —             | high           | low    | 4      | Squarespace Domains II LLC |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 17,796 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 39 high-demand names under $2,500          |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/cam?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_cam_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/cam?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_cam_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_cam_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain`, Fully qualified domain name.
- `status`, Current acquisition state for the domain in the public extract.
- `purchase_price`, Visible purchase price when available.
- `renewal_price`, Visible renewal price when available.
- `attractiveness`, Public composite naming band used as a decision-support signal.
- `demand`, Public buyer-pressure band when available.
- `length`, Character count without the TLD.
- `registrar`, Registrar name when known.
- `created_at`, Creation timestamp when known.
- `expires_at`, Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This list covers one-word domain names on the .cam extension, spanning short, brandable words across modern, elegant, and playful tones. Most of these domains are entry-priced, with 9,130 listed under $500 and 1,327 in the $500–$2,000 range. A thin top tier — 64 domains — asks $10,000 or more, reflecting higher demand signals or shorter, more brandable names.

- 10,098 available, 1,409 premium, 477 resell listings
- 9,130 domains priced under $500
- Median ask near $421 across the full set
- 64 domains priced at $10,000 or higher

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .CAM One-Word Domains*. Version 2026-08-23. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .CAM page](https://unique.domains/domains/tld/cam?utm_source=github&utm_medium=referral&utm_campaign=repo_cam_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_cam_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_cam_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_cam_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
