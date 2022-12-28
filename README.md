# Name-Entity-Recognition-NER-with-sentiment

In this project, posts are extracted from investing subreddit using reddit API. 
NER is done to extract name of different organisation. 
Sentiment analysis is done on these posts and overall investor sentiment for different
organisations is computed


Project contains different notebooks in which following tasks are done

Notebook 1 - extracting data from reddit api by using user defined reddit class

Notebook 2 - using spacy NER model to tag different posts with name of organisations discussed in them

Notebook 3 - applying basic sentiment analysis to our data using a pre-built distilBERT model from the Flair library. 
We then use our organization labels captured through NER in the previous notebook to 
create a list of organizations with the highest and lowest average sentiment scores

Notebook 4 - performing NER with prebuilt roBERTa transformer model and comparing it with spacy NER model.
As expected transformer model outperforms the spacy model
