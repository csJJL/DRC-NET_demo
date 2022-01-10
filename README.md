# DRC-NET Demo
This is a complementary demo for the paper **"DRC-NET: DENSELY CONNECTED RECURRENT CONVOLUTIONAL NEURAL NETWORK FOR SPEECH DEREVERBERATION"**

- **DRC-NET:** our proposed model

- **DRC-NET_causal:** causal version of DRC-NET, by setting the convolution kernel size on time dimension to 1, and using unidirectional LSTM.

- **DRC-NET_mono:** DRC-NET with single channel microphone input 

- **DRC-NET_causal_mono:** causal DRC-NET with single channel microphone input

- **DenseNET:** the baseline model[1]

- **DenseNET_causal:** causal version of DenseNET, by setting the convolution kernel size on time dimension to 1, and using unidirectional LSTM.

- **DenseNET_mono:** DenseNET with single channel microphone input 

- **DenseNET_causal_mono:** causal DenseNET with single channel microphone input

[1] Z. Q. Wang and D. Wang, “Deep learning based target cancellation for speech dereverberation,” IEEE/ACM Transactions on Audio, Speech, and Language Processing, vol. 28, pp. 941–950, 2020
