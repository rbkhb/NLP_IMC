-------
## AU Interacting Minds Centre, NLP Workshop - November 7th 

**Stance Detection & Topic Modelling of Social Media Users' Content**  

*Rebekah Baglini, Luca Nannini, and Arnault-Quentin Vermillet*



![alt text](https://docs.google.com/drawings/d/e/2PACX-1vTRkUtZJSFMxPWXaidljOqwNDnFTLb4E3GWB6AsqVfcWdYKsI4y9f8EaCz2yozWRe4I8vnvePngC-TM/pub?w=1393&h=614)


### Program

1. Data Preprocessing 
 - Load Dataset 
 - Tokenization/Stopword Removal
 - Clean Tweets Strings with Regular Expressions
 - Lemmatization/Stemming

2. Topic modeling
 - Create, Run, and Train the HDP model via Gensim 
 - Visualize topics through an interactive graphs - pyLDAvis 
 - Visualize cosine metrics of topics as a heatmap  
 - HDP and LDA via Gensim Models

 3. Supervised text classification with BERT

### Datasets

Vacc_tweets_raw_n5000.csv
  * Random sample of 5000 (out of > 1 million) tweets from 2019 containing string 'vaccin'
  * Collected using [GetOldTweets3 scraper](https://github.com/Jefferson-Henrique/GetOldTweets-python)

#### Additional sets in Data folder 
5-topic_stance_tweets_training_n2814.csv
  * Training set from [SemEval2016 Task 6](http://alt.qcri.org/semeval2016/task6/) for stance detection task
  * Labels: FAVOR, AGAINST, UNKNOWN
  * Topics: 
    - Atheism
    - Climate change is a concern
    - Feminist movement
    - Hillary Clinton
    - Legalization of abortion

Vacc_articles_w_stance_n3303.csv
  * From [Vaccine sentiment project](https://github.com/gloriakang/vax-sentiment), contains 3303 sentences extracted from online articles labelled pro (n=24), neg (n=22), and neu(tral) (n=7).

Vacc_tweets_w_stance_n1131.csv
* 1131 tweets containing string 'vaccin' labeled for stance
* Labels = pro, anti, unknown

**Or upload your own dataset!**
* Using the upload widget in the Colab file. 

### **Code files**
* During the tutorial, we will be working from a Google Colab notebook. This means you will not have to install or load anything locally. 
* If you'd like to run locally, we've included list of dependencies in Requirements.txt

