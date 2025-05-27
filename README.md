# Crop-Recommendation-System
Crop Recommendation System
This project is a machine learning-based recommendation system that suggests the most suitable crop to cultivate based on soil and weather conditions. It uses classification techniques to analyze key features like nutrient content, pH, temperature, humidity, and rainfall.

Dataset
The dataset (Crop_recommendation.csv) includes the following features:

Feature	Description
N	Nitrogen content in soil
P	Phosphorus content in soil
K	Potassium content in soil
temperature	Average temperature (°C)
humidity	Relative humidity (%)
ph	pH value of the soil
rainfall	Rainfall (mm)
label	Target crop (e.g., rice, maize, etc)

Project Workflow
Install Required Libraries

Upload Dataset (Crop_recommendation.csv)

Preprocess Data: Label encoding of target crop

Train-Test Split

Train Model: Random Forest Classifier

Evaluate Model: Accuracy, Classification Report, Confusion Matrix

Crop Recommendation Function: Predict based on user input

User Interaction: Enter soil/weather parameters to get a crop suggestion

Example Inputs
python
Copy
Edit
N = 90
P = 42
K = 43
temperature = 20.8
humidity = 82.0
ph = 6.5
rainfall = 202.9
Output:

yaml
Copy
Edit
Recommended Crop: rice
Model Performance
Algorithm Used: Random Forest Classifier

Accuracy Achieved: ~99%

Evaluation: Precision, Recall, F1-score, Confusion Matrix

Technologies Used
Python

Scikit-learn

Pandas

NumPy

Seaborn & Matplotlib (for visualization)

Google Colab (for execution environment)

How to Run
Open the code in Google Colab

Upload the Crop_recommendation.csv file when prompted

Run each cell in order

Enter values for soil and climate conditions to receive a crop recommendation

Future Improvements
Add a Streamlit or Flask web interface

Include real-time weather API integration

Expand to region-specific crop suggestions
