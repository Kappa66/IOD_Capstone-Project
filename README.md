# Amazon Book Reviews Sentiment & Topic Analysis

## 📖 Project Overview  
This capstone applies NLP and machine learning to a 51 876-review Kaggle dataset of Amazon book reviews. It automatically classifies sentiment, discovers recurring complaint & praise themes, and delivers actionable insights for Support, Product/Editorial, and Marketing teams.

---

## 🎯 Objectives  
- **Automate Sentiment Classification**  
  - Predict positive vs. negative reviews with high recall on the negative class.  
- **Uncover Thematic Insights**  
  - Use LDA to surface top themes in positive and negative reviews.  
- **Drive Business Action**  
  - Map themes to stakeholder-owned recommendations (e.g. format fixes, marketing advisories).

---

## 🚀 Features  
- **Data Preparation**  
  - Merge book metadata & review tables  
  - Filter to high-volume, recent titles  
  - Text cleaning: regex, Unicode normalization, stop-word removal, lemmatization  
- **Feature Engineering**  
  - TF-IDF (unigrams & bigrams)  
  - VADER polarity scores, review word counts 
- **Topic Modeling**  
  - LDA on positive & negative corpora (7 topics each)  
  - Human-readable theme labels  
- **Sentiment Classification**  
  - Stack ensemble (RandomForest, XGBoost, SVM → LogisticRegression meta-learner)  
  - Negative recall improved from ~50 % → 73 %  
- **Business Recommendations**  
  - Themed recommendations (e.g. QA workflows, content advisories, abridged editions)  
  - Stakeholder mapping for targeted action

---

