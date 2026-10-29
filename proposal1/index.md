---
title: Proposal 1 - Seattle Rent
---

# Seattle Rent and Mixed-Income Housing

**Research question:** Across Seattle census tracts, how are mixed-income apartment counts associated with apartment rent levels and year-over-year rent growth?

## What the analysis shows

After excluding non-positive rent values, the exploratory dataset contains **3,931 observations across 160 tracts**, covering **2001–2025**. Mean monthly contract rent per unit is about **$1,486**, and the median is about **$1,432**. The tract-level count of mixed-income apartments has a positive association with rent level (**Pearson r = 0.464**), while its linear association with annual rent growth is close to zero (**r = -0.014**).

The charts show the time pattern, rent versus mixed-income counts, differences among high-rent communities, and correlations among the analysis variables. These are descriptive relationships; the analysis does not establish that mixed-income development causes rents to rise or fall.

## Visualizations

![Seattle apartment rent trend, 2001 to 2025](rent-trend.png)

![Mixed-income apartment count and tract rent](mixed-income-rent.png)

![Seattle communities with the highest mean rent](community-rent.png)

![Correlation structure of study variables](correlation-heatmap.png)

## Limitations and data note

The records are aggregated by census tract and may be affected by tract size, neighborhood location, housing stock, and other unmeasured differences. The supplied coursework archive does not identify the original publisher or redistribution terms for the raw Seattle data; those terms should be verified before external reuse.

## Reproduce and explore

See the [project README](https://github.com/mc66006/data-science-project/blob/main/proposal1/README.md) for the methods and run instructions. The source folder contains the [analysis notebook](https://github.com/mc66006/data-science-project/blob/main/proposal1/seattle_rent.ipynb), proposal, CSV files, script, and generated figures.

**Project status:** Proposal and exploratory analysis — ongoing.

[Back to portfolio](../)
