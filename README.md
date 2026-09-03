# Available .FAST One-Word Domains (19,944)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-19%2C944%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .fast one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **19,944 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 19,944 domains · **Median ask:** $75.86 · **High-demand under $2,500:** 64

**Last updated:** 2026-09-03
**Canonical page:** `https://unique.domains/domains/tld/fast`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/fast?utm_source=github&utm_medium=referral&utm_campaign=repo_fast_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./fast.csv">CSV</a> / <a href="./fast.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_fast_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_fast_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .FAST search](https://unique.domains/domains/tld/fast?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_fast_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .FAST search](https://unique.domains/domains/tld/fast?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_fast_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_fast_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .FAST one-word domain catalog.

### Files

- `fast.csv`, public CSV extract (1,000 rows)
- `fast.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/fast-oneword-domains/main/fast.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain       | status    | ask_price | renewal_price | attractiveness | demand | length | registrar       |
| ------------ | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------- |
| bulb.fast    | available | $29.49    | $29.49        | high           | low    | 4      | namesilo        |
| doit.fast    | resell    | —         | —             | high           | low    | 5      | Spaceship, Inc. |
| age.fast     | premium   | $625      | —             | high           | low    | 3      | name.com        |
| choc.fast    | available | $29.49    | $29.49        | high           | low    | 4      | namesilo        |
| pivot.fast   | resell    | —         | —             | high           | low    | 5      | NameCheap, Inc  |
| ale.fast     | premium   | $625      | —             | medium         | low    | 3      | name.com        |
| diva.fast    | available | $29.49    | $29.49        | high           | low    | 4      | namesilo        |
| throw.fast   | resell    | —         | —             | high           | low    | 5      | NameCheap, Inc  |
| ana.fast     | premium   | $625      | —             | high           | low    | 3      | name.com        |
| DSLR.fast    | available | $29.49    | $29.49        | high           | low    | 4      | namesilo        |
| attack.fast  | resell    | —         | —             | medium         | low    | 6      | NameCheap, Inc  |
| Ann.fast     | premium   | $625      | —             | high           | low    | 3      | name.com        |
| lego.fast    | available | $29.49    | $29.49        | high           | high   | 4      | namesilo        |
| ignite.fast  | resell    | —         | —             | high           | low    | 6      | Dynadot, LLC    |
| are.fast     | premium   | $625      | —             | high           | low    | 3      | name.com        |
| mash.fast    | available | $29.49    | $29.49        | medium         | low    | 4      | namesilo        |
| matrix.fast  | resell    | —         | —             | medium         | medium | 6      | Dynadot, LLC    |
| atp.fast     | premium   | $625      | —             | medium         | low    | 3      | name.com        |
| nana.fast    | available | $29.49    | $29.49        | high           | low    | 4      | namesilo        |
| biology.fast | resell    | —         | —             | high           | low    | 7      | Spaceship, Inc. |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 19,944 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 64 high-demand names under $2,500          |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/fast?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_fast_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/fast?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_fast_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_fast_oneword_domains&utm_content=related_pricing)

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

This selection covers one-word domain names registered under the .fast extension, ranging from short, punchy names like Acup.fast and Toneup.fast to descriptive terms such as Neuroscience.fast and Counselling.fast. With 10,356 domains in this set and a median asking price near $106, the list spans a wide range of naming styles and price points. Founders can scan for ownable, easy-to-pronounce names, while investors can compare asking prices to judge deal quality within the .fast namespace. Because .fast is a newer extension, brandability and clarity typically matter more than trademark history — evaluate each name for spelling simplicity, industry fit, and renewal cost before committing.

- 10,356 one-word .fast domains in this set
- Median asking price near $106 across the list
- Names range from short brands to descriptive terms
- Evaluate spelling, industry fit, and renewal cost

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .FAST One-Word Domains*. Version 2026-09-03. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .FAST page](https://unique.domains/domains/tld/fast?utm_source=github&utm_medium=referral&utm_campaign=repo_fast_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_fast_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_fast_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_fast_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
