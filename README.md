# Onset Diabetes Prediction in Female Pima Indian Population

## Description
This project predicts the onset of diabetes in the female Pima Indian population using the Pima Indians Diabetes Database. It involves data analysis, visualization, preprocessing, and SVM classification model building.

## Author
- **Student Name:** Nidhi Bendre

## Project Structure
- **Data:** `diabetes.csv` - dataset used for analysis.
- **Code:** Jupyter Notebook or Python script containing code for data loading, analysis, visualization, model building, and evaluation.

## Parts of the Project
1. **Data Exploration and Summary Statistics**
   - Overview of dataset dimensions and summary statistics.
2. **Visualizations**
   - Pairwise plots depicting relationships between variables based on the outcome.
   - Boxplots showcasing distributions for each feature concerning diabetes outcomes.
3. **Data Cleaning**
   - Handling missing or invalid values.
   - Dropping rows with zero values in critical columns (Glucose, Blood Pressure, Skin Thickness, Insulin, BMI).
4. **Data Partitioning and Model Building**
   - Partitioning data into train/test sets.
   - Normalizing numeric data for model fitting.
   - Building an SVM classifier to predict diabetes onset.
5. **Model Evaluation and Tuning**
   - Assessing model accuracy without parameter tuning.
   - Utilizing GridSearchCV for parameter optimization and improving model performance.
6. **Evaluation and Conclusion**
   - Diagnosing bias-variance issues.
   - Concluding remarks on model performance and its potential application in the medical industry.

## How to Use
- Clone the repository to your local machine.
- Ensure necessary libraries are installed (`pandas`, `scikit-learn`, `seaborn`, `matplotlib`).
- Execute the Jupyter Notebook or Python script to reproduce the analysis and model building.
- Follow along with comments and markdown cells for detailed explanations.

## Note
- The model's accuracy is currently at 81%, indicating room for further improvement before considering practical applications, especially in medical diagnosis.
