# A/B Testing

📘A/B testing is a controlled experiment that compares two versions of a webpage, product, or feature to determine which performs better based on a specific metric such as conversion rate.

🧠 Objective:
To statistically determine whether a new version (Variant B) leads to a significant change in behavior compared to the current version (Variant A).

📊 Statistical Overview:
- Test Type: Two-Proportion Z-Test
- Metric: Conversion Rate
- Null Hypothesis (H₀): CRₐ = CRᵦ 
- Alternative Hypothesis (H₁): CRₐ ≠ CRᵦ 
- Significance Level (α): Typically set at 0.05
  

  Key Features:
- Goal: Detect if there's a significant difference between groups.
- Test: Two-proportion Z-test for comparing conversion rates.
- Null Hypothesis (H₀): No difference between A and B.
- Alternative Hypothesis (H₁): A difference exists.
- Decision Rule: If p-value < 0.05, reject H₀.
- Confidence Interval (CI): Shows the range where the true conversion likely falls.
- Sequential Testing: Monitor over time but requires corrections to maintain validity.
