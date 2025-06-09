# Sentiment Analysis using TF-IDF and Logistic Regression

This project performs **Sentiment Analysis** on a dataset of customer reviews using **TF-IDF vectorization** and **Logistic Regression**. It is implemented in a Kaggle Jupyter Notebook.

---

## 📌 Objective

To classify customer reviews into **positive** or **negative** sentiments using:
- **Text Preprocessing**
- **TF-IDF Vectorization**
- **Logistic Regression Model**
- **Performance Evaluation**

---

## 📂 Dataset

The dataset used is the [Amazon Fine Food Reviews](https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews) dataset from Kaggle.

**Features used:**
- `review`: The text of the review.
- `sentiment`: Binary label (1 = positive, 0 = negative) derived from review score.

---

## 🔧 Preprocessing

- Removed neutral reviews (Score = 3)
- Cleaned text (lowercase, removed punctuation and digits)
- Converted reviews to TF-IDF features
- Split data into training and test sets

---

## 🧠 Model

- **Model Used**: Logistic Regression
- **Vectorization**: TF-IDF (`max_features=5000`)
- **Training**: 80% Train / 20% Test split

---

## 📊 Evaluation

- **Accuracy Score**
- **Classification Report**
- **Confusion Matrix (visualized using Seaborn)**

---

## ✅ Results

- Achieved high classification accuracy on test data
- Model successfully classifies reviews into positive and negative sentiments

---

## 🛠️ Libraries Used

- `pandas`, `numpy`
- `scikit-learn`
- `matplotlib`, `seaborn`
- `re` (regex)

---

## 💻 How to Use

1. Upload the dataset to your Kaggle notebook.
2. Run all cells in sequence from the provided notebook.
3. View the model's predictions and evaluation metrics.



