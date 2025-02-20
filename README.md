# Diabetes Prediction App

This is a **Streamlit-based web application** that predicts whether a person has diabetes based on medical input parameters using a pre-trained machine learning model.

## Features
- **User-Friendly Interface**: Built using Streamlit.
- **Input Validation**: Ensures correct numerical inputs.
- **Machine Learning Model**: Uses a pre-trained model for prediction.
- **Performance Metrics**: Displays Accuracy, Precision, Recall, F1-Score, and Confusion Matrix.
- **Automated Predictions**: Provides instant feedback based on user input.

## Installation & Setup

### Prerequisites
Ensure you have the following installed:
- Python 3.7 or higher
- Required Python Libraries

### Install Dependencies
Clone the repository and install the required dependencies:
```sh
pip install streamlit pandas scikit-learn numpy pickle
```

### Running the Application
1. Ensure your **diabetes_model.sav** file is placed in the correct directory.
2. Run the Streamlit app:
   ```sh
   streamlit run app.py
   ```
3. The application will open in your browser.

## Usage
1. **Enter medical parameters** (Pregnancies, Glucose, Blood Pressure, etc.).
2. **Click the "Diabetes Test Result" button** to see the result.
3. **Click "Check Model Accuracy"** to view model performance on test data.
4. **Review Accuracy, Precision, Recall, F1-score, and Confusion Matrix.**

## Model Details
The model used is a **pre-trained machine learning model** stored as `diabetes_model.sav`. Ensure the model file is in the correct directory to avoid loading errors.

## Troubleshooting
- If you get a model loading error, check the file path in the script.
- If dependencies are missing, reinstall them using `pip install -r requirements.txt`.
- Ensure `diabetes.csv` exists for testing model accuracy.

## License
This project is open-source. Feel free to modify and use it as needed.

## Author
Developed by **TAANISH M**.
