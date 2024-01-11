# Sentiment Analysis of Klik Indomaret Reviews on Google Play using Support Vector Machine

## Description
This research focuses on sentiment analysis of user reviews for the "Klik Indomaret" application on Google Play. The study employs text classification using the Support Vector Machine (SVM) algorithm. Furthermore, the author conducts a comparative analysis of SVM kernels, including Linear, Polynomial, Sigmoid, and Radial Basis Function (RBF), to determine the optimal accuracy in text classification. This research using Knowlegde Discovery in Database with the following stage :

### Data Collection:
Gather user reviews for the "Klik Indomaret" application from Google Play. You can check how to do web scrapping in Web Scraping Klik Indomaret notebook. The reviews were collected using the Indonesian language within the time range from February 1 2023 to April 25 2023 (1750 data with 694 negative and 869 positive reviews).

### Data Preprocessing:
There are several stages in this process, including case folding, cleaning, normalization, stopword removal, and transformation. In the normalization process, I create my own file named 'keynormalization.

### Feature Extraction:
Utilize techniques such as TF-IDF (Term Frequency-Inverse Document Frequency) and Bag of Words to convert text data into numerical vectors. Based in this process i separated the code into two different notebooks which is Bag of Words Portofolio dan TF-IDF Portofolio.

### Support Vector Machine:
Implement SVM for sentiment analysis, considering multiple kernel functions: Linear, Polynomial, Sigmoid, and Radial Basis Function (RBF). In the notebook, only one kernel is used. Therefore, if you want to use another kernel, modify in the step 4 which is the Modelling (Machine Learning) with the instructions as follows:
* Linear
kernel="linear", C=1
* Polynomial 
kernel="poly", gamma="scale", C=1, coef0=0.0, degree=3
* Sigmoid
kernel="sigmoid", gamma="scale", C=1, coef0=0.0
* RBF
kernel="rbf", gamma="scale", C=1

Don't forget to customize the training and testing dataset. I use three different ratios for comparison: 70:30, 80:20, and 90:10. 

### Model Evaluation:
Each customization in transformation, kernel selection, and dataset ratio contributes to varied accuracy outcomes. In the conducted research, the Sigmoid with Bag of Words (BoW) and a dataset ratio of 90:10, demonstrates the highest accuracy which is 92%, with precision of 89%, recall of 96%, and an F1-score of 92%. In contrast, the lowest accuracy is observed with the Polynomial kernel at a dataset ratio of 80:20, with Bag of Word for feature extraction, resulting in an accuracy of 64%, precision of 60%, recall of 98%, and an F1-Score of 75%."

## Contact
[![Email](https://img.shields.io/badge/Here-My%20Email-brightgreen?style=for-the-badge&logo=appveyor)](https://www.example.com)
[![LinkedIn](https://img.shields.io/badge/Here-My%20LinkedIn-brightgreen?style=for-the-badge&logo=appveyor)](https://www.example.com)

