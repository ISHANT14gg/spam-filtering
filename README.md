# 📧 Spam Filtering using Machine Learning (Naive Bayes)

This project implements an SMS Spam Classifier using **TF-IDF text features** and a **Multinomial Naive Bayes model**.  
It processes SMS messages and predicts whether the message is **SPAM** or **HAM** with a probability score.

---

## 🚀 Features

- Clean and reproducible **Google Colab notebook**
- Text preprocessing using **TF-IDF Vectorizer**
- Classification using **Naive Bayes**
- Supports **custom user input** to classify messages
- Includes **accuracy**, **precision**, **recall**, and **F1-score** evaluation
- Lightweight — no NLTK required

---

## ▶️ Run on Google Colab

You can run the project directly in Google Colab:

1. Open the Colab notebook (`spam_filtering.ipynb`)
2. Upload the dataset file: **spam.csv**
3. Run all cells (Runtime → Run all)
4. Use the final cell to test custom messages

> This makes the project runnable without installing anything locally.

---

## 🛠️ Run Locally

### 1. Clone the repository
```bash
git clone https://github.com/ISHANT14gg/spam-filtering.git
cd spam-filtering
2. Install dependencies
pip install pandas scikit-learn joblib

3. Run the notebook

Launch Jupyter Notebook or VS Code and open:

spam_filtering.ipynb


Run all cells to train the model and test predictions.

📊 Model Performance (Example Results)

Accuracy: ~82%

Spam Precision: ~88%

Spam Recall: ~65%

Ham Precision: ~94%

Ham Recall: ~98%

⭐ Key Strength

The model has very low false positives — meaning it rarely marks normal messages as spam, which is crucial in real-world systems.

📝 Example Predictions
Input:
"Congratulations! You won a free ticket. Click this link now."

Output:
Spam Probability: 97.45%
Prediction: SPAM

Input:
"Hey, I will reach home in 10 minutes."

Output:
Spam Probability: 3.14%
Prediction: HAM

📂 Project Structure
File	Description
spam_filtering.ipynb	Updated end-to-end notebook for Colab & local use
spam.csv	SMS Spam Collection dataset
README.md	Project documentation
🧠 Technologies Used

Python

Pandas

Scikit-learn

TF-IDF Vectorizer

Multinomial Naive Bayes

Joblib (model persistence)
