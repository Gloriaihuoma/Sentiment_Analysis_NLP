# Sentiment Analysis on Women's E-commerce Clothes Reviews

This repository is dedicated to the project "Sentiment Analysis on Women's E-commerce Clothes Reviews," utilizing advanced deep learning techniques to understand and categorize sentiments expressed in customer reviews. The project aims to provide actionable insights for enhancing product quality and customer experience in the e-commerce fashion sector.

## Project Overview

Leveraging deep learning models like LSTM, GRU, Bi-LSTM, and Bi-GRU, this study achieves remarkable accuracy in distinguishing positive and negative sentiments. The analysis involves a comprehensive use of NLP techniques and deep learning architectures, aiming to support businesses in refining their strategies based on customer feedback.

## Repository Contents

- `Sentiment_Analysis_ClothesReview.ipynb`: Main notebook with the project's code, visualizations, and results.
- `Womens Clothing E-Commerce Reviews.csv`: Dataset containing customer reviews and additional metadata.

## Technical Framework

### Data Preparation and Preprocessing
Data is preprocessed extensively to ensure quality. This involves tokenization, lemmatization, n-grams extraction, removal of stopwords, and data visualization through word clouds.

### Tokenization and Sequence Padding
The dataset is tokenized using Keras' Tokenizer, creating a vocabulary index based on the word frequency in the dataset. Each text sequence is then transformed into a sequence of integers. The sequences are padded to have the same length for model training.

Vocabulary Size: 13477
Max Sequence Length: 115
Libraries and Tools
Key libraries for data manipulation, visualization, NLP, and deep learning include pandas, numpy, matplotlib, seaborn, nltk, and tensorflow.

### Handling Imbalanced Data with SMOTE
SMOTE (Synthetic Minority Over-sampling Technique) is applied to balance the dataset, improving model performance by addressing class imbalance.

### Word Embedding with GloVe
GloVe (Global Vectors for Word Representation) is used for word embedding, transforming words into a numerical format that deep learning models can understand.

### Model Architecture and Training

Various RNN architectures are explored, including LSTM, GRU, and their bidirectional counterparts (Bi-LSTM and Bi-GRU). The models are built using TensorFlow and Keras, featuring layers like Embedding, SpatialDropout1D, Conv1D, and Dense. Regularization techniques and callbacks like EarlyStopping and ReduceLROnPlateau are employed to enhance training efficiency and model performance.

## Results and Discussion

The Bi-GRU model excels with an accuracy of 91%, effectively categorizing sentiments in the reviews. Despite the high accuracy, the models occasionally misclassify certain reviews, pointing to areas for future enhancement. The study demonstrates the potential of deep learning in extracting nuanced sentiment from customer reviews, providing a valuable tool for businesses to understand and cater to customer preferences.

## Conclusion

The project successfully leverages sentiment analysis to classify Women's E-commerce Clothes Reviews into recommended and not recommended categories. With an accuracy of 91%, the Bi-GRU model stands out, offering precise insights into customer sentiment. Future research could delve into more advanced models, larger datasets, and improved word embeddings to refine the analysis further.

---

For a detailed understanding of the methodologies, experiments, and findings, please refer to the Jupyter Notebook included in this repository. 
