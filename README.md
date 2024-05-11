# SmsSpamDetection
IF-102 semester Project



Introduction

The project aims to develop a machine learning model for detecting spam SMS messages. The model is trained on a dataset of SMS messages labeled as either spam or non-spam. The goal is to achieve high accuracy in classifying new, unseen SMS messages as either spam or non-spam.

Dataset Description

The dataset used for this project consists of two files: a CSV file containing the SMS messages and their corresponding labels, and a Jupyter Notebook file for training and testing the model. The CSV file contains 5,169 SMS messages, with 653 labeled as spam and 4,516 labeled as non-spam.

 



Data Preprocessing

The preprocessing step involves cleaning and normalizing the SMS messages. This includes removing punctuation, converting all text to lowercase, and removing any special characters. The dataset is then split into training and testing sets, with 80% of the data used for training and 20% for testing.
 

Model Building

The model used for this project is a Multinomial Naive Bayes (MNB) classifier. This classifier is well-suited for text classification tasks due to its ability to handle high-dimensional data and its simplicity. The MNB classifier is trained on the training set and evaluated on the testing set.
  

Evaluation and Results

The accuracy of the model is evaluated using the testing set. The results show that the model achieves an accuracy of 97.7%. This indicates that the model is highly effective in classifying SMS messages as either spam or non-spam.
  

Conclusion

In conclusion, this project demonstrates the effectiveness of machine learning in detecting spam SMS messages. The Multinomial Naive Bayes classifier achieves an accuracy of 97.7% on the testing set, indicating that it is highly effective in classifying SMS messages as either spam or non-spam. This project highlights the importance of data preprocessing and the selection of the right machine learning algorithm for a specific task.

Future Work

Future work could involve expanding the dataset to include more SMS messages and exploring other machine learning algorithms to see if they can achieve even higher accuracy. Additionally, the model could be fine-tuned by adjusting the hyperparameters to optimize its performance.

Appendices
 Dataset: Spam SMS Collection.csv
 Code: Spam SMS Detection.ipynb


