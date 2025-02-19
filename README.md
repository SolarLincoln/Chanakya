# Chanakya ✍️

Chanakya documents my journey to understand, analyze, visualize, and train a model on the UCI 'Audit Data' dataset.

## Initial Goals:
- Identify **warning signs** and risk factors for fraud or suspicious activity.
- Gain an **understanding** of such warning signs.
- Train a model to **classify firms** as suspicious or not, based on their data.

## Completed Goals:

- **Data Preprocessing:**
   - Loaded in data using Python, Pandas, and Jupyter Notebooks
   - Investigated the structure and nature of audit_risk.csv (dataframe 'ad') and trail.csv (dataframe 'td') using Python, Pandas, and MatplotLib

- **Model Development:**
   - Built **Logistic Regression models** to classify firms as suspicious (Risk = 1) or not suspicious (Risk = 0).
   - Standardized numerical data to **improve model performance**
   - Implemented **Principal Component Analysis (PCA)** to reduce the number of features and improve model interpretability.

- **Model Evaluation:**
   - Evaluated the model's performance, achieving up to a **Classification Accuracy** of 98.96% and **F1 score** of 98.65%.
   - Benchmarked the model both **before and after applying PCA** to assess dimensionality reduction benefits.

## Future Goals 🤔:
- Experiment with other classification algorithms (e.g., **Random Forest**, **Bagging**) to compare performance.
- Tune model hyperparameters for **optimal performance**.
- Investigate other feature engineering techniques to enhance model predictions. I tried creating additional custom features using existing columns, but the effect on accuracy was little-to-none so the idea and code was scrapped.
- Use PCA loading scores to further analyze the effects of the features on the components, to shed more light on the ranking of features by importance, hopefully leading to a more intuitive understanding of this nebulous dataset.
