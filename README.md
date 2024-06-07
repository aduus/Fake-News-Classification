Step1: Unzip the dataset file
Step2: Rename the extracted file to unified_dataset.csv
Step3: Run the colab to train models and save model weights

Approach:

This project aims to achiieve the ability to distinguish between a fake news and real news, and also categorize the fake/real news article into its appropriate topic.
The task was broken down into 2 sub problems called Phase 1 and Phase 2, while both phases working on the same dataset.

Dataset:
The dataset has rows of "text" column which are the features while "labels" represent fake/real and 'category' represents whether the article belongs to politics/sports etc

Phase1:
Models are trained on text as X and labels as Y. Best model is picked that performs well on identifying fake vs new.

Phase2:
Models are trained on text as X and category as Y. Best model is picked that permforms well on categorizing news article.
