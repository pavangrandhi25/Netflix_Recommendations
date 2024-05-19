# Netflix Recommendation System
This project implements a content-based recommendation system for Netflix titles using Streamlit. The app recommends similar titles based on the description of a selected Netflix title.

**Overview**
The recommendation system leverages the following components
    TF-IDF Vectorization: To convert the descriptions of Netflix titles into numerical vectors.
    Cosine Similarity: To compute the similarity between these vectors, enabling the recommendation of similar titles.
    Streamlit: To create an interactive web application for users to get recommendations easily.
    
**Features**
    Select a Title: Choose a Netflix title from a drop-down list.
    Number of Recommendations: Specify how many similar titles you want to be recommended.
    Interactive UI: User-friendly interface built with Streamlit.
    
**How It Works**
    Data Loading: The app loads a dataset of Netflix titles from a CSV file.
    TF-IDF Vectorization: The descriptions of the titles are vectorized using TF-IDF, ignoring common English stop words.
    Cosine Similarity Calculation: Similarity scores are calculated between the selected title and all other titles.
    Recommendation Generation: The app generates a list of titles that are most similar to the selected title based on cosine similarity scores

![image](https://github.com/pavangrandhi25/Netflix_Recommendations/assets/144769655/8b7ffac9-176b-4092-9105-5e3c3bfb169f)
