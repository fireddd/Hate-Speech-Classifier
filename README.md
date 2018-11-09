# Hate-Speech-Classifier
The project aims to clssify the text of wikipedia comments into 6 classes based on the toxicity of the words.

The training data has more than 150 thousand examples of wikipedia comments.

The text can be classified into toxic,severe_toxic,obscene,threat,insult and identity_hate.

The text can be in all the above mentioned classes or be in none. The possibility of each class is independent of the other.

To achieve the task many approaches where used:
1) Without any preprocessing of the data , just train a bidirectional LSTM model and check out the results.
2) Preprocessing the data and then using the Glove embedding as the inital embedding layer and then training the Bidirectional LSTM to predict the results.
3) Preprocessing the data and using the Glove embedding as the inital embedding layer and then training the a combination of CNN and Bidirectional LSTM to predict the results.
4) Preprocessing the data and using the Glove embedding as the inital embedding layer and then using only CNN's to classify the text into the desired categories.

Find the data used to train the model here:https://drive.google.com/drive/folders/1R0sN91QyHilWr3lnKEMVieohrIRwNErQ?usp=sharing
