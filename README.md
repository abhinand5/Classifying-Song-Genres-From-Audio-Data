# Classifying-Song-Genres-From-Audio-Data
This project uses Machine Learning Techniques in Python to classify songs based on genre. 

Using a dataset comprised of songs of two music genres (Hip-Hop and Rock), I trained a classifier to distinguish between the two genres based only on track information derived from [Echonest](http://the.echonest.com/) (now part of Spotify). Made use of pandas and seaborn packages in Python for subsetting the data, aggregating information, and creating plots when exploring the data for obvious trends or factors we should be aware of when doing machine learning. 

Next, I used the scikit-learn package to predict whether I can correctly classify a song's genre based on features such as danceability, energy, acousticness, tempo, etc. I went over implementations of common algorithms such as PCA, logistic regression and decision trees. Found that my model was biased because of skewed training and test samples which I solved by standard resampling. Although balancing removed bias it had a significant hit on the performance plummetting it down by about 5%. Achieved a final accuracy of 72.4% for Decision Tree and 77.5% for Logistic Regression. 

You can open the [notebook.ipynb](https://github.com/abhinand5/Classifying-Song-Genres-From-Audio-Data/blob/master/notebook.ipynb) file to have a look at the code.
