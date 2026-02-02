Project Overview
This project demonstrates an end-to-end A/B testing analysis to compare a Control group and a Test group. The goal is to determine whether the Test version performs significantly better using statistical hypothesis testing and to provide a clear business recommendation.

🎯 Objectives
Identify Control and Test groups

Compare key performance metrics (conversion rate or mean value)

Perform statistical hypothesis testing

Determine statistical significance

Provide a data-driven business decision

🧪 Methodology
Load the dataset and split Control vs Test groups

Define hypotheses (H0, H1) and significance level (α = 0.05)

Calculate group metrics (conversion rate / mean)

Apply appropriate statistical test:

Chi-square test for conversion data

T-test for continuous metrics

Analyze p-value and confidence interval

Visualize group performance

Provide final decision and recommendation

🛠️ Tools & Libraries Used
Python

Pandas

NumPy

SciPy

Matplotlib

📂 Dataset
marketing_AB.csv

Key columns:

group → Control / Test

converted → 0 (No) / 1 (Yes)

📈 Key Results
Conversion rates were calculated for both groups

Statistical significance was evaluated using p-value

Confidence interval quantified the difference between groups

✅ Conclusion & Recommendation
Based on the statistical test results and confidence interval, the project concludes whether the Test version shows a significant improvement over the Control version and recommends whether to roll out the Test variant.
