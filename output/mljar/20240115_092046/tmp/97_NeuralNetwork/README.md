# Summary of 97_NeuralNetwork

[<< Go back](../README.md)


## Neural Network
- **n_jobs**: -1
- **dense_1_size**: 16
- **dense_2_size**: 8
- **learning_rate**: 0.08
- **explain_level**: 0

## Validation
 - **validation_type**: kfold
 - **shuffle**: True
 - **stratify**: True
 - **k_folds**: 5

## Optimized metric
f1

## Training time

17.8 seconds

## Metric details
|           |    score |     threshold |
|:----------|---------:|--------------:|
| logloss   | 0.435138 | nan           |
| auc       | 0.91749  | nan           |
| f1        | 0.847539 |   0.330095    |
| accuracy  | 0.84125  |   0.330095    |
| precision | 1        |   0.999956    |
| recall    | 1        |   1.63273e-15 |
| mcc       | 0.684335 |   0.330095    |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.435138 |  nan        |
| auc       | 0.91749  |  nan        |
| f1        | 0.847539 |    0.330095 |
| accuracy  | 0.84125  |    0.330095 |
| precision | 0.818076 |    0.330095 |
| recall    | 0.879203 |    0.330095 |
| mcc       | 0.684335 |    0.330095 |


## Confusion matrix (at threshold=0.330095)
|                 |   Predicted as -1.0 |   Predicted as 1.0 |
|:----------------|--------------------:|-------------------:|
| Labeled as -1.0 |                 640 |                157 |
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
