**Economic Performance & Incumbent Presidential Vote Share**

**Overview:**

This project analyzes the relationship between economic performance (measured by Real Disposable Income (RDI)) and state-level incumbent presidential vote share in the U.S. from 1976 to 2020. Inspired by James Carville's "It's the economy, stupid!" mantra, the project investigates whether changes in Real Disposable Income (RDI) influence voter behavior.

The RMarkdown code is attached to the main branch. The PDF results are attached as well.

This code was submitted as a part of a final project for POLI 381 at UNC-Chapel Hill, taught by Dr. Alexander Sahn in the Political Science Department.

**Data**

- MIT Election Lab: State-level presidential vote shares (1972-2020)

- Bureau of Economic Analysis: Per-capita state-level average RDI (adjusted for inflation)

- U.S. Census: State-level racial demographics (1970-2020)

- Bureau of Labor Statistics: State-level unemployment data (1976-2020)

**Variables**

- Independent Variable: Percentage change in RDI between election years

- Dependent Variable: Incumbent presidential vote share (percentage of votes for the incumbent party)

- Confounder: Proportion of the population that is Black in each state

**Regression Models**

- Bivariate Regression: Examines the direct relationship between RDI % change and incumbent presidential vote share.

- Multivariate Regression: Introduces Black population proportion as a confounder.

- Interaction Regression: Includes an interaction term between RDI % change and Black population proportion.

- Time-Series Analysis: Analyzes year-by-year regression results to assess how the relationship between economic performance and vote share evolves over time.

- Robustness Check: Substitutes RDI % change with the unemployment rate to test the consistency of results.

**Key Findings**

- Across all election years (1976-2020), there is a statistically significant positive relationship between RDI % change and incumbent presidential vote share.

- When controlling for Black population proportion, the relationship between RDI % change and vote share remains significant, though the effect size slightly diminishes.

- The time-series analysis reveals that the relationship between economic performance and incumbent vote share is not consistent across all election years. Statistical significance is only found in recessionary periods (1992, 2008, 2016).

- The robustness check using the unemployment rate does not yield statistically significant results, suggesting that RDI % change may be a more direct economic indicator influencing voting behavior.

**Limitations**

- Low R-Squared Values: The regression models explain only a small portion of the variance in incumbent vote share, indicating that many other factors influence voter behavior.

- Potential Confounders: Other variables, such as education levels, campaign strategies, and regional economic disparities, were not included.

- Estimation Errors: For years without Census data, the Black population proportion was estimated based on trends, introducing potential inaccuracies.


