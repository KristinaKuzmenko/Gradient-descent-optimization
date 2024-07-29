In this project, I utilized the "Breast Cancer Wisconsin (Diagnostic)" dataset to develop and evaluate classification models aimed at distinguishing between benign and malignant cell samples. The dataset contains 569 samples, with 212 labeled as malignant and 357 as benign, presenting a moderate class imbalance.

Key steps and highlights:

- Data Preprocessing: Managed numerical data without missing values; applied standardization and dimensionality reduction using PCA.
- Feature Analysis: Conducted correlation analysis to identify multicollinear features and assessed their impact on classification accuracy.
- Model Building and Optimization: Implemented logistic regression models and applied various gradient descent optimization methods including Adam, Nadam, and Adamax. These optimized models were compared against sklearn's built-in logistic regression, demonstrating high precision and F1 scores, essential for minimizing false negatives in cancer diagnosis.
- Clustering: Evaluated clustering methods, finding that Gaussian Mixture Models outperformed spectral clustering, especially given the dataset's characteristics.
- Visualization: Created visualizations including pairwise scatter plots and correlation maps to illustrate feature distributions and model effectiveness.
