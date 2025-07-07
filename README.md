# Classifying-the-Audio-Gen-in-spotify
Problem statement:
   “Built a predictive model capable of classifying songs into their respective genres using Spotify audio features.”
In this project, we aim to build a predictive model capable of classifying songs into their respective genres using Spotify audio features

Data:

The data is contained in musicData.csv, and includes 20 columns. The data for each song such as the track name, artist name, album name, and of course the genre. The second step in this process was gathering the audio features for these songs. 
The dataset contains the following features:
•	Basic Track Info: Track Name, Artist Name, Album Name, Genre, Popularity, Duration (milliseconds), Explicit, Track ID, Artist ID
•	Audio Features: Danceability, Energy, Key, Loudness, Mode, Speechiness, Acousticness, Instrumentalness, Liveness, Valence, Tempo

Approach:
. Data Exploration and Preparation
. Model Development
. Streamlit Application Development


Machine Learning
Model	Accuracy
Dummy Classifier (Baseline)	0.083
kNN	0.501
Logistic Regression	0.52
Random Forest	0.74
Gradient Boosting	0.751

![image](https://github.com/user-attachments/assets/1e342878-20f5-4d4d-8b12-bff727db8202)

Summary
The goal of this project is to predict the genre of a song based on its audio features. In a machine learning context, this is a multiclass classification problem.
The final dataset that was used to train and test the machine learning models in this project consisted of 10,843 songs spanning 12 different genres.
The models I tested in this project were kNN, Logistic Regression, Random Forest, and Gradient Boosting. The supervised machine learning model that performed the best was the Gradient Boosting classifier with an accuracy of 72.9% on the test set.
