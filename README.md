# CN-Classificator
This project was created to classify texts into two languages, 文言文 (Wenyan) and 普通话 (Putonghua), using logistic regression. It can be used to determine the language of texts on websites, social networks and other applications where it is important to distinguish texts in different languages.

The text classification model uses logistic regression. The architecture of the model is described in the file *model.py*.

## Dataset
The project uses a dataset which includes texts in Wenyan and Putonghua. The texts are divided into sentences and labelled according to their class affiliation (0 - Wenyang, 1 - Putonghua). Features were identified using the jieba library. The dataset is available at the [link](https://drive.google.com/file/d/1BB6GAcq0MrarXmlbZHEfnqmfeJsdb69Q/view?usp=sharing).

<img src="/images/percentage-of-parts-of-speech.png" alt="Description of image" width="80%">
Figure 1. Percentage of parts of speech

Figure 1 shows the percentage distribution of parts of speech depending on the class of the text.

## Conclusion
The model was trained on datasets of 1 500 000 texts for each language. As a result of testing, the model achieved a classification accuracy of 0.92971.
