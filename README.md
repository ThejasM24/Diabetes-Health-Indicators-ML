# Diabetes Health Indicators — Machine Learning

A Machine Learning Lab project using the **Diabetes Health Indicators (BRFSS 2015)** dataset. The notebook explores regression, classification, dimensionality reduction, ensemble learning, and clustering.

## Project overview

- **Dataset:** Diabetes Health Indicators / BRFSS 2015
- **Source:** [Kaggle — Diabetes Health Indicators Dataset](https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset)
- **Dataset size:** 253,680 records and 22 columns (21 predictors and the target)
- **Target:** `Diabetes_binary` (0 = no diabetes; 1 = prediabetes or diabetes)

## Algorithms and methods

- Linear Regression (simple and multiple; BMI prediction)
- Logistic Regression
- K-Nearest Neighbours (KNN)
- Decision Tree, Random Forest, and Support Vector Machine
- Bagging, AdaBoost, Gradient Boosting, and Stacking
- Principal Component Analysis (PCA)
- K-Means, Hierarchical/Agglomerative Clustering, and DBSCAN
- Five-fold cross-validation and hyperparameter search

## Repository contents

- `Diabetes_Health_Indicators_Project.ipynb` — Google Colab/Jupyter notebook with data analysis and model experiments
- `requirements.txt` — Python dependencies

## Run the notebook

1. Download the dataset from the Kaggle link above.
2. Place `diabetes_binary_health_indicators_BRFSS2015.csv` in the notebook's working directory, or upload it when prompted in Google Colab.
3. Install dependencies with `pip install -r requirements.txt`.
4. Open the notebook in Jupyter or Google Colab and run cells in order.

## Notes and limitations

- The target combines prediabetes and diabetes into one positive class, as defined by the dataset.
- The dataset contains self-reported survey information and is not a clinical diagnostic tool.
- The notebook imports SMOTE but does not apply it to the training data.
- Feature selection is explored using mutual information; interpret each experiment according to the inputs used in that notebook section.
- The dataset CSV is not included. Download it from Kaggle and follow its terms of use.

## Disclaimer

Educational and academic use only. Predictions are not medical advice and must not be used for diagnosis or treatment.
