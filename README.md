# ReviewScorePrediction
Review score prediction using machine learning

Here we use machine learning to predict the resulting score (either negative (1-2 stars), neutral (3 stars) or positive (4-5 stars)) given by a person to a product based on the review they wrote.

In particular, we use two deep learning models: a neural network and a convolutional neural network.

Additionally, we made word clouds of each class of reviews to help easily visualize the differences between each class.

RESULTS:

In the case of book reviews, both the neural network and the convolutional neural network had an accuracy of 58%, and the confusion matrix of both shows that when the prediction of truly positive or negative reviews failed, the most frequent prediction was a neutral review, that is, when the prediction fails, its estimation is not so far from reality.

As for the vacuum cleaner reviews, the neural network had an accuracy of 65% and the convolutional neural network 74%. From the confusion matrices it can be seen that the models almost never predict a review to be neutral. However, since there were very few neutral reviews, this did not affect the accuracy value as much. We conclude that it is necessary to obtain more neutral reviews, as they are the most difficult to classify due to their ambiguity as we observed in the word cloud, we also conclude that the type of product greatly influences the recurring words in the reviews, and that the way people write can affect the data processing quite a lot, so careful cleaning is necessary.

Made in collaboration with Alexia Elizabeth Pérez Echeverría. 

Based on the algorithm by Adriana Alejandra Pérez Echeverría and Iván Roberto Rojas
González for the classification of texts by Edgar Allan Poe, Mary Shelley and HP Lovecraft:
https://colab.research.google.com/drive/1pop81tKwZu8XjDpWZdGE2b3XavcqpxYe
