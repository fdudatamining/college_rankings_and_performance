# Exploring relationships between medical college rankings and performance with big data

If you find this work valuable or reuse parts of it, please cite us: 
> Rao, AR, Clarke, D. *Exploring relationships between medical college rankings and performance with big data*. BMC Big Data Analytics. <https://doi.org/10.1186/s41044-019-0040-9>

## Abstract

**Background**: It is important to examine the cost-effectiveness of medical education.
The public wants to know how government spending is being utilized to train
doctors. There are very few studies that examine national data to understand the
relationships between medical education and outcomes.
We used Big Data analytics with open health data to explore answers. We joined
physician data and hospital total performance score data reported by Center for
Medicare and Medicaid Services (CMS), containing information for nearly 600,000
practitioners and performance scores from three thousand hospitals in the United
States. We combined this data medical college costs from the American Association
of Medical Colleges and medical school rankings. We used Mullan’s social mission to
compare medical schools. We also computed the correlation between the rankings
of 4-year baccalaureate colleges in the US published by the Wall Street Journal, and
the in-state tuition at these colleges in the Integrated Post-secondary Education
System database.

**Results**: We found a statistically significant but negligible correlation (Spearman rank
correlation − 0.04, p-value < 0.0001) between the rank of a medical school and the
total performance score of the hospitals that their graduates practiced in. We found
a statistically significant and high correlation (Spearman rank correlation of − 0.903,
p-value = 0.003) between the averaged rank of medical schools and average number
of graduates produced by these schools associated with CMS hospitals. Similar
results were obtained for the social mission score. In contrast, the correlation
between the ranking of 4-year colleges and (a) their tuition was − 0.34 and (b) their
outcomes was − 0.86 (p-value < 10− 5
).

**Conclusions**: Our results suggest that US medical education is robust and produces
satisfactory performance outcomes. Higher tuition is not correlated with higher ranks
or better outcomes. Hence, the public needs to question what they are getting in
return for higher tuition. We also suggest that it may be better to produce more
graduates from existing medical schools than opening new schools.


## Reproduction
To reproduce this analysis you'll need to [prepare your environment](https://github.com/fdudatamining/system). Alternatively you can [install the framework](https://github.com/fdudatamining/framework) and [obtain the data](https://github.com/fdudatamining/data) separately.

The following data sources are required for the analysis:
- medical_college_costs_ranks_complete
- medical_schools_social_mission_rank
- hospital_practitioners

