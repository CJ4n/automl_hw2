# Summary of 104_ExtraTrees

[<< Go back](../README.md)


## Extra Trees Classifier (Extra Trees)
- **n_jobs**: -1
- **criterion**: entropy
- **max_features**: 0.9
- **min_samples_split**: 40
- **max_depth**: 6
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

23.8 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.464948 | nan         |
| auc       | 0.902964 | nan         |
| f1        | 0.842697 |   0.49973   |
| accuracy  | 0.8425   |   0.49973   |
| precision | 1        |   0.832855  |
| recall    | 1        |   0.0296387 |
| mcc       | 0.68501  |   0.49973   |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.464948 |   nan       |
| auc       | 0.902964 |   nan       |
| f1        | 0.842697 |     0.49973 |
| accuracy  | 0.8425   |     0.49973 |
| precision | 0.844806 |     0.49973 |
| recall    | 0.840598 |     0.49973 |
| mcc       | 0.68501  |     0.49973 |


## Confusion matrix (at threshold=0.49973)
|                 |   Predicted as -1.0 |   Predicted as 1.0 |
|:----------------|--------------------:|-------------------:|
| Labeled as -1.0 |                 673 |                124 |
| Labeled as 1.0  |                 128 |                675 |

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
