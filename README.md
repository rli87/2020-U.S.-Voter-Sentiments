# 2020 U.S. Voter Sentiments
 In this research, I attempt to discuss how voter sentiment and Twitter language differ for different political stances and political topics. To accomplish this goal, I use machine learning and text analysis methods to study voter sentiments and political leanings from a sample of tweets from Oct 15, 2020 -Nov 8, 2020, a roughly two-week time period just before the 2020 U.S. Election date Nov 3, plus another week after the results of the election are announced.

 ## Replication Instructions

1. Data: the data has about 1 million tweets, so obviously it is not feasible to push it to GitHub. Under approval of course instructors, I only uploaded the hand-labeled dataset into the repository.

2. Code: The 'project2_code.ipynb' file is divided into FIVE main sections. 
The first section cleans the tweets by dropping tweets not in English and not sent by users labeled with a U.S. location. It is also cleaned using NLTK's stop words and lemmatization library. Each document is futher tokenized and formed to clean corpus.
The second section produces a set of summary statistics with the help of directions and inspiration of this [guide](https://www.kaggle.com/code/mishki/twitter-sentiment-analysis-using-nlp-techniques#notebook-container), such as forming maps and probability density distributions.
The third section tries to tackle with the pre-labeled political stance and produce a word dictionary to classify the political stance of the main data of interest using the multinomial logit regression.
The fourth section uses LDA to conduct topic-modeling, with a self-selected topic size of 20.
The final section applies [roBERTA](https://github.com/cardiffnlp/tweeteval), a pre-trained sentiment analysis algorithm on tweets, in categories of previously identified political stance and political topics

## Research paper
See the pdf file for final reports.
