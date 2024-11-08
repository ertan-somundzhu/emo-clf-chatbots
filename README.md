# emo-clf-chatbots
This is one of my NLP pet projects. It classifies messages written in English based on the expressed emotion (sadness, joy, love, anger, fear, and suprise). It may be useful for some chatbots to identify emotions of the person who uses it.

This project uses 2 ML models for this:
  1) Logit Regression (multinominal regression)

     Accuracy on training data = 0.9166363436431614

     Accuracy on testing data = 0.8924989803507594
  2) Stochastic Gradient Descent Classifier (with solver set to "hinge" which gives a linear SVM)

     Accuracy on training data = 0.9276006157906311

     Accuracy on testing data = 0.8923670257431443

Libraries used: Pandas, NLTK, Re, Joblib, and Scikit-learn.

Dataset on which the models were trained: 
  1) Emotions (text.csv) (https://www.kaggle.com/datasets/nelgiriyewithana/emotions)



P.S. You could use the code, but the training data isn't mine, so you'll have to look up licences of these datasets.
