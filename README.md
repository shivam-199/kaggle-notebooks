# Kaggle Notebooks

This repository containts python notebooks for various kaggle datasets. They are listed below:

1. [Disaster Tweet](https://www.kaggle.com/c/nlp-getting-started): A binary NLP classification task, where the model takes a tweet and classifies it as a tweet about disaster or not.

**Summary of the Model**

Deep RNN using LSTM.
Used [BeautifulSoup4](https://pypi.org/project/beautifulsoup4/), regex and [nltk](https://pypi.org/project/nltk/) for text processing.
Processed text is vectorized and embeddings are created using the [GLOVE](https://nlp.stanford.edu/data/glove.6B.zip) model.
Achieved train accuracy of 80%.

2. [Brain Tumor Detection](https://www.kaggle.com/jakeshbohaju/brain-tumor): It is a binary class classification of MRI scans of people with and without brain tumors. 

**Summary of the Model**
Keras Tensorflow framework used for classification. Train accuracy: 99.77% Test accuracy: 91.77%
Image dimensions: 224 * 224 * 3
Further playing with the hyper parameters may help in reducing the gap between train and test accuracy.

3. [Intel Image Classification](https://www.kaggle.com/puneet6060/intel-image-classification): In this task, we distinguished between the images of six different scenes. 

**Summary of the Model**
Keras Tensorflow framework used for classification.
  Train accuracy: 93%
  Test accuracy: 83%
RESNET50 model trained using transfer learning to create the current model.
Image dimensions: 96 * 96 * 3
