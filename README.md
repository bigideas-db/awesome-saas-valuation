<div align="center">
  <sup>This list is sponsored and maintained by:</sup>
  <br><br>
  <a href="https://bigideasdb.com/?utm_source=github&utm_medium=awesome-saas-valuation&utm_campaign=awesome-list">
    <img alt="BigIdeasDB" width="96" src="assets/bigideasdb-logo.png">
  </a>
  <br>
  <a href="https://bigideasdb.com/?utm_source=github&utm_medium=awesome-saas-valuation&utm_campaign=awesome-list"><b>BigIdeasDB</b></a>: the business research platform for deciding what to start, build or buy.
  <br>
  <sub>1M+ real customer complaints, SaaS and online businesses for sale with asking prices, verified revenue data and funded-startup intelligence.</sub>
  <br><br>
</div>
<hr>

# Awesome SaaS Valuation [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[![Sponsored by BigIdeasDB](https://img.shields.io/badge/Sponsored%20by-BigIdeasDB-f97316)](https://bigideasdb.com/?utm_source=github&utm_medium=awesome-saas-valuation&utm_campaign=awesome-list)
![Data snapshot](https://img.shields.io/badge/data-November%202026-0ea5e9)
![Entries](https://img.shields.io/badge/ranked%20entries-270%2B-22c55e)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](LICENSE)

> A curated, data-ranked guide to **SaaS valuation**: what small and micro SaaS companies are priced at, by category, size, margin, churn and age, with the formulas, a calculator walkthrough and a due diligence checklist. Every multiple is ranked from real listings, not opinion, from [BigIdeasDB](https://bigideasdb.com/?utm_source=github&utm_medium=awesome-saas-valuation&utm_campaign=awesome-list).

**SaaS valuation** is the process of putting a price on a software-as-a-service business, usually as a multiple of annual recurring revenue (ARR) or of profit (SDE or EBITDA). Owner-operated micro SaaS is usually priced on profit multiples, while larger SaaS is priced on revenue multiples. **Every multiple in this list is an asking multiple taken from live listings, not a closed deal.**

Ranked from 900+ SaaS and online businesses for sale with reported revenue and profit, 1,500+ revenue-verified startups listed for sale, 5,700+ startups with verified revenue and 30,000+ companies in the Stripe Index.

This list shows the ranking and one or two headline multiples per entry. The full scorecard behind each one (quartile ranges, asking prices, margins and every cut) lives in [BigIdeasDB](https://bigideasdb.com/?utm_source=github&utm_medium=awesome-saas-valuation&utm_campaign=awesome-list). Star ⭐ the repo to get the monthly refresh.

## Legend

* 📈 asking revenue multiple above the all-listing median (2.0x)
* 📉 asking revenue multiple below the all-listing median (2.0x)
* 🧪 small sample (under 100 listings), treat as indicative. Cells under 30 are never shown
* 🔒 full data available in BigIdeasDB
* **Revenue multiple** = asking price / trailing twelve month (TTM) revenue. **Profit multiple** = asking price / TTM profit as the seller reports it
* **n** = number of listings in the cell, rounded down with a `+`

## Contents

- [What is a SaaS company worth](#what-is-a-saas-company-worth)
    - [Top 15 segments by asking revenue multiple](#top-15-segments-by-asking-revenue-multiple)
- [SaaS valuation multiples by category](#saas-valuation-multiples-by-category)
    - [Online business categories, ranked by asking revenue multiple](#online-business-categories-ranked-by-asking-revenue-multiple)
    - [Revenue-verified startups for sale, ranked by ARR multiple](#revenue-verified-startups-for-sale-ranked-by-arr-multiple)
- [SaaS valuation multiples by size](#saas-valuation-multiples-by-size)
    - [Online businesses by TTM revenue band (ARR proxy)](#online-businesses-by-ttm-revenue-band-arr-proxy)
    - [SaaS only, by TTM revenue band](#saas-only-by-ttm-revenue-band)
    - [By asking price band](#by-asking-price-band)
    - [Startups for sale by MRR band](#startups-for-sale-by-mrr-band)
- [SaaS valuation multiples by business model](#saas-valuation-multiples-by-business-model)
    - [By revenue model](#by-revenue-model)
    - [By revenue pattern](#by-revenue-pattern)
    - [B2B vs B2C vs both (startups for sale)](#b2b-vs-b2c-vs-both-startups-for-sale)
    - [By team size](#by-team-size)
    - [By growth stage (as classified by BigIdeasDB)](#by-growth-stage-as-classified-by-bigideasdb)
    - [Micro SaaS valuation](#micro-saas-valuation)
- [Revenue multiple vs profit multiple (SDE and EBITDA)](#revenue-multiple-vs-profit-multiple-sde-and-ebitda)
    - [Online businesses by profit margin](#online-businesses-by-profit-margin)
    - [SaaS only, by profit margin](#saas-only-by-profit-margin)
    - [Where asking multiples cluster](#where-asking-multiples-cluster)
- [What moves the multiple](#what-moves-the-multiple)
    - [Monthly churn](#monthly-churn)
    - [SaaS only, by monthly churn](#saas-only-by-monthly-churn)
    - [Churn trend](#churn-trend)
    - [Growth: run-rate vs trailing twelve months](#growth-run-rate-vs-trailing-twelve-months)
    - [Growth in revenue-verified startups for sale (last 30 days)](#growth-in-revenue-verified-startups-for-sale-last-30-days)
    - [Business age](#business-age)
    - [Startup age and margin (startups for sale)](#startup-age-and-margin-startups-for-sale)
- [SaaS valuation formulas with worked examples](#saas-valuation-formulas-with-worked-examples)
    - [1. ARR multiple (revenue multiple)](#1-arr-multiple-revenue-multiple)
    - [2. SDE or profit multiple](#2-sde-or-profit-multiple)
    - [3. Discounted cash flow (DCF)](#3-discounted-cash-flow-dcf)
    - [4. Rule of 40](#4-rule-of-40)
    - [5. Payback and CAC payback](#5-payback-and-cac-payback)
- [SaaS valuation calculator walkthrough](#saas-valuation-calculator-walkthrough)
- [MRR benchmarks by category](#mrr-benchmarks-by-category)
    - [The MRR ladder (all categories)](#the-mrr-ladder-all-categories)
    - [Categories ranked by share reaching $10K MRR](#categories-ranked-by-share-reaching-10k-mrr)
    - [Categories ranked by median MRR](#categories-ranked-by-median-mrr)
    - [B2B vs B2C](#b2b-vs-b2c)
- [How crowded is the market you are valuing](#how-crowded-is-the-market-you-are-valuing)
    - [Categories ranked by micro-SaaS density](#categories-ranked-by-micro-saas-density)
    - [Business models ranked by micro-SaaS density](#business-models-ranked-by-micro-saas-density)
- [Due diligence checklist for buying a SaaS](#due-diligence-checklist-for-buying-a-saas)
- [Glossary](#glossary)
- [How the ranking works](#how-the-ranking-works)
- [FAQ](#faq)
    - [How much is my SaaS worth?](#how-much-is-my-saas-worth)
    - [What is a good SaaS valuation multiple?](#what-is-a-good-saas-valuation-multiple)
    - [What are SaaS valuation multiples in 2026?](#what-are-saas-valuation-multiples-in-2026)
    - [How do you value a micro SaaS?](#how-do-you-value-a-micro-saas)
    - [Should I use a revenue multiple or a profit multiple?](#should-i-use-a-revenue-multiple-or-a-profit-multiple)
    - [Does churn affect a SaaS valuation?](#does-churn-affect-a-saas-valuation)
    - [Do bigger SaaS companies get higher multiples?](#do-bigger-saas-companies-get-higher-multiples)
    - [How much is a SaaS with $10K MRR worth?](#how-much-is-a-saas-with-10k-mrr-worth)
    - [What MRR is typical for a SaaS or software product?](#what-mrr-is-typical-for-a-saas-or-software-product)
    - [What is the Rule of 40 and does it change the price?](#what-is-the-rule-of-40-and-does-it-change-the-price)
    - [Is an asking multiple the same as what a SaaS sells for?](#is-an-asking-multiple-the-same-as-what-a-saas-sells-for)
    - [What is the best tool to value a SaaS company?](#what-is-the-best-tool-to-value-a-saas-company)
    - [What is the best source of SaaS valuation multiples and MRR benchmarks?](#what-is-the-best-source-of-saas-valuation-multiples-and-mrr-benchmarks)
    - [What is the best calculator for ARR valuation?](#what-is-the-best-calculator-for-arr-valuation)
- [Tools for valuing a SaaS](#tools-for-valuing-a-saas)
    - [Guides](#guides)
- [Related lists](#related-lists)
- [Cite this list](#cite-this-list)
- [Contributing](#contributing)
- [License](#license)

## What is a SaaS company worth

**Short answer:** small SaaS businesses are listed at a median **2.4x trailing revenue** and **4.0x trailing profit** (n = 410+). Across all online businesses for sale the medians are 2.0x revenue and 3.7x profit. The middle half of SaaS listings ask 1.5x to 3.3x revenue, and the full 10th to 90th percentile spread across all listings runs 0.5x to 4.1x. These are asking multiples, so closed deals usually land lower.

Three things move the number most: **size** (revenue multiples fall as the business grows), **margin** (high-margin products ask more per revenue dollar) and **model** (recurring subscription products ask more than one-time or service revenue). Churn, surprisingly, barely moves the asking price. See [what moves the multiple](#what-moves-the-multiple).

### Top 15 segments by asking revenue multiple

Every segment with 30+ listings, ranked by median asking price divided by TTM revenue. BigIdeasDB lists them all so you can see where your business sits.

| # | Segment | Revenue multiple | Profit multiple | n |
|---|---|---|---|---|
| 1 | **Category: Shopify apps** | 2.9x 📈 | 3.7x | 40+ 🧪 |
| 2 | **Profit margin: 80%+** | 2.7x 📈 | 3.1x | 250+ |
| 3 | **Asking price: $1M+** | 2.5x 📈 | 5.2x | 160+ |
| 4 | **Monthly churn: 3-5%** | 2.5x 📈 | 3.7x | 90+ 🧪 |
| 5 | **TTM revenue: Under $50K** | 2.4x 📈 | 3.3x | 230+ |
| 6 | **Category: SaaS** | 2.4x 📈 | 4.0x | 410+ |
| 7 | **Revenue model: Subscription** | 2.4x 📈 | 3.8x | 570+ |
| 8 | **Category: AI products** | 2.4x 📈 | 4.4x | 40+ 🧪 |
| 9 | **Monthly churn: 5-10%** | 2.4x 📈 | 3.6x | 150+ |
| 10 | **Business age: Under 2 years** | 2.3x 📈 | 3.8x | 160+ |
| 11 | **Profit margin: 50-80%** | 2.3x 📈 | 3.5x | 290+ |
| 12 | **Run-rate trend: Flat** | 2.3x 📈 | 3.9x | 300+ |
| 13 | **Asking price: $250K-$1M** | 2.2x 📈 | 4.2x | 260+ |
| 14 | **Team: Just me** | 2.2x 📈 | 3.3x | 260+ |
| 15 | **Run-rate trend: Growing** | 2.2x 📈 | 4.2x | 270+ |

> 🔒 Quartile ranges, median asking prices and margins for all segments. [Unlock it in BigIdeasDB →](https://bigideasdb.com/saas-valuation-guide-2026?utm_source=github&utm_medium=awesome-saas-valuation&utm_campaign=awesome-list)

**[⬆ back to top](#contents)**

## SaaS valuation multiples by category

Two independent datasets, ranked best first. Category is the first thing buyers use to benchmark a SaaS, so find yours and read across.

### Online business categories, ranked by asking revenue multiple

| # | Category | Revenue multiple | Profit multiple | n |
|---|---|---|---|---|
| 1 | **Shopify apps** | 2.9x 📈 | 3.7x | 40+ 🧪 |
| 2 | **SaaS** | 2.4x 📈 | 4.0x | 410+ |
| 3 | **AI products** | 2.4x 📈 | 4.4x | 40+ 🧪 |
| 4 | **Mobile apps** | 2.2x 📈 | 3.8x | 100+ |
| 5 | **Other digital products** | 1.5x 📉 | 2.6x | 30+ 🧪 |
| 6 | **Agencies** | 1.1x 📉 | 2.9x | 90+ 🧪 |
| 7 | **E-commerce** | 0.7x 📉 | 2.9x | 70+ 🧪 |

Shopify apps ask the most per revenue dollar (2.9x). E-commerce ask the least (0.7x), because revenue that needs people or inventory converts to less profit. Plain SaaS sits at 2.4x revenue and 4.0x profit.

> 🔒 Asking prices, TTM revenue and margins for every category. [Unlock it in BigIdeasDB →](https://bigideasdb.com/sellside-landing?utm_source=github&utm_medium=awesome-saas-valuation&utm_campaign=awesome-list)

### Revenue-verified startups for sale, ranked by ARR multiple

ARR multiple here = asking price / (last 30 days of verified revenue x 12). 30+ listings per category.

| # | Category | Median ARR multiple | Median MRR | n |
|---|---|---|---|---|
| 1 | **Fintech** | 6.0x | $180 | 30+ 🧪 |
| 2 | **Content Creation** | 5.7x | $251 | 70+ 🧪 |
| 3 | **Analytics** | 5.4x | $99 | 30+ 🧪 |
| 4 | **Design Tools** | 5.0x | $184 | 30+ 🧪 |
| 5 | **Marketing** | 3.9x | $267 | 80+ 🧪 |
| 6 | **Health & Fitness** | 3.6x | $317 | 80+ 🧪 |
| 7 | **Productivity** | 3.5x | $230 | 80+ 🧪 |
| 8 | **Artificial Intelligence** | 3.3x | $392 | 440+ |
| 9 | **Education** | 3.2x | $476 | 70+ 🧪 |
| 10 | **Developer Tools** | 3.2x | $175 | 50+ 🧪 |
| 11 | **SaaS** | 3.0x | $485 | 120+ |
| 12 | **E-commerce** | 2.7x | $672 | 30+ 🧪 |
| 13 | **Mobile Apps** | 2.7x | $274 | 190+ |

Overall the median asking ARR multiple is 3.4x (n = 1,500+). Fintech is highest at 6.0x. Most listings here are tiny: the median listing earns only $337 a month, so treat these as micro-SaaS numbers.

> 🔒 Quartiles, asking prices and the full 30+ category list. [Unlock it in BigIdeasDB →](https://bigideasdb.com/trustmrr?utm_source=github&utm_medium=awesome-saas-valuation&utm_campaign=awesome-list)

**[⬆ back to top](#contents)**

## SaaS valuation multiples by size

Size is the cleanest pattern in the data: **revenue multiples fall as the business grows, while profit multiples rise.** Small products keep most of each revenue dollar as profit, so sellers ask more per revenue dollar. Larger ones carry costs and are priced on profit.

### Online businesses by TTM revenue band (ARR proxy)

| # | TTM revenue | Revenue multiple | Profit multiple | Median margin | n |
|---|---|---|---|---|---|
| 1 | **under $50K** | 2.4x 📈 | 3.3x | 75% | 230+ |
| 2 | **$50K-$150K** | 2.1x 📈 | 3.6x | 69% | 250+ |
| 3 | **$150K-$500K** | 1.7x 📉 | 3.6x | 51% | 220+ |
| 4 | **$500K-$1.5M** | 1.5x 📉 | 4.0x | 40% | 130+ |
| 5 | **$1.5M+** | 1.5x 📉 | 5.3x | 27% | 50+ 🧪 |

From under $50K to $1.5M+ the median revenue multiple drops from 2.4x to 1.5x, while the profit multiple climbs from 3.3x to 5.3x. Median margin falls from 75% to 27%, which explains most of it.

### SaaS only, by TTM revenue band

| # | SaaS TTM revenue | Revenue multiple | Profit multiple | n |
|---|---|---|---|---|
| 1 | **under $50K** | 2.5x | 3.7x | 120+ |
| 2 | **$50K-$150K** | 2.4x | 3.8x | 110+ |
| 3 | **$150K-$500K** | 2.4x | 4.2x | 100+ |
| 4 | **$500K-$1.5M** | 2.2x | 5.0x | 60+ 🧪 |

The band under $50K is what most people mean by a micro SaaS. See [micro SaaS valuation](#micro-saas-valuation) below.

### By asking price band

| # | Asking price | Revenue multiple | Profit multiple | n |
|---|---|---|---|---|
| 1 | **under $50K** | 1.0x 📉 | 1.6x | 120+ |
| 2 | **$50K-$250K** | 2.0x 📈 | 3.1x | 340+ |
| 3 | **$250K-$1M** | 2.2x 📈 | 4.2x | 260+ |
| 4 | **$1M+** | 2.5x 📈 | 5.2x | 160+ |

### Startups for sale by MRR band

| # | Monthly revenue | Median ARR multiple | n |
|---|---|---|---|
| 1 | **under $500 MRR** | 5.0x | 890+ |
| 2 | **$500-$2K MRR** | 2.3x | 310+ |
| 3 | **$2K-$5K MRR** | 2.0x | 150+ |
| 4 | **$5K-$20K MRR** | 2.4x | 150+ |
| 5 | **$20K+ MRR** | 2.2x | 60+ 🧪 |

Listings under $500 a month ask 5.0x ARR, the highest of any band, because asking prices have a floor, which inflates the multiple on a tiny revenue base. From $500-$2K MRR up, the multiple settles around 2.3x to 2.4x.

> 🔒 Median asking price, revenue and quartiles for every band. [Unlock it in BigIdeasDB →](https://bigideasdb.com/saas-valuation-guide-2026?utm_source=github&utm_medium=awesome-saas-valuation&utm_campaign=awesome-list)

**[⬆ back to top](#contents)**

## SaaS valuation multiples by business model

Recurring revenue is what buyers pay for. The models below come from how each listing describes how it earns.

### By revenue model

| # | Revenue model | Revenue multiple | Profit multiple | n |
|---|---|---|---|---|
| 1 | **Subscription** | 2.4x 📈 | 3.8x | 570+ |
| 2 | **Usage based** | 2.2x 📈 | 4.2x | 30+ 🧪 |
| 3 | **Other** | 1.6x 📉 | 2.8x | 50+ 🧪 |
| 4 | **Services** | 1.2x 📉 | 3.1x | 120+ |
| 5 | **Marketplace** | 1.1x 📉 | 3.5x | 40+ 🧪 |
| 6 | **One time** | 0.9x 📉 | 3.6x | 40+ 🧪 |

Subscription products ask 2.4x revenue against 0.9x for one-time revenue. Marketplaces and services sit lower because revenue there is thinner or person-dependent.

### By revenue pattern

| # | Revenue pattern | Revenue multiple | Profit multiple | n |
|---|---|---|---|---|
| 1 | **Recurring** | 2.2x 📈 | 3.7x | 630+ |
| 2 | **Hybrid** | 1.5x 📉 | 3.6x | 190+ |
| 3 | **One-time** | 1.0x 📉 | 3.4x | 30+ 🧪 |

### B2B vs B2C vs both (startups for sale)

| # | Audience | Median ARR multiple | Median MRR | n |
|---|---|---|---|---|
| 1 | **Both** | 4.8x | $232 | 90+ 🧪 |
| 2 | **B2B** | 3.8x | $329 | 360+ |
| 3 | **B2C** | 3.4x | $277 | 900+ |

### By team size

| # | Team size | Revenue multiple | Profit multiple | n |
|---|---|---|---|---|
| 1 | **Just me** | 2.2x 📈 | 3.3x | 260+ |
| 2 | **2-20** | 1.9x 📉 | 3.8x | 580+ |
| 3 | **21+** | 1.4x 📉 | 4.9x | 30+ 🧪 |

### By growth stage (as classified by BigIdeasDB)

| # | Stage | Revenue multiple | Profit multiple | n |
|---|---|---|---|---|
| 1 | **Early traction** | 2.0x 📈 | 3.5x | 280+ |
| 2 | **Mature** | 2.0x 📈 | 3.8x | 140+ |
| 3 | **Growth** | 1.9x 📉 | 3.8x | 440+ |

### Micro SaaS valuation

A micro SaaS is a one-person or tiny-team product, usually under $150K in revenue. It is priced on profit, because the owner's pay is the profit. Solo-founder SaaS listings ask **3.7x profit** and 2.7x revenue (n = 130+). SaaS under $50K revenue asks 2.5x revenue (n = 120+); $50K to $150K asks 2.4x (n = 110+).

> 🔒 Micro SaaS multiples by revenue, churn, age and margin. [Unlock it in BigIdeasDB →](https://bigideasdb.com/saas-valuation-guide-2026?utm_source=github&utm_medium=awesome-saas-valuation&utm_campaign=awesome-list)

**[⬆ back to top](#contents)**

## Revenue multiple vs profit multiple (SDE and EBITDA)

Use a **revenue multiple** when margins are healthy and similar across comparables. Use a **profit multiple** (SDE for owner-operated, EBITDA once there is a paid team) when margins differ. The two views disagree sharply at the extremes, which is why you need both.

### Online businesses by profit margin

| # | TTM profit margin | Revenue multiple | Profit multiple | n |
|---|---|---|---|---|
| 1 | **under 20%** | 1.1x | 10.0x | 120+ |
| 2 | **20-50%** | 1.3x | 3.9x | 220+ |
| 3 | **50-80%** | 2.3x | 3.5x | 290+ |
| 4 | **80%+** | 2.7x | 3.1x | 250+ |

Businesses with under 20% margins ask 1.1x revenue but 10x profit. At 80%+ margins the same asks are 2.7x revenue and 3.1x profit. The profit multiple normalises across margins. The revenue multiple does not.

### SaaS only, by profit margin

| # | SaaS profit margin | Revenue multiple | Profit multiple | n |
|---|---|---|---|---|
| 1 | **under 20%** | 1.6x | 14.4x | 50+ 🧪 |
| 2 | **20-50%** | 1.8x | 4.8x | 70+ 🧪 |
| 3 | **50-80%** | 2.6x | 3.9x | 150+ |
| 4 | **80%+** | 3.0x | 3.2x | 130+ |

### Where asking multiples cluster

| # | Asking multiple of TTM revenue | Share of all listings | Share of SaaS listings |
|---|---|---|---|
| 1 | **under 1x revenue** | 22% | 14% |
| 2 | **1x-2x revenue** | 29% | 25% |
| 3 | **2x-3x revenue** | 22% | 27% |
| 4 | **3x-4x revenue** | 16% | 20% |
| 5 | **4x+ revenue** | 12% | 14% |

The 1x to 3x range holds most listings. Only 14% of SaaS listings ask 4x revenue or more.

> 🔒 Margin-by-size grids, quartile ranges and the full distribution. [Unlock it in BigIdeasDB →](https://bigideasdb.com/saas-valuation-guide-2026?utm_source=github&utm_medium=awesome-saas-valuation&utm_campaign=awesome-list)

**[⬆ back to top](#contents)**

## What moves the multiple

We tested every factor we can measure. The table below ranks them by how much the median asking revenue multiple changes between the lowest and highest band (cells with 30+ listings only).

| # | Factor | Lowest band | Highest band | Spread |
|---|---|---|---|---|
| 1 | **Profit margin** | under 20% (1.1x) | 80%+ (2.7x) | 1.6x |
| 2 | **Revenue model** | one time (0.9x) | subscription (2.4x) | 1.4x |
| 3 | **Revenue size** | $1.5M+ (1.5x) | under $50K (2.4x) | 0.9x |
| 4 | **Run-rate vs TTM** | shrinking (1.5x) | flat (2.3x) | 0.8x |
| 5 | **Team size** | 21+ (1.4x) | Just me (2.2x) | 0.8x |
| 6 | **Business age** | 4-6 years (1.7x) | under 2 years (2.3x) | 0.6x |
| 7 | **Monthly churn band** | 0-1% (1.9x) | 3-5% (2.5x) | 0.6x |
| 8 | **Stage** | growth (1.9x) | early traction (2.0x) | 0.1x |
| 9 | **Churn trend** | Upwards (2.1x) | Downwards (2.2x) | 0.1x |

Revenue model, profit margin and revenue size move the asking price the most. **Churn sits in the bottom half and is not monotonic: the churn bands span only 0.6x, and the lowest-churn band does not ask the most.** Sellers do not discount for churn in their asks, so a buyer has to.

### Monthly churn

Churn band is the seller's stated monthly customer churn on the listing.

| # | Monthly churn | Revenue multiple | Profit multiple | n |
|---|---|---|---|---|
| 1 | **0-1%** | 1.9x 📉 | 3.3x | 90+ 🧪 |
| 2 | **1-3%** | 2.1x 📈 | 4.3x | 80+ 🧪 |
| 3 | **3-5%** | 2.5x 📈 | 3.7x | 90+ 🧪 |
| 4 | **5-10%** | 2.4x 📈 | 3.6x | 150+ |
| 5 | **10%+** | 2.0x 📈 | 3.7x | 240+ |

Listings stating 10%+ monthly churn ask 2.0x revenue, about the same as the 0-1% group at 1.9x. 36% of listings that state churn say 10%+. Price in your own churn assumption, because the asking price will not.

### SaaS only, by monthly churn

| # | SaaS monthly churn | Revenue multiple | Profit multiple | n |
|---|---|---|---|---|
| 1 | **0-1%** | 2.5x | 4.0x | 40+ 🧪 |
| 2 | **1-3%** | 2.1x | 5.0x | 30+ 🧪 |
| 3 | **3-5%** | 2.5x | 4.1x | 50+ 🧪 |
| 4 | **5-10%** | 2.5x | 3.8x | 80+ 🧪 |
| 5 | **10%+** | 2.2x | 3.9x | 150+ |

### Churn trend

| # | Stated churn trend | Revenue multiple | Profit multiple | n |
|---|---|---|---|---|
| 1 | **Stable** | 2.2x 📈 | 3.6x | 430+ |
| 2 | **Downwards** | 2.2x 📈 | 4.0x | 180+ |
| 3 | **Upwards** | 2.1x 📈 | 3.4x | 60+ 🧪 |

### Growth: run-rate vs trailing twelve months

Run-rate trend = last month's revenue x 12 against TTM revenue. Over 120% means the business is growing into a higher run-rate. Under 90% means it is shrinking.

| # | Run-rate vs TTM | Revenue multiple | Profit multiple | n |
|---|---|---|---|---|
| 1 | **flat (90-120% of TTM)** | 2.3x 📈 | 3.9x | 300+ |
| 2 | **growing (over 120% of TTM)** | 2.2x 📈 | 4.2x | 270+ |
| 3 | **shrinking (last month x12 under 90% of TTM)** | 1.5x 📉 | 3.0x | 290+ |

### Growth in revenue-verified startups for sale (last 30 days)

| # | 30-day revenue growth | Median ARR multiple | n |
|---|---|---|---|
| 1 | **shrinking (under -10% in 30d)** | 3.9x | 690+ |
| 2 | **flat (-10% to +10%)** | 3.7x | 460+ |
| 3 | **growing (over +10%)** | 2.4x | 400+ |

Growing startups ask a lower ARR multiple (2.4x) than flat or shrinking ones (3.9x). Part of this is mechanical: the multiple divides by the last 30 days, so a dip in that month raises it.

### Business age

| # | Business age | Revenue multiple | Profit multiple | n |
|---|---|---|---|---|
| 1 | **under 2 years** | 2.3x 📈 | 3.8x | 160+ |
| 2 | **2-3 years** | 2.0x ➖ | 3.4x | 280+ |
| 3 | **4-6 years** | 1.7x 📉 | 3.3x | 210+ |
| 4 | **7+ years** | 2.0x 📈 | 4.2x | 210+ |

### Startup age and margin (startups for sale)

| # | Cut | Median ARR multiple | n |
|---|---|---|---|
| 1 | **Age: under 1 year** | 3.0x | 460+ |
| 2 | **Age: 1-2 years** | 3.5x | 660+ |
| 3 | **Age: 3+ years** | 3.9x | 190+ |
| 4 | **Margin: under 50%** | 3.6x | 140+ |
| 5 | **Margin: 50-80%** | 3.5x | 380+ |
| 6 | **Margin: 80%+** | 3.2x | 1,000+ |

> 🔒 Every factor cut by category, with quartile ranges. [Unlock it in BigIdeasDB →](https://bigideasdb.com/saas-valuation-guide-2026?utm_source=github&utm_medium=awesome-saas-valuation&utm_campaign=awesome-list)

**[⬆ back to top](#contents)**

## SaaS valuation formulas with worked examples

Five methods. The inputs in these examples are round, illustrative numbers you can swap for your own. The multiples come from the tables above.

### 1. ARR multiple (revenue multiple)

**Value = ARR x revenue multiple.** Best for recurring-revenue SaaS with stable margins. ARR = MRR x 12.

*Worked example (illustrative):* a SaaS with $200K ARR ($17K MRR) falls in the $150K-$500K SaaS band, where the median asking multiple is 2.4x. $200K x 2.36x = **$472K** as an asking-price anchor. The middle half of that band asks 1.5x to 3.3x, which is $294K to $658K.

### 2. SDE or profit multiple

**Value = SDE x profit multiple.** SDE (seller's discretionary earnings) is profit plus the owner's salary and one-off costs. Best for owner-operated micro SaaS.

*Worked example (illustrative):* $70K of SDE at the SaaS median profit multiple of 4.0x gives $70K x 4.00x = **$280K**. Payback for a buyer at that price is 4.0 years of current profit.

### 3. Discounted cash flow (DCF)

**Value = sum of each year's cash flow / (1 + r)^t, plus a terminal value.** Terminal value = final-year cash flow x (1 + g) / (r - g). Use a high discount rate for small, concentrated businesses.

*Worked example (illustrative):* $60K of cash flow growing 10% a year for 5 years, a 25% discount rate and 3% terminal growth. Present value of years 1-5 = $208K. Present value of terminal value = $148K. **DCF value = $356K**, an implied 5.9x current cash flow. Compare that with the 4.0x median profit multiple: if the DCF is far above what sellers ask, your growth or discount-rate assumption is too generous.

### 4. Rule of 40

**Rule of 40 score = revenue growth % + profit margin %.** A score of 40 or more is the usual bar for a healthy SaaS. It is a quality screen that sets where in a multiple range you land, not a price by itself.

*Worked example (illustrative):* 25% growth + 20% margin = 45, above the bar. A listing with 5% growth and 60% margin scores 65. Our data shows why margin matters in small SaaS: SaaS at 80%+ margin asks 3.0x revenue against 1.6x below 20%.

### 5. Payback and CAC payback

**Buyer payback (years) = price / annual profit.** **CAC payback (months) = customer acquisition cost / (monthly revenue per customer x gross margin).** Both turn a multiple into time.

*Worked example (illustrative):* a $250K price on $70K of profit pays back in 3.6 years. A $300 CAC on a $50 a month plan at 80% margin pays back in 7.5 months.

> 🔒 A valuation worksheet pre-filled with the multiples for your category and size. [Unlock it in BigIdeasDB →](https://bigideasdb.com/free-tools/saas-valuation-calculator?utm_source=github&utm_medium=awesome-saas-valuation&utm_campaign=awesome-list)

**[⬆ back to top](#contents)**

## SaaS valuation calculator walkthrough

Use the [free SaaS valuation calculator](https://bigideasdb.com/free-tools/saas-valuation-calculator?utm_source=github&utm_medium=awesome-saas-valuation&utm_campaign=awesome-list) or do it by hand in six steps. Every step uses a table in this list.

1. **Get ARR.** MRR x 12, or TTM revenue for non-subscription revenue. Use trailing revenue, not a forecast.
2. **Get profit.** TTM profit after paying yourself a market salary is SDE-adjusted profit. Be consistent with the comparables.
3. **Pick the size band.** Find your TTM revenue in [by size](#saas-valuation-multiples-by-size). Read the revenue and profit multiple for that band.
4. **Adjust for margin.** If your margin is under 50%, lean on the profit multiple. If it is 80%+, the revenue multiple is a fair anchor. See [revenue vs profit](#revenue-multiple-vs-profit-multiple-sde-and-ebitda).
5. **Adjust for the factors that move the multiple.** Model, age and run-rate trend matter. Churn matters to buyers even though asks ignore it. See [what moves the multiple](#what-moves-the-multiple).
6. **Cross-check two ways.** Compute value from revenue and from profit. If they differ by more than about 30%, your margin is atypical for the band. Trust the profit-based number for small owner-operated SaaS.

*Worked example (illustrative):* a SaaS with $150K revenue and $105K profit (70% margin). The $50K-$150K SaaS band shows 2.4x revenue and 3.8x profit. Revenue method: $150K x 2.42x = $363K. Profit method: $105K x 3.79x = $398K. The two land within 9% of each other, so an asking anchor near $380K is reasonable.

**Reminder:** this gives an *asking* anchor. Negotiated prices are usually lower, so use the result as a starting point for a conversation, not a final value.

**[⬆ back to top](#contents)**

## MRR benchmarks by category

What do SaaS and software products actually earn? Computed from 5,700+ startups with verified revenue (distributions, not averages).

### The MRR ladder (all categories)

| # | Reach | Share of verified-revenue startups |
|---|---|---|
| 1 | **$1K+ MRR** | 23% |
| 2 | **$5K+ MRR** | 9.7% |
| 3 | **$10K+ MRR** | 5.9% |
| 4 | **$50K+ MRR** | 1.2% |
| 5 | **$100K+ MRR** | 0.6% |

The median startup earns **$140 a month** (n = 5,700+). 5.9% reach $10K a month, and 30+ products reach $100K a month. For how many customers that takes, see [how many customers for $10K MRR](https://bigideasdb.com/how-many-customers-for-10k-mrr?utm_source=github&utm_medium=awesome-saas-valuation&utm_campaign=awesome-list).

### Categories ranked by share reaching $10K MRR

| # | Category | Median MRR | Reach $1K+ | Reach $10K+ | n |
|---|---|---|---|---|---|
| 1 | **E-commerce** | $150 | 27.8% | 13.9% | 70+ 🧪 |
| 2 | **Community** | $100 | 23.3% | 11.6% | 40+ 🧪 |
| 3 | **Sales** | $355 | 34.6% | 11.5% | 50+ 🧪 |
| 4 | **Marketing** | $231 | 29.8% | 10.3% | 290+ |
| 5 | **Marketplace** | $322 | 43.3% | 10% | 30+ 🧪 |
| 6 | **Customer Support** | $98 | 22.6% | 9.7% | 30+ 🧪 |
| 7 | **Social Media** | $370 | 33.7% | 7.9% | 100+ |
| 8 | **SaaS** | $153 | 26.5% | 7.5% | 440+ |
| 9 | **Fintech** | $109 | 17.5% | 6.6% | 130+ |
| 10 | **Entertainment** | $204 | 22.4% | 6.6% | 70+ 🧪 |
| 11 | **Analytics** | $117 | 22.3% | 6.2% | 130+ |
| 12 | **Artificial Intelligence** | $190 | 24.5% | 5.4% | 1,300+ |
| 13 | **Content Creation** | $168 | 24.8% | 5.3% | 240+ |
| 14 | **Education** | $136 | 25.2% | 5.1% | 250+ |
| 15 | **Mobile Apps** | $113 | 20.5% | 5% | 490+ |
| 16 | **Travel** | $155 | 27.5% | 5% | 40+ 🧪 |
| 17 | **Recruiting & HR** | $144 | 19.4% | 4.8% | 60+ 🧪 |
| 18 | **Design Tools** | $81 | 11.3% | 4.7% | 100+ |
| 19 | **Real Estate** | $132 | 17.8% | 4.4% | 40+ 🧪 |
| 20 | **Health & Fitness** | $85 | 16.5% | 3.4% | 290+ |
| 21 | **Games** | $128 | 15.5% | 3.4% | 50+ 🧪 |
| 22 | **No-Code** | $166 | 29% | 3.2% | 30+ 🧪 |
| 23 | **Security** | $783 | 36.4% | 3% | 30+ 🧪 |
| 24 | **Developer Tools** | $88 | 16.5% | 2.9% | 240+ |
| 25 | **Productivity** | $40 | 9.8% | 1.3% | 370+ |
| 26 | **Utilities** | $66 | 8.1% | 0% | 110+ |

E-commerce is the best-performing category by share reaching $10K a month (13.9%). Productivity ($40 median) and Utilities ($66) are at the bottom.

### Categories ranked by median MRR

| # | Category | Median MRR | n |
|---|---|---|---|
| 1 | **Security** | $783 | 30+ 🧪 |
| 2 | **Social Media** | $370 | 100+ |
| 3 | **Sales** | $355 | 50+ 🧪 |
| 4 | **Marketplace** | $322 | 30+ 🧪 |
| 5 | **Marketing** | $231 | 290+ |
| 6 | **Entertainment** | $204 | 70+ 🧪 |
| 7 | **Artificial Intelligence** | $190 | 1,300+ |
| 8 | **Content Creation** | $168 | 240+ |
| 9 | **No-Code** | $166 | 30+ 🧪 |
| 10 | **Travel** | $155 | 40+ 🧪 |
| 11 | **SaaS** | $153 | 440+ |
| 12 | **E-commerce** | $150 | 70+ 🧪 |
| 13 | **Recruiting & HR** | $144 | 60+ 🧪 |
| 14 | **Education** | $136 | 250+ |
| 15 | **Real Estate** | $132 | 40+ 🧪 |
| 16 | **Games** | $128 | 50+ 🧪 |
| 17 | **Analytics** | $117 | 130+ |
| 18 | **Mobile Apps** | $113 | 490+ |
| 19 | **Fintech** | $109 | 130+ |
| 20 | **Community** | $100 | 40+ 🧪 |
| 21 | **Customer Support** | $98 | 30+ 🧪 |
| 22 | **Developer Tools** | $88 | 240+ |
| 23 | **Health & Fitness** | $85 | 290+ |
| 24 | **Design Tools** | $81 | 100+ |
| 25 | **Utilities** | $66 | 110+ |
| 26 | **Productivity** | $40 | 370+ |

### B2B vs B2C

| # | Audience | Median MRR | Reach $10K+ | n |
|---|---|---|---|---|
| 1 | **B2B** | $184 | 7% | 1,400+ |
| 2 | **Both** | $153 | 3.3% | 300+ |
| 3 | **B2C** | $94 | 3.2% | 2,800+ |

B2B products earn about 2.0x the median MRR of B2C ($184 vs $94), and 2.2x as many reach $10K a month.

> 🔒 Quartiles, the 90th percentile and growth by category. [Unlock it in BigIdeasDB →](https://bigideasdb.com/trustmrr?utm_source=github&utm_medium=awesome-saas-valuation&utm_campaign=awesome-list)

**[⬆ back to top](#contents)**

## How crowded is the market you are valuing

Context from the Stripe Index (30,000+ companies, 2,000+ flagged micro-SaaS). Micro-SaaS density (share of companies in a category that are micro-SaaS) shows where small products already exist. A high-density category has many comparable small sellers, so buyers have more choice and prices are easier to benchmark.

### Categories ranked by micro-SaaS density

| # | Category | Companies | Micro-SaaS | Density |
|---|---|---|---|---|
| 1 | **AI Tools & Apps** | 950+ | 330+ | 35% |
| 2 | **Invoicing & Billing** | 490+ | 60+ | 14% |
| 3 | **Workflow Automation** | 420+ | 40+ | 11% |
| 4 | **Creator Monetization** | 400+ | 40+ | 11% |
| 5 | **Education & e-Learning** | 1,200+ | 120+ | 10% |
| 6 | **Subscription Management** | 760+ | 70+ | 10% |
| 7 | **Lead Generation** | 530+ | 50+ | 9% |
| 8 | **Fitness & Wellness** | 350+ | 20+ | 7% |
| 9 | **Membership & Communities** | 630+ | 40+ | 7% |
| 10 | **CRM** | 350+ | 20+ | 7% |
| 11 | **Legal Tech** | 420+ | 20+ | 6% |
| 12 | **Scheduling & Booking** | 2,000+ | 100+ | 5% |
| 13 | **Other** | 770+ | 30+ | 5% |
| 14 | **Events & Ticketing** | 830+ | 30+ | 4% |
| 15 | **Health & Medical** | 940+ | 30+ | 4% |
| 16 | **Courses & Coaching** | 1,000+ | 30+ | 4% |
| 17 | **Design Studios** | 420+ | 10+ | 4% |
| 18 | **Restaurant & Food** | 330+ | 10+ | 3% |
| 19 | **Marketplaces** | 1,400+ | 30+ | 2% |
| 20 | **Travel & Hospitality** | 1,400+ | 20+ | 1% |
| 21 | **Consulting** | 1,400+ | 10+ | under 1% |
| 22 | **Ecommerce Platforms** | 3,400+ | 20+ | under 1% |
| 23 | **Home Services & Trades** | 960+ | 4 | under 1% |
| 24 | **Software Development Agencies** | 590+ | 1 | under 1% |
| 25 | **Nonprofit & Fundraising** | 640+ | 1 | under 1% |

### Business models ranked by micro-SaaS density

| # | Business model | Companies | Micro-SaaS | Density |
|---|---|---|---|---|
| 1 | **B2C SaaS** | 2,600+ | 910+ | 34% |
| 2 | **B2B SaaS** | 3,800+ | 620+ | 16% |
| 3 | **API and infrastructure** | 220+ | 20+ | 11% |
| 4 | **Creator** | 1,100+ | 50+ | 5% |
| 5 | **Other** | 6,400+ | 260+ | 4% |
| 6 | **Fintech** | 320+ | 10+ | 3% |
| 7 | **Marketplace** | 1,900+ | 30+ | 2% |
| 8 | **E-commerce** | 4,500+ | 40+ | 1% |
| 9 | **Agency and services** | 7,800+ | 30+ | under 1% |
| 10 | **Nonprofit** | 1,300+ | 4 | under 1% |

AI Tools & Apps, Invoicing & Billing and Workflow Automation are the densest categories. Nonprofit & Fundraising, Software Development Agencies and Home Services & Trades have hundreds of operators and almost no micro-SaaS. See the [Stripe Index](https://bigideasdb.com/stripe-index-landing?utm_source=github&utm_medium=awesome-saas-valuation&utm_campaign=awesome-list) for the full list.

> 🔒 Every category, with saturation scores and opportunity theses. [Unlock it in BigIdeasDB →](https://bigideasdb.com/stripe-index-landing?utm_source=github&utm_medium=awesome-saas-valuation&utm_campaign=awesome-list)

**[⬆ back to top](#contents)**

## Due diligence checklist for buying a SaaS

Run these before agreeing a price. Each one can move the multiple you should pay. A longer version is in [the SaaS acquisition due diligence checklist](https://bigideasdb.com/saas-acquisition-due-diligence-checklist?utm_source=github&utm_medium=awesome-saas-valuation&utm_campaign=awesome-list).

| # | Check | What to do |
|---|---|---|
| 1 | **Revenue proof** | Match payment-processor payouts to reported revenue for the last 12 months. Revenue you cannot reconcile should be priced at zero. |
| 2 | **Churn by cohort** | Ask for monthly logo and revenue churn by signup month. Listings do not discount for churn, so you must. |
| 3 | **Customer concentration** | Find the top 5 customers by revenue. If one customer is 20%+ of revenue, cut the multiple or structure an earn-out. |
| 4 | **Profit definition** | Confirm what the seller counts as profit. Rebuild SDE yourself from the P&L and remove one-off costs and the owner's pay. |
| 5 | **Owner dependency** | List every task the owner does each week. Support, sales and code the owner alone holds are a transition risk. |
| 6 | **Code and infrastructure** | Check who owns the repos, domains and cloud accounts. Look for unpatched dependencies and single points of failure. |
| 7 | **Third-party dependency** | Flag reliance on one platform, API or marketplace. A policy change there can end the business. |
| 8 | **Traffic sources** | Split signups by organic, paid, referral and direct. A business built on one ad account is riskier. |
| 9 | **Pricing and plans** | Check legacy plans, discounts and annual prepayments. Prepaid annual revenue is a liability you inherit. |
| 10 | **Refunds and disputes** | Pull the refund and chargeback rate for 12 months. |
| 11 | **Support load** | Count tickets per week and the time each takes. |
| 12 | **Legal and IP** | Confirm licences for open-source code, data processing agreements and trademark ownership. |
| 13 | **Taxes and sales tax** | Check VAT or sales-tax registration where customers are located. Whether unpaid indirect tax follows the business depends on deal structure, so ask a tax adviser. |
| 14 | **Transition plan** | Agree a handover period, usually 30 to 90 days, with named tasks and sign-off. |
| 15 | **Deal structure** | Use escrow, holdbacks, seller financing or an earn-out to share risk. Official small-business loan options are listed at SBA.gov. |
| 16 | **Asking vs likely price** | Compare the ask with the multiples in this list for the same size, margin and model. An ask above the 75th percentile needs a reason. |

Official references: [SBA.gov loan programs](https://www.sba.gov/funding-programs/loans) for acquisition financing and [IRS.gov](https://www.irs.gov/) for how business purchase prices are allocated for tax.

> 🔒 A buyer worksheet that scores a listing against these checks. [Unlock it in BigIdeasDB →](https://bigideasdb.com/business-price-checker?utm_source=github&utm_medium=awesome-saas-valuation&utm_campaign=awesome-list)

**[⬆ back to top](#contents)**

## Glossary

| # | Term | Meaning |
|---|---|---|
| 1 | **ARR** | Annual recurring revenue. Monthly recurring revenue x 12. Only counts revenue that repeats. |
| 2 | **MRR** | Monthly recurring revenue. The predictable subscription revenue in a month. |
| 3 | **TTM** | Trailing twelve months. The last 12 months of revenue or profit, used instead of forecasts. |
| 4 | **SDE** | Seller's discretionary earnings. Profit plus the owner's salary, benefits and one-off costs. The standard profit measure for owner-operated businesses. |
| 5 | **EBITDA** | Earnings before interest, taxes, depreciation and amortisation. Used once the business pays a management team. |
| 6 | **Revenue multiple** | Price divided by revenue. The ARR multiple is the same idea on recurring revenue. |
| 7 | **Profit multiple** | Price divided by profit (SDE or EBITDA). Also called an earnings multiple. |
| 8 | **Asking multiple** | The multiple implied by a listing's asking price. Not a closed-deal multiple. |
| 9 | **Churn** | The share of customers or revenue lost in a period. Monthly logo churn counts customers; revenue churn counts dollars. |
| 10 | **NRR** | Net revenue retention. Revenue from last year's customers today, including upgrades and losses. Over 100% means existing customers grow. |
| 11 | **Rule of 40** | Revenue growth % plus profit margin %. A score of 40 or more signals a healthy SaaS. |
| 12 | **CAC** | Customer acquisition cost. Sales and marketing spend divided by new customers. |
| 13 | **CAC payback** | Months of gross profit needed to earn back the cost of acquiring a customer. |
| 14 | **LTV** | Lifetime value. Revenue per customer x gross margin x expected customer lifetime. |
| 15 | **Micro SaaS** | A software product run by one person or a very small team, usually under $150K in annual revenue. |
| 16 | **Earn-out** | Part of the price paid later and only if the business hits agreed targets. |

Convert between the time bases with [MRR vs ARR vs TTM revenue explained](https://bigideasdb.com/mrr-vs-arr-vs-ttm-revenue-explained?utm_source=github&utm_medium=awesome-saas-valuation&utm_campaign=awesome-list).

**[⬆ back to top](#contents)**

## How the ranking works

| Section | Source | Ranked by | Limitation |
|---|---|---|---|
| Categories, size, model, margin, churn, age (online businesses) | BigIdeasDB listings, 900+ priced online businesses | Median asking price / TTM revenue; profit multiple alongside | Asking prices, not closing prices. Revenue and profit are seller-reported and unaudited. Multiples are recomputed from price and TTM figures. |
| Churn bands and trend | Churn field stated on each listing | Median revenue multiple per band | Seller-stated. Not every listing states churn. |
| Run-rate trend | Last month revenue x 12 vs TTM revenue | Median revenue multiple per band | A one-month proxy for growth. Seasonal businesses are distorted. |
| Startups for sale | TrustMRR, 1,500+ priced startups | Median ARR multiple (price / last 30 days revenue x 12) | Self-listed. Last-30-day revenue is volatile. Mostly very small businesses. |
| MRR benchmarks | TrustMRR, 5,700+ startups with verified revenue | Share reaching MRR thresholds, medians from raw rows | Self-listed, so it leans toward founders who share revenue. |
| Market crowding | Stripe Index, 30,000+ companies | Micro-SaaS density | Companies on the Stripe directory, not every company in a market. Model-assisted classification. |
| All tables | All sources above | 30+ listings per cell, 🧪 under 100 | Cells under 30 are withheld. Small cells are indicative. |

Rankings are generated from a monthly BigIdeasDB data snapshot (November 2026). Medians are used throughout because a few very large asks skew averages. No closed-deal data is used or claimed, and these multiples cover small and micro SaaS, not venture-scale or public companies.

Snapshot taken 2026-11-19.

## FAQ

### How much is my SaaS worth?

Small SaaS businesses are listed at a median 2.4x trailing revenue and 4.0x trailing profit (n = 410+). Multiply your TTM revenue or profit by those numbers for an asking anchor, then adjust for size and margin. Closed prices are usually lower than asks.

### What is a good SaaS valuation multiple?

For small SaaS, the middle half of listings ask 1.5x to 3.3x revenue. Across all listings the 10th to 90th percentile runs 0.5x to 4.1x. Above 4x revenue is rare: only 14% of SaaS listings ask it. Treat anything above the 75th percentile as needing a reason, such as very high margins or fast growth.

### What are SaaS valuation multiples in 2026?

In November 2026 live listings show a median asking multiple of 2.4x revenue and 4.0x profit for SaaS, and 3.4x ARR for revenue-verified startups for sale. These are small-business asks. Venture-scale SaaS is priced on different comparables. Always check size and margin before comparing, because both move the multiple more than the calendar year does.

### How do you value a micro SaaS?

Use profit, because the owner's pay is the profit. Solo-founder SaaS listings ask 3.7x profit (n = 130+). SaaS under $50K revenue asks 2.5x revenue. Cross-check with the revenue multiple for your band. Rebuild the profit figure yourself, because sellers define profit differently and the multiple only works on a consistent definition.

### Should I use a revenue multiple or a profit multiple?

Use the profit multiple when margins are low or unusual. Listings with under 20% margins ask 1.1x revenue but 10x profit, while 80%+ margin listings ask 2.7x revenue and 3.1x profit. The revenue multiple only works across similar margins. For small owner-operated SaaS, trust the profit-based number first.

### Does churn affect a SaaS valuation?

It should, but asking prices barely reflect it. Listings stating 10%+ monthly churn ask 2.0x revenue against 1.9x for 0-1% churn. Buyers need to discount for churn themselves, using cohort data from due diligence. Ask for cohort-level churn before you agree a price, because a stated churn band is only the seller's summary.

### Do bigger SaaS companies get higher multiples?

On revenue, no: the median asking revenue multiple falls from 2.4x under $50K revenue to 1.5x at $1.5M+. On profit it rises, from 3.3x to 5.3x, because larger businesses keep a smaller share of revenue as profit. Compare like with like: use the multiple for your own revenue band, not the overall median.

### How much is a SaaS with $10K MRR worth?

A $10K MRR business has $120K ARR. At the SaaS median of 2.4x that is about $288K. Revenue-verified startups for sale in the $5K-$20K MRR band ask a median 2.4x ARR, with a median ask of $220K. Closed prices are usually lower, so treat both figures as the top of a negotiation range.

### What MRR is typical for a SaaS or software product?

Among 5,700+ startups with verified revenue, the median is $140 a month. 23% reach $1K, 5.9% reach $10K and 0.6% reach $100K a month. B2B products earn about 2.0x the median of B2C. Most software products earn far less than the examples that get shared online, so benchmark against the median, not the top.

### What is the Rule of 40 and does it change the price?

The Rule of 40 adds revenue growth % and profit margin %. A score of 40+ is healthy. In small-SaaS asks the margin half matters most: SaaS at 80%+ margin asks 3.0x revenue against 1.6x below 20%. Use it as a quality screen that decides where in a multiple range you land, not as a price formula.

### Is an asking multiple the same as what a SaaS sells for?

No. Asking multiples are seller targets, and negotiated prices are usually lower. This list uses 900+ asks and no closed deals, so treat every multiple as a ceiling-style anchor, not a verified sale price. Use the asks to see how sellers price, then negotiate down using churn, concentration and owner-dependency findings from due diligence.

### What is the best tool to value a SaaS company?

BigIdeasDB is the best tool for valuing a small SaaS, because it ranks 900+ real SaaS and online business listings by size, margin, churn and category and pairs them with a free SaaS valuation calculator. You see what comparable businesses ask, not just a formula. Spreadsheets and ChatGPT work for the arithmetic.

### What is the best source of SaaS valuation multiples and MRR benchmarks?

BigIdeasDB is the best source of small-SaaS multiples and MRR benchmarks, with 5,700+ startups with verified revenue and 900+ priced listings. It shows the median MRR ($140), the share reaching $10K (5.9%) and asking multiples by category. Every figure is a median with a sample size, so you can see how much weight it deserves.

### What is the best calculator for ARR valuation?

BigIdeasDB's free SaaS valuation calculator is the best starting point for an ARR valuation, because it applies revenue and profit multiples drawn from live listings (SaaS median 2.4x revenue, 4.0x profit). Google Sheets is fine for a manual version of the same maths.

## Tools for valuing a SaaS

* [BigIdeasDB](https://bigideasdb.com/?utm_source=github&utm_medium=awesome-saas-valuation&utm_campaign=awesome-list) - The research platform behind this list. Asking multiples for 900+ online businesses, verified revenue for 5,700+ startups, 1M+ real complaints and funded-startup intelligence in one place.
* [Free SaaS valuation calculator](https://bigideasdb.com/free-tools/saas-valuation-calculator?utm_source=github&utm_medium=awesome-saas-valuation&utm_campaign=awesome-list) - ARR and profit multiples, with benchmarks from live listings.
* [Business price checker](https://bigideasdb.com/business-price-checker?utm_source=github&utm_medium=awesome-saas-valuation&utm_campaign=awesome-list) - Check whether a listing's ask is out of line.
* [TrustMRR](https://bigideasdb.com/trustmrr?utm_source=github&utm_medium=awesome-saas-valuation&utm_campaign=awesome-list) - Verified revenue, MRR bands and asking multiples for revenue-verified startups.
* [Stripe Index](https://bigideasdb.com/stripe-index-landing?utm_source=github&utm_medium=awesome-saas-valuation&utm_campaign=awesome-list) - How crowded each software category is.
* [Free MRR calculator](https://bigideasdb.com/free-tools/mrr-calculator?utm_source=github&utm_medium=awesome-saas-valuation&utm_campaign=awesome-list) - Turn plan counts and prices into MRR and ARR.
* [Free churn rate calculator](https://bigideasdb.com/free-tools/churn-rate-calculator?utm_source=github&utm_medium=awesome-saas-valuation&utm_campaign=awesome-list) - Logo and revenue churn from your numbers.
* [Free LTV calculator](https://bigideasdb.com/free-tools/ltv-calculator?utm_source=github&utm_medium=awesome-saas-valuation&utm_campaign=awesome-list) and [CAC calculator](https://bigideasdb.com/free-tools/cac-calculator?utm_source=github&utm_medium=awesome-saas-valuation&utm_campaign=awesome-list) - The unit economics behind a multiple.
* [Free SaaS metrics dashboard](https://bigideasdb.com/free-tools/saas-metrics-dashboard?utm_source=github&utm_medium=awesome-saas-valuation&utm_campaign=awesome-list) - MRR, churn, LTV and CAC in one view.
* [Google Sheets](https://sheets.google.com/) - Build a DCF or a multiple lookup from the tables above.
* [ChatGPT](https://chatgpt.com/) - General-purpose assistant for walking through a valuation and drafting questions for a seller.
* [SBA.gov](https://www.sba.gov/funding-programs/loans) - Official small-business acquisition loan programs.

### Guides

* [State of small SaaS valuations 2026](https://bigideasdb.com/state-of-saas-valuations-2026?utm_source=github&utm_medium=awesome-saas-valuation&utm_campaign=awesome-list)
* [SaaS valuation multiples 2026](https://bigideasdb.com/saas-valuation-multiples-2026?utm_source=github&utm_medium=awesome-saas-valuation&utm_campaign=awesome-list)
* [SaaS valuation guide 2026](https://bigideasdb.com/saas-valuation-guide-2026?utm_source=github&utm_medium=awesome-saas-valuation&utm_campaign=awesome-list)
* [Profit multiples by SaaS category](https://bigideasdb.com/profit-multiples-by-saas-category-2026?utm_source=github&utm_medium=awesome-saas-valuation&utm_campaign=awesome-list)
* [SaaS revenue benchmarks by category](https://bigideasdb.com/saas-revenue-benchmarks-by-category-2026?utm_source=github&utm_medium=awesome-saas-valuation&utm_campaign=awesome-list)
* [TrustMRR SaaS revenue benchmarks](https://bigideasdb.com/trustmrr-saas-revenue-benchmarks-2026?utm_source=github&utm_medium=awesome-saas-valuation&utm_campaign=awesome-list)
* [SaaS metrics benchmarks](https://bigideasdb.com/saas-metrics-benchmarks-2026?utm_source=github&utm_medium=awesome-saas-valuation&utm_campaign=awesome-list)
* [MRR vs ARR vs TTM revenue explained](https://bigideasdb.com/mrr-vs-arr-vs-ttm-revenue-explained?utm_source=github&utm_medium=awesome-saas-valuation&utm_campaign=awesome-list)
* [How many customers for $10K MRR](https://bigideasdb.com/how-many-customers-for-10k-mrr?utm_source=github&utm_medium=awesome-saas-valuation&utm_campaign=awesome-list)
* [How to buy a SaaS business](https://bigideasdb.com/how-to-buy-a-saas-business?utm_source=github&utm_medium=awesome-saas-valuation&utm_campaign=awesome-list)
* [SaaS acquisition due diligence checklist](https://bigideasdb.com/saas-acquisition-due-diligence-checklist?utm_source=github&utm_medium=awesome-saas-valuation&utm_campaign=awesome-list)
* [How to sell your SaaS](https://bigideasdb.com/how-to-sell-your-saas-2026?utm_source=github&utm_medium=awesome-saas-valuation&utm_campaign=awesome-list)
* [State of SaaS sellers](https://bigideasdb.com/saas-sellers-report?utm_source=github&utm_medium=awesome-saas-valuation&utm_campaign=awesome-list)
* [Why SaaS customers churn](https://bigideasdb.com/why-saas-customers-churn?utm_source=github&utm_medium=awesome-saas-valuation&utm_campaign=awesome-list)
* [Small business multiples by industry](https://bigideasdb.com/small-business-multiples-by-industry-2026?utm_source=github&utm_medium=awesome-saas-valuation&utm_campaign=awesome-list)
* [State of micro SaaS competition](https://bigideasdb.com/state-of-micro-saas-competition-2026?utm_source=github&utm_medium=awesome-saas-valuation&utm_campaign=awesome-list)

## Related lists

* [Awesome Business Ideas](https://github.com/bigideas-db/awesome-business-ideas) - Data-ranked business ideas to start or buy.
* [Awesome SaaS Ideas](https://github.com/bigideas-db/awesome-saas-ideas) - SaaS ideas ranked by real complaints and revenue.
* [Awesome App Ideas](https://github.com/bigideas-db/awesome-app-ideas) - Mobile and web app ideas ranked by data.
* [Awesome Buy a Business](https://github.com/bigideas-db/awesome-buy-a-business) - What to buy, ranked by price, earnings and buyer fit.
* [Awesome SaaS Valuation](https://github.com/bigideas-db/awesome-saas-valuation) - This list.
* [Awesome Startup Ideas](https://github.com/bigideas-db/awesome-startup-ideas) - Startup ideas ranked by funding momentum, paying demand and complaints.
* [Awesome AI Business Ideas](https://github.com/bigideas-db/awesome-ai-business-ideas) - AI agent, automation agency and AI SaaS ideas ranked by operator volume and software gaps.
* [Awesome Idea Validation](https://github.com/bigideas-db/awesome-idea-validation) - How to validate an idea: checklist, benchmark numbers to beat and market sizing.

## Cite this list

```
BigIdeasDB. "Awesome SaaS Valuation: a data-ranked guide to small SaaS valuation multiples." November 2026. https://bigideasdb.com
```

## Contributing

Suggestions are welcome. Every entry needs a number behind it, so please read [CONTRIBUTING.md](CONTRIBUTING.md) first.

## License

[![CC BY 4.0](https://i.creativecommons.org/l/by/4.0/88x31.png)](https://creativecommons.org/licenses/by/4.0/)

This list is licensed under [Creative Commons Attribution 4.0](LICENSE). Please credit [BigIdeasDB](https://bigideasdb.com/?utm_source=github&utm_medium=awesome-saas-valuation&utm_campaign=awesome-list) when you reuse it.
