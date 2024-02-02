# CA-02

Building a Spam Detector Using Naive Bayes Algorithm


Synopsis:
This repository contains a Jupyter Notebook for the purpose of the creation of a simple spam detection program that uses Gaussian Naive Bayes Algorithm. The dataset used contains various emails in text format to be further analyzed. 

In this exercise we shall train the model with set of emails labelled as either from Spam or Not Spam. There are 702 emails equally divided into spam and non spam category. Next, we shall test the model on 260 emails. We shall ask model to predict the category of these emails and compare the accuracy with correct classification that we already know.


Dataset: 
The dataset used in this project is test:train-mails.zip which contains 702 various emails in text format presorted as either spam or not spam. 

For this project, I am using two datasets. One for Training and the other for testing. They can be found here:
https://github.com/LanceRoyston/Intro-to-Machine-Learning-BSAN-6070-02/blob/main/CA02%20Spam%20Detector%20Using%20Naive%20Bayes/test%3Atrain-mails.zip


Findings: 
After testing our Naive Bayes algorithm we were able to acheive an accuracy of ~96.5% in successfully classifying an email as spam. We then did further testing by slicing our feature matrix in order to test the model on different word counts. Results proved to be similar with 3000 and 1000 most common words. We then also added a cofusion matrix and classification report so you can see precision and recall. 


Requirements:
Libraries used in the environment to be able to run the code include:

numpy 1.24.3
sklearn 1.3.0

Python Standard Library
os module
collections module


Usage:
To run this notebook-
Clone the repository. Ensure you have Jupyter Notebook installed. If not, install it using: pip install notebook

Instructions on project were given by ArinB:
https://github.com/ArinB


