# RECOMMENDATION-SYSTEM

*COMPANY* : CODTECH IT SOLUTIONS

*NAME* : AERPULA PRADEEP KUMAR

*INTERN ID* : CTIS8911

*DOMAIN* : MACHINE LEARNING

*DURATION* : 4 WEEKS (23 APRIL 2026 - 21 MAY 2026)

*MENTOR* : NEELA SANTHOSH KUMAR

## Description

In this task, I built a Book Recommendation System using Collaborative Filtering technique. The system recommends books to users based on the reading preferences and ratings given by similar users.

The dataset contains book ratings given by 5 users named Arjun, Priya, Ravi, Sneha, and Kiran for 5 different books. Each user rated some books on a scale of 1 to 5. The goal is to recommend unread books to a target user based on what similar users liked.

I used Cosine Similarity to find how similar each user is to other users based on their ratings. Users with higher similarity scores have similar reading preferences. Then I used weighted average of ratings from similar users to predict scores for unread books.

For example, Arjun has already read Alchemist, Ikigai, and AtomicHabits. The system predicted that Arjun would rate RichDadPoorDad as 4.72 stars and Wings as 4.31 stars. So RichDadPoorDad was the top recommendation for Arjun.

The model was also evaluated using RMSE score which measures how far the predicted ratings are from actual ratings. Lower RMSE means better predictions.

This task helped me understand how recommendation systems work in real world applications like Netflix, Amazon, and Spotify where personalized suggestions are made based on user behaviour and preferences.

Tools used in this task are Python, Pandas, NumPy, Scikit-learn, Cosine Similarity, and Google Colab.

The output of this task is a Jupyter Notebook showing the rating matrix, similarity scores, predicted ratings, book recommendations, and RMSE evaluation.

#output

<img width="398" height="744" alt="Image" src="https://github.com/user-attachments/assets/c7ebad0e-66c0-4e9e-a801-d79c6c30bdd5" />
