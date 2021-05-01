# GSoC'21 Evaluation Task: CGM
Evaluation Tasks for **Google Summer of Code (GSOC) 2021**

***
## Results

| Task | Metric | Value  |
| :---:   | :-: | :-: |
| 3.1 | AUROC | 0.732 |
| 3.2 | AUROC | 0.653 |

## Strategy

**Task 3.1:** Trained LGBM Classifier and Neural Network to classify data with AUROC as evaluation metric. Ensured that model does not overfit by comparing Train and Test ROC Curves.

**Task 3.2:** Reduced dimensions of data using Principal Component Analysis (PCA) and Autoencoders. Reduced the dimensions from 28 to 20 ensuring that there isn't significant drop in the classification performance.
