# Available .FAST One-Word Domains (7,376)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-7%2C376%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-7%2C376%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated dataset of available and resale .fast one-word domains from Unique Domains.

> **Note:** this repository currently mirrors the full live catalog for this exact search.
> Unique Domains counts can still change as the search refreshes.

**Public extract:** 7,376 rows · **Live catalog:** 7,376 domains

**Last updated:** 2026-04-12  
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

- `fast.csv` — public CSV extract (7,376 rows)
- `fast.json` — public JSON extract (7,376 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/fast-oneword-domains/main/fast.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain         | status    | ask_price | renewal_price | attractiveness | demand | length | registrar      |
| -------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | -------------- |
| seventeen.fast | available | $35.98    | —             | 84             | 62     | 9      | namecheap      |
| gold.fast      | resell    | —         | —             | 72             | 99     | 4      | Dynadot, LLC   |
| easy.fast      | premium   | $325      | $325          | 128            | 68     | 4      | namecheap      |
| cozy.fast      | available | $35.98    | —             | 110            | 37     | 4      | namecheap      |
| chase.fast     | resell    | —         | —             | 66             | 85     | 5      | NameCheap, Inc |
| free.fast      | premium   | $1,250    | $1,250        | 88             | 59     | 4      | name.com       |
| aesthetic.fast | available | $35.98    | —             | 88             | 31     | 9      | namecheap      |
| paddle.fast    | resell    | —         | —             | 77             | 78     | 6      | NameCheap, Inc |
| ace.fast       | premium   | $625      | $625          | 88             | 57     | 3      | name.com       |
| curative.fast  | available | $35.98    | —             | 92             | 27     | 8      | namecheap      |
| switch.fast    | resell    | —         | —             | 70             | 68     | 6      | NameCheap, Inc |
| good.fast      | premium   | $312.50   | $312.50       | 82             | 55     | 4      | name.com       |
| crisp.fast     | available | $35.98    | —             | 68             | 27     | 5      | namecheap      |
| match.fast     | resell    | —         | —             | 102            | 65     | 5      | NameCheap, Inc |
| alpha.fast     | premium   | $312.50   | $312.50       | 90             | 54     | 5      | name.com       |
| adept.fast     | available | $35.98    | —             | 92             | 26     | 5      | namecheap      |
| power.fast     | resell    | —         | —             | 82             | 62     | 5      | Porkbun LLC    |
| zero.fast      | premium   | $312.50   | $312.50       | 112            | 53     | 4      | name.com       |
| tonic.fast     | available | $35.98    | —             | 114            | 25     | 5      | namecheap      |
| digital.fast   | resell    | —         | —             | 100            | 50     | 7      | Dynadot, LLC   |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                                   |
| ----------------------- | ------------------------------------------------ |
| 7,376-row public sample | 7,376 live domains                               |
| Static CSV / JSON       | live search and daily refresh                    |
| Basic exported fields   | deeper price, demand, risk, and workflow context |
| No persistence          | Radar, saved search, and alerts                  |
| No founder workflow     | Project, shortlist, and next-step workflow       |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/fast?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_fast_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/fast?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_fast_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_fast_oneword_domains&utm_content=related_pricing)

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

This repository follows the exact public search represented by the canonical page above.

- This repository is a public extract, not the full live catalog.
- Counts, prices, and statuses can change over time.
- Scores are decision-support signals, not guarantees of resale value.
- Trademark, SEO, and risk signals should be treated as screening inputs, not legal or specialist advice.
- Unique Domains contains deeper filters, monitoring, and decision workflows than this public extract.

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .FAST One-Word Domains*. Version 2026-04-12. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .FAST page](https://unique.domains/domains/tld/fast?utm_source=github&utm_medium=referral&utm_campaign=repo_fast_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_fast_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_fast_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_fast_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
