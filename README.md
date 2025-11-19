# Understanding Code Smell Detection Through Hyperparameter Optimization and Metric Correlation Analysis

The code implements and evaluates three hyperparameter optimization strategies—Grid Search, Random Search, and a two-stage Hybrid (Random → Grid) Search for Support Vector Machine (SVM)–based detection of four object-oriented code smells:
- God Class (BLOB)
- Spaghetti Code (SC)
- Functional Decomposition (FD)
- Swiss Army Knife (SAK)
The empirical evaluation is conducted on three representative open-source Java systems:
- ArgoUML v0.19.8
- Azureus v2.3.0.6
- Xerces v2.7.0

Each system is represented through static code metrics at class level, and all models are evaluated under a reproducible 10-fold cross-validation protocol.

## Objetives:
1. Reproduce the comparative study of hyperparameter optimization strategies for SVM-based code smell detection (Grid, Random, Hybrid). 
2. Quantify the impact of hyperparameter tuning on standard performance measures (Accuracy, Precision, Recall, F1-score) across systems and smell categories. 
3. Analyze the relationship between software metrics and code smells via point-biserial correlation, highlighting the top positively and negatively associated metrics for each smell and project. 

## Citation
If you use this repository in academic work, please cite the associated article:

M. Mosquera, R. Bojorque, and P. Flores, “Understanding Code Smell Detection Through Hyperparameter Optimization and Metric Correlation Analysis,” IEEE Access, vol. XX, XXXX doi XX.
