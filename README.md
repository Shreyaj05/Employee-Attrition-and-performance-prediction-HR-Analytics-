# Employee-Attrition-and-performance-prediction-HR-Analytics-
This project aims to predict employee attrition in an organization using supervised machine learning techniques. Attrition, or employee turnover, is a critical issue in Human Resource (HR) analytics, and early prediction helps in strategic decision-making for employee retention. A real-world HR dataset was used, containing various employee attributes such as age, gender, job satisfaction, monthly income, distance from home, and more. The target variable is Attrition, classified as Yes or No.¶
Steps Performed:
     1. Data Preprocessing:
             Dropped unnecessary columns.
             Converted categorical features into numerical.
             Label Encoded the target variable (Attrition).
     2. Train-Test Split:
             The dataset was split into training and test sets using an 80-20 split.
     3. Feature Scaling:
             Standardized numerical features using StandardScaler to ensure all features contribute equally to the model.
     4. Model Building:
             Implemented a Logistic Regression model with class weights set to balanced to handle residual class imbalance.
     5. Trained on the SMOTE-resampled training data.
     6. Model Evaluation:
             Evaluated using Accuracy.
Tools & Technologies Used:
       Python (Jupyter Notebook)
       Libraries: pandas, numpy, seaborn, matplotlib, scikit-learn, imblearn.
Key Learnings:
      How to handle imbalanced datasets using SMOTE.
      Importance of scaling features before modeling.
      Evaluation metrics for classification problems.
Outcome:
     The logistic regression model performed well on the test data, achieving a high accuracy and perfect classification due to oversampling. However, further investigation and cross-validation are recommended to      avoid overfitting and ensure generalizability.
