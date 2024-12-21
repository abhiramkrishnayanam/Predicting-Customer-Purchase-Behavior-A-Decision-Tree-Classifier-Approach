# Predicting-Customer-Purchase-Behavior-A-Decision-Tree-Classifier-Approach

# Task 3: Customer Purchase Prediction in Bank Marketing  
This project was completed as part of the Data Science Internship at SkillCraft Technology. The primary objective was to predict whether a customer would purchase a product or service offered by a bank. The dataset used for this task was sourced from the [UCI Bank Marketing Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/bank+marketing).

## Project Overview  
The goal of this task was to:  
1. **Clean and preprocess the dataset** to ensure it was ready for analysis.  
2. Use a **Decision Tree Classifier** to build a predictive model for determining customer purchase behavior.  

## Dataset  
The dataset includes various features related to customer demographics, marketing interactions, and campaign outcomes.  
- **Source**: UCI Bank Marketing Machine Learning Repository  
- **Key Features**:  
  - Age, job, marital status, education  
  - Contact details and last campaign details  
  - Outcome of the previous campaign  
  - Target variable: Whether the customer purchased the product (`yes` or `no`)  

## Methodology  

### 1. Data Cleaning  
- **Null Value Handling**: Identified and managed missing values.  
- **Feature Encoding**: Encoded categorical variables into numerical form.  
- **Outlier Detection**: Removed or treated outliers to improve model performance.  
- **Scaling**: Normalized numerical features to ensure consistency across variables.  

### 2. Model Development  
- **Model Used**: Decision Tree Classifier  
- **Steps**:  
  1. Splitting the data into training and test sets.  
  2. Training the Decision Tree Classifier using the training dataset.  
  3. Evaluating the model's performance on the test dataset using metrics like accuracy, precision, recall, and F1-score.  

## Results  
- **Accuracy**: Achieved an accuracy of 87 % .  
- **Insights**: The model highlighted key factors influencing customer purchase behavior, such as previous campaign outcome and education level.  

## Tools & Technologies Used  
- Python (Pandas, NumPy, Scikit-learn)  
- Jupyter Notebook  

## Conclusion  
This project successfully demonstrated the application of Decision Tree Classifier for customer behavior prediction in bank marketing. 
It emphasized the importance of data cleaning and preprocessing in building a robust machine learning model.


