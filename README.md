# 🎓 NSAKCET Virtual Assistant Chatbot 🤖

This is a college information chatbot built as a **Capstone Project** under the **Code Unnati Program by Edunet Foundation**, in collaboration with **AICTE** and **IBM SkillsBuild**.

It is designed to answer commonly asked questions about **NSAKCET (Nawab Shah Alam Khan College of Engineering and Technology)** — including fees, admissions, courses, placements, and student life.

---

## 📌 Project Objective

To build a smart virtual assistant using **Natural Language Processing (NLP)** that helps prospective and current students get instant answers to college-related queries.

---

## 🧠 Features

- 📝 Fee structure for UG/PG programs  
- 🎓 Courses and eligibility  
- 🧑‍🎓 Admissions process (UG & PG)  
- 🧑‍💼 Placement and internship support  
- 🏛️ Facilities and student life  
- 🎉 Fests, clubs, and technical communities  
- 📍 Location and contact info  
- 🎯 Fallback and unknown intent handling  

---

## 🛠️ Tech Stack

- **Python 3.11**
- **PyTorch** – for training a simple neural network
- **NLTK** – for tokenization and stemming
- **JSON** – for intent dataset
- **TorchScript** – to save the model

---

## 🗂️ Project Structure

nsakbot/
├── chat.py              # Script to start the chatbot
├── train.py             # Script to train the model
├── model.py             # Neural network model definition
├── nltk_utils.py        # Tokenization, stemming, and bag-of-words functions
├── intents.json         # Dataset with intents, patterns, and responses
├── data.pth             # Trained model saved as a PyTorch file
├── requirements.txt     # List of Python dependencies
├── README.md            # Project documentation
└── venv/      

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/that-ar-guy/nsakbot.git
cd nsakbot
```

2. Create Virtual Environment
```
python -m venv venv
venv\Scripts\activate  # On Windows
```

3. Install Dependencies
```
pip install -r requirements.txt
requirements.txt 
torch
nltk
```

4. Train the Model
```
python train.py
```

5. Start the Chatbot
```
python chat.py
```

## 📈 Sample Questions You Can Ask
"What is the fee structure?"

"Which companies come for placements?"

"Tell me about internships."

"Are there any clubs in college?"

"How to apply for PG courses?"

"Where is NSAKCET located?"

## 🎓 About Code Unnati

This project is developed under the Code Unnati Capstone Project — a digital skilling initiative by Edunet Foundation, supported by SAP.
Learn more: https://codeunnati.edunetfoundation.com

## 🤝 Contributors
Mohammed Abdul Rahman 
Hamza Raza Khan 

NSAKCET – Institutional Support

Edunet Foundation – Capstone Mentorship

## 📬 Contact
📧 Email: info@nsakcet.ac.in
🌐 Website: https://nsakcet.ac.in

## 📄 License
This project is for educational purposes under the Code Unnati Capstone Program.

Let me know if you want to include screenshots, a demo video link, 