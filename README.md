# Titanic Survival Prediction

This project aims to predict the survival of passengers on the Titanic using various machine learning models. The goal is to explore different classification algorithms and find the best performing model. The project includes training models, evaluating their performance, and making predictions on test data.


## Project Structure

- `train.csv`: Training dataset containing all features and the target column (`Survived`).
- `test.csv`: Test dataset containing all features except the target column (`Survived`).
- `predictions.csv`: Actual results of the target column (`Survived`) for the test dataset.
- `titanic_prediction.py`: Main Python script to train models, make predictions, and evaluate performance.
- `README.md`: This file.

## Requirements

- Python 3.x
- pandas
- scikit-learn

## Setup

1. Clone the repository to your local machine:
    ```sh
    git clone https://github.com/yourusername/titanic-survival-prediction.git
    cd titanic-survival-prediction
    ```

2. Install the required packages:
    ```sh
    pip install pandas scikit-learn
    ```

## Usage

1. Place the `train.csv`, `test.csv`, and `actual.csv` files in the project directory.

2. Open file `titanic.ipynb` and run the file to train the models, evaluate their performance, make predictions and see the results

## Models Used

- RandomForestClassifier
- LogisticRegression
- GaussianNB

## Results

The performance metrics (accuracy, precision, recall, F1 score) for each model are printed to the console. Predictions for the test dataset are saved in separate text files.

## Contributing

Feel free to contribute to this project by opening issues or submitting pull requests. 
