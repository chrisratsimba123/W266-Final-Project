# Binning Reviews - Sentiment Analysis on TripAdvisor Reviews

## Proposal 
The objective of this project is to conduct analysis on a dataset of 148k TripAdvisor reviews and answer two questions: (1) Can text elements from a user review be leveraged to predict their eventual rating? And (2) can aspect-based sentiment analysis be conducted to build a classifier model that distinguishes a good hotel from a bad one. Outside of our motivating questions, the main aim is to determine the effectiveness of various algorithms in predicting review scores based on text reviews. The study will utilize popular deep learning algorithms, including Naive Bayes Classifiers, CNN, and Long Short-Term Memory. After preliminary results are drawn, a special focus will be drawn on using the BERT model to see how it stacks up compared to other models in achieving this task. Current implementations of the BERT model on the TripAdvisors dataset have shown improved accuracy in sentiment classification tasks across both training and test sets.
TripAdvisor is a prominent platform for travel reviews which has achieved success namely through its effective use of user-generated content to connect users, advertisers, hotels, restaurants and other partners in the travel industry. This sample dataset offers a chance to dive into the psyche of their engine, and to apply classification tools studied in W266.
Categorizing text into 5 bins is a type of task we have looked at throughout this course. Outside of text categorization, we aim to conduct information retrieval - that is, identifying the most relevant parts of each text review in determining the user’s final rating. This specific dataset does present challenges such as the use of specific place/people names, non-English languages being used in some reviews, and differences in length. More generally, the large number of types of venues and experiences being described might make sentiment analysis trickier, but perhaps this challenge will not exist in the computer’s mind.

## Dataset
https://www.kaggle.com/datasets/arnabchaki/tripadvisor-reviews-2023

## References
Brown, T. B., Mann, B., Ryder, N., Subbiah, M., Kaplan, J., Dhariwal, P., ... & Amodei, D. (2021). Language models are few-shot learners. https://arxiv.org/pdf/2305.13654.pdf
F. Sun, N. Chu and X. Du, "Sentiment Analysis of Hotel Reviews Based on Deep Learning," 2020 International Conference on Robots & Intelligent System (ICRIS), Sanya, China, 2020, pp. 627-630, doi: 10.1109/ICRIS52159.2020.00158.
Kim, Y. (2014). Convolutional neural networks for sentence classification. https://arxiv.org/pdf/1408.5882.pdf
Pennington, J., Socher, R., & Manning, C. D. (2014). Glove: Global vectors for word representation. Proceedings of the 2014 conference on empirical methods in natural language processing (EMNLP), 1532-1543. https://arxiv.org/pdf/1510.03820.pdf
