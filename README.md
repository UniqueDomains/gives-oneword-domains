# Available .GIVES One-Word Domains (15,701)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-15%2C701%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .gives one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **15,701 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 15,701 domains · **Median ask:** $10.23 · **High-demand under $2,500:** 16

**Last updated:** 2026-08-14
**Canonical page:** `https://unique.domains/domains/tld/gives`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/gives?utm_source=github&utm_medium=referral&utm_campaign=repo_gives_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./gives.csv">CSV</a> / <a href="./gives.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_gives_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_gives_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .GIVES search](https://unique.domains/domains/tld/gives?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_gives_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .GIVES search](https://unique.domains/domains/tld/gives?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_gives_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_gives_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .GIVES one-word domain catalog.

### Files

- `gives.csv`, public CSV extract (1,000 rows)
- `gives.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/gives-oneword-domains/main/gives.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain        | status    | ask_price | renewal_price | attractiveness | demand | length | registrar        |
| ------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ---------------- |
| content.gives | available | $5.99     | $40.99        | high           | low    | 7      | name.com         |
| come.gives    | available | $5.99     | —             | high           | low    | 4      | name.com         |
| ape.gives     | available | $5.99     | $40.99        | medium         | low    | 3      | name.com         |
| code.gives    | resell    | —         | —             | high           | medium | 4      | Dynadot Inc      |
| new.gives     | premium   | $78.54    | $78.54        | high           | medium | 3      | namesilo         |
| awe.gives     | available | $5.99     | —             | high           | low    | 3      | name.com         |
| receive.gives | resell    | —         | —             | high           | low    | 7      | GoDaddy.com, LLC |
| zen.gives     | premium   | $118.80   | $118.80       | high           | medium | 3      | namesilo         |
| bag.gives     | available | $5.99     | —             | high           | low    | 3      | name.com         |
| beer.gives    | premium   | $78.54    | $78.54        | high           | low    | 4      | namesilo         |
| bee.gives     | available | $5.99     | —             | high           | medium | 3      | name.com         |
| wife.gives    | premium   | $82.50    | —             | high           | low    | 4      | name.com         |
| clx.gives     | available | $5.99     | $40.99        | low            | low    | 3      | name.com         |
| angel.gives   | premium   | $82.50    | —             | high           | low    | 5      | name.com         |
| dip.gives     | available | $5.99     | $40.99        | high           | low    | 3      | name.com         |
| gates.gives   | premium   | $78.54    | $78.54        | high           | low    | 5      | namesilo         |
| due.gives     | available | $5.99     | —             | high           | low    | 3      | name.com         |
| hotel.gives   | premium   | $85.80    | $85.80        | high           | medium | 5      | namecheap        |
| Eid.gives     | available | $5.99     | —             | high           | low    | 3      | name.com         |
| promo.gives   | premium   | $82.50    | —             | high           | low    | 5      | name.com         |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 15,701 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 16 high-demand names under $2,500          |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/gives?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_gives_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/gives?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_gives_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_gives_oneword_domains&utm_content=related_pricing)

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

This selection covers one-word domain names on the .gives extension, a TLD naturally aligned with giving, causes, and gift-oriented branding. With 12,595 options and a median asking price near $12, the set ranges from plain nouns like "finals" and "criteria" to compound phrases like "midautumn" and "rolemodel." Because .gives is a newer extension, evaluating these names means weighing word clarity, pronounceability, and fit against traditional .com equivalents before committing.

- Median asking price near $12 across 12,595 .gives domains
- One-word, dictionary-based names like dogsick, finals, presents
- Well suited for causes, gifts, and donation-driven brands
- Updated daily to reflect the current .gives inventory

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .GIVES One-Word Domains*. Version 2026-08-14. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .GIVES page](https://unique.domains/domains/tld/gives?utm_source=github&utm_medium=referral&utm_campaign=repo_gives_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_gives_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_gives_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_gives_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
