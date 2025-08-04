
# 🍽️ Restaurant Review Sentiment Analysis

## 📋 Project Description

This project is a sentiment analysis of restaurant reviews. The main objective is to automatically classify customer reviews into two categories: **positive** or **negative**, using Natural Language Processing (NLP) techniques and machine learning models.

🔁 The workflow includes:

1. 🧹 **Text Data Preprocessing:** Cleaning and tokenizing the reviews.  
2. 📊 **Exploratory Data Analysis (EDA):** Identifying the most common words and bigrams in each sentiment category.  
3. 🧮 **Text Vectorization:** Converting the reviews into a numerical format using TF-IDF.  
4. 🤖 **Model Selection and Evaluation:** Training and hyperparameter tuning for Logistic Regression and LinearSVC models, with cross-validation.

## 📁 Repository Structure

* 📓 `nlp_analysis_sentiment.ipynb`: The Jupyter notebook containing all the code and analysis.  
* 📄 `README.md`: This file.  
* 📂 `dataset.csv`: The original dataset (assuming it is in the repository).

## ⚙️ Requirements

Make sure you have the following Python libraries installed. You can install them using pip:

```bash
pip install pandas scikit-learn nltk
```

## ▶️ Steps to Run the Code

1. 🌀 **Clone the repository:**

```bash
   git clone <repository_URL>
```
## 🧭 Open the Notebook

Open the `nlp_analysis_sentiment.ipynb` notebook in your preferred development environment (Jupyter Notebook, JupyterLab, VS Code).

## ⚡ Run the Code

Run the notebook cells in order to replicate the analysis.

---

## 📈 Results and Conclusion

Two linear classification models (**Logistic Regression** and **LinearSVC**) were trained and evaluated using cross-validation and hyperparameter tuning.

### 🏆 Best Model Metrics:

| 📊 Metric               | 🔁 Logistic Regression | 🔀 LinearSVC |
|------------------------|------------------------|-------------|
| 🎯 Accuracy             | 0.795                  | 0.795       |
| 🎯 Precision (Negative) | 0.77                   | 0.77        |
| 🎯 Recall (Negative)    | 0.82                   | 0.81        |
| 🎯 F1-Score (Negative)  | 0.79                   | 0.79        |
| 🎯 Precision (Positive) | 0.82                   | 0.82        |
| 🎯 Recall (Positive)    | 0.77                   | 0.78        |
| 🎯 F1-Score (Positive)  | 0.80                   | 0.80        |

---

## 🧾 Conclusion

Both the **Logistic Regression** and **LinearSVC** models showed nearly identical performance after hyperparameter tuning.  
Both are excellent choices for this sentiment classification problem.  
✅ Either one can be selected as the final model for predicting new reviews.