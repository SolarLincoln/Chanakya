# Chanakya ✍️

Chanakya will document my journey to understand, analyze, visualize, and train a model on the UCI 'Audit Data' dataset.

## Initial Goals:
- Identify **warning signs** and risk factors for fraud or suspicious activity.
- Gain an **understanding** of such warning signs.
- Train a model to **classify firms** as suspicious or not, based on their data.

## Completed Goals:

- **Data Preprocessing:**
   - Identified irrelevant or redundant features (e.g. 'Total' column) to **clean the dataset**.
   - Handled **missing values** appropriately.
   - Standardized numerical data to **improve model performance**.

- **Exploratory Data Analysis (EDA):**
   - Analyzed the distribution of **key features**.
   - Identified **correlations between features** and the target variable (Risk).

- **Model Development:**
   - Built a **Logistic Regression model** to classify firms as suspicious (Risk = 1) or not suspicious (Risk = 0).
   - Implemented **Principal Component Analysis (PCA)** to reduce the number of features and improve model interpretability.

- **Model Evaluation:**
   - Evaluated the model's performance using **Accuracy** and **F1 score**.
   - Benchmarked the model both **before and after applying PCA** to assess dimensionality reduction benefits.

- **Results:**
   - Achieved a balance between **model complexity** and **performance** by tuning hyperparameters and evaluating metrics like F1 score and accuracy.
   - Explored trade-offs between **model interpretability** (with fewer components in PCA) and **performance metrics**.

## Future Goals 🤔:
- Experiment with other classification algorithms (e.g., **Random Forest**, **XGBoost**) to compare performance.
- Tune model hyperparameters for **optimal performance**.
- Investigate other feature engineering techniques to enhance model predictions.
