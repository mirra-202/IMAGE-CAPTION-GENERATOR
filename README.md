# IMAGE-CAPTION-GENERATOR

**OVERVIEW:**
This project aims to create an image captioning system using deep learning techniques. Given an input image, the system generates a descriptive caption that describes the contents of the image.

**DATASET DESCRIPTION:**
The Flickr8K dataset is a collection of 8,000 high-quality images sourced from the Flickr photo-sharing platform. Each image in the dataset is paired with five descriptive captions, providing different textual descriptions of the visual content. The dataset is commonly split into training, validation, and test sets, facilitating model training, evaluation, and benchmarking. Researchers use this dataset to develop and assess image captioning algorithms, aiming to automatically generate informative and contextually relevant captions for images.

**LINK TO DOWNLOAD DATASET:** https://www.kaggle.com/datasets/adityajn105/flickr8k

**KEY FEATURES:**

*Image Feature Extraction:* Utilizes a pre-trained convolutional neural network (VGG16) to extract high-level features from input images. These features serve as input to the captioning model.
*Text Preprocessing:* Cleans and preprocesses text data by converting captions to lowercase, removing special characters, and adding start and end tags to indicate the beginning and end of sentences.
*Sequence Modeling:* Employs a sequence-to-sequence model architecture comprising an encoder and a decoder. The encoder processes image features, while the decoder generates captions word by word.
*Model Training:* Trains the model using a combination of image features and corresponding captions. The training process involves optimizing the model parameters to minimize the cross-entropy loss.
*Evaluation:* Evaluates the model performance using BLEU (Bilingual Evaluation Understudy) scores, which measure the similarity between predicted and ground truth captions.
*Prediction:* Provides functionality to generate captions for new images using the trained model. Users can input an image path, and the system generates a descriptive caption for the image.

**TECHNOLOGIES USED:**
  -Python
  -Keras (Deep Learning Library)
  -NumPy (Numerical Computing Library)
  -NLTK (Natural Language Toolkit)
  -PIL (Python Imaging Library)
  -Matplotlib (Data Visualization Library)
