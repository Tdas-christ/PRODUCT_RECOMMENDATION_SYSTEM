Fashion Recommendations System
This repository contains code for a fashion recommendations system that uses multimodal features including textual embeddings from BERT and visual embeddings from VGG16 to recommend fashion products to users.

Overview
The system consists of the following components:

Data Preprocessing: Text preprocessing techniques are applied to product names to generate BERT embeddings. Images are preprocessed and passed through a VGG16 model to generate visual embeddings.
Feature Extraction: BERT embeddings are extracted for textual features, while visual embeddings are extracted for image features.
Similarity Computation: The similarity between a given product and all other products in the dataset is computed based on the combined textual and visual embeddings.
Recommendation Generation: The top 5 most similar products are recommended based on the computed similarities.
