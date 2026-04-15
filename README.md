# Employee-attrition-Hypothesis-A-B-testing
Statistical analysis of employee attrition using hypothesis testing and A/B testing.

# Employee Attrition: Hypothesis Testing & A/B Analysis

# Project Overview
This project investigates factors associated with employee attrition using statistical hypothesis testing. The analysis demonstrates practical applications of t-tests, chi-squared tests, ANOVA, and A/B testing, along with corresponding effect size measures.

#  Objectives
- Identify factors associated with employee attrition.
- Demonstrate statistical hypothesis testing techniques.
- Evaluate practical significance using effect sizes.
- Simulate an A/B testing framework for business decision-making.

# Dataset
The dataset contains employee demographic and organizational information, including:
- Age
- Education
- PaymentTier
- Gender
- City
- EverBenched
- ExperienceInCurrentDomain
- LeaveOrNot (Target)

*Source: Kaggle – Employee Attrition Dataset*

# Statistical Methods

| Test | Purpose | Effect Size |
|------|---------|-------------|
| **t-test** | Compare mean age between leavers and stayers | Cohen’s d |
| **Chi-Squared** | Association between categorical variables and attrition | Cramér’s V |
| **ANOVA** | Differences in tenure across education and payment tiers | Eta Squared (η²) |
| **A/B Test** | Impact of benching on attrition | Chi-Squared / Two-Proportion Test |

# Key Findings
- **Age:** Statistically significant but negligible practical impact (Cohen’s d ≈ 0.11).
- **Education & PaymentTier:** No significant differences in years of experience (η² ≈ 0).
- **Categorical Features:** Weak associations with attrition (low Cramér’s V).
- **EverBenched:** No statistically significant difference in retention rates.

# Business Implications
- No single feature strongly predicts attrition.
- Age may serve as a control variable in multivariate models.
- Multivariate modeling (e.g., logistic regression) is recommended for deeper insights.

# Technologies Used
- Python
- Pandas
- NumPy
- SciPy
- Statsmodels
- Matplotlib
- Jupyter Notebook
