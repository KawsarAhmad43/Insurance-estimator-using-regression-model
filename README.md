# Insurance Cost Estimator

## Overview
This project is an insurance cost estimator built using machine learning techniques. It analyzes a dataset containing information about individuals' age, sex, BMI, number of children, smoking status, region, and their corresponding insurance charges. The goal is to develop a model that predicts insurance costs based on these factors.

## Dataset
The dataset used for this project is stored in the file `insurance.csv`. It contains the following columns:
- Age: Age of the individual
- Sex: Gender of the individual (male or female)
- BMI: Body mass index of the individual
- Children: Number of children/dependents covered by the insurance
- Smoker: Smoking status of the individual (yes or no)
- Region: Geographic region of the individual (northeast, northwest, southeast, southwest)
- Charges: Insurance charges billed to the individual

## Data Preprocessing
- Converted categorical variables (sex, smoker, region) into numerical form using label encoding.
- Split the dataset into training and testing sets.
- Scaled the numerical features using StandardScaler to ensure uniformity in scale.

## Model Building and Evaluation
- Utilized various regression models including Linear Regression, Support Vector Regression (SVR), and Random Forest Regression.
- Performed hyperparameter tuning using GridSearchCV to optimize model performance.
- Evaluated models using mean absolute error and root mean squared error metrics.

## Results
- Linear Regression: Achieved a mean absolute error of X and a root mean squared error of Y.
- SVR: Achieved a mean absolute error of X and a root mean squared error of Y.
- Random Forest Regression: Achieved a mean absolute error of X and a root mean squared error of Y.

## Usage
- Clone the repository to your local machine.
- Ensure Python and necessary libraries are installed.
- Run the Jupyter notebook `Insurance Cost Estimator.ipynb` to view the project.
- Modify the notebook as needed for further analysis or experimentation.

## Future Improvements
- Explore additional feature engineering techniques to improve model performance.
- Experiment with different regression algorithms and ensemble methods.
- Gather more data to enhance model accuracy and generalization.

## Author
- [Your Name]

## License
This project is licensed under the [MIT License](LICENSE).
