# Streamlit Automated Essay Scoring

This README provides instructions on how to run the Streamlit Automated Essay Scoring application. The application can be run either using a standalone executable file or directly within an IDE like PyCharm.

## Running the Application

### Option 1: Using the Executable File
1. **Locate the Executable File**:
Navigate to the dist folder where the executable file (app.exe on Windows) is located. This file was created using PyInstaller and includes all the necessary dependencies.

2.**Run the Executable**:
On Windows, double-click the app.exe file to run the application.
Alternatively, you can run it from the command line: ./dist/app.exe

3.**Application Launch**:

Once the executable is launched, a new tab should automatically open in your default web browser displaying the Streamlit app.
If the browser does not open automatically, you can manually open your browser and go to `http://192.168.8.247:8501`.
local Url `http://localhost:8501`

4.**Using the Application**:

Enter an essay in the text area provided on the web interface.
Click the "Predict Score" button to get the predicted score for the essay.

5.**Troubleshooting**
If you encounter issues related to missing packages, ensure that all required packages are installed in your Python environment.
Make sure that the best_model.pkl file is present in the same directory as the script.
If the application fails to start, check the Streamlit logs in the terminal for error messages.

6.**Open and run the project in pycharm**
   - In PyCharm, open `app.py`.
   - Click the green play button (`Run`) at the top right or right-click the `app.py` file and select `Run 'app'`.
   - The application will start, and a tab will open in your default web browser displaying the Streamlit app.
   - If the browser does not open automatically, you can manually open your browser and go to `http://192.168.8.247:8501`.
   - local Url `http://localhost:8501`

   - If not run by green button use the command "streamlit run app.py" in the terminal

## Application Features

- **User Input**: The app allows users to input various essays.
- **Prediction**: The app provides a prediction of the score based on the input data using a trained XGBoost model.
- **Model**: The XGBoost model is serialized in a `model.pkl` file.


## Files in This Repository

- `app.py`: The main Python script for the Streamlit app.
- `best_model.pkl`: The serialized XGBoost model.
- `Untitled10` : jupyter source file
- `README.md`: This readme file.


## License
This project is licensed under the MIT License.

## contact
pleasae contact Ravishka Jyasundara at ravimadu27@gmail.com