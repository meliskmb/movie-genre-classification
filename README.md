
# Movie Genre Classification

This project is a machine learning pipeline designed to classify movie genres using IMDb's Top 1000 movie dataset. The pipeline includes text preprocessing, feature extraction, and classification using machine learning models.

## Dataset

- **Source:** IMDb Top 1000 Movies dataset  
- **Format:** CSV file (`imdb_top_1000.csv`)  
- **Features used:**
  - Movie title
  - Description (Overview)
  - Genre
  - Metadata such as director, cast, etc.

## ML Pipeline

1. **Data Loading & Cleaning**
   - Dataset is loaded from Google Drive
   - Basic cleaning and missing value handling

2. **Text Preprocessing**
   - Tokenization, stopword removal
   - Lemmatization using spaCy
   - Natural Language Toolkit (NLTK) support

3. **Feature Extraction**
   - TF-IDF vectorization applied on movie descriptions

4. **Modeling**
   - Classification model(s) such as Logistic Regression, Naive Bayes, etc.
   - Evaluation metrics (Accuracy, F1-score)

## Technologies

- Python
- Pandas, NumPy
- Scikit-learn
- NLTK & spaCy
- Google Colab

## Project Status

Data loaded and preprocessed  
TF-IDF vectorization implemented  
Model training and evaluation completed

## Getting Started

1. Clone the repository  
2. Upload the dataset to Google Drive  
3. Open the notebook in Google Colab  
4. Mount your drive and run the cells sequentially  

## Note

This notebook assumes that the dataset file is located in:

```
/content/drive/My Drive/CSV Dosyaları/imdb_top_1000.csv
```

Update the path accordingly if your directory is different.
