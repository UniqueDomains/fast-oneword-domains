# Available .FAST One-Word Domains (10,351)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-10%2C351%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .fast one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **10,351 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 10,351 domains · **Median ask:** $82.43 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-06  
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

- `fast.csv` — public CSV extract (1,000 rows)
- `fast.json` — public JSON extract (1,000 rows)
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

| domain            | status    | ask_price | renewal_price | attractiveness | demand | length | registrar             |
| ----------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------------- |
| CocaCola.fast     | available | $35.98    | —             | 92             | 82     | 9      | namecheap             |
| warp.fast         | resell    | —         | —             | 72             | 44     | 4      | 101domain GRS Limited |
| hotels.fast       | premium   | $3,125    | —             | 64             | 82     | 6      | name.com              |
| RedSox.fast       | available | $35.98    | —             | 72             | 60     | 7      | namecheap             |
| update.fast       | resell    | —         | —             | 88             | 29     | 7      | NameCheap, Inc        |
| makers.fast       | premium   | $53.92    | $53.92        | 62             | 67     | 6      | namesilo              |
| matcha.fast       | available | $35.98    | —             | 86             | 39     | 6      | namecheap             |
| reservations.fast | resell    | —         | —             | 50             | 17     | 12     | NameCheap, Inc        |
| travelers.fast    | premium   | $53.92    | $53.92        | 58             | 61     | 9      | namesilo              |
| whynot.fast       | available | $35.98    | —             | 74             | 39     | 7      | namecheap             |
| farmers.fast      | premium   | $62.50    | —             | 54             | 59     | 7      | name.com              |
| neuroscience.fast | available | $35.98    | —             | 80             | 37     | 12     | namecheap             |
| Ryan.fast         | premium   | $350      | $350          | 60             | 44     | 4      | namecheap             |
| popup.fast        | available | $35.98    | —             | 84             | 29     | 6      | namecheap             |
| lets.fast         | premium   | $312.50   | —             | 77             | 39     | 4      | name.com              |
| Trex.fast         | available | $35.98    | —             | 80             | 24     | 5      | namecheap             |
| stories.fast      | premium   | $625      | —             | 58             | 36     | 7      | name.com              |
| pops.fast         | available | $29.49    | $29.49        | 74             | 24     | 4      | namesilo              |
| teams.fast        | premium   | $125      | —             | 62             | 32     | 5      | name.com              |
| echoes.fast       | available | $29.49    | $29.49        | 56             | 24     | 6      | namesilo              |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 10,351 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

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

This selection is made up of one-word domains on the .fast extension. The set spans broad styles, from clean generics like first.fast and detail.fast to more expressive options like reflex.fast and resounding.fast. With a median ask of $82.43, many of these domains sit in a low entry-price range, but price alone should not decide the pick. When comparing these domains, focus on whether the word is easy to say, easy to remember, and naturally fits the speed-driven signal of .fast. Also check for trademark sensitivity, especially on branded or character-based terms such as Godzilla.fast.

- One-word .fast domains with broad brandability range
- Median ask across this selection is $82.43
- Best fits pair clean words with the .fast meaning
- Check trademark risk on branded or famous terms

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .FAST One-Word Domains*. Version 2026-05-06. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .FAST page](https://unique.domains/domains/tld/fast?utm_source=github&utm_medium=referral&utm_campaign=repo_fast_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_fast_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_fast_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_fast_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
