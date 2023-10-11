# Spam-Detection

## Overview

This repository presents a Spam Detection project with the following key findings:

- Achieved 99% precision and 94% recall with the final model based on Pipeline3.
- Implemented a Spam Detection model using TF-IDF Vectorization and Feature Engineering.

## Project Details

### Load the Dataset
- Utilized the Kaggle spam dataset, available [here](<dataset-link>).
- Loaded the data into a Pandas DataFrame.
- Renamed columns to 'label' and 'message'.
- Determined the percentage of 'ham' and 'spam' messages in the dataset.

### Metric for Evaluating Model
- Recognized the highly imbalanced data nature.
- Selected an appropriate evaluation metric, avoiding the accuracy trap.
- Chose a metric that aligns with the imbalance, providing a more meaningful evaluation.

### Classification Pipelines
- Explored various methods to create features, including:
  - Sparse Embeddings (TF-IDF)
  - Feature Engineering
  - Sparse Embeddings (TF-IDF) + Feature Engineering
- Conducted analysis on smaller dataset subsets.
- Based on analysis (model score, learning curves), selected the most suitable pipeline.
- Applied hyperparameter tuning for imbalanced dataset.
- Considered a range of feature engineering options.

## Model Performance

### Classification Report Inference
- Achieved a high level of precision and recall:
  - 'ham' class precision: 99%
  - 'spam' class precision: 96%
  - 'ham' class recall: 99%
  - 'spam' class recall: 94%
- High F1-scores, particularly for 'ham' (99%) and 'spam' (95%) classes.

### Final Inference
- The model performed exceptionally well on the test data.
- The chosen final model is based on Pipeline3 (Sparse Embeddings + Feature Engineering).

## Conclusion

This Spam Detection project showcases robust model performance, emphasizing the importance of an appropriate evaluation metric in handling imbalanced datasets.
