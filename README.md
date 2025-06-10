## **Anomaly Detection in Clinical Data Using PCA and Mahalanobis Distance**

- Handled Missing Data by removing columns with excessive nulls and imputing remaining values using MICE with Bayesian Ridge and Logistic Regression.

- Cleaned Dataset by dropping irrelevant columns and consolidating ICU-related features into a single simplified indicator.

- Standardized Numerical Features to ensure consistent scale for effective PCA and distance-based anomaly detection.

- Visualized Data Distributions using histograms, Q-Q plots, and scatter plots to understand feature behavior and spot outliers.

- Detected Anomalies using Mahalanobis Distance and PCA, followed by Z-score ranking for identifying the most extreme data points.
