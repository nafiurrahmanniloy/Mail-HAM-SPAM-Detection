# Mail-HAM-SPAM-Detection

## Overview
This project demonstrates an email classification system to detect spam and ham (non-spam) emails. Using the Bag-of-Words (BoW) model and machine learning techniques, the system analyzes email content to classify messages accurately.

## Features
- Preprocessing of email data (removal of stop words, tokenization, etc.)
- Implementation of the Bag-of-Words (BoW) model for feature extraction
- Training and evaluation of machine learning classifiers
- Performance metrics for assessing model accuracy

## Dataset
The project uses the `spam.csv` dataset, which contains labeled email messages:
- **ham**: Legitimate emails
- **spam**: Unsolicited or junk emails

### Dataset Format
- `v1`: Labels (ham/spam)
- `v2`: Email content

### Source
The dataset is included in the repository as `spam.csv`.

## Usage
1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
2. Load the `Bag_of_words(BOW).ipynb` or `Bag_of_words(BOW)-checkpoint.ipynb` file.
3. Run the cells to:
   - Load and preprocess the dataset
   - Extract features using the BoW model
   - Train and evaluate the classifier

## Results
The notebook provides:
- Confusion matrix
- Accuracy, precision, recall, and F1-score

### Model Accuracy
The achieved accuracy is approximately **98.9% to 99%**.



