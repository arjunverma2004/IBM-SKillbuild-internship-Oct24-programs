# IBM-SKillbuild-internship-Oct24-programs
Hey Guys, These are the projects I created during my IBM SKillBuild Internship.
# Diabetes Prediction using Logistic Regression

This project demonstrates how to predict diabetes using a Logistic Regression model in Python. It uses the Pima Indians Diabetes dataset and involves data preprocessing, model training, evaluation, and visualization.

## Dataset

The Pima Indians Diabetes dataset is used in this project. It contains medical information about female patients of Pima Indian heritage and whether they have diabetes. The dataset is available in the `diabetes.csv` file.

## Requirements

To run this project, you'll need the following libraries:

- NumPy
- Pandas
- Matplotlib
- Scikit-learn

You can install these libraries using pip:
```bash
pip install numpy pandas matplotlib scikit-learn
```
## Usage

1. **Data Preprocessing:** The code imports the dataset, selects relevant features (Glucose, BMI, and Age), and splits the data into training and testing sets. It also applies feature scaling using StandardScaler.

2. **Model Training:** A Logistic Regression model is trained on the training data.

3. **Model Evaluation:** The model's performance is evaluated using a confusion matrix and accuracy score.

4. **Visualization:** The training and testing data are visualized in 3D scatter plots to understand the data distribution and model predictions.

5. **Prediction:** The code includes a section to predict diabetes for a new individual based on their Glucose, BMI, and Age.

## Results

The model achieves an accuracy of 83.11% on the test set. You can find the confusion matrix and accuracy score in the code output.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.



