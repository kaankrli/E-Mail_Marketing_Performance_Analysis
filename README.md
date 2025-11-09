# 📧 Email Marketing Performance Analysis

This project analyzes **email marketing campaign performance** using **A/B testing** and **Natural Language Processing (NLP)** techniques.  
It is designed for **Google Colab or Jupyter Notebook** and includes both statistical tests and machine learning modeling.

---

## 🧠 Project Overview

- **Goal:** Evaluate which email variant (A/B) performs better in open and click rates.
- **Dataset:** Synthetic dataset with 1,500 rows (`email_campaign_dataset.csv`).
- **Environment:** Google Colab / Jupyter Notebook.
- **Skills Covered:**  
  - Exploratory Data Analysis (EDA)  
  - Hypothesis Testing (Z-test)  
  - Natural Language Processing (tokenization & sentiment)  
  - Logistic Regression (predictive modeling)  
  - Visualization (Seaborn / Matplotlib)

---

## 📊 Dataset Description

| Column | Description |
|--------|--------------|
| `row_id` | Unique identifier |
| `variant` | A/B test group |
| `send_date` | Date email was sent |
| `send_hour` | Hour of the day (0-23) |
| `day_of_week` | Day name |
| `subject_line` | Email subject text |
| `subject_sentiment_score` | Sentiment score (-1 to +1) |
| `word_count_subject` | Subject line word count |
| `opened` | Whether the email was opened (0/1) |
| `clicked` | Whether the link was clicked (0/1) |
| `device` | Device type (Desktop/Mobile/Tablet) |
| `list_segment` | Audience segment (New, Returning, Premium) |

---

## ⚙️ Installation

You can run this notebook directly on **Google Colab**.

```bash
# Optional: install dependencies
!pip install wordcloud scikit-learn seaborn
