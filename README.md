# Credit Risk Scorecard - PD Model

Credit risk modeling project using HELOC data to build a probability of default model with logistic regression and optimal binning techniques. Generates risk scores in the 300-850 range.

## Dataset

HELOC (Home Equity Line of Credit) dataset with 11 features covering credit history, payment behavior, and credit utilization.

**Target**: RiskPerformance (Good/Bad)

**Key Features**: External risk estimate, credit age, delinquency history, revolving burden, and inquiry counts.

## Methodology

1. **Exploratory Data Analysis**: Data loading, visualization, and distribution analysis
2. **Model Selection**: Optimal binning with logistic regression
3. **Scorecard Building**: 300-850 point scale with min-max scaling
4. **Business Implications**: Feature importance analysis using Information Value (IV)

## Technologies

- Python, Pandas, NumPy
- Scikit-learn (Logistic Regression)
- OptBinning (Scorecard development)
- Matplotlib, Seaborn (Visualization)

## Key Insights

- External risk estimate (IV: 0.97) is the strongest predictor
- Credit utilization (IV: 0.55) and payment history (IV: 0.35) are critical factors
- Model provides interpretable, explainable credit decisions

## Usage

Open and run `PD_Model (Credit Score Card).ipynb` sequentially to reproduce the analysis.
