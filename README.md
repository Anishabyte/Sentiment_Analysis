# Sentiment_Analysis

📌 Plan of Action
* Load IMDb Movie Review dataset(50000 reviews)
 "/content/drive/MyDrive/a1_IMDB_Dataset.csv"
* Preprocess dataset by removing special characters numbers etc from user
* review and convert sentiment labels positive negative to number 0 &1 respectively
* Import Glove Word Embedding (glove.6B.100d.txt) to build Embedding Dictionary +use this to build 
* Embedding matrix to your  corpus
* Model Training using Deep Learning in Keras for separate simple Neural Net,CNN and LSTM
* Last perform prediction on real IMDb movie reviews


# 🚀 Models Used
Multiple Deep learning models were implemented and compared to find the best-performing algorithm:

* Neural Network (achieved accuracy at 76%) 
*  Convolutional Neural Network (achieved accuracy at 85% )
* LSTM (achieved highest accuracy at 86%) The LSTM  model was selected as the final model due to its high accuracy and robust performance on test data.

# ⚙️ Key Features
We got the best results from LSTM model with an accuracy of 86% 
After that Performed Model Performance on Unseen IMDB dataset preprocessed the unseen data set and we got the accuracy pretty close to actual IMDB rating .
![image](https://github.com/user-attachments/assets/3f78f08e-fa1b-49be-8bf2-142df1dc6fbf)

# 🛠️ Technologies Used
Python for data manipulation and model training Keras for model building and Preprocessing like Removing Stopwords , HTML tags ,removing Punctuation ,Single character Removal ,Removing multiple spaces 
# 💻 How to Use 
Clone the repository and install dependencies. Run the Flask application. Access the web interface to input car details and get a price prediction. This project highlights skills in machine learning, data preprocessing, model evaluation, and deploying models through a web application.
