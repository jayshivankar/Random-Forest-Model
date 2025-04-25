🌲 Random Forest Classification on Custom Dataset
This repository demonstrates the application of the Random Forest algorithm for classification using a custom dataset (data.csv). The model is trained, evaluated, and visualized using Python libraries such as pandas, scikit-learn, and matplotlib.

📁 Dataset
The dataset used in this project is located in data.csv.
It is assumed to be a tabular dataset suitable for classification tasks, with one target column and one or more feature columns.

🧠 Model: Random Forest Classifier
The Random Forest algorithm is an ensemble learning method that builds multiple decision trees and merges them together to get a more accurate and stable prediction.

📌 Project Structure
.
├── data.csv                  # Input dataset
├── random_forest_model.py    # Main script for training & evaluation
├── requirements.txt          # Dependencies
├── README.md                 # Project documentation

🔧 Requirements
Install required libraries:
pip install -r requirements.txt
Contents of requirements.txt:
pandas
scikit-learn
matplotlib


🚀 How to Run
Place your data.csv file in the root directory.

Make sure the target column name is defined correctly in the script.

Run the training script:
python random_forest_model.py


📝 Script Overview
Data Loading: Reads data.csv using pandas.

Preprocessing: Splits the data into features and target.

Training: Applies a Random Forest classifier.

Evaluation: Prints accuracy, confusion matrix, and classification report.

Visualization: Optional feature importance plot.

📊 Output
Model Accuracy

Classification Report

Confusion Matrix

Feature Importance Plot (if enabled)

Accuracy: 0.87

Classification Report:
              precision    recall  f1-score   support
           0       0.85      0.89      0.87       100
           1       0.89      0.85      0.87       100

Confusion Matrix:
[[89 11]
 [15 85]]


