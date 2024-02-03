# Rails Issue Analyzer

## Project Overview

This project aims to classify issues from the Ruby on Rails GitHub repository into their respective labels automatically. Utilizing Hugging Face's transformers, we developed a machine learning model to analyze issue descriptions and predict appropriate labels, aiding maintainers in categorizing and prioritizing issues more efficiently.

## Key Features

- **Automatic Issue Classification**: Leverages NLP techniques to understand and categorize issue descriptions.
- **Data Analysis**: Includes a comprehensive analysis of issue trends, common labels, and contributor activity.
- **Model Evaluation**: Detailed evaluation of the model's performance, including accuracy, precision, recall, and F1 score.

The model was trained on a dataset derived from the Rails GitHub issues, split into training and validation sets. The evaluation metrics post-training are as follows:

Accuracy: 33%
Precision: 14%
Recall: 12%
F1 Score: 8%
These results indicate areas for improvement, particularly in enhancing the model's precision and recall. Future work will focus on refining the model through advanced NLP techniques, data augmentation, and hyperparameter optimization.


