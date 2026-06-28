# 🎬 IMDB Sentiment Analysis using LSTM

## 📌 Overview

This project presents an end-to-end **Deep Learning based Sentiment Analysis System** designed to classify IMDb movie reviews into **Positive** or **Negative** sentiment categories using an **LSTM (Long Short-Term Memory) Neural Network**.

The project demonstrates the complete NLP workflow including **data preprocessing, sequence preparation, model development, training, evaluation, and prediction**.

By leveraging sequence modeling capabilities of LSTM networks, the system captures contextual relationships within text and delivers accurate sentiment classification.

---

# 🎯 Project Objectives

This project aims to:

* Perform sentiment classification on movie reviews
* Process raw textual data into machine-readable sequences
* Build an LSTM-based Deep Learning model
* Analyze sentiment distribution
* Evaluate classification performance
* Demonstrate practical Natural Language Processing (NLP)

---

# 📊 Dataset

Dataset Used: **IMDb Movie Reviews Dataset**

The dataset consists of labeled movie reviews.

## Target Classes

| Label    | Meaning                 |
| -------- | ----------------------- |
| Positive | Positive user sentiment |
| Negative | Negative user sentiment |

---

## Dataset Characteristics

| Feature     | Description                 |
| ----------- | --------------------------- |
| Review Text | Original movie review       |
| Sentiment   | Target classification label |

---

# ⚙️ Technologies Used

| Category                | Tools              |
| ----------------------- | ------------------ |
| Programming             | Python             |
| Deep Learning           | TensorFlow / Keras |
| Data Processing         | Pandas, NumPy      |
| Visualization           | Matplotlib         |
| Evaluation              | Scikit-learn       |
| Development Environment | Google Colab       |

---

# 🏗 Project Workflow

## 1️⃣ Data Exploration & Analysis

Initial exploration was performed to understand dataset quality and sentiment distribution.

### Steps:

* Loaded dataset
* Inspected structure
* Checked null values
* Performed exploratory analysis
* Reviewed sentiment balance

---

## 2️⃣ Data Preprocessing

Text data was transformed into a format suitable for neural network training.

### Processing Pipeline

| Step         | Description                            |
| ------------ | -------------------------------------- |
| Cleaning     | Removed unnecessary symbols            |
| Tokenization | Converted text into sequences          |
| Padding      | Standardized sequence length           |
| Encoding     | Converted labels into numerical values |

---

## 3️⃣ Deep Learning Model

A sequence-based neural network architecture was implemented.

### Model Architecture

| Layer           | Purpose              |
| --------------- | -------------------- |
| Embedding Layer | Text representation  |
| LSTM Layer      | Sequence learning    |
| Dense Layer     | Classification       |
| Output Layer    | Sentiment prediction |

---

# 🧠 Model Training Pipeline

```text
IMDb Reviews
      ↓
Text Cleaning
      ↓
Tokenization
      ↓
Sequence Padding
      ↓
Train-Test Split
      ↓
Embedding Layer
      ↓
LSTM Network
      ↓
Prediction
      ↓
Evaluation
```

---

# 📊 Methodology

| Stage          | Description                      |
| -------------- | -------------------------------- |
| Data Analysis  | Exploratory Data Analysis (EDA)  |
| Preprocessing  | Text cleaning and transformation |
| Model Building | LSTM sequence model              |
| Evaluation     | Accuracy and confusion matrix    |

---

# 📈 Model Evaluation

Model performance was evaluated using standard classification metrics.

| Metric           | Purpose                              |
| ---------------- | ------------------------------------ |
| Accuracy         | Overall prediction quality           |
| Confusion Matrix | Classification performance           |
| Precision        | Positive prediction quality          |
| Recall           | Sensitivity measurement              |
| F1 Score         | Balance between precision and recall |

---

# 📉 Results

The LSTM model successfully achieved strong performance in sentiment classification by capturing contextual information from review sequences.

### Achievements

✅ Built complete NLP pipeline
✅ Applied sequence modeling with LSTM
✅ Generated sentiment predictions
✅ Evaluated model performance
✅ Demonstrated practical Deep Learning workflow

---

# 🔍 Example Predictions

| Review                                          |
| ----------------------------------------------- |
| "This movie was incredible!" → 😊 Positive      |
| "Worst film I have ever watched." → 😡 Negative |

---

# 🖼 Workflow Visualization

<img width="1536" height="1024" alt="Work Flow" src="https://github.com/user-attachments/assets/07488b44-2a8a-4ffd-ad96-de65540ee196" />


```text
Data → Preprocessing → Tokenization → LSTM → Prediction → Evaluation
```

(See images folder for workflow image)

---

# 🚀 Future Improvements

| Enhancement           | Expected Benefit            |
| --------------------- | --------------------------- |
| Bidirectional LSTM    | Better context learning     |
| Attention Mechanism   | Improved text understanding |
| Transformer Models    | Higher performance          |
| Deployment            | Web application integration |
| Hyperparameter Tuning | Better optimization         |

---

# 📂 Project Structure

```bash
IMDB-Sentiment-Analysis/
│
├── dataset/
│
├── notebook/
│
├── images/
│
├── model/
│
├── README.md
│
└── requirements.txt
```

---

# 👩‍💻 Author

**Minal Sadiq**


---

⭐ If you found this project useful, consider giving it a star.
