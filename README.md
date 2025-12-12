# 🎬 Movie Sentiment Analysis using Simple RNN

A complete end-to-end **Movie Review Sentiment Analysis** project built using **Recurrent Neural Networks (SimpleRNN)** and deployed with **Streamlit** for easy user interaction.

This project classifies movie reviews as **Positive** or **Negative** using the IMDB dataset.

---

## 🚀 Key Features

* ✔ **SimpleRNN-based Deep Learning model**
* ✔ **Word Embedding layer** for text vectorization
* ✔ **Streamlit Web App Deployment**
* ✔ **Real-time Sentiment Prediction**
* ✔ Clean and modular folder structure
* ✔ Ready for production or learning use

---

## 🧠 Model Overview

The model uses:

* **Embedding Layer** → Converts words into dense vectors
* **SimpleRNN(128)** → Learns sequential patterns
* **Dense(sigmoid)** → Outputs binary sentiment
* **Binary Crossentropy Loss**

A perfect project to understand fundamentals of RNNs.

---

## ⚙️ Installation & Setup

Clone the repository:

```bash
git clone https://github.com/your-username/movie_sentiment_Rnn.git
cd movie_sentiment_Rnn
```

Install dependencies:

```bash
pip install -r requirement.txt
```

---

## ▶️ Training the Model

Run:

```bash
python main.py
```

This will:

* Load IMDB dataset
* Tokenize & pad sequences
* Train SimpleRNN
* Save:

  * `rnn_model.h5`
  * `tokenizer.pkl`
  * `embedding_matrix.npy` (if used)

---

## 🌐 Running the Streamlit App

Once the model is trained and saved:

```bash
streamlit run app.py
```

The UI allows you to:

* Enter a movie review
* Process it through tokenizer + embeddings
* Get a **Positive/Negative** prediction instantly

---

## 📝 Example Prediction

```
Input: "The storyline was beautiful and emotional."
Output: Positive 😊
```

```
Input: "The movie was boring and predictable."
Output: Negative 👎
```

---

## 🔧 Future Enhancements

* Add GRU and LSTM model versions
* Add charts for loss/accuracy in Streamlit
* Deploy to HuggingFace Spaces / Render
* Add language support (Hindi + English Tamil sentiment)

