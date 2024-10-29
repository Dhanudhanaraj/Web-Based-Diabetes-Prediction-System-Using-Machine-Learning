# Web-Based Diabetes Prediction System Using Machine Learning

## About

     This project aims to provide an accessible tool for predicting the risk of diabetes, leveraging machine learning algorithms integrated into a web-based interface. Users can input health data, and the system returns real-time predictions about their diabetes risk. This proactive approach can help individuals make informed decisions about their health and seek medical advice if necessary.

## Features
## Features
- Data Input Interface: Users can enter health metrics such as age, BMI, blood pressure, and cholesterol.

- Real-Time Predictions: The system uses a trained machine learning model to predict diabetes risk.

- Multiple Models: Compares several models to select the most effective one, ensuring optimal prediction accuracy.

- User-Friendly Interface: Designed for ease of use by both technical and non-technical users.

## Development Requirements

1.Operating System: 64-bit OS (Windows 10, macOS, Ubuntu).

2.Development Environment: Python 3.10+.

3.Machine Learning Libraries: Scikit-learn for model implementation and evaluation.

4.Frameworks and Tools: Django for backend development, Flask for API integration, and HTML/CSS for frontend.

5.Additional Dependencies: NumPy, Pandas for data handling, and Matplotlib for visualizing results.

## System Architecture

Frontend: HTML5, CSS3, and JavaScript.
Backend: Django-based backend for request handling and model integration.
Model: A Decision Tree model optimized for accuracy and interpretability.
Database: SQLite for storing user inputs and model predictions.
Methodology
Data Preprocessing:
Cleaning data by removing duplicates and handling missing values.
Selecting key features, including age, BMI, blood pressure, and cholesterol, as predictors.
Model Training:
Multiple algorithms were trained, including Decision Tree, Random Forest, and Gradient Boosting, to determine the most effective model.
The Decision Tree model achieved the highest accuracy, making it ideal for deployment in this application.
Model Evaluation:
Evaluated using accuracy, precision, recall, and F1-score.
The Decision Tree model demonstrated balanced performance and interpretability.
Setup Instructions
Clone the Repository:
bash
Copy code
git clone <repository-url>
Install Required Dependencies:
Copy code
pip install -r requirements.txt
Run the Django Server:
Copy code
python manage.py runserver
Access the Web Interface: Visit http://127.0.0.1:8000/ in your web browser.
Project Structure
models/diabetes_prediction_model.pkl: Trained machine learning model for diabetes risk prediction.
app/: Django app containing:
views.py: Logic for processing user inputs and generating predictions.
forms.py: Form for inputting health metrics.
templates/: HTML templates for the web interface.
Results
The Decision Tree model achieved an accuracy of approximately 92%, making it effective for predicting diabetes risk in a non-clinical setting. This accuracy enables users to gain valuable insights into their health status, encouraging early action and potentially preventing severe complications associated with diabetes.

Future Improvements
Expand Feature Set: Incorporate additional health indicators, such as family history and genetic data.
Model Refinement: Experiment with ensemble methods to further improve prediction accuracy.
Enhanced User Interface: Introduce data visualization for better user engagement.
References
Victor, K. F., & Michael, I. Z. (2018). Intelligent data analysis and machine learning: Are they really equivalent concepts? Springer-Verlag.
John, L. A., & Rose, M. B. (2021). Early Detection of Diabetes Using Machine Learning Algorithms. CRC Press.
Clarke, R. S., & Emerson, N. T. (2020). Diabetes Prediction Using Machine Learning Techniques: A Comparative Study of Algorithms. Wiley.
Mitchell, D. R., & Thomson, A. E. (2022). Diabetes Mellitus Prediction Using Machine Learning Techniques: A Comprehensive Review. Elsevier.




