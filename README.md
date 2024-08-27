This repository includes soruce code for both scrapper and sentiment analysis of DAWN News.
In this project data was acquired via scrapping from DAWN News website, which was stored in a .json file. 
After that necessary preprocessing steps were performed, which included: removal of stop words, lemmatization and tokenization. 
After that polarity score of sentences was determined and sentiment analysis was performed. 
For feature selection TF-IDF was used. 
The final step was to determine accuracy of prediction using machine learning models.
Machine Learning models which were used are: Logistic Regression, Naive Bayes, Decision Tree, Random Forest Classifier and Recurrent Neural Networks.
These models were used with a combination of n-grams which also determined how n-grams are useful for accurate model training in NLP.
