# Image Caption Generator
The purpose of this project is to predict and generate captions for input images. Over 8K images are included in the dataset, each with five captions. Feature extraction has been done for both images and captions. By concatenating the features, the next word in the caption can be predicted.
• CNN: Extracting features from images. A pre-trained VGG16 architecture has been used.
• LSTM: To generate descriptions from the extracted information from images.
• BLEU Score is used as a metric to evaluate the performance of the trained model.
[Flicker 8K Dataset](https://www.kaggle.com/datasets/adityajn105/flickr8k)
