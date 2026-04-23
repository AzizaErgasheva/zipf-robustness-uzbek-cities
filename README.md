# Zipf's Law Robustness for Uzbek Cities

This project analyzes the robustness of Zipf's Law for Uzbek city populations using various regression methods (OLS, WLS, MLE, L1) and advanced models like Double Pareto-Lognormal (dPLN).

## Overview
- **Data**: Population data for 32 Uzbek cities.
- **Methods**: Ordinary Least Squares (OLS), Weighted Least Squares (WLS), Maximum Likelihood Estimation (MLE), Quantile Regression (L1), Cook's Distance for outlier analysis, and dPLN fitting.
- **Findings**: Robust methods provide more stable α estimates (~1.05), supporting Zipf's Law.

## How to Run
1. Clone the repo: `git clone https://github.com/yourusername/zipf-robustness-uzbek-cities.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Open and run the notebook: `zipf_robustness_article_(1) (5).ipynb`

## Dependencies
- Python 3.8+
- See `requirements.txt`

## License
MIT License.