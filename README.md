Claat Document : https://codelabs-preview.appspot.com/?file_id=18WLcxWBdVEqO-dMcvrffmENybG-OnntUDcsJ0fdQzKQ#3

Heroku Link : https://datadooclassifier.herokuapp.com/

Youtube Link : https://youtu.be/8qFAVImDW1A

Steps : 

1. Read training and validation data : 
    https://raw.githubusercontent.com/rasbt/musicmood/master/dataset/training/train_lyrics_1000.csv
    https://github.com/rasbt/musicmood/blob/master/dataset/validation/valid_lyrics_200.csv
2. Perform Naive Bayes Data modelling along with Count and TFIDF vectorizer.
3. Calculate Accuracy , F1 score and Precision on training and valid lyrics
4. Scrape Data from https://www.musixmatch.com/explore
5. Predict mood of top-K songs using the Final classifier
6. Use Flask : a micro web framework written in Python to build the web application
7. Hosted the web app on Heroku

Using the app:

1. Go to the link : https://datadooclassifier.herokuapp.com/
2. Enter the number of songs you want to predict and Click on Predict 
3. A responsive page with all the songs with the mood prediction is displayed along with the probability
