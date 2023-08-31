# Financial Sentiment Analysis Project

This initiative focuses on discerning the mood of financial news pieces through advanced techniques in natural language processing and machine learning. Our exploration will delve into various text data representations, including TF-IDF, the use of Google News' pre-trained Word2Vec features, and Doc2Vec. The efficiency of classifiers like SVM, KNN, and Random Forest will be assessed, with hyperparameters being refined through cross-validation.

## Data

The project leverages a dataset of financial news articles aggregated from multiple outlets. This data is publicly accessible and can be retrieved from https://www.kaggle.com/datasets/ankurzing/sentiment-analysis-for-financial-news. 

## Data Preprocessing

Prior to model training, the data must be refined. This involves steps such as excluding common words, stemming, and translating the textual information into numeric vectors.

## Feature Representation

Our exploration will be rooted in three distinct methods to represent textual data:

1. TF-IDF: Through TF-IDF, we'll transform textual data into numerical arrays. To understand the distinction between various mood categories, we'll apply PCA and t-SNE for visualization.

2. Google News Pre-trained Word2Vec: Leveraging pre-existing Google News Word2Vec attributes, we'll depict the articles. The efficacy of using both the maximum and average word vectors for each piece will be weighed against each other.

3. Doc2Vec: An additional method we'll be experimenting with to represent articles is Doc2Vec.

## Classification Models

Our approach will incorporate SVM, KNN, and Random Forest classifiers to determine the mood of the financial news pieces. Cross-validation will aid in refining the hyperparameters for these models.

## Results

The effectiveness of each model will be consolidated in a tabulated form, showcasing metrics like accuracy, precision, recall, and the F1-score for every category.

## Conclusion

Throughout this endeavor, we delved into various techniques to represent textual data and juxtaposed the efficacy of diverse classifiers in the domain of financial sentiment assessment. The combination of TF-IDF and Random Forest emerged as the most effective, trailed by Max Word2Vec, Doc2Vec, and subsequently, Average Word2Vec.

## Future work

Pondering the forthcoming advancements in this project, there's a strong case for enhancing these results using sophisticated neural networks, notably Convolution Neural Networks (CNNs) and Transformers. CNNs possess the capability to grasp localized semantics and interlinkages among adjacent words. On the other hand, Transformers employ a self-attention mechanism to simultaneously discern relationships between all input tokens. This empowers them to model enduring dependencies, thereby effectively garnering contextual nuances.
