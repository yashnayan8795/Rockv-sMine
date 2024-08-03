# Sonar Rock vs Mine Prediction

This project uses logistic regression to predict whether an object is a rock or a mine based on sonar signal data. The model is trained on the sonar dataset and can make predictions on new data. Additionally, the prediction is verified against the actual label to check its accuracy.

## Dataset

The dataset used in this project is the Sonar dataset, which contains 208 instances and 61 attributes. Each instance is a set of 60 sonar readings, and the last column is the label ('R' for rock, 'M' for mine).

## Requirements

- Python 3.x
- NumPy
- Pandas
- scikit-learn

You can install the necessary Python packages using:
    ```sh
    pip install numpy pandas scikit-learn

Usage

    Load the dataset: Load the Sonar dataset from a CSV file.
    Train the model: Train a logistic regression model on the training data.
    Make a prediction: Randomly select a row from the dataset and make a prediction.
    Verify the prediction: Check if the predicted label matches the actual label.
    
Steps

  1.Clone the repository or download the project files.

  2.Install the required packages:

    pip install numpy pandas scikit-learn
  
  Ensure your dataset file (sonar_data.csv) is in the same directory as the script or provide the correct path.

  Run the script:
  
    python sonar_prediction.py

Results

  The script prints the accuracy of the model on both the training and test data. It also randomly selects a row from the dataset, makes a prediction, and verifies if the prediction is correct by comparing it with the actual label.

License

  This project is licensed under the MIT License - see the LICENSE file for details.

