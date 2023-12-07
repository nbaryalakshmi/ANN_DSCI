Artificial Neural Networks

Music genre classification with mel spectrogram images  using Deep Convolutional Neural Networks

This research utilizes mel spectrogram image data from GTZAN dataset [https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification] to classify the musical genre of audio songs. Blues, classical, country, disco, hip-hop, jazz, metal, pop, reggae, and rock are the ten genres included in this dataset. Deep Convolutional Neural Network (DCNN) is the method employed in this study to classify the musical genre. Several convolutional layers are stacked on top of one another in a DCNN, coupled with a number of fully connected layers. These networks are appropriate for more complicated tasks since they are significantly deeper than conventional CNNs and can be trained on larger datasets. Each layer of the architecture is intended to learn more complicated representations of the input data, with the output of earlier layers being used to extract higher-level features. Deep CNNs are distinguished from conventional shallow CNNs by the depth of the network.   

In this study, two Deep Convolutional Neural Network (DCNN) models were used to classify the music genre. Both models used 10 and 25 execution epochs, respectively.

The first model with 10 epochs outperformed the other three in a comparison of all four model executions because it had superior training and validation accuracy of 88.25% and 64.32%, respectively, and it trained faster with less number of epochs.
 
Metal music genre could be accurately predicted by the first model with 10 and 25 epochs and the second model with 10 epochs. Jazz and classical music genres were accurately predicted by the second model, which had 25 epochs. In all models, the disco music genre has a low rate of prediction. 

Further work can be done by including a larger amount of data from other musical genres in order to increase the validation accuracy. It is necessary to experiment with various layer combinations and parameter values for the deep convolutional neural network. Moreover, a hybrid model can be created using the dcnn architecture and other appropriate neural network models to test the performance level.  


![image](https://github.com/nbaryalakshmi/ANN_DSCI/assets/127498506/5d49c4a5-c250-4c06-9845-004596a4aefe)
