Repair Our Air (ROA): AQI Policy Recommendations


Overview


This project is my personal work at Repair Our Air (ROA), an environmental think tank dedicated to improving air quality across America. I have utilized data-driven methods based on the Environmental Protection Agency's Air Quality Index (AQI) to develop strategic policy recommendations.

AQI values near 0 indicate little to no public health concern.

Higher AQI values signify an increased risk to public health.

Through rigorous hypothesis testing, I aimed to generate actionable insights to prioritize ROA’s efforts in air quality improvement.

Policy Decision Analysis:

1. Metropolitan Focus in California
Objective:
To determine if the mean AQI in Los Angeles County is statistically different from the rest of California.

Hypotheses:

Null hypothesis: The mean AQI in LA County = Rest of California

Alternative hypothesis: The means are different

Methodology:
I used Welch’s t-test (scipy.stats.ttest_ind() with equal_var=False) at a 5% significance level.

Visualization:
Boxplots comparing AQI distributions for Los Angeles County versus other parts of California.

2. Regional Office Placement: New York vs Ohio
Objective:
To assess whether New York has a lower mean AQI than Ohio, guiding the decision for the next regional office.

Hypotheses:

Null: Mean AQI in New York ≥ Ohio

Alternative: Mean AQI in New York < Ohio

Methodology:
Conducted a one-sided Welch’s t-test (equal_var=False) at α=0.05

Visualization:
Comparative bar plots illustrating AQI levels to support the analysis.

3. Impact of New Policy on Michigan
Objective:
To evaluate whether Michigan’s mean AQI is ≥ 10, determining if the policy will affect the state.

Hypotheses:

Null: Mean AQI Michigan < 10

Alternative: Mean AQI Michigan ≥ 10

Methodology:
Performed a one-sample t-test against the threshold value 10.

Visualization:
AQI distribution plots with a reference line at AQI = 10 to illustrate Michigan’s status.

My Approach:

Throughout this analysis, I ensured:

Applying Welch’s t-test to account for unequal variances.

Maintaining a 5% significance level for confident decision-making.

Combining statistical tests with clear visualizations for better interpretability.

This project showcases my ability to apply statistical methods to real-world environmental issues and to translate data insights into policy recommendations.

Feel free to explore or contact me for a deeper discussion of the findings or methodologies!
