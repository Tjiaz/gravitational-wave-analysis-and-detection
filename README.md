# gravitational-wave-analysis-and-detection

This project proposes a means for analysing the spectrogram of temporal domain waveforms via the CQT transform and detecting the presence of gravitational wave signals in them with the ResNet artificial neural network architecture

The dataset utilised in the paper is an annotated dataset obtained from kaggle open data source platform [1]. The dataset consists of 560,000 samples and each sample is stored in a single .npy file. Each sample contains simulated gravitational wave + detector noise from a network of three gravitational wave interferometers (LIGO Hanford, LIGO Livingston and Virgo). Each waveform contains either detector noise or detector noise + a simulated gravitational wave signal and spans 2 seconds with a sample rate of 2048Hz. The entire dataset consumes about 70 gigabytes of computer ROM.

The aim of this project is to formulate a means for properly analysing and detecting gravitational wave signals in given signal waveforms of the three LIGO detectors.
The objectives of this research are to formulate an algorithm that generates spectrogram representation of temporal signals with the aid of the Constant Q Transform (CQT) and to formulate a Neural Network Model for predicting the presence of gravitational waves using these spectrogram representations.
