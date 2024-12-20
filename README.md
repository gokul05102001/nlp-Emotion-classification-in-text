# Emotion Classification in Text

A Machine Learning Approach
## Objective
The project aims to classify emotions in text samples using machine learning techniques.

## Workflow
1. Loading and Preprocessing (3 marks)
Objective: Clean and prepare text data for feature extraction and model development.

### Steps:

#### Text Cleaning: Remove unnecessary characters, punctuation, and lowercase all text.
#### Tokenization: Split text into individual words or tokens.
Stopwords Removal: Eliminate common words (e.g., “the”, “is”) that do not contribute to emotion classification.
Impact on Performance:
Text preprocessing ensures that the input data is clean and consistent, leading to better feature extraction and improved model accuracy.
Removing stopwords reduces dimensionality and noise, enhancing model generalization.
## 2. Feature Extraction (2 marks)
#### Objective: Convert textual data into numerical representations.

### Techniques Used:

#### TfidfVectorizer: Transforms text into Term Frequency-Inverse Document Frequency (TF-IDF) features.
Description:
TF-IDF measures how important a word is relative to a document and the entire dataset. It provides normalized numerical weights, ensuring that frequently occurring but less informative words have lower scores.

### Output:
The processed text is converted into a feature matrix for training machine learning models.

## 3. Model Development (2 marks)
Objective: Train machine learning models for emotion classification.

#### Models Implemented:
Naive Bayes (MultinomialNB):
Support Vector Machine (SVM):


## 4. Model Comparison (2 marks)
Metrics Used:

#### Accuracy: Measures the percentage of correct predictions.
#### F1-score: Combines precision and recall for a balanced evaluation.
Model Comparison:

Metric	
Naive Bayes             :   Accuracy	91%	    F1-Score	91
Support Vector Machine  :  Accuracy	95%	    F1-Score	95

Conclusion:

 the SVM model have higher accuracy and F1 score than  the Naive Bayes model , suggesting it is better at understanding and classifying emotions in text data. This means that for tasks like identifying feelings expressed in writing, SVM may be a more reliable choice than Naive Bayes based on these results.
