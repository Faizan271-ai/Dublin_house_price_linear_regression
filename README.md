# Binary Classification Using Linear Regression on Dublin House Prices

## Student Information
- **Email:** Faizan33377@gmail.com

---

## Project Overview
This project applies **Linear Regression** to a real-world housing dataset to classify houses based on whether their price is **above or below the median price**.  
Although Linear Regression is primarily a regression algorithm, it is adapted here for **binary classification** by applying a decision threshold.

The project demonstrates data preprocessing, model training, evaluation using both regression and classification metrics, and result visualization.

---

## Dataset Information
- **Dataset Name:** Dublin House Prices (Cleaned)
- **Source:** Kaggle
- **File Format:** Excel (`.xlsx`)
- **Description:**  
  The dataset contains information related to housing properties in Dublin, including price and other numerical attributes.

---

## Target Variable
- **Original Target:** `Price`
- **Binary Target Created:** `above_median_price`
  - `1` → House price above the median  
  - `0` → House price below or equal to the median  

---

## Features Used
- All **numeric features** available in the dataset except `Price`
- Datetime columns were converted into numerical format
- Non-numeric columns were excluded automatically

---

## Data Preprocessing
The following preprocessing steps were performed:
- Loaded the dataset using Pandas
- Created a binary target variable using the median house price
- Converted datetime columns into numeric values
- Selected only numeric columns for modeling
- Handled missing values using mean imputation
- Split the dataset into training and testing sets (80% / 20%)

---

## Model Description
- **Model Used:** Linear Regression
- Linear Regression was trained to predict a continuous output
- A threshold of **0.5** was applied to convert predictions into binary class labels
- This approach allows Linear Regression to be evaluated as a binary classifier

---

## Model Training
- The dataset was divided into training and testing sets using `train_test_split`
- The model was trained on the training data
- Predictions were generated for the test data

---

## Evaluation Metrics

### Regression Metrics
- **Mean Squared Error (MSE)**
- **R² Score**

### Classification Metrics
- **Confusion Matrix**
- **Accuracy**
- **Precision**
- **Recall**
- **F1 Score**
- **ROC Curve**
- **Area Under the Curve (AUC)**

---

## Visualizations
The following visual outputs are included in the notebook:
- Confusion Matrix (heatmap)
- Bar chart comparing Accuracy, Precision, Recall, and F1 Score
- ROC Curve showing classifier performance

---

## Results
The model successfully classified houses as above or below the median price.  
The evaluation metrics and visualizations provide insight into the model’s predictive performance and its limitations when used as a classifier.

---

## Instructions to Run
1. Open the Jupyter Notebook (`.ipynb`) file.
2. Ensure the dataset file `dublin_house_prices_cleaned.xlsx` is in the same folder.
3. Run all cells sequentially.
4. Review the outputs:
   - Regression metrics  
   - Classification metrics  
   - Confusion matrix  
   - Performance graphs  
   - ROC curve  

---

## Conclusion
This project demonstrates how Linear Regression can be adapted for binary classification problems using thresholding. While not originally designed for classification, Linear Regression can still provide meaningful results when evaluated using appropriate metrics.

---

## Tools & Libraries Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
