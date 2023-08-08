# Classify Disaster Tweets
These are the notebooks that I worked on for [the Natural Language Processing with Disaster Tweets competition on Kaggle](https://www.kaggle.com/competitions/nlp-getting-started). As of July 24th, 2023, the best performing model has the score of 0.83971 (Rank: 93). 

## Models (and their Folders)
- **BERT-based Classifier (Tensorflow Models)**: We train three different models using BERT and achieve ~78% validation accuracy. This is not impressive compared to the performance of other models that are on the leaderboard (Best score: 0.79742; Rank: 528; Submission on: July 20th, 2023).

- **BERT + LSTMs (Trensorflow Models)**: We train two additional models using Bi-directional LSTMs and achieve ~80% validation accuracy. This is a small improvement from the first set of models. We did not submit predictions using these models.

- **BERTweet (Hugging Face Models)**: We fine-tune a Hugging Face model (BERTweet) that has been trained on Twitter data and achieve ~83% validation accuracy. This is a considerable improvement from the first set of models and ranked moderately high on the leaderboard (Best score: 0.83971; Rank: 93; Submission on: July 26th, 2023).

- **BERTweet V2 (Hugging Face Models)**: We fine-tune the same Hugging Face model (BERTweet) alongside additional preprocessing steps and an early-stopping callback. The model achieved ~82% validation accuracy. This was not a significant improvement from the other BERTweet model, so we did not submit predictions of this model.
- 
