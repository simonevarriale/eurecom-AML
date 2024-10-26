# Sentiment Analysis
# Overview

Sentiment analysis is a rapidly growing field, as large databases become increasingly available, and companies have an interest in automatically extracting sentiment from internet users.

With the increasing amount of content and debate on social media platforms such as Twitter, there is an interest in automatically extracting meaning and sentiment from users' posts, to be able to evaluate the aggregate opinion of a large number of users. Capturing sentiment in language is important in these times where decisions and reactions are created and updated in seconds.

For this challenge, students are provided with tweets from Figure Eight's Data for Everyone platform. Your task will be to classify tweets with positive, neutral, or negative labels, reflecting the sentiment of the user writing the tweet.

**Examples**:
> - "I love this ice-cream, it is so good! :-)" -> **positive**
> - "Last week I visited San Francisco" -> **neutral**
> - "Disappointed by the last Avengers movie..." -> **negative**

The performance criterion is based on your model's ability to predict the correct labels for the testing data.

At the end of the challenge, if you wish to do so, there is a bonus task which consists of detecting the relevant words inside the tweet which are most responsible for the attributed sentiment. For example, in the phrase "I really like this song", the relevant words are: "really like".

## Dataset Description

- `train.csv` - the training set
- `test.csv` - the test set
- `sample_submission.csv` - a sample submission file in the correct format, containing random predictions

## Metrics

The evaluation metric for this competition is **Macro F1-Score**. The F1 score, commonly used in information retrieval, measures accuracy using the statistics precision (p) and recall (r). Precision is the ratio of true positives (tp) to all predicted positives (tp + fp). Recall is the ratio of true positives to all actual positives (tp + fn). The Macro F1-Score takes the mean score over all classes.

### Bonus

For the bonus task, you can estimate the overlap between your prediction and the selected words ground truth using the **Jaccard coefficient**, which measures the ratio of intersection to union of predicted and label sets.