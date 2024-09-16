In this code, I try to predict the rating of a corresponding review based on the text's features. First, I use BERT to embed each review text.
After that, I find each review's similar reviews to build a graph. I connect each review to 8 most similar reviews that is in the dataset, and then a graph is constructed.
Finally, I use graph neural networks to predict the rating of each review based on the similarity graph that has been created.
