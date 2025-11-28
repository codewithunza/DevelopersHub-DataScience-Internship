# DevelopersHub Corporation - Data Science & Analytics Internship

---

## 📋 Overview

This repository contains the completed tasks for the Data Science & Analytics Internship at **DevelopersHub Corporation**. The internship focuses on developing core data science skills including data exploration, visualization, model building, and performance evaluation using Python.

**Total Tasks Completed**: 3

---

## 🎯 Completed Tasks

### ✅ Task 1: Exploring and Visualizing a Simple Dataset
**Status**: Completed ✓

**Objective**: Understand how to read, summarize, and visualize the Iris dataset.

**Key Deliverables**:
- Data loading and inspection using pandas
- Dataset structure analysis (.shape, .columns, .head())
- Multiple visualizations:
  - Scatter plots for relationship analysis
  - Histograms for distribution analysis
  - Box plots for outlier detection
  - Pairplot for comprehensive feature relationships
  - Correlation heatmap

**Skills Demonstrated**:
- ✅ Data loading and inspection
- ✅ Basic data summarization
- ✅ Visualization using matplotlib and seaborn
- ✅ Statistical analysis

**📊 Results**: Successfully analyzed 150 samples across 3 species with 4 features. Identified strong correlations and clear species separability.

**[Click here to open the Colab Notebook for Task 1](https://colab.research.google.com/drive/1joDmmr2BqOR6Sz3L-oZi7j7Wvthau2wy?usp=sharing)**

---

### ✅ Task 2: Credit Risk Prediction
**Status**: Completed ✓

**Objective**: Predict whether a loan applicant is likely to default on a loan.

**Key Deliverables**:
- Handled missing data using median (numerical) and mode (categorical)
- Comprehensive EDA with 9+ visualizations
- Trained classification models:
  - Logistic Regression
  - Decision Tree Classifier
- Model evaluation using confusion matrix and accuracy metrics

**Skills Demonstrated**:
- ✅ Data cleaning and handling missing values
- ✅ Exploratory Data Analysis (EDA)
- ✅ Binary classification modeling
- ✅ Model evaluation and comparison

**📊 Results**: 
- Logistic Regression Accuracy: ~80%
- Decision Tree Accuracy: ~78%
- Key Insight: Credit history is the strongest predictor of loan approval

**[Click here to open the Colab Notebook for Task 2](https://colab.research.google.com/drive/14tfeu9roqM7H_o7xQvmu-ZqHIjF5M-m9?usp=sharing)**

---

### ✅ Task 3: Customer Churn Prediction (Bank Customers)
**Status**: Completed ✓

**Objective**: Identify bank customers who are likely to leave (churn).

**Key Deliverables**:
- Data cleaning and preparation (removed unnecessary columns)
- Categorical encoding:
  - Label Encoding for Gender
  - One-Hot Encoding for Geography
- Trained multiple classification models:
  - Logistic Regression (81% accuracy)
  - Decision Tree (79% accuracy)
  - Random Forest (86% accuracy - Best Model)
- Feature importance analysis to identify churn factors

**Skills Demonstrated**:
- ✅ Categorical data encoding (Label & One-Hot)
- ✅ Supervised classification modeling
- ✅ Feature importance analysis
- ✅ Model comparison and selection

**📊 Results**:
- Best Model: Random Forest with 86% accuracy
- **Top Churn Factors**: Age, Number of Products, Balance, Geography (Germany), Active Membership
- Business Insight: Older customers in Germany with multiple products are at higher churn risk

**[Click here to open the Colab Notebook for Task 3](https://colab.research.google.com/drive/1D-_eijJOL6Cgd15xs0WB5drVVpdIWEfi?usp=sharing)**

---

## 🛠️ Technologies & Tools Used

### Programming Language:
- **Python 3.x**

### Libraries:
- **pandas**: Data manipulation and analysis
- **numpy**: Numerical computing
- **matplotlib**: Data visualization
- **seaborn**: Statistical data visualization
- **scikit-learn**: Machine learning models and metrics
  - Models: Logistic Regression, Decision Tree, Random Forest
  - Preprocessing: LabelEncoder, StandardScaler
  - Metrics: Accuracy, Confusion Matrix, Classification Report

### Development Environment:
- **Google Colab**: Primary development environment
- **GitHub**: Version control and code repository

---

## 📊 Overall Performance Summary

| Task | Dataset | Samples | Best Model | Accuracy | Status |
|------|---------|---------|------------|----------|--------|
| Task 1 | Iris | 150 | EDA Only | N/A | ✅ Complete |
| Task 2 | Loan Prediction | 614 | Logistic Regression | 80% | ✅ Complete |
| Task 3 | Bank Churn | 10,000 | Random Forest | 86% | ✅ Complete |

---

## 🚀 How to Use This Repository

To view the completed tasks, simply click on the **"Open in Colab"** badge under each task. This will open the notebook directly in Google Colab, where you can view and run the code.

---

## 📂 Repository Structure

This repository contains a single `README.md` file that provides a summary of all completed tasks. The actual project code and analysis for each task are available as Google Colab notebooks, accessible via the links provided.

---

## 🎓 Key Learnings & Skills Acquired

### Technical Skills:
- ✅ Data loading, cleaning, and preprocessing
- ✅ Handling missing values effectively
- ✅ Exploratory Data Analysis (EDA)
- ✅ Data visualization using matplotlib and seaborn
- ✅ Categorical data encoding (Label and One-Hot)
- ✅ Feature scaling and normalization
- ✅ Classification model training and evaluation
- ✅ Feature importance analysis
- ✅ Model comparison and selection

### Domain Knowledge:
- ✅ Credit risk assessment factors
- ✅ Customer churn patterns in banking
- ✅ Feature engineering for predictive modeling
- ✅ Business insights extraction from data

### Tools & Best Practices:
- ✅ Version control with Git/GitHub
- ✅ Code documentation and commenting
- ✅ Professional notebook structure
- ✅ Reproducible research practices

---

## 📈 Visualizations Highlights

### Task 1: Iris Dataset
- Comprehensive pairplot showing species relationships
- Correlation heatmap revealing feature dependencies
- Distribution analysis through histograms and box plots

### Task 2: Loan Prediction
- Missing data analysis and visualization
- Demographic analysis (Gender, Education, Property Area)
- Income and loan amount distributions
- Confusion matrices for model comparison

### Task 3: Customer Churn
- Churn rate analysis by demographics
- Feature importance ranking visualization
- Age, Balance, and Credit Score distributions by churn status
- Model performance comparison charts

---

## 💡 Business Insights & Recommendations

### Credit Risk (Task 2):
- Credit history is the primary factor in loan approval decisions
- Applicants with higher education show better repayment patterns
- Combined household income significantly impacts approval rates
- **Recommendation**: Implement credit history verification as a mandatory step

### Customer Churn (Task 3):
- Age is the strongest predictor of customer churn
- German market shows higher churn rates (requires investigation)
- Customers with 3-4 products are at higher risk
- Inactive members are more likely to leave
- **Recommendations**:
  1. Target retention programs for customers aged 40+
  2. Investigate service quality issues in Germany
  3. Review product bundling strategy
  4. Implement engagement campaigns for inactive members

---

## 📝 Code Quality Standards

All notebooks in this repository follow these standards:
- ✅ Clear introduction and problem statement
- ✅ Dataset description and understanding
- ✅ Step-by-step data cleaning process
- ✅ Comprehensive EDA with multiple visualizations
- ✅ Well-commented code explaining each step
- ✅ Model training with proper train-test split
- ✅ Evaluation metrics clearly displayed
- ✅ Conclusions summarizing key insights
- ✅ Professional formatting and organization
