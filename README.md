## Classifying gender based on Audio

This repository contains two jupyter notebooks that set out to classify gender based on audio. The data collected was from Voxforge which contain X samples. 

Data Collection and Feature Extraction: In this notebook, data is is downloaded from the voxforge website using beautiful soup and the requests library. Meta data such as the gender, age and dialect of the speaker is extracted. Further for the purpose of deep learning MFCC's are extracted for individual audio samples using the librosa library. Finaly, some data exploration is carried out to explore the nature of the scraped data.

Using CNNs and RNN's to classify gender.
