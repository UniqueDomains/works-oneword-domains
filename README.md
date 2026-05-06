# Available .WORKS One-Word Domains (10,493)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-10%2C493%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .works one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **10,493 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 10,493 domains · **Median ask:** $17.75 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-06  
**Canonical page:** `https://unique.domains/domains/tld/works`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/works?utm_source=github&utm_medium=referral&utm_campaign=repo_works_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./works.csv">CSV</a> / <a href="./works.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_works_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_works_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .WORKS search](https://unique.domains/domains/tld/works?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_works_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .WORKS search](https://unique.domains/domains/tld/works?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_works_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_works_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .WORKS one-word domain catalog.

### Files

- `works.csv` — public CSV extract (1,000 rows)
- `works.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/works-oneword-domains/main/works.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain             | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                                 |
| ------------------ | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------------------------------------------------- |
| ladies.works       | available | $7.99     | —             | 80             | 17     | 6      | name.com                                                  |
| geton.works        | available | $7.99     | —             | 82             | 10     | 6      | name.com                                                  |
| getup.works        | available | $7.99     | —             | 82             | 14     | 6      | name.com                                                  |
| playin.works       | available | $7.99     | —             | 80             | 10     | 7      | name.com                                                  |
| toneup.works       | available | $7.99     | —             | 80             | 5      | 7      | name.com                                                  |
| hangon.works       | available | $7.99     | —             | 82             | 6      | 7      | name.com                                                  |
| stirup.works       | available | $7.99     | —             | 82             | 3      | 7      | name.com                                                  |
| getlife.works      | available | $7.99     | —             | 80             | 5      | 8      | name.com                                                  |
| presents.works     | available | $7.99     | —             | 80             | 9      | 8      | name.com                                                  |
| Snickers.works     | available | $51.98    | —             | 80             | 10     | 8      | namecheap                                                 |
| rumcake.works      | available | $7.99     | —             | 81             | 3      | 8      | name.com                                                  |
| FabFour.works      | available | $7.99     | —             | 82             | 3      | 8      | name.com                                                  |
| lightup.works      | available | $7.99     | —             | 82             | 15     | 8      | name.com                                                  |
| neuroscience.works | available | $7.99     | —             | 80             | 37     | 12     | name.com                                                  |
| online.works       | resell    | —         | —             | 70             | 62     | 7      | Global Domains International, Inc. DBA DomainCostClub.com |
| tickets.works      | premium   | $500      | —             | 64             | 34     | 7      | name.com                                                  |
| seeds.works        | available | $7.99     | —             | 59             | 28     | 5      | name.com                                                  |
| art.works          | resell    | —         | —             | 90             | 51     | 3      | Porkbun LLC                                               |
| solutions.works    | premium   | $500      | —             | 56             | 31     | 9      | name.com                                                  |
| destination.works  | available | $7.99     | —             | 90             | 25     | 11     | name.com                                                  |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 10,493 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/works?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_works_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/works?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_works_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_works_oneword_domains&utm_content=related_pricing)

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

This selection is focused entirely on one-word domains in the .works extension. The set is broad, with examples ranging from action-led words like Getup.works and Geton.works to category or audience terms like Jewels.works, Ladies.works, and Finals.works. For founders, the main question is whether the word and the .works ending form a clear, memorable brand. For investors, the priority is whether the pairing feels commercially usable enough to attract resale demand. With a median ask of 17.75, price discipline matters less than fit, spelling clarity, and whether the term looks generic, versatile, and easy to understand at a glance.

- Check whether the word reads naturally with .works
- Favor clear, generic words over awkward pairings
- Use price discipline: median ask is 17.75
- Review possible trademark sensitivity in branded terms

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .WORKS One-Word Domains*. Version 2026-05-06. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .WORKS page](https://unique.domains/domains/tld/works?utm_source=github&utm_medium=referral&utm_campaign=repo_works_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_works_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_works_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_works_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
