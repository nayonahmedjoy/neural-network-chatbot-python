# Neural Network Chatbot (Python)

An intent-based gaming information chatbot built **from scratch** using Python, NLTK, and TensorFlow.  
This project focuses on understanding **Natural Language Processing (NLP)** fundamentals rather than using pre-built AI APIs.

---

## 🚀 Project Overview

The Gaming Info Chatbot is designed to answer gaming-related questions such as:
- Popular games
- Game genres (FPS, RPG, Multiplayer, etc.)
- Gaming platforms (PC, Console, Mobile)
- Basic chatbot interactions (greetings, thanks, goodbye)

The chatbot uses a **Bag-of-Words model** and a **Neural Network classifier** to predict user intent and respond accordingly.

---

## 🧠 How It Works

1. User input is tokenized and lemmatized using **NLTK**
2. Text is converted into a **Bag-of-Words vector**
3. A trained **Neural Network model** predicts the intent
4. A random response is selected from the matched intent

---

## 🛠️ Technologies Used

- **Python**
- **NLTK** (tokenization & lemmatization)
- **TensorFlow / Keras** (neural network model)
- **NumPy**
- **Pickle** (saving words & classes)
- **Git & GitHub**
- **Linux environment**

---

## 📁 Project Structure

```
python-chatbot/
│
├── chatbot.py        # Chat runtime (user interaction)
├── new.py            # Model training script
├── intents.json     # Gaming-related dataset
├── README.md        # Project documentation
└── .gitignore       # Ignored files (venv, models, cache)
```

---

## ▶️ How to Run the Project

### 1️⃣ Install dependencies
```bash
pip install nltk tensorflow numpy
```

### 2️⃣ Download NLTK data (first time only)
```python
import nltk
nltk.download('punkt')
nltk.download('punkt_tab')
nltk.download('wordnet')
```

### 3️⃣ Train the model
```bash
python new.py
```

This will generate:
- `chatbot_model.h5`
- `words.pkl`
- `classes.pkl`

### 4️⃣ Run the chatbot
```bash
python chatbot.py
```

---

## 🎯 Purpose of This Project

- Strengthen understanding of NLP fundamentals
- Learn intent classification using neural networks
- Practice building ML projects **without using GPT or APIs**
- Showcase a real, hands-on project for a developer portfolio

---

## 🔮 Future Improvements

- Add confidence threshold to avoid wrong answers
- Expand gaming dataset with more intents
- Improve response variety
- Add GUI or web interface
- Store unknown queries for retraining

---

## 📜 License

This project is open-source and created for educational and portfolio purposes.

---

## 🙌 Author

**Nayon Ahmed**  
Linux user | Python learner | NLP enthusiast  
GitHub: https://github.com/nayonahmedjoy
