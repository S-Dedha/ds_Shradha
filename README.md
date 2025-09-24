Trading Behavior vs Market Sentiment Analysis

This project explores how trading behavior (profitability, risk, volume, leverage) aligns or diverges from the overall market sentiment (Fear vs. Greed). The goal is to uncover hidden trends and signals that could inform smarter and more adaptive trading strategies.

📌 Project Overview

Datasets Used

Bitcoin Market Sentiment Dataset: Provides daily sentiment classification (Fear/Greed).

Historical Trader Data (Hyperliquid): Contains account-level trading activity including execution price, side, leverage, closedPnL, etc.

Objectives

Analyze trader profitability and risk across different sentiment phases.

Measure how trading volume and leverage fluctuate between Fear and Greed markets.

Detect misalignments where trader behavior contradicts market mood.

Identify hidden signals and behavioral biases that impact performance.

🛠️ Methodology

Data Preprocessing: Cleaning, formatting timestamps, and merging datasets.

Feature Engineering: Creating metrics such as daily PnL, average leverage, risk exposure, etc.

Exploratory Data Analysis (EDA): Visualizing sentiment cycles against trader performance.

Statistical & Correlation Analysis: Quantifying relationships between sentiment and behavior.

Pattern & Signal Detection: Identifying divergences (e.g., profitable trading during Fear).

Reporting: Generating visual and written insights for trading strategy improvement.

📊 Key Insights (to be expanded after analysis)

Do traders take higher leverage during Greed phases?

Is profitability better when traders go against market sentiment?

Which sentiment regime (Fear/Greed) has higher risk-adjusted returns?

Can trader behavior itself be a predictor of upcoming sentiment shifts?

🚀 Tech Stack

Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)

Jupyter Notebook for interactive analysis

Data Visualization: Time-series charts, correlation heatmaps, sentiment overlays

Report Generation: Automated summary & insights export

📂 Project Structure
├── data/                # Raw and processed datasets  
├── notebooks/           # Jupyter notebooks for analysis  
├── reports/             # Generated insights, charts, and final report  
├── src/                 # Python scripts (data preprocessing, analysis)  
├── README.md            # Project description  

✅ Outcomes

Better understanding of how sentiment drives (or misguides) trader behavior.

Actionable signals for strategy development and risk management.

A reproducible framework for combining sentiment and trading data in research.
