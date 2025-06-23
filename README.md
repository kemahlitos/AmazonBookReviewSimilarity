# AmazonBookReviewSimilarity

Final project for **Algorithm for Massive Datasets – Spring 2024–2025**  
Author: Yusuf Kemahlı

## Project Overview

This project focuses on detecting similar book reviews from the large scale Amazon Book Reviews dataset using **MinHash** and Locality Sensitive Hashing (LSH). The goal is to demonstrate a scalable, from-scratch implementation that can efficiently handle massive datasets.

- Dataset: [Amazon Book Reviews (Kaggle)](https://www.kaggle.com/datasets/mohamedbakhet/amazon-books-reviews)
- ~ 3 million reviews

Techniques Used

- **Shingling** 
- **MinHashing** to approximate Jaccard similarity
- **LSH** for sublinear candidate retrieval thanks to banding
- **Prefix Filtering** to reduce unnecessary comparisons


You can find the project’s working notebook and detailed report in this repository.
This project also includes scalability analysis with runtime and precision metrics.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kemahlitos/AmazonBookReviewSimilarity/blob/main/massive_datasets.ipynb)



