# CRM & CM with Business Intelligence — Coursework 1

Stock Segmentation Using Risk–Return and RFM Analysis

## Project Overview
This project analyses historical stock-market data to identify groups of shares with similar financial and trading characteristics.
The analysis covers 498 shares using historical price data from January 2021 to December 2024, with the S&P 500 index as the market benchmark.

### Project Objectives
- Prepare and validate historical stock-market data.
- Calculate weekly returns and market beta.
- Develop stock-level Recency, Frequency and Monetary (RFM) indicators based on trading activity.
- Apply Ward hierarchical clustering and K-means clustering.
- Compare Risk–Return and RFM segmentation.
- Evaluate cluster quality, sensitivity and sector composition.
- Discuss business intelligence applications and limitations.

### Methodology
Task 1 — Data Preparation and Feature Engineering
    Historical stock data was collected using Yahoo Finance through the Python `yfinance` library. The S&P 500 constituent list was obtained from Wikipedia.
    Data validation, exclusions, weekly return calculations, beta estimation and RFM feature engineering were performed.

Task 2 — Stock Segmentation
    Ward hierarchical clustering and K-means clustering were applied to Risk–Return and RFM feature sets.
    Cluster quality was evaluated using silhouette scores, and the results were examined using cluster profiles, visualisations and sensitivity analysis.

Task 3 — Business Intelligence and Critical Review
    The analysis compared cluster profiles, GICS sector composition and relationships between Risk–Return and RFM segmentation.
    The findings support a critical discussion of segmentation methods, analytical limitations and potential business intelligence applications.

### Repository Structure
- 'CR_&_CM_with_BI_CWK1_2026.ipynb' — Complete Python notebook.
- 'requirements.txt' — Python package dependencies.
- 'data/' — Historical stock prices, constituent list and acquisition metadata.
- 'results/' — Calculated features, clustering outputs and evaluation results.
- 'figures/figures/' — Saved visualisations.

### Reproducing the Analysis
1. Download the repository as a ZIP file.
2. Open the notebook in Google Colab.
3. Upload the repository's 'data' folder to Google Drive under 'MyDrive/CRM_CWK1_2026/'.
4. Run the notebook in order, starting with the environment setup and Google Drive connection.
5. Keep 'USE_SAVED_SNAPSHOT = True' to use the fixed historical dataset rather than download updated prices.
6. The notebook produces analysis outputs in the project's 'results' and 'figures' folders.

The original historical snapshot is dated 11 November 2026. The 26 individual download batches are not included in the repository because a combined historical dataset is provided.

### Reproducibility and Limitations
The analysis uses a fixed historical dataset to support consistent results. The stock universe is based on a constituent list retrieved in November 2026, while prices cover 2021–2024. Consequently, retrospective constituent selection and survivorship bias are important limitations.

RFM indicators in this project represent stock trading activity rather than conventional customer purchase behaviour. The resulting clusters should be interpreted as exploratory analytical groups, not investment recommendations.

  ### Technologies
Python, Google Colab, Pandas, NumPy, yfinance, SciPy, scikit-learn, Matplotlib and Seaborn.

  ### Coursework
Customer Relationship and Change Management with Business Intelligence — Coursework 1.
