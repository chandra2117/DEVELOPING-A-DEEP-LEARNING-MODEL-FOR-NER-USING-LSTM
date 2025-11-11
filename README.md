# DL- Developing a Deep Learning Model for NER using LSTM

## AIM
To develop an LSTM-based model for recognizing the named entities in the text.

## DESIGN STEPS

1. Data Preparation – Load and preprocess the NER dataset, extract unique words and tags, and encode them as integers.

2. Sentence Grouping – Group words and corresponding tags by sentence for sequence labeling.

3. Model Building – Design a Bidirectional LSTM (BiLSTM) network with embedding, dropout, and linear output layers.

4. Training – Train the model using CrossEntropyLoss and Adam optimizer, tracking training and validation loss.

5. Evaluation and Visualization – Generate the classification report, visualize loss curves, and perform word-level predictions.


### OUTPUT

## Loss Vs Epoch Plot

<img width="941" height="616" alt="image" src="https://github.com/user-attachments/assets/2950a306-6694-444f-a9cd-429e881e1ec2" />


### Sample Text Prediction

<img width="615" height="499" alt="image" src="https://github.com/user-attachments/assets/802c15cc-e02e-4d03-a884-905f20d65ec7" />


## RESULT

The BiLSTM Named Entity Recognition model was successfully implemented and trained on the NER dataset.

After 3 epochs, the model achieved an overall accuracy of 86% with strong performance on major entity classes like GPE, PER, GEO, and ORG.

The classification report and word-level predictions show that the model effectively recognizes named entities in text sequences.
