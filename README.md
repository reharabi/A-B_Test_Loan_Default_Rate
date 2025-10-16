#**Loan Default A/B Test: Prime Borrower Badge Impact**

This project evaluates whether highlighting “Prime Borrower” status for applicants with above-median credit scores reduces loan default rates.

## Experiment Design

- **Variant A**: No badge
- **Variant B**: “Prime Borrower” badge
- **Metric**: Loan default rate

## Results

| Variant | Defaults | Total | Default Rate |
|---------|----------|-------|--------------|
| A       | 61       | 299   | 20.40%       |
| B       | 47       | 301   | 15.61%       |

- **Two-Proportion Z-Test**  
  - Z-statistic: −1.53  
  - P-value: 0.0635  
  - Conclusion: Not statistically significant at the 5% level, but suggestive at the 10% level

- **95% Confidence Interval (Score Method)**  
  - Difference in default rates (B − A):  
    

\[
    [-10.88\%, +1.38\%]
    \]



## Executive Summary
We conducted an A/B test to evaluate whether highlighting “Prime Borrower” status for applicants with credit scores above the median correlates with lower loan default rates.

- Variant A (no badge): 20.40% default rate (61/299)
- Variant B (“Prime Borrower” badge): 15.61% default rate (47/301)

A two-proportion z-test yielded a Z-statistic of −1.53 and a p-value of 0.0635, indicating that the difference is not statistically significant at the 5% level, but suggestive at the 10% level.

The 95% confidence interval for the difference in default rates (B − A) ranges from −10.88% to +1.38%, suggesting a potential reduction in default risk. We recommend further testing with a larger sample to confirm the effect



## Files

- [View the analysis notebook](): Python notebook with hypothesis testing and confidence interval calculations
- 

## Tools Used

- Python 
- Jupyter Notebook


---

## 📬 Contact 

**Reha Rabi**

For questions or collaboration, feel free to reach out via GitHub Issues or LinkedIn.
