# Summary of 41_RandomForest

[<< Go back](../README.md)


## Random Forest
- **n_jobs**: -1
- **criterion**: gini
- **max_features**: 1.0
- **min_samples_split**: 30
- **max_depth**: 3
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

14.7 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.545717 | nan         |
| auc       | 0.800422 | nan         |
| f1        | 0.745076 |   0.427245  |
| accuracy  | 0.735    |   0.500452  |
| precision | 1        |   0.898752  |
| recall    | 1        |   0.0759508 |
| mcc       | 0.470016 |   0.500452  |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.545717 |  nan        |
| auc       | 0.800422 |  nan        |
| f1        | 0.737948 |    0.500452 |
| accuracy  | 0.735    |    0.500452 |
| precision | 0.732515 |    0.500452 |
| recall    | 0.743462 |    0.500452 |
| mcc       | 0.470016 |    0.500452 |


## Confusion matrix (at threshold=0.500452)
|                 |   Predicted as -1.0 |   Predicted as 1.0 |
|:----------------|--------------------:|-------------------:|
| Labeled as -1.0 |                 579 |                218 |
| Labeled as 1.0  |                 206 |                597 |

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
