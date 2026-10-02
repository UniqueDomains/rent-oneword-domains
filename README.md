# Available .RENT One-Word Domains (32,610)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-32%2C610%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .rent one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **32,610 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 32,610 domains · **Median ask:** $55.11 · **High-demand under $2,500:** 122

**Last updated:** 2026-10-02
**Canonical page:** `https://unique.domains/domains/tld/rent`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/rent?utm_source=github&utm_medium=referral&utm_campaign=repo_rent_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./rent.csv">CSV</a> / <a href="./rent.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_rent_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_rent_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .RENT search](https://unique.domains/domains/tld/rent?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_rent_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .RENT search](https://unique.domains/domains/tld/rent?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_rent_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_rent_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .RENT one-word domain catalog.

### Files

- `rent.csv`, public CSV extract (1,000 rows)
- `rent.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/rent-oneword-domains/main/rent.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain     | status    | ask_price | renewal_price | attractiveness | demand | length | registrar          |
| ---------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ------------------ |
| aku.rent   | available | $17.99    | $59.99        | high           | low    | 3      | namesilo           |
| job.rent   | resell    | —         | —             | high           | medium | 3      | Spaceship, Inc.    |
| bin.rent   | premium   | $250      | $250          | high           | low    | 3      | name.com           |
| auc.rent   | available | $17.99    | $59.99        | high           | low    | 3      | namesilo           |
| cool.rent  | resell    | —         | —             | high           | medium | 4      | GoDaddy.com, LLC   |
| llc.rent   | premium   | $640      | $640          | high           | low    | 3      | namesilo           |
| bad.rent   | available | $29.99    | $94.99        | high           | medium | 3      | name.com           |
| data.rent  | resell    | —         | —             | high           | medium | 4      | DNC Holdings, Inc. |
| oak.rent   | premium   | $1,092.18 | $1,092.18     | high           | low    | 3      | porkbun            |
| bmi.rent   | available | $17.99    | $59.99        | high           | medium | 3      | namesilo           |
| hype.rent  | resell    | —         | —             | high           | medium | 4      | —                  |
| six.rent   | premium   | $3,450    | $3,450        | high           | low    | 3      | namesilo           |
| chp.rent   | available | $1.50     | $81.98        | medium         | low    | 3      | namecheap          |
| lord.rent  | resell    | —         | —             | high           | low    | 4      | GoDaddy.com, LLC   |
| exit.rent  | premium   | $1,300    | $1,300        | high           | low    | 4      | namecheap          |
| chu.rent   | available | $17.99    | $59.99        | medium         | low    | 3      | namesilo           |
| pets.rent  | resell    | —         | —             | medium         | low    | 4      | —                  |
| late.rent  | premium   | $650      | $650          | high           | low    | 4      | namecheap          |
| cot.rent   | available | $17.99    | $59.99        | high           | low    | 3      | namesilo           |
| aware.rent | resell    | —         | —             | high           | low    | 5      | Spaceship, Inc.    |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 32,610 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 122 high-demand names under $2,500         |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/rent?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_rent_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/rent?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_rent_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_rent_oneword_domains&utm_content=related_pricing)

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
- `status_verified_at`, When status was last established against the registry. Null means never checked.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This set gathers one-word domain names on the .rent extension, spanning everyday nouns, verbs, and short phrases like presents.rent, tips.rent, and edamame.rent. With 12,128 names and a median asking price near $106, the range covers both budget-friendly picks and higher-priced options. Because .rent ties directly to housing, leasing, and short-term rental use cases, many names carry clear thematic relevance for founders in that space, while investors can compare asking prices across a large pool of available names. Updated daily, this list reflects current asking prices so you can weigh cost against brandability and renewal risk before committing to a name.

- 12,128 one-word .rent domain names in this selection
- Median asking price near $106 across the set
- Includes everyday words like tips.rent and presents.rent
- Updated daily to reflect current pricing

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The snapshot date above is when this file was written, not when each row was checked. Read `status_verified_at` for that: a name whose status was last established months ago is exported with its real date rather than the snapshot's.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .RENT One-Word Domains*. Version 2026-10-02. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .RENT page](https://unique.domains/domains/tld/rent?utm_source=github&utm_medium=referral&utm_campaign=repo_rent_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_rent_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_rent_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_rent_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `kai@unique.domains`
