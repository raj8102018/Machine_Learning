Lead Classification using Pretrained Transformers
Overview
This project aims to classify potential business leads into categories (cold, warm, hot) using advanced NLP techniques. The project employs two distinct approaches:

Approach 1: Using embeddings from transformers and feeding them into a feed-forward neural network for classification.
Approach 2: Directly utilizing transformers by fine-tuning them for classification.
The preprocessing step for both approaches is handled using SpaCy, ensuring that the data is clean and standardized.

Features

Approach 1:

Extracts embeddings from transformer models.
Uses a feed-forward neural network for lead classification.
Utilizes SpaCy for text preprocessing.

Approach 2:

Fine-tunes a transformer model directly for classification.
Uses preprocessed data from Approach 1.

Technologies Used
Python: Primary programming language for implementation.
Hugging Face Transformers: For extracting embeddings and fine-tuning transformer models.
TensorFlow/Keras: For implementing the feed-forward neural network and other model-related operations.
SpaCy: For preprocessing text data.
Scikit-learn: For additional machine learning utilities and metrics.
NumPy: For numerical operations.
Pandas: For data handling and manipulation.
using SMOTE for handling class imbalance

Project Highlights:
• Successful comparison of different techniques for classificaiton.
