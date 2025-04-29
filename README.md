### HR Analytics: Why Employees Left

This project is an HR analytics case study focused on predicting employee attrition using machine learning models.
It uses a dataset from IBM (sourced via Kaggle) and explores different strategies such as balancing datasets, hyperparameter tuning, and model comparisons to improve predictive performance.

### Project Structure
Data: IBM HR Analytics Employee Attrition Dataset (via Kaggle)

Notebook: Complete EDA, preprocessing, modeling, evaluation

Models Used:

• Logistic Regression

• Random Forest

• Support Vector Machine (SVM)

• XGBoost

Techniques:

• Class imbalance handling

• Hyperparameter tuning

• Confusion matrix and classification reports for evaluation

### Key Insights

• Balancing the dataset significantly affects model performance, especially recall for minority classes (employees who leave).

• XGBoost and SVM showed strong results depending on the evaluation metric used.

• Logistic Regression performed well on a balanced dataset but needed careful tuning.

• Simply increasing overall accuracy is not enough — especially when predicting rare events like employee resignations.

### Future Considerations

Based on critical feedback and reflection:

Real-World Data Collection:

• Introduce Exit Interviews at resignation to capture reasons for leaving.

• Annual Surveys for active employees to monitor satisfaction, engagement, and possible risk of resignation.

Feature Expansion:

• Add features like job satisfaction scores, management feedback, growth opportunities, etc.

Predictive Risk Scores:

• Build models not just to predict binary leave/stay, but attrition risk scores over time.

### Installation and Usage

• Clone this repository

• Install required Python packages

• Open the notebook HR Analytics_Why Employee Left.ipynb

• Run all cells

### License

This project is licensed under the MIT License — see the LICENSE file for details.

### Author

Kenrick Saputra Tedja - nkgmnekogami
