# 📧 Spam Detection using Deep Learning (NLP)

A minimal **Natural Language Processing (NLP)** project that detects whether an SMS message is **Spam or Ham (Not Spam)** using a deep learning model.

This project demonstrates a complete NLP workflow including **text preprocessing, tokenization, word embeddings, model training, and evaluation** implemented inside a single Jupyter Notebook.

---

# 🚀 Project Overview

Spam messages are a common problem in messaging platforms. This project builds a **binary classification model** that predicts whether a message is spam.

The model is trained on the **SMS Spam Collection Dataset** and uses a deep learning architecture based on **Embedding and LSTM layers**.

The project is intentionally designed to be **minimal and easy to understand**, with the entire pipeline implemented in a single notebook.

---

# 📂 Project Structure

```

spam-detection-nlp/
│
├── notebooks/
│ └── spam_detection.ipynb
│
├── results/
│ ├── class_distribution.png
│ ├── wordcloud_spam.png
│ ├── wordcloud_ham.png
│ ├── confusion_matrix.png
│ └── training_curve.png
├── LICENSE
└── README.md

```

---

# 📊 Dataset

This project uses the **SMS Spam Collection Dataset**, which contains labeled SMS messages.

Each message belongs to one of two classes:

- **Ham (0)** → Normal message  
- **Spam (1)** → Unwanted or promotional message  

The dataset is loaded directly using the **datasets library**, so no manual dataset download is required.

---

# 🧠 Model Architecture

```

Embedding Layer
↓
LSTM Layer
↓
Dropout
↓
Dense Layer (Sigmoid)

```

---


# 🧪 Layer Description

**Embedding Layer**  
Transforms words into dense vector representations.

**LSTM Layer**  
Captures sequential relationships in the text.

**Dropout Layer**  
Reduces overfitting during training.

**Dense Layer with Sigmoid**  
Performs binary classification (Spam vs Ham).

---

# 🔎 NLP Pipeline

The notebook implements the following pipeline:

1. Load dataset
2. Exploratory Data Analysis
3. Text preprocessing
4. Tokenization
5. Sequence padding
6. Train/test split
7. Model training
8. Model evaluation
9. Visualization of results

---

# 📈 Generated Visualizations

The notebook automatically generates and saves the following visual outputs:

| Visualization | Description |
|---|---|
| `class_distribution.png` | Distribution of spam vs ham messages |
| `wordcloud_spam.png` | Most common words in spam messages |
| `wordcloud_ham.png` | Most common words in normal messages |
| `training_curve.png` | Training vs validation accuracy |
| `confusion_matrix.png` | Model performance visualization |

All visualizations are saved inside the **outputs/** folder.

---

# 🛠 Technologies Used

- Python
- TensorFlow / Keras
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- WordCloud
- HuggingFace Datasets

---

# 🎯 Learning Outcomes

This project demonstrates:

- Natural Language Processing fundamentals
- Text preprocessing techniques
- Word embeddings
- Sequence modeling with LSTM
- Binary text classification
- Model evaluation and visualization

---

# 📜 License

This project is open-source and available under the MIT License.

---

# 👨‍💻 Author

Rajarshi Saha