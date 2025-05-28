🧪 Lagged Correlation Analysis Between COVID-19 Vaccination and ICU Admissions

📌 Overview
This project investigates the relationship between COVID-19 vaccination rates and ICU admissions in Singapore (2023–2024). Using weekly epidemiological data, the analysis explores the timing and effectiveness of vaccinations in mitigating severe health outcomes.

📊 Objectives
Assess if higher vaccination uptake correlates with reduced ICU admissions.

Examine time-lagged effects of vaccination on hospitalization trends.

Analyze the role of behavioral factors (e.g., mobility) in shaping health outcomes.

🧬 Data Sources
Vaccination data: Doses administered, population coverage.

Infection data: Weekly infection estimates.

Hospitalization data: Weekly hospital and ICU admissions.

🔍 Methodology
Preprocessing: Cleaned and merged datasets by EPI week.

Exploratory analysis: Visualized trends and generated correlation matrices.

Hypothesis testing: Used Pearson correlation and linear regression to test associations.

Lagged analysis: Shifted vaccination data (1–4 weeks) to detect delayed effects on ICU admissions.

📈 Key Findings
Weak correlation: A slight positive correlation (r = 0.14) between vaccination rates and ICU admissions, not statistically significant (p = 0.318).

Lagged regression: Two-week lagged vaccinations showed no significant predictive value for ICU admissions (R² ≈ 0).

Trends: ICU admissions declined during periods of increased vaccinations, suggesting potential indirect effects.

⚠️ Limitations
Short time frame (2 years).

Lack of demographic breakdown and external policy data.

Correlation does not imply causation; further modeling is needed.

🔮 Future Work
Include demographic and behavioral data.

Use machine learning to improve predictive insights.

Expand to multi-year datasets for long-term trend analysis.
