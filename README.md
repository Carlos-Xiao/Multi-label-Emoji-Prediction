# Multi-label Emoji Prediction for Tweet Texts

The project is developing an emoji prediction model based on Tweet text content, offering benefits to both users and social platforms. The project extends beyond existing literature by employing a multi-label approach. Stacking with sub-sampling and the weighted loss function, the pre-trained BERT model has achieved a weighted F1 score of 0.43 and an average cosine similarity of 0.42 across a pre-defined set containing 30 distinct emojis.

![Pre-defined Emoji Set](https://raw.githubusercontent.com/Carlos-Xiao/Multi-label-Emoji-Prediction/master/emoji_set.png)

## Dataset

[enryu43/twitter100m_tweets](https://huggingface.co/datasets/enryu43/twitter100m_tweets)

## Setup

* data_cleaning.ipynb - To preprocess the original Twitter dataset
* baseline_analysis.ipynb - To evaluate the baseline models
* bert_model_training.ipynb - To carry out sub-sampling and train the pre-trained BERTs using weighted loss trainer
* explainable_error_analysis.ipynb - To generate feature importance using SHAP package



