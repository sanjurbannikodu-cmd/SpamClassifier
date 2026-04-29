# 📧 Spam Message Classifier

A simple Machine Learning web application that classifies text messages as **Spam** or **Not Spam (Ham)** using Natural Language Processing techniques.

This project includes a clean user interface built with Gradio and a text classification model trained on labeled SMS data.

---

## 🚀 Features

* Classifies messages as **Spam** or **Ham**
* Displays prediction confidence
* Interactive web interface
* Easy to run locally or in Google Colab
* Lightweight and beginner-friendly

---

## 🧠 Tech Stack

* Python
* Scikit-learn
* Pandas
* Gradio (for UI)

---

## 📂 Dataset

This project uses a labeled SMS dataset with two columns:

* `v1` → Label (`spam` or `ham`)
* `v2` → Message text

Example:

```
ham, Hey how are you?
spam, Congratulations! You won a prize!
```

---

## ⚙️ How It Works

1. Text data is converted into numerical features using **TF-IDF Vectorization**
2. A **Naive Bayes classifier** is trained on the dataset
3. User input is transformed and passed to the model
4. The model predicts whether the message is spam or not

---

## ▶️ Installation & Setup

### 1. Clone the repository

```
git clone https://github.com/your-username/spam-classifier.git
cd spam-classifier
```

### 2. Install dependencies

```
pip install -r requirements.txt
```

### 3. Run the app

```
python app.py
```

---

## 💻 Usage

* Upload or load the dataset
* Enter a message in the input box
* Click **Submit**
* View prediction and confidence score

---

## 📸 Demo

(Add screenshots or demo GIF here)

---

## 📈 Future Improvements

* Use advanced models (Logistic Regression, SVM, Deep Learning)
* Add text preprocessing (stemming, stopword removal)
* Deploy to cloud (Hugging Face Spaces / Render)
* Improve UI/UX design

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repo and submit a pull request.

---

## 📜 License

This project is open-source and available under the MIT License.

---


