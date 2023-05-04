# CN-Classificator
This project was created to classify texts into two languages, 文言文 (Wenyang) and 普通话 (Putonghua), using neural network methods. It can be used to determine the language of texts on websites, social networks and other applications where it is important to distinguish texts in different languages.

The project uses a dataset which includes texts in Wenyang and Putonghua. The texts are divided into sentences and labelled according to their class affiliation (0 - Wenyang, 1 - Putonghua). The dataset is located in a the data.

The text classification model uses a recurrent neural network (RNN). The architecture of the model is described in the file model.py.

STARTUP INSTRUCTIONS
1. Install the dependencies listed in the requirements.txt file
2. Run the train.py file to train the model on the available data
3. Run the file predict.py to use the model to predict the text language

EXAMPLE
...

CONCLUSION
The model was trained on datasets of ... texts for each language. As a result of testing, the model achieved a classification accuracy of ...
