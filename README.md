# Diabetes Prediction App

This is a **Streamlit-based web application** that predicts whether a person has diabetes based on medical input parameters using a pre-trained machine learning model.

## Features
- User-friendly interface built with Streamlit
- Takes multiple medical parameters as input
- Uses a pre-trained machine learning model for predictions
- Provides instant results with an easy-to-use interface

## Installation & Setup

### Prerequisites
Ensure you have the following installed:
- Python 3.7 or higher
- pip

### Install Dependencies
Clone the repository and install the required dependencies:
```sh
pip install streamlit numpy pickle
```

### Running the Application
1. Ensure your **diabetes_model.sav** file is placed in the correct directory.
2. Run the Streamlit app:
   ```sh
   streamlit run app.py
   ```
3. The application will open in your browser.

## Usage
- Enter the required medical parameters.
- Click the **Predict** button to see the result.
- Click **Clear Inputs** to reset all fields.

## Model
The model used is a pre-trained machine learning model stored as `diabetes_model.sav`. Ensure the model is in the correct directory to avoid loading errors.

## Troubleshooting
- If you get a model loading error, check the file path in the script.
- If dependencies are missing, reinstall them using `pip install -r requirements.txt`.

## License
This project is open-source. Feel free to modify and use it as needed.

## Author
Developed by **TAANISH M**.

