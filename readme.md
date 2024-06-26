# Twitter Account Classification Project

This project is part of the CSIT946 course, focusing on processing text data to classify Twitter accounts. The goal is to distinguish between human and non-human accounts using machine learning techniques. Note that the model is considered as a vanilla approach only, served as a baseline for future development of more complex models.

## Project Overview

- **Data Preprocessing**: Implemented stratified splitting to preserve the original distribution of Twitter account types.
- **Modeling**: Used a bag of words model coupled with logistic regression to classify accounts.
- **Text Preprocessing**: Developed a custom `cleanTweet` function to preprocess text data, ensuring optimal input quality for model training.
- **Analysis**: Analyzed and presented key findings on distinctive keywords associated with human and non-human Twitter accounts.
- **Model Optimization**: Fine-tuned the logistic regression model to enhance performance metrics.

## Performance Summary

- **Class 0 (Human)**: Precision - 83%, Recall - 93%, F1-Score - 0.88
- **Class 1 (Non-Human)**: Precision - 80%, Recall - 59%, F1-Score - 0.68
- **Overall Accuracy**: 83%

### Limitations

1. **Simple Feature Extraction**: Uses a basic bag of words approach.
2. **Imbalanced Recall**: Lower recall for non-human classification.
3. **Data Limitations**: Limited ground truth for accurate classification.

### Suggestions for Improvement

1. **Advanced Feature Extraction**: Implement TF-IDF or word embeddings.
2. **Enhanced Model Techniques**: Explore other machine learning models or deep learning approaches.
3. **Increase Training Data**: Collect more labeled data to improve the model's learning capability.

## Installation: 
Clone the repository and install the required libraries.

## Built with:
![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)
![Pandas](https://img.shields.io/badge/pandas-150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Sci](https://img.shields.io/badge/scikitlearn-F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)

## Dependencies
This project requires the following Python libraries:
- pandas
- numpy
- scikit-learn
- nltk
- matplotlib
- wordcloud

## Usage
- **Data Preprocessing**: Ensure the dataset is clean and split into training and test sets.
- **Model Training**: Train the logistic regression model using the preprocessed data.
- **Evaluation**: Evaluate the model performance using accuracy, precision, recall, and F1-score metrics.
- **Analysis**: Analyze the results and present key findings.

## Restriction
This project is part of the CSIT946 subject at UoW. The code is provided for educational purposes and demonstration use only. 

## Disclaimer
This code is provided "as is" without warranty of any kind, and I, as the author, am not liable for any issues that arise from its use. While you're welcome to learn from it, please do not copy or distribute it for your own coursework or assignments without permission.

