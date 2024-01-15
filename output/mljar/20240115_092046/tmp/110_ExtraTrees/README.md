# Summary of 110_ExtraTrees

[<< Go back](../README.md)


## Extra Trees Classifier (Extra Trees)
- **n_jobs**: -1
- **criterion**: entropy
- **max_features**: 1.0
- **min_samples_split**: 20
- **max_depth**: 5
- **eval_metric_name**: f1
- **explain_level**: 0

## Validation
 - **validation_type**: kfold
 - **shuffle**: True
 - **stratify**: True
 - **k_folds**: 5

## Optimized metric
f1

## Training time

22.6 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.485696 | nan         |
| auc       | 0.888762 | nan         |
| f1        | 0.823745 |   0.49598   |
| accuracy  | 0.82125  |   0.501329  |
| precision | 1        |   0.780371  |
| recall    | 1        |   0.0586639 |
| mcc       | 0.642547 |   0.501329  |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.485696 |  nan        |
| auc       | 0.888762 |  nan        |
| f1        | 0.823239 |    0.501329 |
| accuracy  | 0.82125  |    0.501329 |
| precision | 0.817178 |    0.501329 |
| recall    | 0.82939  |    0.501329 |
| mcc       | 0.642547 |    0.501329 |


## Confusion matrix (at threshold=0.501329)
|                 |   Predicted as -1.0 |   Predicted as 1.0 |
|:----------------|--------------------:|-------------------:|
| Labeled as -1.0 |                 648 |                149 |
| Labeled as 1.0  |                 137 |                666 |

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
