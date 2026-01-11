# Dublin House Price Prediction (Linear Regression)

## 📌 Project Overview
This project applies **Linear Regression** to predict whether a house price in Dublin is **above or below the median price**.  
Since Linear Regression outputs continuous values, thresholding is applied to perform **binary classification**.

---

## 📂 Dataset
- **Source:** Kaggle
- **File:** `dublin_house_prices_cleaned.xlsx`
- **Target Variable:** `above_median_price`
  - `1` → Price above median
  - `0` → Price below or equal to median

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Google Colab

---

## ⚙️ Methodology
1. Load and preprocess data
2. Convert house price into a binary target
3. Train Linear Regression model
4. Apply thresholding (0.5) for classification
5. Evaluate using:
   - Mean Squared Error (MSE)
   - R² Score
   - Confusion Matrix
   - Accuracy, Precision, Recall, F1-score
   - ROC Curve & AUC
6. Visualize all evaluation metrics

---

## 📊 Results
The model performance is evaluated using both regression and classification metrics and visualized through:
- Confusion Matrix heatmap
- Performance metrics bar chart
- ROC Curve

---

## 🚀 How to Run
1. Clone the repository
2. Open the notebook in Google Colab or Jupyter
3. Upload `dublin_house_prices_cleaned.xlsx`
4. Run all cells

---

## 📌 Note
This project demonstrates how Linear Regression can be adapted for binary classification using thresholding.

---

## 👤 Author
**Muhammad Faizan Shafiq**
