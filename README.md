# AI Fake News Detector

This repository contains our final project for **CAP 4630 042 – Intro to Artificial Intelligence** class.  
Our goal is to build a simple AI model that classifies news headlines as **Fake** or **Real** using Natural Language Processing (NLP) and machine learning.
- The final and complete version of this project is "Fake_News_Detector_V6.ipynb".
- Recorded Presentation: https://youtu.be/IlczHIGsbIY

---

## Team

- Azaan Fatta  
- Stone Harward  
- Juan Ramirez Castrejon  
- Connor Delk  
- Dominique Penney  

---

##  Project Overview

Online misinformation and fake news spread quickly and can be difficult to detect manually.  
In this project, we:

- Use a labeled dataset of real and fake news articles
- Focus on the **headline text**
- Convert text into numerical features using **TF-IDF**
- Train a **Logistic Regression** classifier
- Evaluate the model using Accuracy, Precision, Recall, F1 Score, and a Confusion Matrix
- Built a small demo that predicts Fake vs Real for custom input headlines

---

## Dataset

We use the **Fake and Real News** dataset from Kaggle:

- Kaggle dataset:  
  https://www.kaggle.com/datasets/jainpooja/fake-news-detection

From this dataset, we use the following two CSV files:

- `Fake.csv` – fake news articles/headlines  
- `True.csv` – real news articles/headlines  

Because these files are large and exceed GitHub’s upload limits, we host them on Google Drive:

- **Fake.csv (Google Drive):**  
  https://drive.google.com/file/d/1sQV8Tp5zwnOfdQzEEDh0BsEmn3gGSBVH/view?usp=drive_link  

- **True.csv (Google Drive):**  
  https://drive.google.com/file/d/1Gm_bDcNVSRICLuptLHJfEuNqQoGgKHWW/view?usp=drive_link  


---

## Repository Contents

- `Fake_News_Detector_V6.ipynb`  
  Main Jupyter/Colab notebook containing:
  - Data loading (from Google Drive links)
  - Data preparation and cleaning
  - TF-IDF vectorization
  - Model training (Logistic Regression)
  - Evaluation (metrics + confusion matrix)
  - Demo section for custom headline predictions

- `README.md`  
  This file – project description, setup, and instructions.

---

## Dependencies

The notebook is designed to run in **Google Colab**, which already includes most libraries.  
The main Python packages used are:

- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn`

If you run this locally instead of Colab, you can install them with:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
