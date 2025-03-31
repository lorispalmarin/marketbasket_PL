# Market Basket Analysis on Amazon Book Reviews 📚
## Authors
- Paola Loi (33088A)
- Loris Palmarin (32349A)

This project was developed for the *Algorithms for Massive Datasets* course (AY 2024/25) and implements Market Basket Analysis using the Amazon Book Reviews dataset.

## Project Overview
We applied two key frequent itemset mining algorithms:
- **Apriori**
- **SON (Savasere, Omiecinski, Navathe)**

Implemented using **PySpark** to handle large-scale data in a distributed and parallel fashion.

## Features
- Efficient data loading and preprocessing
- Distributed frequent itemset mining (pairs and triplets)
- Generation and analysis of **Association Rules** (Support, Confidence, Lift)
- Scalability testing with full and sampled dataset

You can run this notebook directly on [Google Colab](https://colab.research.google.com/) by clicking the badge below:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/lorispalmarin/marketbasket_PL/blob/main/main.ipynb)
