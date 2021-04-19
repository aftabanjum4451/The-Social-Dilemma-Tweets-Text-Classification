#IMDb-Movie-Review-Sentiment-analysis
Machine Learning and NLP: Text Classification using python, scikit-learn and NLTK
## Dataset
(https://www.kaggle.com/kaushiksuresh147/the-social-dilemma-tweets)

##Libraries Needed
- sklearn
- numpy
- pandas
- matplotlib
- seaborn
- nltk
- keras
- imblearn

### Required Embedding 
-Glove pre-trained(840B tokens, 2.2M vocab, 300d vectors)


## Description of Project1
In this work i have done pre-processing including, stemming, stop words and punctuation removal. After that i have performed some data analysis to analysis the data, after the data analysis, we can see that the dataset has in-balance classes distribution. In my first project I did implement any data imbalance techniques. After the data-pre-processing I used the pre-trained glove embedding to convert the text into high dimensional numeric vectors. Where the words are aligned in the vector space and puts the words that have similar contexts in close positions in a vector space. The I designed and applied the LSTM model and get the predictions and calculate the accuracy score. At the end create the classification matric in order to check the performance of the model.
## Description of Project2
In project2, I execute the same steps that I performed in project1, the only difference is, after data pre-processing, I applied the SMOTE techniques in order to handle data imbalance. Then for model evaluation I used LSTM with glove embedding as mentioned in project1.

## How to Run The Code
All the code and comments are listed the jupyter notbook (in The Social dilemma tweets classification.ipynb)


