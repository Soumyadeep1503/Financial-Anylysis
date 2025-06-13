# Financial-Analysis:
Sectoral Analysis and Portfolio Evaluation using Sensex and Sector Indices

Objective:
The objective of this project is to perform a comprehensive quantitative analysis on the Sensex and four key sectoral indices—Healthcare, FMCG, Bankex, and Auto. The analysis focuses on return characteristics, volatility patterns, risk-adjusted performance, portfolio construction, and stress testing, aiming to evaluate investment opportunities and relative performance across sectors.

Indices Used: BSE Sensex, BSE Healthcare, BSE FMCG, BSE Bankex, and BSE Auto.
Data Frequency: Daily closing prices

Methodology and Analysis:

1. Return Analysis:
Computed daily and monthly logarithmic returns for each index.
Compared cumulative returns to assess long-term performance trends.
I've used return histograms to visualize distribution characteristics.

2. Volatility Analysis:
Rolling Standard Deviation (Rolling SD): Applied a rolling window (e.g., 30 days) to observe time-varying volatility across indices.
Constant Standard Deviation: Calculated overall standard deviation for the full period to benchmark long-term volatility.

3. Portfolio Construction:
Constructed both equally-weighted and variance-optimized portfolios using the sectoral indices.
Evaluated portfolio diversification benefits and tracked portfolio performance over time.
Calculated portfolio-level risk and return characteristics.

4. Alphas and Betas:
Performed regression analysis using Sensex as the market benchmark.
Calculated beta coefficients to measure each sector’s systematic risk.
Derived Jensen’s alpha to estimate excess returns after adjusting for market risk.

5. Risk-Free Analysis:
Incorporated a constant risk-free rate (e.g., 6.5%) based on prevailing short-term government bond yields.
Used the risk-free rate in the calculation of Sharpe and Treynor ratios for evaluating risk-adjusted returns.

6. Moving Averages:
Implemented both short-term (e.g., 20-day) and long-term (e.g., 100-day) moving averages.
Analyzed crossover signals to identify momentum and trend-reversal opportunities.
Compared sector indices based on technical signals.

7. Performance Ratios:
Sharpe Ratio: Measured excess return per unit of total risk (standard deviation).
Treynor Ratio: Measured excess return per unit of systematic risk (beta).
Compared performance across indices and portfolio compositions.

8. Stress and Exuberance Indices:
Stress Index: Constructed using volatility spikes, drawdowns, and correlation breakdowns during market turmoil (e.g., COVID-19 period).
Exuberance Index: Measured deviation from historical return-volatility relationships, indicating overvaluation or overheating in specific sectors.
