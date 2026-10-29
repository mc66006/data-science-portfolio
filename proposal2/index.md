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

**What this figure shows:** Each point represents an institution, with separate trend lines for public and private colleges. Both lines slope upward, while the substantial overlap shows why the association should not be read as a guarantee of higher earnings for an individual student.

![Earnings by institution type](earnings-by-institution-type.png)

**What this figure shows:** The box plot compares the spread of ten-year median earnings for public and private institutions. Their medians are similar even though the private group has much higher tuition, which is a useful caution against equating price with outcome.

![Tuition distribution](tuition-distribution.png)

**What this figure shows:** The tuition distributions make the public/private price gap visible. Public in-state tuition is lower in the sample; the values are institutional measures and do not represent each student's net price after aid.

## Conclusion

Tuition and ten-year median earnings have positive descriptive associations in both institution groups, with correlations of **0.523** for public and **0.644** for private institutions. Private institutions have a much higher median tuition but similar median earnings in this sample. The analysis therefore supports a question for deeper study, not a claim that tuition causes later earnings. Cohort differences, inflation, financial aid, field of study, selectivity, geography, and the combined nonprofit/for-profit private category remain important limitations.

## Methods, limitations, and data source

The institution-level extract was downloaded from the U.S. Department of Education [College Scorecard data portal](https://collegescorecard.ed.gov/data/). When checked on 2026-10-29, the official page said its data were last updated on 2026-10-15. The exact release date of the archived CSV in this project has not been verified. Consult the source page and its current data-use notice before redistributing the extract outside this coursework.

The analysis filters the extract to predominantly bachelor-degree institutions, converts suppressed earnings values to missing, removes unusable tuition or earnings records, and compares public and private groups. The private group combines nonprofit and for-profit colleges. Tuition and earnings may represent different cohorts; the analysis does not adjust for inflation, financial aid, debt, field of study, student background, geography, or cost of living. Correlations and fitted trend lines describe association and do not establish causation.

## Reproduce and explore

The [source project folder](https://github.com/mc66006/data-science-project/tree/main/proposal2) contains the revised proposal, notebook, data extract, cleaning script, cleaned data, generated figures, and a detailed [results and limitations report](https://github.com/mc66006/data-science-project/blob/main/proposal2/RESULTS.md). Run `python analyze_college_scorecard.py` from that folder.

**Project status:** Proposal and exploratory analysis — ongoing.

## Reflection

This College Tuition and Ten-Year Earnings project developed my ability to work with a large institutional dataset and make a research question operational. I selected predominantly four-year institutions, converted suppressed earnings values to missing, removed unusable records, grouped institutions by control type, and compared tuition and earnings with medians, correlations, trend lines, box plots, and distribution plots. I produced both a Jupyter notebook and a standalone Python script, which made the cleaning and figure-generation steps easier to inspect and reproduce. The analysis taught me to distinguish an institution-level association from an individual return on investment. Peer feedback highlighted that the portfolio needed text explaining what each visualization means and a clear conclusion. I responded in commit a1179c6 by adding interpretation below every chart and stating the practical meaning of the public/private comparison. The main limitation is confounding: cohort, inflation, financial aid, field of study, selectivity, geography, debt, and living costs are not fully controlled. The College Scorecard extract was downloaded from the U.S. Department of Education data portal, and its source and use note are recorded in the project README. My next step would be to inflation-adjust the measures, separate nonprofit and for-profit institutions, and run sensitivity analyses with additional covariates. This project demonstrates data cleaning, statistical reasoning, visualization, documentation, and careful communication of uncertainty.

[Back to portfolio](../)
