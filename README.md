# Image-Captioning
Project assignment for Deep Learning.

The primary objective of this project is to create an image captioning program based on the Flickr datasets. The implementation uses Flickr8k and Flickr30k datasets, the Inception architecture for image feature extraction, GloVe word embedding and a RNN for the caption generation based on the provided information.

This repository includes the Python Notebook with the code implementation and the source files. Source files are:

**- Code Files:**
  - Project_Image_Captions_Final_8k.ipynb: Implementation using Flickr8k dataset.
  - Project_Image_Captions_Final_30k.ipynb: Adapted implementation using Flickr30k dataset, simplified for faster running time.

**- Data Files:**
  - Flickr8k and Flickr30ks folders: contain supporting information for the images and captions.

**- Additional Files:**
  - glove6b: supporting file for applying GloVe word embedding.
  - image_features_train_30k.pkl, image_features_train_30k.pkl: Files that save the image features extracted for each image in the 30k dataset.
  - model_Flickr8k.pkl, model_Flickr30k.pkl: Files that save the trained model for each dataset.
