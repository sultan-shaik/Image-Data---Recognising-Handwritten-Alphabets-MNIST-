# Image-Data---Recognising-Handwritten-Alphabets-MNIST-
 Recognising Handwritten Alphabets MNIST dataset
# MNIST Handwritten Alphabets Recognition

This repository contains code for recognizing handwritten alphabets using the MNIST dataset. The MNIST dataset consists of a large collection of grayscale images of handwritten digits. This project focuses on building a machine learning model to classify these images into their corresponding alphabets.

## Project Overview

- **Data**: The MNIST dataset includes 28x28 pixel images of handwritten alphabets (A-Z).
- **Preprocessing**: Images are normalized and reshaped for model input.
- **Model**: A convolutional neural network (CNN) is used for classification.
- **Training**: The model is trained on the MNIST dataset.
- **Evaluation**: Classification report provides precision, recall, and f1-score for each alphabet.
- **Results**: The model achieves an accuracy of 88% on the test set.

## Usage

1. Clone the repository: `git clone https://github.com/yourusername/mnist-handwritten-alphabets.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Run `python main.py` to train and evaluate the model.
4. Check the classification report for precision, recall, and f1-score per alphabet.

## Results

Classification Report:
```


| Algorithm                | Accuracy   | Precision  | F1-Score   |
|--------------------------|------------|------------|------------|
| RandomForestClassifier   | 97.65%     | 98.00%     | 97.65%     |
| DecisionTreeClassifier   | 92.87%     | 92.87%     | 92.87%     |
| GBDTClassifier           | 89.62%     | 90.00%     | 90.00%     |
| KNNClassifier            | 58.23%     | 65.00%     | 56.00%     |
| AdaBoostClassifier       | 53.75%     | 54.00%     | 53.00%     |
| LogisticRegression      | 35.63%     | 35.00%     | 35.63%     |

![image](https://github.com/sultan-shaik/Image-Data---Recognising-Handwritten-Alphabets-MNIST-/assets/120010630/4f6a0ced-6b84-4436-b7b8-ac60bdd862f0)

Conclusions
Given Dataset has imbalance Data, Alphabets like ‘O’ and ‘S’ are having major Percentage of Data
GBDT Classifier is taking too much time to train the model whereas KNN Classifier is taking much time in predicting the data
Good Performers: Random Forest Classifier, Decision tree classifier, and GBDT classifier
Bad Performers: KNN classifier, ADA boost Classifier, and Logistic Regression
Best Algorithm: Random Forest classifier at 97.6% accuracy

## Credits

This project is based on the MNIST dataset and was implemented by [shaik sultam](https://github.com/sultan-shaik).



Feel free to contribute and improve the model's performance or explore different aspects of the dataset!
