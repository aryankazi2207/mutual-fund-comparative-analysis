📊 Comparative Analysis of Two Mutual Funds
Statistical & Financial Data Analysis Project

This project performs a comprehensive statistical comparison of two mutual funds to evaluate their performance, risk, and return behavior over a three-year period. The analysis applies quantitative techniques from statistics and finance, including descriptive statistics, hypothesis testing, correlation, and regression, to determine whether the two funds differ significantly in their average monthly returns.

🏦 Funds Analyzed

Fidelity Advisor Blue Chip Growth (FBCJX)

JPMorgan US Equity I (JUESX)

These funds were randomly selected from a population of over 500 mutual funds.

🎯 Objective

To determine whether there is a statistically significant difference between the mean monthly returns of the two funds over the period:

October 2021 – September 2024

📊 Data Collection

Monthly historical price data was collected from Yahoo Finance. Monthly returns were calculated using:

Monthly Return=𝑃𝑡−𝑡−1/𝑃𝑡−1
Monthly Return=Pt−1/Pt−Pt−1
	​
The same time periods were used for both funds, making this a matched-pair (paired) dataset.

🔧 Methods & Techniques
1. Descriptive Statistics

Mean

Median

Standard deviation

Minimum and maximum returns

Used to compare risk and performance.

2. Visual Analysis

Boxplots to compare distributions

Difference boxplot to visualize spread of return differences

Scatter plot to show relationship between funds

3. Correlation Analysis

Correlation coefficient: 0.63

Indicates a moderate positive relationship.

4. Hypothesis Testing (Paired t-test)

Null Hypothesis (H₀): μ₁ − μ₂ = 0
Alternative Hypothesis (H₁): μ₁ − μ₂ ≠ 0

Significance level: α = 0.05

t-statistic: 0.083

p-value: 0.934

Decision: Fail to reject H₀
There is no statistically significant difference in mean returns.

5. Confidence Intervals

Fund 1: −1.30% to 3.20%

Fund 2: −0.86% to 2.64%

The overlapping intervals support the hypothesis test results.

6. Prediction

Linear regression was used to forecast October 2024 returns:

Fund 1: 2.06%

Fund 2: 3.58%

🏆 Key Findings

Fund 1 has higher average return but also higher risk.

Fund 2 is more stable.

No significant difference in average returns.

Funds are moderately correlated.
