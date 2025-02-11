## Repository Structure

```mermaid
graph TB
  A[covidproject]
  A1[README.md]
  A2[LICENSE.md]
  B[SCRIPTS]
  B1[EDA Pre Analysis.ipynb]
  B2[covid_EDA.ipynb]
  C[DATA]
  C1[Corona_NLP_test.csv]
  C2[Corona_NLP_train.csv]
  C3[Data Appendix]
  D[OUTPUT]
  D1[figures]

  A --> A1
  A --> A2
  A --> B
  B --> B1
  B --> B2
  A --> C
  C --> C1
  C --> C2
  C --> C3
  A --> D
  D --> D1

