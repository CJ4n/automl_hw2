# Summary of 39_RandomForest_Stacked

[<< Go back](../README.md)


## Random Forest
- **n_jobs**: -1
- **criterion**: entropy
- **max_features**: 0.8
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

41.6 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.303403 |  nan        |
| auc       | 0.951691 |  nan        |
| f1        | 0.906367 |    0.511738 |
| accuracy  | 0.90625  |    0.511738 |
| precision | 0.981982 |    0.99774  |
| recall    | 0.996264 |    0        |
| mcc       | 0.812511 |    0.511738 |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.303403 |  nan        |
| auc       | 0.951691 |  nan        |
| f1        | 0.906367 |    0.511738 |
| accuracy  | 0.90625  |    0.511738 |
| precision | 0.908636 |    0.511738 |
| recall    | 0.90411  |    0.511738 |
| mcc       | 0.812511 |    0.511738 |


## Confusion matrix (at threshold=0.511738)
|                 |   Predicted as -1.0 |   Predicted as 1.0 |
|:----------------|--------------------:|-------------------:|
| Labeled as -1.0 |                 724 |                 73 |
| Labeled as 1.0  |                  77 |                726 |

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
