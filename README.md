#Early Cancer Detection through Transcriptomic Data Analysis Based on Transcriptomic Data

Cancer is a devastating disease that requires early detection to improve patient outcomes. In this project, we developed a deep learning model to detect any type of cancer as an anomaly in transcriptomic data. The model has the ability to act independently and is not restricted to any specific type of cancer.


#Data

In this project, we used the TCGA and GTEx datasets to train our model. The data was preprocessed and analyzed using various bioinformatics tools. The link to the dataset can be found here: https://drive.google.com/drive/folders/1izcpbMjd_acrWBAOw5BbCZyi__DeJvDy?usp=sharing.


#Model

Our model is a deep neural network called a Variational Autoencoder (VAE), which consists of an encoder and a decoder with a hidden layer. We defined an algorithm for detecting anomalies in the output of the VAE. We trained the model for six types of cancer using the Adam optimizer with decay learning for training, and a two-component loss function.


#Results

Our model achieved an accuracy of 0.950 and a recall of 0.830, demonstrating its effectiveness in detecting any type of cancer as an anomaly in transcriptomic data. This research leads us to the design of a deep learning model for the early detection of cancer as an anomaly in transcriptomic data.

#Contributors

This project was developed by Innocent Tatchum Sado, Louis Fippo Fitime, Géraud Fokou Pelap, Claude Tinku, Gaelle Mireille Meudje, and Thomas Bouetou Bouetou.


#Usage

To use this project, simply clone the repository, download the dataset and save it in the project folder and open the different anomaly detection * files and run them.


#Copyright

© 2023 by Innocent Tatchum Sado, Louis Fippo Fitime, Géraud Fokou Pelap, Claude Tinku, Gaelle Mireille Meudje, and Thomas Bouetou Bouetou. All rights reserved.
