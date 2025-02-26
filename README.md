Image Captioning Using Deep Learning
This project implements an image captioning model using deep learning techniques. It utilizes a pre-trained VGG16 model for feature extraction and an LSTM-based sequence model to generate captions for images.

Dataset
The model is trained on the Flickr8K dataset, which contains 8,000 images and their corresponding captions.

Features
Feature Extraction: Uses VGG16 to extract features from images.
Text Processing: Tokenizes and cleans captions.
LSTM Model: Generates captions using a combination of CNN and LSTM.
BLEU Score Evaluation: Evaluates model performance using BLEU scores.
Model Training: Uses a batch generator for training.

Model Architecture
The model consists of:

Feature Extractor: Uses a pre-trained VGG16 model to extract 4096-dimensional feature vectors from images.
LSTM Network: Generates captions from extracted features using an LSTM-based sequence model.
Embedding Layer: Maps words into a vector space.
Dropout Layer: Prevents overfitting.
Results
The model is evaluated using BLEU scores, which measure the similarity between generated captions and actual captions.
