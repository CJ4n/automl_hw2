# Summary of 109_ExtraTrees

[<< Go back](../README.md)


## Extra Trees Classifier (Extra Trees)
- **n_jobs**: -1
- **criterion**: entropy
- **max_features**: 0.8
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

23.8 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.495209 | nan         |
| auc       | 0.884657 | nan         |
| f1        | 0.820225 |   0.498039  |
| accuracy  | 0.82     |   0.498039  |
| precision | 1        |   0.831717  |
| recall    | 1        |   0.0785397 |
| mcc       | 0.64001  |   0.498039  |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.495209 |  nan        |
| auc       | 0.884657 |  nan        |
| f1        | 0.820225 |    0.498039 |
| accuracy  | 0.82     |    0.498039 |
| precision | 0.822278 |    0.498039 |
| recall    | 0.818182 |    0.498039 |
| mcc       | 0.64001  |    0.498039 |


## Confusion matrix (at threshold=0.498039)
|                 |   Predicted as -1.0 |   Predicted as 1.0 |
|:----------------|--------------------:|-------------------:|
| Labeled as -1.0 |                 655 |                142 |
| Labeled as 1.0  |                 146 |                657 |

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
