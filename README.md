AquaSafe: Water Quality Prediction using Machine Learning

AquaSafe is a machine learning project designed to predict the potability of water (safe or unsafe for drinking) using key water quality parameters.
This project implements four supervised machine learning algorithms and provides a step-by-step workflow for data preprocessing, model building, evaluation, and prediction.

Features:

Algorithms Used:
Linear Regression
Logistic Regression
Random Forest
Extra Trees Classifier

End-to-End Workflow:
Data exploration and visualization
Feature scaling and data splitting
Model training and evaluation
Hyperparameter tuning
Predictive system to classify water as safe or unsafe


Interactive Functionality:
Input custom water quality values to predict potability.

Technologies :
Python
Jupyter Notebook

Libraries:
Pandas
NumPy
Seaborn
Matplotlib
Scikit-learn


Setup and Installation

1. Clone this repository:

git clone https://github.com/yourusername/AquaSafe.git  
cd AquaSafe

2. Install required libraries:

pip install -r requirements.txt

3. Open the Jupyter Notebook:

jupyter notebook AquaSafe.ipynb


Usage
1. Load the provided dataset (water_potability.csv).
2. Run the notebook cells sequentially to preprocess the data, build models, and evaluate their performance.
3. Customize the input values in the prediction section to test the water potability.

Results
Random Forest achieved the highest accuracy, making it the preferred model for this application.

How It Works
1. Data Preprocessing: Handles missing values, scales features, and splits data into training and testing sets.
2. Model Training: Trains each algorithm using cross-validation for robust performance.
3. Evaluation: Uses metrics like accuracy, precision, recall, and F1-score.
4. Prediction System: Enables users to input water parameters and get instant predictions.

Future Enhancements
Add deployment options using Flask or Streamlit.
Integrate additional machine learning algorithms.
Provide real-time predictions using a web application.


Contributing

Contributions are welcome! If you have suggestions or improvements, feel free to open an issue or submit a pull request.

License

This project is licensed under the MIT License.

