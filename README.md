# galaxy-morphology-prediction
The main requirement to study the formation and evolution of galaxies is measuring the morphological parameters.
The traditional method to carry out morphological analysis is by visual inspection which is time consuming.
Only the trained experts can do the conventional way of analysis.
But in order to have an automated system which can give the
parameters directly using neural networks, we need a lot of
images to train the network. So the surveys like Sloan Digital
Survey (SDSS) made available a very large collection of images.
To classify those images, Galaxy Zoo project introduced the
crowdsourcing methodology. But still this method also didn’t
reach the required level of accuracy. Here we present a deep
neural network model to classify the galaxies on the basis of
their morphology. This greatly reduces the experts workload
and gives the better accuracy.

This repository contains the code, a sample image from dataset and model file. 

The link for the dataset is https://www.kaggle.com/c/galaxy-zoo-the-galaxy-challenge/data. 

The steps to use this repository are:
1. Install the Keras API using pip install keras. Also download the galaxy zoo dataset from the provided link and store into a directory.
2. Change the DATA_PATH and run till plotting the train and test data.
3. Change the FILTERED_DATA_PATH and DATASETS_PATH and run till augmentation. Augmented data will be generated into the FILTERED_DATA_PATH.
4. Change the path in the model_checkpoint and run the training and code to get the results and graphs.
