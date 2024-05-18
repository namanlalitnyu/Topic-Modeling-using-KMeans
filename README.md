# Topic Modeling using K-Means Algorithm

This project utilizes topic modeling to extract themes from a corpus of 32 documents. Key tasks include:

1. **Data Cleaning**: Convert PDFs to text, preprocess to remove stop words, special characters, and apply lemmatization.
2. **Embeddings**: Generate document embeddings using two distinct pre-trained models.
3. **Dimensionality Reduction**: Reduce the dimensionality of embeddings using techniques like PCA or UMAP.
4. **Clustering**: Cluster the reduced embeddings and determine optimal clusters using the Elbow method.
5. **Class-based TF-IDF**: Extract top keywords from each cluster.
6. **Topic Representation**: Enhance topic representations using ChatGPT APIs.

Deliverables include cluster information in CSV format, 2D visualization of clusters, theoretical answers, and code files.


### Technologies Used
Python, Pandas, Numpy, Matplotlib, NLTK, Sckit-learn, Tensorflow Hub, Prompt Engineering.

### Libraries Used
K-Means, Principal Component Analysis (PCA), Doc2Vec Embeddings, Universal Sentence Encoder.
