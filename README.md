### Summary of Data Science Projects and Model Performance

1. Belarus Car Price Prediction:
    - Data Preprocessing: Filled null values without disturbing data distribution, reduced unique values in the car_make column, removed outliers.
    - Visualization and Feature Engineering: Visualized data, standardized, and labeled categorical values.
    - Model Performance: The XGBoost model achieved an accuracy of 88%.

2. Breast Cancer Prediction:
    - Data Preprocessing: Removed unnecessary columns.
    - Visualization and Feature Engineering: Conducted data visualization, standardized, and labeled categorical values.
    - Model Performance: The Logistic Regression model achieved an accuracy of 97.4%.

3. Cardiovascular Disease Prediction:
    - Data Preprocessing: Removed unnecessary columns, visualized data, removed outliers, standardized data, labeled categorical values.
    - Special Techniques: Applied ADASYN due to poor initial performance on certain classes.
    - Model Performance: The application of ADASYN improved the model accuracy to 95.3%.

4. Customer Churn Prediction:
    - Data Preprocessing: Removed unnecessary columns, visualized data, standardized data, labeled categorical values.
    - Special Techniques: Applied ADASYN due to poor initial performance on one of the target classes.
    - Model Performance: The application of ADASYN improved the model accuracy to 89.2%.

5. Diamond Price Prediction:
    - Data Preprocessing: No major issues in data.
    - Visualization and Feature Engineering: Conducted various data visualizations, standardized, and labeled categorical values.
    - Model Performance: The Random Forest model achieved an accuracy of 98.1%.

6. E-commerce Product Delivery Prediction:
    - Data Preprocessing: Visualized data, standardized data, labeled categorical values.
    - Special Techniques: Applied SMOTE due to poor initial performance on one of the target classes.
    - Model Performance: The application of SMOTE improved the model accuracy to 74.5%.

7. Hotel Reservation Cancellation Prediction:
    - Data Preprocessing: No changes needed due to clean data.
    - Visualization and Feature Engineering: Performed thorough data visualization, standardized, and labeled categorical values.
    - Model Performance: The Random Forest model achieved an accuracy of 90.7%.

8. House Price Prediction:
   - Data Preprocessing: Formatted date column, reduced unique values in some columns, removed outliers.
   - Visualization and Feature Engineering: Conducted data visualization, standardized data.
   - Model Performance: The Random Forest model achieved an accuracy of 88.3%.

9. Indian Used Car Price Prediction:
   - Data Preprocessing: Converted string values in the price column to numbers, removed columns with many null values, reduced unique values in categorical columns.
   - Visualization and Feature Engineering: Visualized data, standardized, and labeled categorical values, improved model accuracy with Grid Search.
   - Model Performance: The Random Forest model achieved an accuracy of 74.8%, which is satisfactory given the complexity of the data.

10. Loan Approval Prediction:
   - Data Preprocessing: Removed spaces from column names and values.
   - Visualization and Feature Engineering: Conducted data visualization, standardized and labeled categorical values.
   - Model Performance: The XGBoost model achieved an accuracy of 98.2%.

11. Medical Cost Prediction:
   - Data Preprocessing: Converted age to categorical, removed outliers.
   - Visualization and Feature Engineering: Performed data visualization, standardized data, labeled categorical values.
   - Model Performance: The ensemble of Gradient Boosting and XGBoost models achieved an accuracy of 88.6%.

12. Pima Indians Diabetes Prediction:
    - Data Preprocessing: Grouped age values, removed outliers, visualized data, standardized data, labeled categorical values.
    - Special Techniques: Applied SMOTE due to poor initial performance on one of the target classes.
    - Model Performance: The application of SMOTE improved the model accuracy to 89%.

13. Wine Quality Prediction:
   - Data Preprocessing: Simplified target column (quality) into two categories.
   - Visualization and Feature Engineering: Conducted data visualization and standardization, improved model accuracy with Grid Search.
   - Model Performance: The Random Forest model achieved an accuracy of 91.2%.

14. Room Occupancy Detection:
   - Data Preprocessing: Split datetime column into day and hour, stored only relevant parts.
   - Visualization and Feature Engineering: Effective data visualization, standardized data.
   - Model Performance: The Random Forest model achieved an accuracy of 99%.

15. Salary Prediction:
   - Data Preprocessing: Removed sparse null values, reduced gender categories, simplified unique values for education and job columns.
   - Visualization and Feature Engineering: Performed visualizations, standardized and labeled data, improved model accuracy with Grid Search.
   - Model Performance: The final ensemble model achieved an accuracy of 95.4%.

16. Sleep Disorder Prediction:
   - Data Preprocessing: Filled null values without disturbing data distribution, converted age to categorical, reduced job categories, split blood pressure into two columns, simplified BMI categories.
   - Visualization and Feature Engineering: Conducted suitable data visualizations, standardized data, and labeled categorical values.
   - Model Performance: The XGBoost model achieved an accuracy of 94.5%.

17. Telecom Customer Churn Prediction:
    - Data Preprocessing: Reduced unique values in some columns, visualized data, standardized data, labeled categorical values.
    - Special Techniques: Applied SMOTE due to poor initial performance on one of the target classes.
    - Model Performance: The application of SMOTE improved the model accuracy to 85.2%.

18. Warranty Claims Fraud Prediction:
    - Data Preprocessing: Reduced unique values in some columns, visualized data, standardized data, labeled categorical values.
    - Special Techniques: Applied ADASYN due to poor initial performance on the '1' target value.
    - Model Performance: The application of ADASYN improved the model accuracy to 95.3%.

### Note:
Each model was built with meticulous data preprocessing, including handling null values, converting categorical variables, removing outliers, and performing necessary visualizations. Advanced techniques like Grid Search, SMOTE, and ADASYN were used to enhance model performance, resulting in high accuracy across various datasets.
