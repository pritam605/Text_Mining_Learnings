This project contains data downloaded from Twitter API (V2 Bearer token) for the year 2020-2022.

Project workflow - 
1. Downloading Data from Twitter API (v2 bearer token) and loading text into a pandas data frame.
2. Dropping irrelevant columns
3. Taking out hours, day and year number 
4. Creating context windows based on dates
5. Data Preprocessing (Including Lemmatization)
        a. Emoji 
        b. URL, HTML, 
        c. StopWords, Tokenization, 
        d. Length of words with characters less than 3 removals,        Removing whitespace
6. Dump 1 - Preprocessing pickle file 
7. Gensim preprocessing and lemmatization
8. Dump 2 - Lemmatization
9. id2Word implementation - Word Embedding
10. Dump 3 -  Corpus pickle file.
11. Dump 4 -  id2Word
12. LDA model implementation
13. Getting a perplexity score.
14. Coherence score calculation using the 'u_mass' argument
15. Checking the best number of topics using a coherence score
16. Obtaining 20 as our ideal topic number
17. Dumping optimal topic into a text file
18. Getting dominant topics - for each of the tweets

19. Text Summarization - Reverse tracking of Tweets under each of the Topics obtained
20. Assigning Text and Weight for each of the Tweets & Setting a threshold value to filter summarized tweets.
21. Checking burst keywords using word cloud within the summarized texts for each of the tweets
22. Visualization using pyLDAvis library
23. Sentiment analysis for each topic within our 2 Context window
24. Implementing Word2Vec - CBOW for each of our contextes

