A/B Testing Homepage Conversion Rate Analysis
📌 Project Overview

This project analyzes the impact of a new homepage design on the conversion rate of an e-commerce website using A/B Testing methodology.
The experiment compares user behavior between:

Control Group → users who saw the old homepage design
Treatment Group → users who saw the new homepage design
The main objective is to determine whether the new homepage design significantly improves conversion rates.


🎯 Objective

To evaluate whether the redesigned homepage increases the website conversion rate compared to the previous homepage design.

🧪 Hypothesis Testing
Null Hypothesis (H0)

Null Hypothesis (H0)

There is no significant difference in conversion rate after the homepage redesign.

H0​:Conversion Rateold​ = Conversion Ratenew​
	​

Alternative Hypothesis (H1)

There is a significant difference in conversion rate after the homepage redesign.

H1​:Conversion Rate old​ (not same) Conversion Ratenew​
	​

	​

📂 Dataset Description
Column	Description
user_id: unique id of the user who came to the website
timestamp: timestamp that the user came to the page
group: whether the user in treatment group or control group
landing_page: whether the user saw the old page or new page
converted: whether the user converted to a paid user. 1 means converted, 0 means not converted.

Group Definition
Control Group → Old homepage design
Treatment Group → New homepage design

⚙️ Tools & Libraries
Python
Pandas
NumPy
SciPy
Statsmodels
Matplotlib / Seaborn

🔍 Analysis Steps
Data Cleaning & Validation
Exploratory Data Analysis (EDA)
Calculate Conversion Rate per Group
Perform Statistical Hypothesis Testing
Analyze p-value and Confidence Level
Draw Business Conclusion & Recommendation
📊 Statistical Method

This project uses:

Two-Proportion Z-Test
Significance level (α) = 0.05

Decision Rule:

If p-value < 0.05 → Reject H0
If p-value ≥ 0.05 → Fail to Reject H0

📈 Result Interpretation
Conversion Rate
Control Group (Old Homepage) achieved a conversion rate of 12.04%
Treatment Group (New Homepage) achieved a conversion rate of 11.88%

This indicates that the new homepage design produced a slightly lower conversion rate compared to the old homepage.

Statistical Test Result
Z-statistic = 1.31
The observed difference between both groups is approximately 1.31 standard deviations away from the null hypothesis value.
P-value = 0.1897

This represents the probability of obtaining the observed result (or a more extreme result) assuming the null hypothesis is true.
Hypothesis Decision
Because the P-value (0.1897) > 0.05, we fail to reject the null hypothesis (H0).
This means there is no statistically significant difference in conversion rates between the old homepage and the new homepage design.

💡 Business Insight

Even though the new homepage may improve visual appearance or user experience, the experiment suggests that the redesign alone may not significantly impact user conversion behavior.

📌 Recommendations
Based on the A/B testing results, the following recommendations are proposed:

- Maintain the Current Homepage Design
Since the new homepage design did not show a statistically significant improvement in conversion rate, it is recommended to keep the existing homepage design for now. This decision can help minimize unnecessary implementation and redesign costs.

- Conduct Further Analysis
Additional analysis can be performed by segmenting users based on demographics, behavior, or traffic source. Future experiments can also be conducted during specific periods such as payday seasons, promotional events, or holiday periods to observe potential differences in user behavior.

- Optimize the New Homepage Design
Instead of fully discarding the new design, further evaluation should identify which sections of the homepage may need improvement, such as:

-CTA button placement
-Product visibility
-Navigation flow
-Visual hierarchy
-Mobile responsiveness

- Evaluate Additional Metrics
Conversion rate alone may not fully capture user engagement. Future analysis should also consider other performance metrics, including:

-Time spent on page
-Bounce rate
-Number of pages visited
-Click-through rate (CTR)
-User engagement behavior


These metrics can provide deeper insights into how users interact with the homepage and help identify opportunities for optimization.
