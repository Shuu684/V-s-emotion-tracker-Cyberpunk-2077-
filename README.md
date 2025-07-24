# V-s-emotion-tracker-Cyberpunk-2077-
Project on the program of the HSE course "Computational Linguistics"

This project explores emotion tracking of the main character V from Cyberpunk 2077 by analyzing the emotional tone of their dialogue lines across quests. Both classic machine learning models and pretrained transformer models were used to classify emotions and visualize narrative dynamics.

## Objective

The goal is to track how the emotional state of the protagonist evolves throughout the game storyline and to compare the effectiveness of traditional ML models versus pretrained language models in emotion classification.

## Project Highlights

- Emotion labeling of dialogue lines across quests.
- Comparison between non-pretrained (Logistic Regression, Naive Bayes, MLP, Random Forest) and pretrained models (CardiffNLP, Bhadresh GoEmotions).
- Visualizations showing how emotions change throughout the game.

## Models Used

### Non-Pretrained Models:
- Logistic Regression
- Naive Bayes
- MLP Classifier
- Random Forest (+ GridSearchCV)

### Pretrained Transformers:
- `cardiffnlp/twitter-roberta-base-emotion`
- `bhadresh-savani/bert-base-go-emotion`

## Visualizations

- WordClouds per emotion
- Storyline emotion trajectory of V
