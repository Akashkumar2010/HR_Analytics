## HR Analytics: Employee Promotion Prediction

## Project Description

This project aims to predict employee promotions within a company based on various HR data. Using machine learning models, the analysis helps identify the factors most strongly associated with promotions, thereby assisting the HR department in making data-driven decisions.

## Dataset

The project uses two datasets:
- **Train Dataset**: Contains 54,808 employee records with features such as department, education, gender, performance metrics, and whether the employee was promoted.
- **Test Dataset**: Contains 23,490 employee records without the promotion label.

## Key Features of the Dataset
- **employee_id**: Unique ID for each employee
- **department**: Employee's department
- **region**: Region of employment
- **education**: Employee's education level
- **gender**: Gender of the employee
- **recruitment_channel**: Recruitment channel through which the employee was hired
- **no_of_trainings**: Number of trainings completed
- **age**: Age of the employee
- **previous_year_rating**: Employee's rating from the previous year
- **length_of_service**: Duration of employment
- **KPIs_met >80%**: Key Performance Indicator flag
- **awards_won?**: Whether the employee has won any awards
- **avg_training_score**: Average score in training
- **is_promoted**: Promotion flag (target variable)

## Models Used
- Logistic Regression
- Naive Bayes
- Decision Trees
- Random Forest
- Support Vector Machine (SVM)
- Gradient Boosting
- XGBoost
- AdaBoost
- K-Nearest Neighbors (KNN)

## Installation and Usage

1. Clone the repository:
    ```sh
    git clone <repository-url>
    ```
2. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```
3. Run the notebook using Jupyter:
    ```sh
    jupyter notebook HR_Analytics.ipynb
    ```

## Results
The notebook provides an analysis of various models' performance, including accuracy, precision, recall, and F1-score. The best-performing model is identified based on these metrics.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request.

## License
This project is licensed under the MIT License.
