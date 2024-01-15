# Summary of 36_CatBoost

[<< Go back](../README.md)


## CatBoost
- **n_jobs**: -1
- **learning_rate**: 0.2
- **depth**: 7
- **rsm**: 1.0
- **loss_function**: Logloss
- **eval_metric**: F1
- **explain_level**: 0

## Validation
 - **validation_type**: kfold
 - **shuffle**: True
 - **stratify**: True
 - **k_folds**: 5

## Optimized metric
f1

## Training time

16.4 seconds

## Metric details
|           |    score |    threshold |
|:----------|---------:|-------------:|
| logloss   | 0.32461  | nan          |
| auc       | 0.936252 | nan          |
| f1        | 0.881398 |   0.495597   |
| accuracy  | 0.88125  |   0.495597   |
| precision | 1        |   0.99698    |
| recall    | 1        |   0.00168422 |
| mcc       | 0.762511 |   0.495597   |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.32461  |  nan        |
| auc       | 0.936252 |  nan        |
| f1        | 0.881398 |    0.495597 |
| accuracy  | 0.88125  |    0.495597 |
| precision | 0.883605 |    0.495597 |
| recall    | 0.879203 |    0.495597 |
| mcc       | 0.762511 |    0.495597 |


## Confusion matrix (at threshold=0.495597)
|                 |   Predicted as -1.0 |   Predicted as 1.0 |
|:----------------|--------------------:|-------------------:|
| Labeled as -1.0 |                 704 |                 93 |
| Labeled as 1.0  |                  97 |                706 |

## Learning curves
![Learning curves](learning_curves.png)
## Confusion Matrix

![Confusion Matrix](confusion_matrix.png)


## Normalized Confusion Matrix

![Normalized Confusion Matrix](confusion_matrix_normalized.png)


## ROC Curve

![ROC Curve](roc_curve.png)


## Kolmogorov-Smirnov Statistic

![Kolmogorov-Smirnov Statistic](ks_statistic.png)


## Precision-Recall Curve

![Precision-Recall Curve](precision_recall_curve.png)


## Calibration Curve

![Calibration Curve](calibration_curve_curve.png)


## Cumulative Gains Curve

![Cumulative Gains Curve](cumulative_gains_curve.png)


## Lift Curve

![Lift Curve](lift_curve.png)



[<< Go back](../README.md)
