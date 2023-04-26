# Depression-Detection

## Dataset Path : 
1. Labeled data - Depression-Detection/Dataset/depression_dataset_reddit_cleaned.csv
2. Unlabeled data - Depression-Detection/Dataset/Scraped Datasets/merged_dataset.csv

## SSL+SklearnClassifier+Explainability.ipynb
1. Shows comparision between supervised and semi-supervised learning on various machine learning models like:-
* SGD
* Naive Bayes
* KNN
* Random Forest
* Perceptron
* SVC
2. Further we have perform local and global explainability using LIME and SHAPLEY respectively

## Deep Models
1. The folder contains three files:-
* NN_w2v.ipynb - showing neural network performance between supervised and semi-supervised learning having Word2Vec embedding
* NN_BERT.ipynb - showing neural network performance between supervised and semi-supervised learning having BERT Sentence embedding
* GRU_w2v.ipynb - showing Gated Rectified Units performance between supervised and semi-supervised learning having Word2Vec embedding

## Explainability-Shapley-Deep-Models.ipynb
1. The code includes a neural network made with keras and tfidf vectorisation. We then use this model with Shap to provide global explanation.

## Scraping.ipynb
1. Script we used to scrape the unlabelled data
