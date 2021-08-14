# BookReviews_RNN
This ML project classifies book reviews as positive or negative based on the review title using a RNN.

# About
The code uses reccurent neural networks to classify book reviews as either negative or positive based on the words used in the review title. There are 4 models tested, with the same architecture, however the output dimension in the embedded layer is varied.

### Install
This project requires **Python**, and the following libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [keras](https://keras.io/)

You will also need to have software to run and execute Jupyter Notebook.

### Code

The code containing the model training is provided in the 'L3T20.ipynb' notebook file. You will be required to include the 'positive.txt' and 'negative.txt' files to execute the code. 

# Dataset

The two applicable datasets are the contained in the 'positive.txt' and 'negative.txt' files. The 'positive.txt' dataset contains 872 positive reviews and the 'negative.txt' dataset contains 921 negative reviews. The mean number of words per review is 4.34 words.

**Features**
Tokenized reviews: The reviews are reduced to maximum 4 words and shorter reviews are padded. The 4 word reviews are tokenized. 
**Target Variable**
The book review sentiment, indicated by one-hot encoding - [1, 0] (positive) or [0, 1] (negative)

