# Summary of 100_ExtraTrees

[<< Go back](../README.md)


## Extra Trees Classifier (Extra Trees)
- **n_jobs**: -1
- **criterion**: entropy
- **max_features**: 0.9
- **min_samples_split**: 50
- **max_depth**: 7
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

20.9 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.448656 | nan         |
| auc       | 0.90825  | nan         |
| f1        | 0.844252 |   0.499864  |
| accuracy  | 0.8425   |   0.499864  |
| precision | 1        |   0.850014  |
| recall    | 1        |   0.0302118 |
| mcc       | 0.685055 |   0.499864  |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.448656 |  nan        |
| auc       | 0.90825  |  nan        |
| f1        | 0.844252 |    0.499864 |
| accuracy  | 0.8425   |    0.499864 |
| precision | 0.838037 |    0.499864 |
| recall    | 0.85056  |    0.499864 |
| mcc       | 0.685055 |    0.499864 |


## Confusion matrix (at threshold=0.499864)
|                 |   Predicted as -1.0 |   Predicted as 1.0 |
|:----------------|--------------------:|-------------------:|
| Labeled as -1.0 |                 665 |                132 |
| Labeled as 1.0  |                 120 |                683 |

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
