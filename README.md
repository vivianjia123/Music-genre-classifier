# Music-genre-classifier
The goal of this project is to build and critically analyse some supervised Machine Learning algorithms, to automatically identify the genre of a song on the basis of its audio, metadata and textual features. That is, given a list of songs, our job is to implement one or more Machine Learning model(s), train them using the training dataset, and evaluate using the test validation and test dataset.


# Steps of implementation

1. Firstly, the related Python libraries are introduced, including pandas, sklearn and Matplotlib

2. Read the training, verification and test data, and add the label of training and verification data to the training data to facilitate the later training.

3. Tdidf is used to process the tags and titles text features of the data, and then PCA is used to reduce the dimension and merge into the original feature data set.

4. Standardize the data, then use Baseline, SVM, MLP and LGB models to train the training data, verify with the verification data, and finally predict the test data. Finally, the results of validation data are presented and compared.Model tuning optimization is performed and the performance of each model is evaluated based on the learning curve.
