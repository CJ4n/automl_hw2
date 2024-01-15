# Summary of 45_RandomForest

[<< Go back](../README.md)


## Random Forest
- **n_jobs**: -1
- **criterion**: entropy
- **max_features**: 0.8
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

17.5 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.432596 |  nan        |
| auc       | 0.897578 |  nan        |
| f1        | 0.830655 |    0.499735 |
| accuracy  | 0.83375  |    0.524455 |
| precision | 0.990291 |    0.979547 |
| recall    | 0.998755 |    0        |
| mcc       | 0.668228 |    0.524455 |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.432596 |  nan        |
| auc       | 0.897578 |  nan        |
| f1        | 0.830573 |    0.524455 |
| accuracy  | 0.83375  |    0.524455 |
| precision | 0.850065 |    0.524455 |
| recall    | 0.811955 |    0.524455 |
| mcc       | 0.668228 |    0.524455 |


## Confusion matrix (at threshold=0.524455)
|                 |   Predicted as -1.0 |   Predicted as 1.0 |
|:----------------|--------------------:|-------------------:|
| Labeled as -1.0 |                 682 |                115 |
| Labeled as 1.0  |                 151 |                652 |

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
