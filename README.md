# Kaggle_Tabular_playground_Nov22

## Dataset Description
In this competition, you are given a folder of submissions that contain predictions for a binary classification task. The ground truth for these rows are provided in the file train_labels.csv. Each file name in the submissions folder corresponds to the logloss score of the the first half of the prediction rows against the ground truth labels in that file. This is effectively the "training" set.

Your task is to use blend (ensemble) the various submission files to produce better model predictions. You can tell if the blend produces better results because you have the ground truth labels for the first half of the rows. In other words, you can blend two files together, check the score on the first half of the rows, and the score improves, you can submit the results from the rest of the rows to the leaderboard.

A simple example is shown in this notebook.

## Files
submission_files/ - a folder containing binary model predictions
train_labels.csv - the ground truth labels for the first half of the rows in the submission files
sample_submission.csv - a sample submission file in the correct format, only containing the row ids for the second half of each file in the submissions folder; your task is to blend together submissions that achieve the improvements in the score.

Link to the Kaggle page: https://www.kaggle.com/competitions/tabular-playground-series-nov-2022/overview