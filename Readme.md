## Repository Structure

```mermaid
graph TB
  A[My_Project]
  A1[README.md]
  A2[LICENSE.md]
  B[SCRIPTS]
  B1[01_data_cleaning.py]
  B2[02_eda.py]
  B3[03_sentiment_analysis.py]
  B4[04_statistical_testing.py]
  C[DATA]
  C1[raw_data.csv]
  C2[cleaned_data.csv]
  C3[data_preprocessing.md]
  D[OUTPUT]
  D1[sentiment_trends.png]
  D2[t_test_results.txt]
  D3[sentiment_analysis_report.pdf]
  E[Data_Appendix.pdf]

  A --> A1
  A --> A2
  A --> B
  B --> B1
  B --> B2
  B --> B3
  B --> B4
  A --> C
  C --> C1
  C --> C2
  C --> C3
  A --> D
  D --> D1
  D --> D2
  D --> D3
  A --> E
