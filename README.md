# 🧬 Exploratory Data Analysis on Cancer Data
![image](https://github.com/user-attachments/assets/246c765c-a80b-468d-9fa0-312864252bef)

This project performs exploratory data analysis (EDA) and predictive modeling on cancer-related datasets. The goal is to understand cancer incidence patterns globally and use regression to estimate cancer rates based on incidence data.

## 📌 Project Summary
- Combined multiple datasets related to cancer incidence and frequency
- Cleaned and preprocessed data for analysis
- Visualized key trends and relationships
- Built a simple linear regression model to predict overall cancer rate
- Evaluated model performance using R² score

## 🛠️ Tools & Libraries Used
- **Python (VS Code)**
- `pandas`, `numpy` – data manipulation
- `seaborn`, `matplotlib` – data visualization
- `scikit-learn` – modeling & evaluation

## 📊 EDA Highlights
- **Histogram** of cancer rates
- **Boxplot** of incidence rates
- **Pairplot** of selected numeric features
- **Heatmap** to visualize correlation among numeric variables
- **Countplot** for country distribution in the dataset

## 🧹 Data Processing
- Merged multiple datasets with common keys
- Handled missing values and inconsistent entries
- Selected relevant features for analysis
- Renamed columns and normalized values as needed

## 🔍 Predictive Modeling
Used **Simple Linear Regression** from `scikit-learn` to predict the `'Cancer rate'` using:

- `'Including NMSC Rate'`
- `'Excluding NMSC Rate'`

## 📷 Sample Visualizations
![image](https://github.com/user-attachments/assets/bdfbdf40-c561-4ca6-a7d1-89bad043ed3c)

![image](https://github.com/user-attachments/assets/55079a9b-578c-4f21-9439-25f48e3a2393)

![image](https://github.com/user-attachments/assets/d356a5c6-09b6-41ed-9ef8-c612b87dd569)

![image](https://github.com/user-attachments/assets/1528c03b-110a-4f8f-9fa7-2e9e49d94c32)

### Modeling Workflow:

1. Initialize and train the model on training data
2. Predict cancer rates on the test set
3. Evaluate using **R² score**
4. Visualize **Predicted vs. Actual** cancer rates

## 📈 Key Insight
The regression model shows that cancer incidence rates (`Including/Excluding NMSC`) are **moderately predictive** of overall cancer frequency — suggesting room for deeper multivariate modeling in the future.
