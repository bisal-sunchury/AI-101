# **Movie Recommender System**



### **Overview**



A simple movie recommendation system using user–item collaborative filtering.

It predicts movies for a user based on their past ratings and the ratings of similar users using cosine similarity.

The system recommends the top 5 movies a user is likely to enjoy.



### **Dataset**



Uses the MovieLens 100K dataset:



u.user → user information (user\_id, age, sex, occupation, zip\_code)



u.data → ratings (user\_id, movie\_id, rating, timestamp)



u.item → movie information (movie\_id, title, release date, IMDb URL, genres)





### **Requirements**



Python 3.x



numpy, pandas, scikit-learn



Install dependencies:



pip install -r requirements.txt





### **Usage**



\- Load the dataset and create the user–item matrix.



\- Compute user and item similarities using cosine similarity.



\- Use the predict() function to generate rating predictions.



\- Recommend top 5 movies per user by filtering out already-rated movies.





