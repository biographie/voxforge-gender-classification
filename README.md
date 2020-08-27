## Classifying gender based on Audio

This repository contains two jupyter notebooks that set out to classify gender based on audio. The data collected was from [Voxforge](http://www.repository.voxforge1.org/downloads/SpeechCorpus/Trunk/Audio/Main/16kHz_16bit/) which contain a various number of audio samples from  6247 speakers. 

**data_colection_feature_extraction.ipynb:**  In this notebook, data is is downloaded from the Voxforge website using beautiful soup and the requests library. Meta data such as the gender, age and dialect of the speaker is extracted. Further for the purpose of deep learning MFCC's are extracted for individual audio samples using the librosa library. Finally, some data exploration is carried out to explore the nature of the scraped data.

**cnn_rnn.ipynb:** In the second notebook, a Convolutional Neural Network and a Recurrent Neural Network are explored to identify gender from audio. 

