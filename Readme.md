## Repository Structure
graph TD
  %% Root Project Node
  A[covidproject]
  A1[README.md]
  A2[LICENSE.md]
  
  %% Scripts Folder
  B[SCRIPTS]  
  B1[EDA Pre Analysis.ipynb]
  B2[covid_EDA.ipynb]
  
  %% Data Folder
  C[DATA]  
  C1[Corona_NLP_test.csv]
  C2[Corona_NLP_train.csv]
  C3[Data Appendix]

  %% Output Folder
  D[OUTPUT]  
  D1[figures]

  %% Connections
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

  %% Styling (Optional: Adding colors and rounded corners)
  style A fill:#8ecae6,stroke:#003d5b,stroke-width:2px
  style B fill:#ffb703,stroke:#003d5b,stroke-width:2px
  style C fill:#ffd166,stroke:#003d5b,stroke-width:2px
  style D fill:#6a4c93,stroke:#003d5b,stroke-width:2px
  style A1 fill:#f1faee,stroke:#003d5b,stroke-width:1px
  style A2 fill:#f1faee,stroke:#003d5b,stroke-width:1px
  style B1 fill:#f1faee,stroke:#003d5b,stroke-width:1px
  style B2 fill:#f1faee,stroke:#003d5b,stroke-width:1px
  style C1 fill:#f1faee,stroke:#003d5b,stroke-width:1px
  style C2 fill:#f1faee,stroke:#003d5b,stroke-width:1px
  style C3 fill:#f1faee,stroke:#003d5b,stroke-width:1px
  style D1 fill:#f1faee,stroke:#003d5b,stroke-width:1px
