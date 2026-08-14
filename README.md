# Available .MODA One-Word Domains (15,819)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-15%2C819%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .moda one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **15,819 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 15,819 domains · **Median ask:** $25.75 · **High-demand under $2,500:** 3

**Last updated:** 2026-08-14
**Canonical page:** `https://unique.domains/domains/tld/moda`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/moda?utm_source=github&utm_medium=referral&utm_campaign=repo_moda_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./moda.csv">CSV</a> / <a href="./moda.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_moda_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_moda_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .MODA search](https://unique.domains/domains/tld/moda?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_moda_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .MODA search](https://unique.domains/domains/tld/moda?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_moda_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_moda_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .MODA one-word domain catalog.

### Files

- `moda.csv`, public CSV extract (1,000 rows)
- `moda.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/moda-oneword-domains/main/moda.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain        | status    | ask_price | renewal_price | attractiveness | demand | length | registrar       |
| ------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------- |
| ago.moda      | available | $19.99    | $52.99        | medium         | low    | 3      | name.com        |
| only.moda     | resell    | —         | —             | high           | medium | 4      | Dynadot Inc     |
| bag.moda      | premium   | $118.80   | $118.80       | high           | low    | 3      | namesilo        |
| ape.moda      | available | $19.99    | $52.99        | medium         | low    | 3      | name.com        |
| house.moda    | resell    | —         | —             | high           | low    | 5      | Dynadot Inc     |
| hat.moda      | premium   | $118.80   | $118.80       | high           | low    | 3      | namesilo        |
| ask.moda      | available | $19.99    | —             | high           | medium | 3      | name.com        |
| digital.moda  | resell    | —         | —             | high           | medium | 7      | NameCheap, Inc. |
| lp.moda       | premium   | $118.80   | $118.80       | medium         | low    | 3      | namesilo        |
| Ava.moda      | available | $19.99    | —             | high           | medium | 3      | name.com        |
| baseball.moda | resell    | —         | —             | high           | low    | 8      | NameSilo, LLC   |
| men.moda      | premium   | $123.75   | —             | high           | low    | 3      | name.com        |
| azo.moda      | available | $19.99    | $52.99        | low            | low    | 3      | name.com        |
| red.moda      | premium   | $854      | $854          | high           | medium | 3      | namesilo        |
| bob.moda      | available | $19.99    | —             | high           | medium | 3      | name.com        |
| wig.moda      | premium   | $118.80   | $118.80       | high           | low    | 3      | namesilo        |
| bud.moda      | available | $19.99    | —             | high           | low    | 3      | name.com        |
| mint.moda     | premium   | $118.80   | $118.80       | high           | high   | 4      | namesilo        |
| bus.moda      | available | $19.99    | —             | high           | low    | 3      | name.com        |
| navy.moda     | premium   | $123.75   | —             | high           | low    | 4      | name.com        |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 15,819 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 3 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/moda?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_moda_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/moda?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_moda_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_moda_oneword_domains&utm_content=related_pricing)

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

This list covers one-word domain names registered under the .moda extension, a TLD often associated with fashion, design, and lifestyle branding. Names like jewels.moda, thanksgiving.moda, and neuroscience.moda show the range of vocabulary available in single-word form. With a median ask near $28, these domains sit at an accessible price point for comparing cost, renewal, and brandability before committing to a name. Updated daily, the selection spans everyday words, seasonal terms, and niche vocabulary suited to distinct positioning.

- 12,703 one-word .moda domain names in this selection
- Median ask near $28 across sampled listings
- Includes everyday words, seasonal terms, and niche vocabulary
- Updated daily to reflect current .moda availability and pricing

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .MODA One-Word Domains*. Version 2026-08-14. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .MODA page](https://unique.domains/domains/tld/moda?utm_source=github&utm_medium=referral&utm_campaign=repo_moda_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_moda_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_moda_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_moda_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
