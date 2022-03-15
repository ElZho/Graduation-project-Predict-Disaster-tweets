# Graduation-project-Predict-Disaster-tweets
I took a Kaggle competition https://www.kaggle.com/c/nlp-getting-started for my project.
I was interesting to understand how transformers works.
I made baseline and then finetine Bert model. I tried differnt Bert models for this task and added one or two fullyconnected layers.\
I have some problem with Large Bert pretrained model with one added layer. Model did not learn. The problem was in learning rate. I \
tried to decreace Lr and had my best result. Moreover I used scheduler to prevent overfitting.
## My plan of works:
1. Upload files from Kaggle
2. Merge data into one dataset to make analyses und cleaning easier.
3. Find duplicates in tweets, analyse and remove or leave.
4. Clean tweets from simbols
5. Analyse data
6. Make Bert model und results analyse.
