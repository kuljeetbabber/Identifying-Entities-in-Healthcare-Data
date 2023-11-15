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

### Methodology

To accomplish the tasks, the following methodology was followed:

- **Data Preprocessing:**
  - Utilized Python and pandas for constructing sentences and handling blank lines.
  - Checked the correctness of sentences and label counts.

- **Concept Identification:**
  - Implemented PoS tagging using spaCy to identify nouns and proper nouns.
  - Created a dictionary of concept counts and outputted the top 25.

- **Defining Features for CRF:**
  - Defined features considering PoS tags and preceding words.

- **Getting Features and Labels of Sentences:**
  - Coded functions to extract features and labels for sentences.

- **Defining Input and Target Variables:**
  - Extracted features and labels for both test and train datasets.

- **Building the Model:**
  - Utilized scikit-learn to build a CRF model.

- **Evaluation:**
  - Predicted labels for test dataset tokens and calculated F1 score.

- **Identifying Diseases and Treatment using Custom NER:**
  - Created logic to map diseases to their probable treatments.

### Findings

Upon completing the tasks, the following findings were observed:

- Successful construction of sentences from token format.
- Identification of top concepts using PoS tagging.
- Effective definition and application of features for CRF.
- Successful extraction of features and labels for model building.
- CRF model demonstrated on the test dataset.
- Creation of a logic to map diseases to their probable treatments.

## Contributor
- [Kuljeet Babber](https://github.com/kuljeetbabber)

