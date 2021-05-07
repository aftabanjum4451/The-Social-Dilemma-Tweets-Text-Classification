# The-Social-Dilemma-Tweets---Text-Classification
Machine Learning and NLP: Text Classification using python, scikit-learn and NLTK
## Dataset
(https://www.kaggle.com/kaushiksuresh147/the-social-dilemma-tweets)

## Libraries Needed
- sklearn
- numpy
- pandas
- matplotlib
- seaborn
- nltk
- keras
- imblearn

### Required Embedding 
- Glove pre-trained(840B tokens, 2.2M vocab, 300d vectors)

### Project highlights
- Data anlysis & data cleanning 
- Bidirectional LSTM
- Handling Data Imbalance  
- SMOTE Overlamping 

## Description of Project1
I initiated this project with data pre-processing which included: stemming, stop words and punctuation removal. After that, I  performed some data analysis to analyse the data, due to which, we could see that the dataset had in-balance class distribution. In my first project, however, I had not handled in-balance class distribution problem before. After this, I used the pre-trained glove embedding to convert the text into high dimensional numeric vectors, where the words align in the vector space and the words with similar context gather in close positions in the high dimensional space. Then, I designed and applied the LSTM models and got the predictions and calculated the accuracy score. At the end, I created the classification matric in order to check the performance of the model.
## Description of Project2
In project2, I executed the same steps that I had performed in project1; the only difference is that after data pre-processing, I applied the SMOTE techniques in order to handle data imbalance. Then, for model evaluation, I used LSTM with glove embedding as mentioned in project1.

## How to Run The Code
All the code and comments are listed in the jupyter notbook (in The Social dilemma tweets classification.ipynb)


