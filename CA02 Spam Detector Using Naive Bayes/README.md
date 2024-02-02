CA02
# Building a Spam Detector Using Naive Bayes Algorithm
 
## Overview:
This repository features a Jupyter Notebook implementing a simple spam detection program utilizing the Gaussian Naive Bayes Algorithm. The project involves training the model on a dataset containing 702 emails in text format, equally divided into 2 categories: spam and non-spam, and subsequently testing the model on a set of 260 emails. We will then compare the accuracy with the correct classification.
 
## Datasets:
 
The 2 datasets used in this project is available in the file [test:train-mails.zip](https://github.com/LanceRoyston/Intro-to-Machine-Learning-BSAN-6070-02/blob/main/CA02%20Spam%20Detector%20Using%20Naive%20Bayes/test%3Atrain-mails.zip).
 
Both datasets contain emails in text format, pre-sorted as spam or not spam:
Training: 702 emails
Testing: 260 emails
 
## Requirements:
Please ensure the following libraries are installed in your environment:
 
- `numpy` 1.24.3
- `sklearn` 1.3.0 
- `os`
- `collections`
 
## Usage:
 
To run this notebook:
- Clone the repository.
- Ensure Jupyter Notebook is installed; if not, install it using: `pip install notebook`
 
## Insights:
After testing the Naive Bayes algorithm, the model achieved an accuracy of ~96.5% in distinguishing between spam and non-spam emails. Further experimentation involved slicing the feature matrix to test the model with different word counts -- 3000, 2500, 2000, 1500, and 1000.
The accuracy scores for each configuration:
- 2000 words: 97.31%
- 3000 words: 96.54%
- 2500 words: 96.15%
- 1500 words: 96.15%
- 1000 words: 89.23%
### These results provide insights into the model's performance under different feature matrix compositions, with 2000 words yielding the highest accuracy.
Additionally, a confusion matrix and classification report have been included, providing insights into precision and recall.
 
## Acknowledgment:
This project follows the instructions provided by [ArinB](https://github.com/ArinB).
