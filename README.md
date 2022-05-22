# Auto-Encoders

Auto Encoders are a type of Neural Network structure that is popular for the case of dimensionality reduction and anomaly detection. At a high-level AEs consists of encoding, hidden, and decoding layers. The encoding layer --> hidden layer converts the data from raw input into lower-level latent representation. The hidden layer --> decoding then tries to recreate the input by only using the hidden layer. This methodology has been cited in robotics, and finance, and can overall be a very useful tool for modelers in determining when a model needs retraining based on a shift in the underlying data.

# Projects
These are the projects included in this repo utilizing Auto Encoders. The projects are introductory explorations with commentary to explore different data preparatory and modeling techniques. 

## Project-1 (Credit Card Fraud Detection)
This implementation is based on the Kaggle credit card fraud dataset (https://www.kaggle.com/code/shivamb/semi-supervised-classification-using-autoencoders/data). The purpose of this project is for anomaly detection to identify fraudulent credit card transactions. 
