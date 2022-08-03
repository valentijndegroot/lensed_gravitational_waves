# lensed_gravitational_waves
Building a machine learning model to differentiate between unlensed and lensed gravitational waves

#First we import data and visualise it. The data of the waves is given in the frequency domain and we convert it to specrograms. This is done in the file Data_Visualisation. You need to save the spectrograms in a local directory file on your pc. We also convert it to WAV-files which will be used for the Yamnet transfer learning model.

#With the spectrograms, we train several machine learning models which can be found in:
Convolutional Neural Network
RandomForest_SVM
Transferlearning
Yamnet_Transfer
