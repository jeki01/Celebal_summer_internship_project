News Article Clustering using K-Means
This project groups similar news articles together using unsupervised K-Means clustering. The pipeline includes text preprocessing, feature extraction, clustering, and evaluation.
Project Structure
news-clustering/
├── data/ # Raw news articles (organized by source/date)
│ ├── source1/
│ │ ├── 20230101_title1.txt
│ │ └── ...
├── notebooks/
│ └── News_Clustering.ipynb # Main Jupyter notebook
├── models/ # Saved models
│ ├── kmeans_model.joblib
│ └── tfidf_vectorizer.joblib
└── README.md
 Dependencies

- Python 3.8+
- Required packages:
  ```bash
  pip install pandas numpy scikit-learn nltk matplotlib 


Data Processing Pipeline
1. Data Loading
Reads .txt files from nested directories

Extracts metadata from filenames (date, source)

Sample structure per article:

2. Text Preprocessing
3. Feature Extraction (TF-IDF)
4. Clustering (K-Means)
