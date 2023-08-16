# Predicting Liver Disease in Indian Patients

This project focuses on predicting liver disease in Indian patients using machine learning methods. It employs the `indian_liver_patient.csv` dataset and is developed using Python programming language along with the following libraries: `numpy`, `pandas`, `plotly.express`, `sklearn`, and `tensorflow`.

## Project Overview

The primary objective of this project is to create a predictive model for identifying liver disease in Indian patients using relevant medical features. The dataset provides various attributes like age, gender, total bilirubin, direct bilirubin, alkaline phosphatase, etc., which serve as input features for the predictive model.

## Libraries Utilized

The subsequent libraries play a crucial role in this project:

- `numpy`: Used for numerical computations and array manipulation.
- `pandas`: Used for data manipulation and analysis.
- `plotly.express`: Employed for generating interactive visualizations to comprehend the dataset.
- `sklearn`: Utilized for data preprocessing tasks including standardization and train-test splitting.
- `tensorflow`: Used for constructing and training machine learning models.

## Dataset

The dataset that underpins this project is called `indian_liver_patient.csv`. It encompasses medical data related to Indian patients, forming the foundation for training and assessing the predictive model.

## Workflow

1. Load the dataset via `pandas`.
2. Conduct exploratory data analysis with the help of `plotly.express` to gain insights into feature distributions and relationships.
3. Preprocess the data using `sklearn`'s `StandardScaler` to normalize the features.
4. Partition the dataset into training and testing subsets using `sklearn`'s `train_test_split`.
5. Construct and train a machine learning model using `tensorflow`.
6. Evaluate the model's performance on the test dataset.
7. Leverage the trained model for making predictions on new data.

## How to Use

1. Ensure Python is installed on your system.
2. Install the necessary libraries with the command `pip install numpy pandas plotly scikit-learn tensorflow`.
3. Place the `indian_liver_patient.csv` dataset file in the project directory.
4. Open the main project script.
5. Follow the code comments to comprehend each project phase.
6. Run the script to load, preprocess, train, and assess the model.
7. Interpret the outcomes and use the trained model for making predictions.

Feel free to tailor the code to your preferences and experiment with diverse machine learning algorithms or methods to enhance the model's performance.

## Conclusion

This project showcases the application of machine learning in predicting liver disease among Indian patients. By harnessing various libraries and techniques, we have crafted a model that can aid in early detection and diagnosis of liver-related ailments.

