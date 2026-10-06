**Clinical Trial Product & Experimentation Analytics**

**Short project overview**
This project analyzes a synthetic clinical trial dataset to evaluate treatment effectiveness, compare Treatment vs Control groups, assess statistical significance, and explore adverse events, medication adherence, and patient-level subgroups.
The analysis combines Snowflake SQL, Python, SciPy, and Power BI to demonstrate an end-to-end data analytics workflow from data preparation and statistical testing to interactive dashboard development.
Note: The dataset is fully synthetic and is intended for portfolio and educational purposes only. It does not represent real patients or clinical recommendations.

**Tech stack**
Snowflake | SQL | Python | Pandas | NumPy | SciPy | Matplotlib | Power BI | GitHub

**Key findings**
Metric	Result
Total Participants	- 10,000
Control Response Rate	- 43.66%
Treatment Response Rate -	72.40%
Treatment Effect	-  +28.74 pp
95% CI	- +26.89 to +30.59 pp
Relative Improvement - 65.83%
Number Needed to Treat - 3.48
Control Avg. Outcome Change -	8.58
Treatment Avg. Outcome Change -	14.71
Control Adverse Event Rate - 27.20%
Treatment Adverse Event Rate -	27.44%
Adverse Event p-value -	0.805


**Statistical analysis**
The project uses SciPy to perform:
- Two-proportion statistical testing
- 95% confidence interval estimation
- Welch's t-test
- Chi-square testing
- Practical significance analysis
- Subgroup analysis
  
**Dashboard**
The Power BI dashboard focuses on:
- Treatment vs Control response
- Treatment effect
- Outcome change
- Baseline severity
- Risk category
- Adverse events
- Medication adherence
  
**Important interpretation**
The Treatment group achieved a substantially higher response rate than the Control group, with an estimated treatment effect of +28.74 percentage points and a statistically significant difference (p < 0.001).
Average outcome change was also higher for Treatment than Control. Adverse-event rates were nearly identical between groups, with no statistically significant difference (p = 0.805).
Subgroup results showed a consistent treatment advantage across baseline severity and known risk categories. The adherence analysis showed differences across adherence bands, but the relationship was non-monotonic, so the analysis does not establish that higher adherence causes higher response.





