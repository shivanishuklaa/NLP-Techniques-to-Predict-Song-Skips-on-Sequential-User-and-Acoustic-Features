# NLP-Techniques-to-Predict-Song-Skips-on-Sequential-User-and-Acoustic-Features
The skip button plays a large role in the user’s experience, as they are free to abandon songs as they choose.
Music providers are also incentivized to recommend songs that their users like in order to increase user experience and time spent on the platform.
SongPredict is a web application that predicts whether a user will skip a song based on various song attributes and user behavior. This app leverages a machine learning model, built using historical data, to predict the likelihood of song skipping.

# Features
User Input: The web form allows users to input attributes like song duration, acousticness, session length, context type, and user behavior data.
Model Prediction: A machine learning model predicts whether the user will skip the song or not based on the input data.
Results Display: The prediction result ("skipped track" or "Track Not Skipped") is displayed to the user after they submit the form.

# Interface
![image](https://github.com/user-attachments/assets/335f8c1a-43fb-41fc-900f-ab5b69b20f5d)


# Technologies Used
1. Backend: Flask (Python)
2. Machine Learning: KNN (K-Nearest Neighbors) model, pickled for easy deployment.
3. Frontend: HTML, CSS (Bootstrap)
4. Model Serialization: Pickle (for saving and loading the trained machine learning model)

# Project Setup Prerequisites
Before running the project, make sure you have the following installed:

1. Python 3.8
2. Flask
3. Scikit-learn
4. Numpy
5. Pickle
6. HTML,CSS (for frontend styling)

# Using the App
Enter the song attributes (duration, acousticness, speechiness, etc.) in the form.
Click on "Predict Now!" to submit the form.
The model will predict whether the song will be skipped or not, and the result will be displayed on the webpage.

# Model Details
The machine learning model used in this project is a K-Nearest Neighbors (KNN) classifier, trained on a dataset containing song attributes and user behavior data. The model predicts whether a user is likely to skip a track based on their listening habits and song characteristics.
