# Sentiment Analysis on Amazon Reviews

This project applies sentiment analysis to Amazon product reviews using both classical machine learning models and a transformer-based BERT model.

## Project Overview

We aim to classify Amazon product reviews as positive or negative based on their content. The pipeline includes:

- Data cleaning and preprocessing
- Exploratory data analysis (EDA)
- Word cloud visualization
- Classical ML models: Naive Bayes, Logistic Regression, SVM
- Fine-tuned BERT model using Hugging Face Transformers
- Evaluation using precision, recall, F1-score, and accuracy

---

## Dataset

We use the Amazon Review Polarity Dataset, available via Google Drive:

```bash
!gdown --folder https://drive.google.com/drive/folders/1P_T7loBWVaDDl8hRu0W6F5bmwOisQPEv
```

---

## Models Used

| Model                | Accuracy |
|---------------------|----------|
| Naive Bayes         | ~81.7%   |
| Logistic Regression | ~83.2%   |
| SVM                 | ~82.3%   |
| BERT (fine-tuned)   | ~87%     |

---

## Requirements

```bash
pip install -U gdown nltk wordcloud transformers datasets
```

---

## How to Run

1. Download the dataset (via the link above)
2. Open the notebook:
   - Sentiment Analysis on Amazon Reviews.ipynb
3. Run all cells in Colab or Jupyter
4. To test your own reviews, update the text in the prediction section

---

## Folder Structure

```
Sentiment Analysis on Amazon Reviews/
├── Sentiment Analysis on Amazon Reviews.ipynb
├── README.md
├── .gitignore
```

---

## Contact

Created by Meri Asatryan  
For questions or collaboration, reach out via [GitHub](https://github.com/meriasatryan)
