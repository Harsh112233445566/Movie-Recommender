# Movie Recommendation System

## Drive link for webapp : https://drive.google.com/drive/folders/1Cyb9OW_xDTC6O5hVKci9m9Lfi_aG0R6H?usp=drive_link

## Overview

This repository contains a **Movie Recommendation System** built with Python. It suggests movies to users based on movie descriptions using **vectorization techniques** (TF-IDF). The project is hosted on **Streamlit**, providing an interactive web interface. The recommendation model and the movie data are saved using **Pickle** for efficient loading and use.

### Key Features:
- **Movie Recommendations**: Suggests similar movies based on the input movie title.
- **Vectorization**: Uses **TF-IDF** (Term Frequency-Inverse Document Frequency) to convert movie descriptions into vectors for similarity analysis.
- **Streamlit Interface**: A simple, interactive web interface for users to input movie titles and receive recommendations.
- **Pickle**: Uses Pickle to load pre-trained models and datasets, ensuring faster and more efficient loading.

---

## Technologies used

- **Python**: Programming language used for the implementation.
- **Streamlit**: For building the interactive web app.
- **Scikit-learn**: For TF-IDF vectorization and similarity calculations.
- **Pickle**: For serializing and deserializing models and datasets.
- **Pandas & NumPy**: For data manipulation and numerical operations.

---


1. Install Required Dependencies
Make sure you have Python 3.6+ installed. Then, install the required libraries using pip:

bash
Copy code
pip install -r requirements.txt
This will install the following dependencies:

pandas
numpy
scikit-learn
streamlit
pickle-mixin

2. Ensure the Pickle Files Are Present
Ensure that the necessary Pickle files (e.g., model.pkl, movie_data.pkl) are available in the project directory. These files contain the pre-trained recommendation model and the vectorized movie data.

If these files are missing, you can train the model yourself (instructions below).

3. Run the Streamlit App
To launch the application, simply run:

bash
Copy code
streamlit run web.py
This will open the Streamlit app in your web browser, where you can interact with the movie recommendation system.


## How It Works
1. Data Preprocessing:
The dataset consists of movie titles and descriptions. The text data is preprocessed (cleaning, removing stopwords) and then vectorized into numerical data using TF-IDF.

2. Vectorization:
TF-IDF: Converts movie descriptions into numerical vectors that reflect the importance of words within the context of all movie descriptions.
Cosine Similarity: Used to measure the similarity between movies based on their vectorized representations.
3. Pickle for Efficiency:
Once the model is trained, it is saved using Pickle, allowing for faster loading of the trained model and vectorized movie data without having to retrain the model every time the app is launched.

4. Streamlit Interface:
Users can input a movie title or select from a list. The system will recommend similar movies based on the movie description.

## Samples
<img width="959" alt="image" src="https://github.com/user-attachments/assets/3617d8d3-09b1-4cee-9d22-f9d553ce28fd">

<img width="907" alt="image" src="https://github.com/user-attachments/assets/4a47ec2e-7c17-4dd7-aed6-4f4ebcf7144f">

<img width="907" alt="image" src="https://github.com/user-attachments/assets/baf1bee5-70ca-4118-823d-8c006dc32759">

<img width="885" alt="image" src="https://github.com/user-attachments/assets/3be4ad21-8fbd-42fe-8772-19cacbbe06aa">





