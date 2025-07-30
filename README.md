Trader Behavior vs Market Sentiment Analysis
Overview
This project analyzes trader behavior in the crypto market relative to the Fear & Greed Index, exploring how market sentiment affects profitability, risk, and trading volume. Using detailed historical trade data merged with daily sentiment classification, the study identifies key patterns and tests the statistical significance of sentiment-driven performance differences. The goal is to uncover insights that can inform smarter, sentiment-aware trading strategies.

Project Structure
text
ds_<your_name>/
├── notebook_1.ipynb                # Main Colab notebook with data analysis and visualizations using Plotly
├── notebook_2.ipynb                # (Optional) Additional analyses
├── csv_files/                     # Processed datasets and summaries used for analysis
│   ├── merged_trades_with_sentiment.csv
│   ├── sentiment_summary.csv
│   └── ...
├── outputs/                      # Exported figures and plots in PNG/JPG formats
│   ├── profit_distribution_boxplot.png
│   ├── rolling_pnl_lineplot.png
│   └── ...
├── ds_report.pdf                 # Final project report summarizing methodology, findings, and recommendations
└── README.md                    # This file
Getting Started
Prerequisites
Google Colab or Jupyter Notebook environment

Python 3 with the following packages:

pandas

plotly

scipy

Installation
Install the required packages by running:

bash
pip install pandas plotly scipy
How to Run
Upload the datasets (Fear & Greed Index and Historical Trader Data) to your environment or place them in the working directory.

Open notebook_1.ipynb in Google Colab or Jupyter.

Run the notebook cells step-by-step to:

Load and clean the data

Merge trader data with daily market sentiment

Conduct exploratory data analysis (EDA)

Perform statistical testing (t-tests)

Visualize key metrics using Plotly

Export processed data and visualizations

Refer to ds_report.pdf for a detailed summary of findings and actionable insights.

Main Findings
Traders have statistically significantly higher average profitability during "Greed" market times compared to "Fear" (t = -2.51, p = 0.0122).

Large profits and losses occur across all sentiment states, highlighting that sentiment alone does not guarantee outcomes.

Trading strategies can benefit by considering sentiment regimes but must be combined with strong risk management.

Repository Contents
Notebooks with clean, commented code and markdown explanations

CSV files for reproducibility and further analysis

Plots exported as PNG/JPG for reporting

Final report summarizing methodology, results, and strategic recommendations
