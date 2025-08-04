Developed a complete Value at Risk (VaR) framework in Python to quantify and visualize potential losses in a financial portfolio under normal and extreme market conditions. The model evaluates risk using three major approaches:

# 1. Historical Simulation (Non-parametric VaR)
- Used actual historical returns data without making distributional assumptions.
- Computed VaR by sorting past returns and selecting the appropriate quantile (e.g., 5% for 95% confidence level).
- Ideal for portfolios with non-normal return distributions and fat tails.

# 2. Parametric Method (Variance-Covariance Approach)
- Assumed returns follow a normal distribution.
- Calculated VaR using portfolio mean and standard deviation, adjusting for different confidence levels (95%, 99%).
- Visualized how changing the confidence level impacts estimated risk.

 # 3. Monte Carlo Simulation
- Generated thousands of possible future return scenarios using random number generation and assumed volatility.
- Estimated the distribution of potential portfolio values and derived VaR from the resulting simulations.
- Useful for modeling non-linear instruments and complex risk factors.

# Visualizations & Insights
- Plotted the loss distribution curves for each method.
- Highlighted tail-risk exposure and the impact of distribution assumptions on risk estimation.
- Understood how model choice affects VaR estimates.
- Gained insights into portfolio risk sensitivity across varying market conditions.
