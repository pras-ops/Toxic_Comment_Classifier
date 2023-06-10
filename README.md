# Toxic_Comment_Classifier
This repository contains code for a toxic comment classifier. The classifier is trained to identify toxic comments in text data. It utilizes machine learning algorithms and natural language processing techniques for preprocessing and modeling the data.

## Dataset

The classifier is trained on a dataset containing comments labeled as toxic or non-toxic. The dataset includes the following categories of toxic comments:

-   Toxic
-   Severe Toxic
-   Obscene
-   Threatening
-   Insulting
-   Identity Hate

The dataset does not contain any null values. The distribution of toxic and non-toxic comments in each category can be visualized using bar graphs.

## Data Pre-processing

The text data is pre-processed using various techniques to remove special characters, convert text to lowercase, and remove stop words. The preprocessing steps include:

-   Removal of special characters
-   Conversion to lowercase
-   Removal of newlines
-   Removal of non-ASCII characters

## Data Visualization

The distribution of sentence types (toxic, severe toxic, obscene, threatening, insulting, and identity hate) is visualized using a bar graph. The graph shows the number of sentences in each category.

## Word Clouds

Word clouds are generated to visualize the most frequent words in each category of toxic comments. Word clouds provide a visual representation of the most common words in the comments.

## Balancing the Dataset

To address class imbalance, the dataset is balanced by selecting an equal number of toxic and non-toxic comments for each category. The balanced datasets are created and used for further analysis and modeling.

## Machine Learning Models

Several machine learning models are trained on the balanced datasets to classify toxic comments. The models used include:

-   Logistic Regression
-   K-Nearest Neighbors
-   Naive Bayes (Bernoulli and Multinomial)
-   Support Vector Machine
-   Random Forest

The performance of each model is evaluated using various evaluation metrics such as F1 score. The models are trained and tested on different categories of toxic comments.

## Testing the Model

The trained model can be used to classify new comments as toxic or non-toxic. By providing a comment as input, the model predicts the probability of the comment being toxic.

## Report

The findings of the analysis are as follows:

-   The dataset contains a high number of toxic comments, followed by obscene comments and a small number of threatening comments.
-   ![download](https://github.com/pras-ops/Toxic_Comment_Classifier/assets/56476064/b453342a-6368-4677-a689-9b87521eabd2)
-   The word clouds show the most frequent words in each category of toxic comments, providing insights into the language used in toxic comments.
-   ![download](https://github.com/pras-ops/Toxic_Comment_Classifier/assets/56476064/47104d18-700b-44bb-b980-8a1a13bea236)
-   The balanced datasets improve the performance of the models by addressing class imbalance.
-   The evaluation of the models on different categories of toxic comments shows varying performance. Multinomial Naive Bayes performs well for severe toxic and identity hate comments, while Random Forest shows better performance for obscene and threatening comments. Support Vector Machine performs well for insulting comments.
-   The trained model can accurately classify new comments as toxic or non-toxic based on the given text.

Overall, this toxic comment classifier provides a tool to automatically identify toxic comments in text data and can be used for various applications, such as content moderation and sentiment analysis.
