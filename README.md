# Deep-Learning
A repository for Speech emotion recognition with Python on the RAVDESS data set.

Deep learning implemantions with different approaches:
1: Using Traditional Deep Convolutional Neural Networks, 
2: Using simple CNN and LSTM
3: Using simple LSTM

For the Deep Convolutional Neural Networks we extrateed the Mfcc's data from the samples (2d).
We chose to extract only 3.1 seconds from every sample with 500 milliseconds offset, and fill with zero is there is missing data.
Then we split our data to training data and test data with train size set to 75% of our samples.
We trained 4 different set-up of CNNs to compare and understand what are the changes tha are optimising our CNNs.

For the the next architectures we created augmented data by Applying noise, time-stretching, and pitch-shifting.
Those augmented data where used only in the training of our models and not in their evaluation.
And we created 1d features

The second approach was to perform Convolutional feature extraction from our data and fed them to an LSTM Network.
Our final approach was to use a simple LSTM. Here we used the dropout technique to avoid overfitting. 



