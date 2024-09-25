# Graph Representation and Classification of Text using LLMs and GNNs

This project explores an innovative approach to classify text by transforming it into semantic graphs using **Large Language Models (LLMs)** and **Graph Neural Networks (GNNs)**. The primary goal is to improve text classification accuracy through semantic graph representations and leveraging the capabilities of GNNs for complex data structures.

## 📜 Abstract

The project focuses on transforming text data into semantic graphs, particularly for mental health-related posts (e.g., "depression" and "SuicideWatch"). The text is pre-processed and key phrases are extracted using **KeyBERT**. These keywords are then transformed into graphs, which are subsequently used to train a **GNN model**. By capturing the intricate relationships between words, the GNN can more accurately classify text data.

## 🚀 Features

- **Text Preprocessing**: Tokenization, stopword removal, and keyword extraction using KeyBERT.
- **Graph Construction**: Semantic graphs are built from keywords to represent relationships within the text.
- **Graph Neural Networks (GNN)**: GNNs are used to capture complex relationships and classify text based on its semantic graph.
- **Comparative Analysis**: Performance comparisons between GNNs and traditional machine learning models (e.g., Logistic Regression, KNN, Naive Bayes).

## 🛠️ Tools and Technologies

- **Languages**: Python
- **Libraries and Frameworks**:
  - **KeyBERT**: For extracting keywords from text.
  - **NetworkX**: For building and manipulating graphs.
  - **PyTorch**: For deep learning, specifically training the GNN model.
  - **PyTorch Geometric**: For graph-based machine learning.
  - **Cytoscape**: For graph visualization.
  - **Matplotlib**: For data visualization.
  
## 📊 Data

The dataset consists of 20,364 text posts from social media related to mental health, focusing on "depression" and "SuicideWatch" labels. Each post is converted into a semantic graph, and GNNs are applied to classify the text into one of these two categories.

## 📈 Results

- **GNNs** achieved significant improvement over traditional machine learning models for text classification.
- **Accuracy**: The GNN model achieved 66.6% accuracy on the test dataset.
- **Comparisons**: GNN outperformed models such as KNN and Logistic Regression in text classification tasks.

## ⚙️ How it Works

1. **Data Preprocessing**: Text posts are tokenized, cleaned, and transformed into semantic graphs using KeyBERT.
2. **Graph Construction**: Nodes represent keywords, and edges represent semantic relationships.
3. **Model Training**: A **Graph Convolutional Network (GCN)** is trained using PyTorch and PyTorch Geometric.
4. **Evaluation**: The model is evaluated based on classification accuracy, F1-score, and comparison with other ML models.

## 🔧 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-project.git
