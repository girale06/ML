# Practicing Machine Learning Algorithms
## Image Captioning using Encoder-Decoder Attention structure
`Image_Captioning.ipynb` contains my submission for a university assignment. The task was to train a custom *image captioning model* using the `Flickr8k` [dataset](https://www.kaggle.com/datasets/adityajn105/flickr8k). In this project I created my own Vocabulary class, Dataset, tokenised the text inputs, created an encoder with a pretrained Vision Transformer, an LSTM based decoder, implemented my own Attention class and trained the model on an A100 GPU. Finally I compared my results with the [BLIP](https://github.com/salesforce/BLIP) model, evaluated both models using metrics like the BLEU score.

## Natural Language Processing with Disaster Tweets

`Twitter.ipynb` is my submission to the running [competition](https://www.kaggle.com/competitions/nlp-getting-started/data) Organised by the Kaggle team. 
This was a great way to dive into the world of language processing. Understanding the fundementals of RNN and LSTM.

## Experimenting with the KNN algorithm

In the `KNN.ipynb` I use the Car Evaluation Database. Based on the features like buying price, price of maintenance, estimated safety of the car etc. I try to evaulate the car and give it an evaulation level from unacceptable to good.
I solve this exercise by implementing the K-Nearest Neighbors algorithm using Sklearn and Tensorflow as well.

## Solving MNIST digit classification problem

In `MNIST.ipynb` I use libraries like numpy, tensorflow, matplotlib. This exercise is considered to be the *"Hello World"*  of machine learning.

## Python and numpy practice

In the file `Python_and_numpy_practice.ipynb` some homework exercises can be seen from my university's machine learning course.

These were assigned to practice Python and Numpy.

## Support Vector Machine

In  `SVM.ipynb` I use the SVM algorithm for classification on two famous datasets.
- Firstly the breast cancer dataset imported from skicit-learn. This dataset provides numerous features which can be used to predict whether the tumor is malignant or benign.
- Secondly I work with the IRIS dataset, introduced by Ronald Fischer in 1936. The data has 4 features from which have to predict the species of the plant: setosa, versicolor or virginica.

## Linear regression

In this little project I predict student performance using linear regression. See file `Linear_regression.ipynb`
