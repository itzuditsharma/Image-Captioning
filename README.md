# Image-Captioning
This project implements an image captioning model using attention mechanisms, designed to generate meaningful captions for images. The model uses the Flickr8k dataset for training and evaluation and includes an Encoder-Decoder architecture enhanced by an attention mechanism.

# Evaluation Results
The model's performance was evaluated using the BLEU metric, which measures n-gram overlaps between predicted and ground truth captions. Below are some results:

![image](https://github.com/user-attachments/assets/f183944b-d483-4224-80ee-8674ad75d729)
![image](https://github.com/user-attachments/assets/84ec3836-cc98-46df-a25c-3e62c3d61133)

![image](https://github.com/user-attachments/assets/f7fd4c28-5d5c-4270-8b14-ffa8a9cddd2e)
![image](https://github.com/user-attachments/assets/b77517d8-cf5f-44a3-a799-b82e638c1c31)

![image](https://github.com/user-attachments/assets/42c0f06f-083f-4453-bc22-b298538f38db)
![image](https://github.com/user-attachments/assets/e65834e6-dc18-4152-95f4-99e43d126852)


![image](https://github.com/user-attachments/assets/000822e2-d614-4eac-83f0-3f5df4717827)

# How It Works
**Feature Extraction:**
Uses InceptionV3 to extract features from input images.

**Encoder-Decoder Architecture:**
The encoder processes image features, and the decoder generates captions using an LSTM network combined with an attention mechanism.

**Training Process:**
Trains on the Flickr8k dataset to optimize caption generation using word embeddings and cross-entropy loss.


**Dependencies**
- TensorFlow
- Keras
- NumPy
- NLTK (for BLEU score computation)



