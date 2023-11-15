## Problem Statement

This repository contains the assignment details for building a custom Named Entity Recognition (NER) system for extracting diseases and their probable treatments from medical data. The task involves processing datasets, defining features, building a Conditional Random Fields (CRF) model, and creating a dictionary mapping diseases to treatments.

## Dataset

The dataset consists of four files:

- [Train Sentence Dataset]: Contains words that need to be grouped into sentences.
- [Test Sentence Dataset]: Similar to the train dataset, used for model evaluation.
- [Train Label Dataset]: Provides labels ('O', 'D', 'T') corresponding to words in the train sentence dataset.
- [Test Label Dataset]: Labels for the test sentence dataset.

## Assignment Steps

1. **Data Processing:**
    - Combine words in the 'train_sent' and 'test_sent' datasets to form sentences.
    - Identify and handle blank lines to delineate sentences.

2. **Feature Definition:**
    - Understand and define features required for building the CRF model.

3. **Feature Application:**
    - Apply features to each sentence in both train and test datasets to obtain feature values.

4. **CRF Model Building:**
    - Define the target variable.
    - Build a CRF model using the processed data.

5. **Model Evaluation:**
    - Evaluate the CRF model using the test dataset.

6. **Dictionary Creation:**
    - Build a dictionary mapping diseases to their probable treatments.

## Methodology

To solve this assignment, I followed the following methodology:

- **Data Processing:**
    - Utilized Python and pandas to combine words in the 'train_sent' and 'test_sent' datasets, forming coherent sentences.
    - Implemented logic to identify and manage blank lines to create well-structured sentences.

- **Feature Definition:**
    - Studied the dataset and identified key features necessary for training the CRF model.
    - Considered linguistic patterns, word context, and label information to define relevant features.

- **CRF Model Building:**
    - Used the scikit-learn library to build a Conditional Random Fields (CRF) model.
    - Defined the target variable based on labeled data and applied features to train the model.

- **Model Evaluation:**
    - Employed the test dataset to evaluate the performance of the built CRF model.
    - Assessed metrics such as precision, recall, and F1-score to measure the effectiveness of the model.

## Findings

Upon completing the assignment, several findings emerged:

- The CRF model demonstrated on the test dataset, indicating its ability to accurately identify diseases and treatments.
- The dictionary created successfully mapped diseases to their probable treatments, providing a structured output.


## Contributor
- [Kuljeet Babber](https://github.com/kuljeetbabber)

