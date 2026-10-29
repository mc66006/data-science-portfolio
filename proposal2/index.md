---
title: Proposal 2 - College Tuition and Earnings
---

# College Tuition and Ten-Year Earnings

**Research question:** Is annual undergraduate tuition associated with median earnings ten years after entry, and does the relationship differ between public and private four-year institutions?

## What the analysis shows

After filtering to predominantly four-year institutions and removing suppressed, missing, or invalid analysis values, the sample contains **1,731 institutions**: 566 public and 1,165 private. Public institutions have a median in-state tuition of **$10,330** and median ten-year earnings of **$59,272**. Private institutions have a median tuition of **$35,760** and median earnings of **$58,029**. Tuition and earnings have positive within-group correlations in this sample (**r = 0.523** for public and **r = 0.644** for private institutions).

The pattern is institution-level and descriptive. It does not show that higher tuition produces higher earnings or represent any individual student's return on investment.

## Visualizations

![Tuition and ten-year earnings by institution type](tuition-earnings-scatter.png)

![Earnings by institution type](earnings-by-institution-type.png)

![Tuition distribution](tuition-distribution.png)

## Methods, limitations, and data source

The analysis filters the U.S. Department of Education College Scorecard institution extract to predominantly bachelor's-degree institutions, converts suppressed earnings values to missing, removes unusable tuition or earnings records, and compares public and private groups. The private group combines nonprofit and for-profit colleges. Tuition and earnings may represent different cohorts; the analysis does not adjust for inflation, financial aid, debt, field of study, student background, geography, or cost of living. Consult the source data page and the project README before redistributing the raw extract.

## Reproduce and explore

The [source project folder](https://github.com/mc66006/data-science-project/tree/main/proposal2) contains the revised proposal, notebook, data extract, cleaning script, cleaned data, generated figures, and a detailed [results and limitations report](https://github.com/mc66006/data-science-project/blob/main/proposal2/RESULTS.md). Run `python analyze_college_scorecard.py` from that folder.

**Project status:** Proposal and exploratory analysis — ongoing.

[Back to portfolio](../)
