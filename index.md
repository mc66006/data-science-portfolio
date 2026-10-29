# Li WaiCheng | Data Science Portfolio

Hello! I am a CISC7204 student building practical skills in data cleaning, exploratory analysis, visualization, reproducible Python workflows, and responsible interpretation.

## Technical skills

Python · pandas · NumPy · Matplotlib · Seaborn · scikit-learn · Jupyter Notebook · Git · GitHub Pages

## Project showcase

### Seattle Apartment Rent and Mixed-Income Housing

**Status:** Completed course portfolio project; descriptive analysis with a reproducible script.

**Research question:** How are mixed-income apartment counts associated with median apartment rent per unit across Seattle census tracts from 2001 to 2025? Does the pattern differ for year-over-year rent growth, and how well can year, mixed-income count, and property count predict rent levels?

The project uses the City of Seattle's Apartment Market Rent Prices by Census Tract dataset. The cleaned analysis contains 3,931 tract-year rows from 2001–2025. Mixed-income count has a moderate positive correlation with rent per unit (r = 0.464) and a near-zero correlation with year-over-year rent change (r = -0.014). The simple random 80/20 regression benchmark has test R² = 0.422 and RMSE = $329.08. These results describe associations and prediction, not causal effects.

![Average Seattle apartment rent over time](figures/rent-trend.png)

![Mixed-income apartments and median rent](figures/mixed-income-rent.png)

![Mixed-income apartments and year-over-year rent growth](figures/mixed-income-rent-growth.png)

![Community rent comparison](figures/community-rent.png)

The main limitations are repeated observations for the same tract, omitted factors such as location and inflation, and the fact that market rent is not a complete affordability measure. A verified classmate review and committed response are still pending for the projects shown here; the project repository includes a factual feedback-record template.

- **Project repository:** [CISC7204-MC66006-2026GitHub](https://github.com/mc66006/CISC7204-MC66006-2026GitHub)
- **Data source:** [City of Seattle Open Data](https://data.seattle.gov/dataset/Apartment-Market-Rent-Prices-by-Census-Tract/h27p-5k3i)
- **Feedback record:** [`FEEDBACK.md`](https://github.com/mc66006/CISC7204-MC66006-2026GitHub/blob/main/FEEDBACK.md)

### College Tuition and Graduate Earnings

**Status:** Completed descriptive analysis; proposal, executed results, and reproducible figures are archived in the standalone Assignment 02 repository.

**Research question:** Is annual undergraduate tuition associated with median earnings 10 years after entry, and does the relationship differ between public and private four-year institutions?

This project uses an institution-level extract from the U.S. Department of Education [College Scorecard](https://collegescorecard.ed.gov/data/). After restricting to predominantly bachelor's-degree institutions and removing suppressed or invalid values, the analysis contains 1,731 institutions: 566 public and 1,165 private (nonprofit and for-profit combined). Median in-state tuition is $10,330 for public institutions and $35,760 for private institutions, while median 10-year earnings are $59,272 and $58,029. Within-group tuition/earnings correlations are 0.523 for public institutions and 0.644 for private institutions.

![Tuition and 10-year median earnings by institution type](figures/tuition-earnings-scatter.png)

![10-year median earnings by institution type](figures/earnings-by-institution-type.png)

![Annual tuition distribution by institution and residency](figures/tuition-distribution.png)

The analysis is descriptive and institution-level. It does not establish that tuition causes earnings: the data do not control for field of study, geography, preparation, selectivity, financial aid, inflation, living costs, or cohort differences. The complete [Assignment 02 proposal repository](https://github.com/mc66006/CISC7204-Assignment02-College-Tuition-Proposal) contains the results, limitations, reproduction script, proposal, notebook, cleaned data, and figures.

## Reflection

This portfolio demonstrates data cleaning, visualization, Python scripting, and responsible interpretation. I analyzed City of Seattle tract-level apartment-rent data from 2001–2025 to examine mixed-income apartment counts, rent levels, and annual rent change. After validation, 3,931 tract-year records remained. Mixed-income count correlated moderately with rent per unit (r = 0.464) and almost not at all with annual rent change (r = -0.014). A random-split regression produced R² = 0.422 and RMSE = $329.08. These are associations, not causal effects; repeated tracts and omitted factors limit conclusions. My next step is time-aware modeling with inflation-adjusted rent, followed by a classmate review and a documented improvement.

The [approximately 200-word rubric reflection](https://github.com/mc66006/CISC7204-MC66006-2026GitHub/blob/main/REFLECTION.md) and [approximately 100-word checklist reflection](https://github.com/mc66006/CISC7204-MC66006-2026GitHub/blob/main/REFLECTION_SHORT.md) are both in the project repository.

## Responsible sharing

The public project uses tract-level aggregate data, contains no passwords, API keys, or private individual records, and links to the City of Seattle source and its listed Open Data Commons PDDL licence.
