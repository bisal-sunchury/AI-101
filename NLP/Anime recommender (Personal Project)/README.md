This project is an AI-powered anime recommendation system that suggests similar anime based on genre and synopsis. It uses natural language processing (NLP) and cosine similarity on TF-IDF vectors to find content most relevant to user preferences.



#### Key Achievements



Built a dataset of 50+ anime with titles, genres, and synopses via the Jikan API (MyAnimeList).



Processed and combined textual features to create rich representations for content similarity.



Implemented real-time recommendations based on user-selected anime titles.



Handled data cleaning, preprocessing, and vectorization for accurate similarity computation.



#### Technical Highlights



Feature Engineering: Combined genres and synopsis into a single textual feature for analysis.



Vectorization: TF-IDF with English stopwords removed to capture meaningful content.



Similarity Computation: Cosine similarity applied to TF-IDF matrix for top-N recommendations.



Libraries \& Tools: Python, Pandas, scikit-learn, Requests, Jikan API.



#### Next Steps / Extensions



Expand dataset to include hundreds or thousands of anime for better recommendations.



Incorporate user ratings or watch history for hybrid recommendations.

