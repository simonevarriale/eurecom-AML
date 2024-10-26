# Aerial Imagery
# Cactus Classification Dataset

This dataset contains a large number of 32 x 32 thumbnail images of aerial photos featuring columnar cacti (Neobuxbaumia tetetzo). The images have been resized from the original dataset to ensure uniformity. Each image's file name corresponds to its unique ID.

## Objective

Your task is to create a classifier capable of predicting whether an image contains a cactus.

## Files

- **train/** - Directory containing the training set images.
- **test/** - Directory containing the test set images (you need to predict the labels for these).
- **train.csv** - CSV file with training set labels, indicating whether an image contains a cactus (`has_cactus = 1`).

## Metrics

For this challenge, you are required to define an appropriate metric. You face a binary classification problem, but at this stage you do not know if your data is balanced. Throughout your work, especially the data analysis part, you will first need to characterize your data, and then come up with a valid performance metric to assess the quality of your model. 