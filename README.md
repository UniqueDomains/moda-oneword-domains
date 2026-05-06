# Available .MODA One-Word Domains (12,704)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C704%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .moda one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,704 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,704 domains · **Median ask:** $26.08 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-06  
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

- `moda.csv` — public CSV extract (1,000 rows)
- `moda.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/moda-oneword-domains/main/moda.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain            | status    | ask_price | renewal_price | attractiveness | demand | length | registrar |
| ----------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------- |
| WiFi.moda         | available | $45.98    | —             | 83             | 37     | 5      | namecheap |
| dogsit.moda       | available | $19.99    | —             | 96             | 2      | 6      | name.com  |
| makeit.moda       | available | $19.99    | —             | 82             | 22     | 7      | name.com  |
| messages.moda     | available | $19.99    | —             | 80             | 16     | 8      | name.com  |
| presents.moda     | available | $19.99    | —             | 80             | 9      | 8      | name.com  |
| Ryan.moda         | available | $45.98    | —             | 60             | 44     | 4      | namecheap |
| jobs.moda         | premium   | $123.75   | —             | 79             | 42     | 4      | name.com  |
| shortcuts.moda    | available | $19.99    | —             | 48             | 41     | 10     | name.com  |
| trends.moda       | premium   | $123.75   | —             | 60             | 32     | 6      | name.com  |
| prompts.moda      | available | $19.99    | —             | 54             | 39     | 7      | name.com  |
| tips.moda         | premium   | $123.75   | —             | 80             | 26     | 4      | name.com  |
| justin.moda       | available | $19.99    | —             | 58             | 38     | 7      | name.com  |
| designs.moda      | premium   | $1,000    | —             | 72             | 21     | 7      | name.com  |
| watches.moda      | premium   | $123.75   | —             | 84             | 19     | 7      | name.com  |
| neuroscience.moda | available | $19.99    | —             | 80             | 37     | 12     | name.com  |
| nails.moda        | premium   | $123.75   | —             | 62             | 18     | 5      | name.com  |
| Cats.moda         | available | $45.98    | —             | 59             | 33     | 4      | namecheap |
| coats.moda        | premium   | $123.75   | —             | 68             | 12     | 5      | name.com  |
| inspiration.moda  | available | $19.99    | —             | 88             | 30     | 11     | name.com  |
| dresses.moda      | premium   | $1,000    | —             | 58             | 10     | 7      | name.com  |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,704 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/moda?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_moda_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/moda?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_moda_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_moda_oneword_domains&utm_content=related_pricing)

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

This selection is entirely made up of one-word .moda domains. That makes relevance the first filter: the best candidates are words that immediately make sense in fashion, beauty, accessories, or style-led retail. Examples such as jewels.moda, ladies.moda, and getup.moda are more intuitive than broader terms like forces.moda or finals.moda. The median ask is 26.08, so price is generally accessible, but extension fit matters more than headline cost. When comparing these domains, focus on whether the word is easy to read, category-specific, and strong enough to offset the narrower recognition of .moda outside fashion contexts.

- Best fit: fashion, beauty, apparel, jewelry, style retail
- Median ask is 26.08 across 12,704 .moda domains
- Clear category words tend to feel more brandable here
- Check trademark overlap before choosing generic-looking terms

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .MODA One-Word Domains*. Version 2026-05-06. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .MODA page](https://unique.domains/domains/tld/moda?utm_source=github&utm_medium=referral&utm_campaign=repo_moda_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_moda_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_moda_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_moda_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
