# Predicting Youth Drug Use with Machine Learning

This project uses survey data from the **NSDUH 2020 Youth Dataset** to build machine learning models that predict marijuana use behavior among youth in the U.S. It explores three types of prediction tasks:

- **Binary Classification:** Whether a youth has ever used marijuana (MRJFLAG)
- **Multiclass Classification:** Frequency of marijuana use in the past year (MRJYDAYS)
- **Regression:** Age of first marijuana use (IRMJAGE)

## Project Goals

- Understand behavioral and demographic predictors of marijuana use
- Address class imbalance through techniques like SMOTE
- Compare model performance across Decision Trees, Random Forests, and Gradient Boosting
- Emphasize ethical modeling and the potential for real-world early intervention


## Key Insights

- **School Grade**, **Missed School Days**, and **Health Rating** were among the strongest predictors.
- Random Forest and Gradient Boosting performed best across tasks.
- SMOTE improved minority class recall in multiclass classification.
- Ethical considerations were prioritized throughout modeling and interpretation.

## Final Model Highlights

| Task               | Best Model              | RMSE / Accuracy |
|--------------------|--------------------------|------------------|
| Binary Classification | Pruned Tree / Random Forest | ~84–85% Accuracy |
| Multiclass Classification | Random Forest (with SMOTE) | ~86–87% Accuracy |
| Regression            | Gradient Boosting Regressor | RMSE ~1.47 years |

## Ethical Considerations

This project focuses on youth behavior, and predictions should never be used for punitive purposes. The goal is to support **early intervention**, not to judge. All data has been anonymized and processed with privacy in mind.


