# Bachelor's thesis
# Sentiment analysis based on multifractal methods
***

**Sentiment** analysis is crucial for decision-making in corporate platforms and for users. Traditional techniques face limitations, such as low prediction accuracy, large training datasets, and computational inefficiency. Our work addresses these limitations by applying multifractal methods combined with machine learning techniques, reducing data requirements while preserving accuracy.
The **aim** of this project is to develop algorithmic and software for solving the sentiment analysis problem of user comments based on **multifractal methods** and **machine learning** approaches.
---
The **RuReviews** corpus consisting of approximately 19,000 user reviews of the online women's clothing store was used as input data. Positive and negative emotions were used as labels.  **Embedding methods** are used to represent words as vectors that reflect the unique features of words and the semantic relationship between them. By averaging these vectors in a sentence, one can obtain a vector representation of the sentence that reflects its meaning. 

Using the **multifractal method** (MF-DMA, MF-DFA) will not only reduce the dimension of the vector space, but also highlight the semantic features of the text. The feature vectors of sentences are represented as time series of length N, over which the Hurst exponents for d different values of the averaging coefficient q are calculated, thereby obtaining a time series of d elements for each sentence, where d is much less than N. 

The obtained series of Hurst exponents H(q) are input data for **Random Forest** model for binary classification. As a result, using **the multifractal approach**, a classification accuracy of **93 percent** was obtained, which is 2 percent higher than the accuracy of classification based on the classical approach. It is worth noting that a dataset of 10,000 comments was used to build the system, however, even with a decrease in the amount of data, the proposed approach achieves higher classification accuracy than the classic one.

The project showed that the researched time series have **multifractal properties**, and there is a **clear separation** of the Hurst exponents for positive and negative comments. Thus, this approach solves the problems of neural networks and machine learning, because it is possible to **more accurately** predict text emotions **without extensive data**.
