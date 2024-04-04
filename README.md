# IMAGE-CAPTION-GENERATOR

**OVERVIEW:** <br>
This project aims to create an image captioning system using deep learning techniques. Given an input image, the system generates a descriptive caption that describes the contents of the image. <br>

**DATASET DESCRIPTION:** <br>
The Flickr8K dataset is a collection of 8,000 high-quality images sourced from the Flickr photo-sharing platform. Each image in the dataset is paired with five descriptive captions, providing different textual descriptions of the visual content. The dataset is commonly split into training, validation, and test sets, facilitating model training, evaluation, and benchmarking. Researchers use this dataset to develop and assess image captioning algorithms, aiming to automatically generate informative and contextually relevant captions for images.<br>

**LINK TO DOWNLOAD DATASET:** https://www.kaggle.com/datasets/adityajn105/flickr8k <br>

**KEY FEATURES:** <br>

*Image Feature Extraction:* Utilizes a pre-trained convolutional neural network (VGG16) to extract high-level features from input images. These features serve as input to the captioning model.<br>
*Text Preprocessing:* Cleans and preprocesses text data by converting captions to lowercase, removing special characters, and adding start and end tags to indicate the beginning and end of sentences.<br>
*Sequence Modeling:* Employs a sequence-to-sequence model architecture comprising an encoder and a decoder. The encoder processes image features, while the decoder generates captions word by word.<br>
*Model Training:* Trains the model using a combination of image features and corresponding captions. The training process involves optimizing the model parameters to minimize the cross-entropy loss.<br>
*Evaluation:* Evaluates the model performance using BLEU (Bilingual Evaluation Understudy) scores, which measure the similarity between predicted and ground truth captions.<br>
*Prediction:* Provides functionality to generate captions for new images using the trained model. Users can input an image path, and the system generates a descriptive caption for the image.<br>

**TECHNOLOGIES USED:** <br>
  -Python<br>
  -Keras (Deep Learning Library)<br>
  -NumPy (Numerical Computing Library)<br>
  -NLTK (Natural Language Toolkit)<br>
  -PIL (Python Imaging Library)<br>
  -Matplotlib (Data Visualization Library)<br>
