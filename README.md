# AIML-PROJECT

# Movie Recommendation System

# Introduction
In today’s digital age, users are often overwhelmed by the sheer volume of media available. A movie
recommendation system helps filter this vast collection and provide personalized suggestions. This
mini project aims to build a recommendation system using machine learning to recommend movies
based on user preferences.

# Abstract
This project implements a hybrid movie recommendation system using the popular MovieLens
dataset. It combines collaborative filtering and content-based filtering (using genres) to generate top
5 personalized recommendations for any selected movie. A Streamlit-based web interface allows
users to interact with the system in real-time. This project demonstrates the power of combining
different machine learning techniques for better accuracy and usability in recommendation engines.

# Dataset
We used the [MovieLens 100K Dataset](https://grouplens.org/datasets/movielens/100k/) provided by GroupLens. It contains 100,000 ratings from 943 users on 1,682 movies.

# Tools & Technologies Used
- Language: Python
  
- Libraries:
- Pandas
- Scikit-learn
- Streamlit
  
- IDE: VS Code
 
- MovieLens 100k Dataset

- Web Framework: Streamlit for frontend interface
  
# Steps Involved in Building the Project

1. Dataset Preparation
Downloaded and extracted the MovieLens 100k dataset. Loaded movie and rating data using
pandas.

2. Preprocessing
Merged ratings with movie titles and genres. Cleaned and reshaped data for model input.

3. Collaborative Filtering
Constructed a user-movie rating matrix. Computed cosine similarity between movie vectors to
recommend based on similar rating behavior.

4. Content-Based Filtering
Used genre vectors from the dataset. Calculated similarity between movies based on genre
overlap using cosine similarity.

5. Hybrid Recommendation Model
Averaged both collaborative and content-based scores to generate final recommendations.

6. User Interface (UI)
Built an interactive interface using Streamlit, allowing users to select a movie and view top 5
recommendations.

# Conclusion
This project successfully demonstrates a working hybrid movie recommendation system using
machine learning techniques. The system provides accurate and personalized suggestions based
on both user behavior and movie content. It is efficient, scalable, and can be extended in the future
by integrating review sentiment analysis, user authentication, or real-time data.

# Output
[INTERNSHIP_MINI_PROJECT.pdf](https://github.com/user-attachments/files/21385639/INTERNSHIP_MINI_PROJECT.pdf)

# Vedio
https://github.com/user-attachments/assets/e975b183-cc9f-497c-a1a7-74290a4ca269

# Report
[Movie_Recommendation_System_Report_Final.pdf](https://github.com/user-attachments/files/21385679/Movie_Recommendation_System_Report_Final.pdf)



