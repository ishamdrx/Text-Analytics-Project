# 📊 Text Analytics Project

This project explores the sentiment and topic analysis of Amazon US customer reviews for iPhone 14, 15, and 16 using Natural Language Processing (NLP) in Python, with visualisation via Power BI.

---

## 📌 Objectives

- Classify iPhone reviews into positive, negative, and neutral sentiments.
- Discover major topics (e.g. battery, camera, screen) mentioned in customer feedback.
- Derive insights to improve customer experience and guide product decision-making.

---

## 📁 Project Files

| File Name                    | Description |
|-----------------------------|-------------|
| `Dashboard.pbix`            | Power BI dashboard visualising sentiment trends and topic distributions |
| `Iphone 14,15,16 Reviews on Amazon.xlsx` | Raw dataset of iPhone reviews from Amazon |
| `Raw Review Data.xlsx`      | Cleaned and structured version of the dataset |
| `Data Pre-Processing.ipynb` | Jupyter Notebook for text cleaning and tokenisation |
| `Processed_IpReviews.xlsx`  | Pre-processed review data ready for modelling |
| `Sentiment Analysis.ipynb`  | Jupyter Notebook implementing SVM-based sentiment classification |
| `sentiment_results.xlsx`    | Output sentiment classification results |
| `SentimentAnalysisVisual.ipynb` | Visualisation of sentiment results using Python |
| `Topic Modeling.ipynb`      | Jupyter Notebook for topic discovery using LDA |
| `topic_results.xlsx`        | Output of topic modelling (topic labels, top words) |

---

## ⚙️ Tools & Libraries

- **Python**: `NLTK`, `scikit-learn`, `Gensim`, `pandas`, `matplotlib`
- **Power BI**: For sentiment and topic visualisations
- **Excel**: For data handling and intermediate results

---

## 📈 Methods Used

### 1. Sentiment Analysis
- Technique: **Support Vector Machine (SVM)**
- Output: Labelled sentiments (positive, negative, neutral)

### 2. Topic Modeling
- Technique: **Latent Dirichlet Allocation (LDA)**
- Output: Hidden themes such as **battery**, **screen**, **camera**, **return experience**

---

## 📊 Summary of Findings

- **Positive reviews**: ~67%
- **Negative reviews**: ~25%
- **Neutral reviews**: ~8%
- Common terms: `phone`, `great`, `battery`, `screen`, `buy`, `return`

---

## 📎 License

This project is licensed under the **MIT License** – see the [LICENSE](./LICENSE) file for full terms.

---

## 👤 Author

**Muhamed Hisham bin Mohamed Bahurudeen**  
Class Project @ Universiti Tenaga Nasional (UNITEN)

---

