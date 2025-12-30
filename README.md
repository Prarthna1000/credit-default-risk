# Credit Default Risk Analysis (Rule-Based vs Model-Based)

## Objective
This project analyzes credit default risk using Lending Club loan data.
It compares traditional rule-based credit policies with probability-based
decisioning using a logistic regression model.

The goal is to understand the trade-off between portfolio risk reduction
and loan approval volume.

## Dataset
- Lending Club loan data (2007–2015)
- Target variable: loan default
- Key features: interest rate, debt-to-income ratio (DTI)

## Analysis Overview
1. Exploratory analysis of default behavior
2. Interest rate and DTI bucketing
3. Rule-based credit policies (Policy V1 and V2)
4. Trade-off analysis and diminishing returns
5. Logistic regression model for default prediction
6. Probability threshold testing (20% vs 25%)
7. Comparison of rule-based vs model-based decisioning
8. Monitoring and population stability considerations

## Key Findings
- Higher interest rates and higher DTI are associated with higher default risk
- Rule-based policies reduce risk but show diminishing returns as they tighten
- Logistic regression provides smoother risk separation
- For similar risk reduction, model-based thresholds reject fewer borrowers

## Business Takeaway
Probability-based decisioning enables flexible control of credit risk,
allowing better risk–volume trade-offs compared to rigid rule-based cutoffs.

## Tools Used
- Python
- Pandas, NumPy
- Scikit-learn
- Jupyter Notebook

