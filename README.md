# Flair-tag-prediction
Approach to solve the Problem-
Scrap data from reddit using the reddit Praw API
Perform EDA on it and Understand data
Clean Data
Vectorize Data using Bag of Vectors and TFIDF
Build Models using ML models
Save the vectorizer weights and model weights

How to reproduce the results-
Run the Download+EDA.ipynb notebook
It will download the Data and put it into a .csv file
After that run the Models.ipynb notebook
It will dump the vectorizer and model into .pkl files
If you want to make it retrainable, just download it as .py file

Deployment--
The Models.ipynb dumps two pickle files
app.py uses these two .pkl files to predict new results
To learn how to productionize the model, use this link: https://www.youtube.com/watch?v=1umQhC2iWdY&t=536s
