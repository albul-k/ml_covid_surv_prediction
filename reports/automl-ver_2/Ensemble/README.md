# Summary of Ensemble

[<< Go back](../README.md)


## Ensemble structure
| Model                                     |   Weight |
|:------------------------------------------|---------:|
| 6_Xgboost_GoldenFeatures_SelectedFeatures |       15 |

## Metric details
|           |    score |    threshold |
|:----------|---------:|-------------:|
| logloss   | 0.274481 | nan          |
| auc       | 0.9571   | nan          |
| f1        | 0.892308 |   0.631021   |
| accuracy  | 0.895    |   0.631021   |
| precision | 1        |   0.942777   |
| recall    | 1        |   0.00713377 |
| mcc       | 0.790989 |   0.631021   |


## Confusion matrix (at threshold=0.631021)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |               92 |                8 |
| Labeled as 1 |               13 |               87 |

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
