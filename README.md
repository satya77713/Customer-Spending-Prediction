# Customer Spending Category Prediction Using Machine Learning

## 📌 Project Overview

This project focuses on predicting customer spending categories using Machine Learning techniques.

The objective is to classify customers into three spending categories:

- Low Spending
- Medium Spending
- High Spending

The project uses customer demographic and income-related information to build classification models and understand customer spending behavior.

This project was completed as **Task 31** of the Veda Technology AI & ML Internship.

## 🎯 Project Objectives

- Understand customer data through Exploratory Data Analysis (EDA).
- Clean and preprocess the dataset.
- Handle missing values and duplicate records.
- Perform feature engineering.
- Create meaningful data visualizations.
- Build machine learning classification models.
- Compare model performance using evaluation metrics.
- Predict customer spending categories.
- Identify important features influencing predictions.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- Google Colab

## 📂 Dataset Information

**Dataset Name:** Mall_Customers.csv

The dataset contains customer-related information such as:

| Feature | Description |
|---|---|
| CustomerID | Unique customer identifier |
| Gender | Customer gender |
| Age | Customer age |
| Annual Income (k$) | Annual customer income |
| Spending Score (1-100) | Customer spending score |

## ⚙️ Project Workflow

### 1. Data Loading

- Imported the dataset using Pandas.
- Examined dataset dimensions and structure.
- Displayed the first few records.

### 2. Data Cleaning

- Checked missing values.
- Identified duplicate records.
- Removed duplicate records.
- Handled missing values using median and mode.

### 3. Exploratory Data Analysis (EDA)

Performed data analysis using visualizations:

- Customer spending category distribution.
- Customer age distribution.
- Annual income distribution.
- Spending category by gender.
- Customer age versus annual income.
- Average income by spending category.

### 4. Feature Engineering

- Created customer age groups.
- Created annual income groups.
- Prepared numerical and categorical features.
- Encoded categorical variables.

### 5. Machine Learning Models

Implemented two classification algorithms:

**Logistic Regression**
- Used for customer spending category classification.
- Applied feature scaling and preprocessing.

**Random Forest Classifier**
- Used for classification based on multiple decision trees.
- Compared its performance with Logistic Regression.

### 6. Model Evaluation

Evaluated the classification models using:

- Accuracy
- Precision
- Recall
- F1-Score

Additional evaluation techniques:

- Confusion Matrix
- Classification Report
- Feature Importance

### 7. Customer Prediction

Created a prediction function that accepts customer information and predicts the spending category:

- Low
- Medium
- High

### 8. Business Insights

Generated insights about:

- Total number of customers.
- Average customer age.
- Average annual income.
- Most common spending category.
- Most influential prediction features.
- Model performance comparison.

## 📊 Model Evaluation

The project compares Logistic Regression and Random Forest using the following metrics:

| Metric | Purpose |
|---|---|
| Accuracy | Overall correct predictions |
| Precision | Correct positive predictions |
| Recall | Ability to identify actual classes |
| F1-Score | Balance between precision and recall |

Actual model scores are generated when the notebook is executed.

## 📁 Project Structure

```text
Customer-Spending-Prediction/
│
├── Mall_Customers.csv
│
├── Cleaned_Customer_Data.csv
│
├── Customer_Spending_Prediction.ipynb
│
├── Customer_Spending_Model.pkl
│
├── Model_Comparison.csv
│
├── Feature_Importance.csv
│
└── README.md
```

## 🚀 How to Run the Project

### Step 1: Clone the Repository

```bash
git clone https://github.com/satya77713/Customer-Spending-Prediction.git
```

### Step 2: Navigate to the Project Folder

```bash
cd Customer-Spending-Prediction
```

### Step 3: Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter joblib
```

### Step 4: Open Jupyter Notebook

```bash
jupyter notebook
```

### Step 5: Run the Notebook

Open `Customer_Spending_Prediction.ipynb` and execute all cells.

Make sure the `Mall_Customers.csv` dataset is available in the project directory.

## 💡 Key Learnings

Through this project, I gained practical experience in:

- Data cleaning and preprocessing.
- Exploratory Data Analysis.
- Feature engineering.
- Data visualization.
- Classification algorithms.
- Model evaluation techniques.
- Customer behavior analysis.
- Machine learning predictions.
- Business insight generation.

## 🎓 Internship Details

- **Organization:** Veda Technology
- **Program:** AI & ML Internship
- **Task Number:** 31
- **Project:** Customer Spending Category Prediction

## 👨‍💻 Author

**Satya**

GitHub: [@satya77713](https://github.com/satya77713)

## 📝 Conclusion

This project demonstrates an end-to-end beginner-friendly Machine Learning workflow for customer spending category prediction.

By applying data cleaning, exploratory analysis, feature engineering, visualization, and classification algorithms, the project provides practical experience in understanding customer behavior and building predictive models.

⭐ If you find this project useful, feel free to star the repository!

