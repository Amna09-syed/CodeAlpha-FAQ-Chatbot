# CodeAlpha-FAQ-Chatbot
NLP-powered FAQ chatbot using TF-IDF and cosine similarity with Tkinter GUI
# 🤖 FAQ Chatbot (CodeAlpha Internship Project)

An **NLP-powered FAQ Chatbot** built using **Python, Tkinter, and Machine Learning** that intelligently matches user questions with predefined answers.

---

## 🚀 Features

* 💬 Interactive chat-based UI
* 🧠 NLP-based question matching
* 📊 TF-IDF + Cosine Similarity
* ⚡ Smart confidence threshold (avoids wrong answers)
* 📋 FAQ list with clickable questions
* ⌨️ Typing indicator for realistic experience
* 🔄 Suggestion buttons for quick interaction
* 🧵 Multithreading (smooth UI)

---

## 🛠️ Technologies Used

* Python
* Tkinter (GUI)
* NLTK (Natural Language Processing)
* Scikit-learn (Machine Learning)
* TF-IDF Vectorization
* Cosine Similarity

---

## 📦 Installation

### 1. Clone the repository

```bash id="clonefaq"
git clone https://github.com/yourusername/CodeAlpha-FAQ-Chatbot.git
cd CodeAlpha-FAQ-Chatbot
```

### 2. Install dependencies

```bash id="installfaq"
pip install nltk scikit-learn
```

---

## ▶️ How to Run

```bash id="runfaq"
python faq_chatbot.py
```

---

## 🧠 How It Works

1. **Text Preprocessing**

   * Lowercasing
   * Tokenization
   * Stopword removal
   * Lemmatization

2. **TF-IDF Vectorization**

   * Converts questions into numerical vectors

3. **Similarity Matching**

   * Uses cosine similarity to find best match

4. **Confidence Threshold**

   * If similarity is low, bot refuses to guess

---

## 💬 Chatbot Features

* Chat bubbles (User vs Bot)
* Confidence score with each response
* FAQ suggestion buttons
* Scrollable chat history
* Typing simulation

---

## 📁 Project Structure

```bash id="structurefaq"
CodeAlpha-FAQ-Chatbot/
│── faq_chatbot.py
│── README.md
│── images/
    └── chatbot_output.png
```

---

## 📸 Output Preview

![Chatbot Output](images/chatbot_output.png)

---

## 🔧 How to Extend

You can add more FAQs by editing:

```python id="faqedit"
FAQ_DATA = [
    {"question": "...", "answer": "..."}
]
```

---

## 🎯 Internship Project

This project demonstrates:

* NLP techniques
* Machine learning concepts
* GUI development
* Real-world chatbot logic

---

## 👩‍💻 Author

**Amna Manal**

---

## 📸 Output Preview

![Chatbot UI](images/chatbot_output.png)!![WhatsApp Image 2026-04-09 at 7 51 26 PM](https://github.com/user-attachments/assets/21d6ccee-5df9-49af-aff6-6478acb47a33)

![WhatsApp Image 2026-04-09 at 7 52 05 PM](https://github.com/user-attachments/assets/30ac778d-713f-4665-a8af-154c56de83f7)


