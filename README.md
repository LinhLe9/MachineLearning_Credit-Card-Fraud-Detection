This project aims to evaluate and compare the efficacy of variety classifiers across two distinct data architectures:
  - Transactional Data: reserves original transactional patterns, requiring extensive ”Feature Engineering” pipeline to
    extract behavioral patterns such as transaction frequency, geographical distance, and spending ratios.
  - PCA-Transformed Data: numerical variables resulting from Principal Component Analysis (PCA), which representing a
    scenario where features are anonymized and numerically encoded
To address these challenges, I applied a structured pipeline that includes data exploration, feature processing,
model training and performance evaluation using appropriate metrics for imbalanced classification.
The primary objective is to optimize the F1-Score and PRAUC, ensuring the model achieves a robust balance in the trade-
off between maximizing fraud detection (Recall) and minimizing false alarms (Precision).
