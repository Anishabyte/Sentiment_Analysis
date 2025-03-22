# Sentiment_Analysis
# Plan of Action
* Load IMDb Movie Review dataset(50000 reviews)
 "/content/drive/MyDrive/a1_IMDB_Dataset.csv"
* Preprocess dataset by removing special characters numbers etc from user
* review and convert sentiment labels positive negative to number 0 &1 respectively
* Import Glove Word Embedding (glove.6B.100d.txt) to build Embedding Dictionary +use this to build 
* Embedding matrix to your  corpus
* Model Training using Deep Learning in Keras for separate simple Neural Net,CNN and LSTM
* Last perform prediction on real IMDb movie reviews

We got the best results from LSTM model with an accuracy of 86% 
other models showed accuracy of 85% for CNN (Convolutional Neural Network ) and 75 % for Feedforward Neural Network .
After that Performed Model Performance on Unseen IMDB dataset preprocessed the unseen data set and we got the accuracy pretty close to actual IMDB rating .
![image](https://github.com/user-attachments/assets/3f78f08e-fa1b-49be-8bf2-142df1dc6fbf)
