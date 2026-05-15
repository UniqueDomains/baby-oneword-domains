# Available .BABY One-Word Domains (11,452)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-11%2C452%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .baby one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **11,452 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 11,452 domains · **Median ask:** $51.60 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-15  
**Canonical page:** `https://unique.domains/domains/tld/baby`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/baby?utm_source=github&utm_medium=referral&utm_campaign=repo_baby_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./baby.csv">CSV</a> / <a href="./baby.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_baby_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_baby_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .BABY search](https://unique.domains/domains/tld/baby?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_baby_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .BABY search](https://unique.domains/domains/tld/baby?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_baby_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_baby_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .BABY one-word domain catalog.

### Files

- `baby.csv` — public CSV extract (1,000 rows)
- `baby.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/baby-oneword-domains/main/baby.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain            | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                    |
| ----------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | -------------------------------------------- |
| makers.baby       | available | $17.99    | $54.99        | 62             | 67     | 6      | namesilo                                     |
| lens.baby         | resell    | —         | —             | 62             | 69     | 4      | Spaceship, Inc.                              |
| sites.baby        | premium   | $250      | —             | 53             | 26     | 5      | name.com                                     |
| donuts.baby       | available | $29.99    | —             | 54             | 62     | 6      | name.com                                     |
| fun.baby          | resell    | —         | —             | 90             | 62     | 3      | Xiamen ChinaSource Internet Service Co., Ltd |
| loans.baby        | premium   | $3,125    | —             | 58             | 24     | 5      | name.com                                     |
| bits.baby         | available | $29.99    | —             | 71             | 33     | 4      | name.com                                     |
| ideas.baby        | resell    | —         | —             | 62             | 37     | 5      | Go Daddy, LLC                                |
| suits.baby        | premium   | $250      | —             | 61             | 13     | 5      | name.com                                     |
| popup.baby        | available | $29.99    | —             | 84             | 29     | 6      | name.com                                     |
| Bets.baby         | resell    | —         | —             | 72             | 34     | 4      | Spaceship, Inc.                              |
| status.baby       | premium   | —         | —             | 76             | 40     | 6      | —                                            |
| dogs.baby         | available | $29.99    | —             | 76             | 28     | 4      | name.com                                     |
| spectra.baby      | resell    | —         | —             | 62             | 34     | 7      | Dynadot LLC                                  |
| volcano.baby      | premium   | —         | —             | 70             | 25     | 7      | —                                            |
| commonground.baby | available | $29.99    | —             | 74             | 28     | 13     | name.com                                     |
| spin.baby         | resell    | —         | —             | 76             | 31     | 4      | Spaceship, Inc.                              |
| hill.baby         | premium   | —         | —             | 66             | 25     | 4      | —                                            |
| pages.baby        | available | $29.99    | —             | 52             | 28     | 5      | name.com                                     |
| toy.baby          | resell    | —         | —             | 76             | 29     | 3      | Dynadot LLC                                  |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 11,452 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/baby?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_baby_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/baby?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_baby_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_baby_oneword_domains&utm_content=related_pricing)

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

This selection is entirely made up of one-word .baby domains, which makes it useful for buyers comparing exact-word clarity against extension fit. The set ranges from concrete words like floor.baby and mill.baby to broader terms like discuss.baby and correlate.baby, plus geographic or commercial words such as canada.baby and ticket.baby. With a median ask of 51.60, price is accessible at the middle of the list, but the stronger names still depend on how naturally the word pairs with .baby. When comparing these domains, focus on memorability, direct relevance to baby products or parenting, and whether the word creates trust rather than confusion or negative tone.

- Prefer words that pair naturally with the .baby extension
- Check for clear meaning, spelling ease, and recall
- Watch for weak or negative terms like shame.baby
- Use price discipline around the 51.60 median ask

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .BABY One-Word Domains*. Version 2026-05-15. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .BABY page](https://unique.domains/domains/tld/baby?utm_source=github&utm_medium=referral&utm_campaign=repo_baby_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_baby_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_baby_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_baby_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
