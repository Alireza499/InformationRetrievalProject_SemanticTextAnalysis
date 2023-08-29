

# Semantic Text Analysis Project

This project focuses on implementing various methods for semantic text analysis using Python and Google Colab. The goal is to explore different techniques to calculate the similarity between words, sentences, and documents, and to perform efficient querying based on these methods.

## Methods Overview

### Method 1: Lexical Window
- Calculate the similarity matrix for all documents using a lexical window approach.
- Compare cosine similarity between the query similarity matrix and the document matrix.
- Sort results based on similarity scores.

### Method 2: Sentence-based Lexical Similarity
- Similar to Method 1, but the lexical window length matches sentence length.

### Method 3: Character-based Approach
- Measure similarity of words with similar characters using Jaccard method.
- Sum and average matrices for all words in documents and queries.
- Calculate cosine similarity and sort results.

### Method 4: Subjective Comparison
- Similar to Method 3, but using a different function to calculate word similarity.

## How to Use

1. Open the provided Google Colab notebook.
2. Upload your text documents or use the provided sample documents.
3. Choose the desired method by uncommenting the relevant sections in the code.
4. Run the notebook to execute the selected method.
5. The notebook will display the sorted results based on the chosen semantic analysis method.

## Note

- Ensure you have a Google account and access to Google Colab.
- Feel free to modify and experiment with the code to suit your specific needs.
- The project showcases different methods, their implementation, and usage within a single notebook for your convenience.

---

Feel free to customize this "Read Me" to better fit the specifics of your project and any additional details you want to include.
