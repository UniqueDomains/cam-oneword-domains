# Available .CAM One-Word Domains (11,971)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-11%2C971%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .cam one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **11,971 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 11,971 domains · **Median ask:** $288.75 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-27  
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

- `cam.csv` — public CSV extract (1,000 rows)
- `cam.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/cam-oneword-domains/main/cam.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain       | status    | ask_price | renewal_price | attractiveness | demand | length | registrar       |
| ------------ | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------- |
| RedSox.cam   | available | $22.98    | —             | 72             | 60     | 7      | namecheap       |
| matcha.cam   | resell    | —         | —             | 86             | 39     | 6      | Spaceship, Inc. |
| jobs.cam     | premium   | $1,875    | —             | 79             | 42     | 4      | name.com        |
| letsgo.cam   | available | $22.98    | —             | 57             | 31     | 7      | namecheap       |
| justin.cam   | resell    | —         | —             | 58             | 38     | 7      | Dynadot LLC     |
| Tools.cam    | premium   | $560      | $19.60        | 56             | 40     | 5      | namecheap       |
| quotes.cam   | available | $22.98    | —             | 58             | 29     | 6      | namecheap       |
| gems.cam     | resell    | —         | —             | 70             | 28     | 4      | Spaceship, Inc. |
| WiFi.cam     | premium   | $2,100    | $19.60        | 83             | 37     | 5      | namecheap       |
| brands.cam   | available | $22.98    | —             | 62             | 28     | 6      | namecheap       |
| sites.cam    | resell    | —         | —             | 53             | 26     | 5      | Porkbun, LLC    |
| etc.cam      | premium   | $1,000    | —             | 58             | 32     | 3      | name.com        |
| systems.cam  | available | $22.98    | —             | 46             | 27     | 7      | namecheap       |
| reports.cam  | resell    | —         | —             | 58             | 24     | 7      | Spaceship, Inc. |
| William.cam  | premium   | $1,120    | $19.60        | 74             | 31     | 7      | namecheap       |
| chem.cam     | available | $22.98    | —             | 74             | 24     | 4      | namecheap       |
| products.cam | resell    | —         | —             | 60             | 23     | 8      | Porkbun, LLC    |
| dogs.cam     | premium   | $1,875    | —             | 76             | 28     | 4      | name.com        |
| inhouse.cam  | available | $22.98    | —             | 70             | 24     | 8      | namecheap       |
| guns.cam     | resell    | —         | —             | 68             | 22     | 4      | Spaceship, Inc. |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 11,971 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/cam?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_cam_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/cam?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_cam_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_cam_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain` — Fully qualified domain name.
- `status` — Current acquisition state for the domain in the public extract.
- `purchase_price` — Visible purchase price when available.
- `renewal_price` — Visible renewal price when available.
- `attractiveness` — Composite naming score used as a decision-support signal.
- `demand` — Relative buyer-pressure score when available.
- `length` — Character count without the TLD.
- `registrar` — Registrar name when known.
- `created_at` — Creation timestamp when known.
- `expires_at` — Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This set is focused on one-word .cam domains, which gives it a very specific profile. The names range from short, flexible words like eleven.cam and desire.cam to longer dictionary terms like allowance.cam and compulsory.cam. For founders, the main question is whether the word is memorable, easy to say, and strong enough to carry a brand on a less common extension. For investors, the key is price discipline: the median ask is 288.75, so compare each word’s clarity and commercial relevance against that baseline. In this selection, stronger candidates are usually simple words with broad meaning and fewer spelling doubts.

- One-word .cam names only
- 11,958 domains in this selection
- Median ask: 288.75
- Short, clear words tend to compare better

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .CAM One-Word Domains*. Version 2026-05-27. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .CAM page](https://unique.domains/domains/tld/cam?utm_source=github&utm_medium=referral&utm_campaign=repo_cam_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_cam_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_cam_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_cam_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
