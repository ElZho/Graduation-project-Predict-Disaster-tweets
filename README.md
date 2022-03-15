# Graduation-project-Predict-Disaster-tweets
I took a Kaggle competition https://www.kaggle.com/c/nlp-getting-started for my project.
I was interesting to understand how transformers works.
I made baseline and then finetine Bert model. I tried differnt Bert models for this task and added one or two fullyconnected layers.\
I have some problem with Large Bert pretrained model with one added layer. Model did not learn. The problem was in learning rate. I \
tried to decreace Lr and had my best result. Moreover I used scheduler to prevent overfitting.
