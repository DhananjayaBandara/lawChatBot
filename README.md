## Chatbot for Sri Lankan Law 🏛️

### Overview
This is a simple chatbot built using Python and Natural Language Processing (NLP) techniques. The chatbot is designed to answer queries related to Sri Lankan law by referring to a legal text document. It uses **TF-IDF vectorization** and **cosine similarity** to match user queries with relevant information from the document.

### Features
✅ Answers questions about Sri Lankan law  
✅ Uses **TF-IDF and cosine similarity** for response generation  
✅ Simple and lightweight, requiring only **NLTK** and **scikit-learn**  
✅ Pretrained on a **Sri Lankan law text document**  

### Technologies Used
- **Python** 🐍
- **NLTK (Natural Language Toolkit)**  
- **Scikit-learn**  
- **TF-IDF Vectorization**  
- **Cosine Similarity for response generation**  

---

## Installation & Setup 🚀

1️⃣ **Clone the repository**  
```bash
git clone https://github.com/DhananjayaBandara/lawChatBot/
cd chatbot-sri-lankan-law
```

2️⃣ **Install dependencies**  
```bash
pip install nltk scikit-learn
```

3️⃣ **Download required NLTK packages** (if running for the first time)  
```python
import nltk
nltk.download('punkt')
nltk.download('wordnet')
```

4️⃣ **Run the chatbot**  
```bash
python chatbot_NLP.py
```

---

## How It Works 🤖
1️⃣ The chatbot reads **chatbot.txt**, which contains information about Sri Lankan law.  
2️⃣ It tokenizes the text into **sentences and words** for processing.  
3️⃣ If a user greets the chatbot (e.g., "Hello", "Hi"), it responds with a friendly greeting.  
4️⃣ For legal queries, it calculates **TF-IDF similarity** between the user's question and sentences in the document.  
5️⃣ The chatbot returns the most relevant sentence from **chatbot.txt**.  

---

## Example Usage 📝
```
User: What is the definition of law?
ROBO: Law can be defined as a system of rules used for controlling formal human behaviour and human activities in a community or in a country.
```

```
User: What are the types of laws in Sri Lanka?
ROBO: According to the way that laws are exercised, they are classified as domestic and international law.
```

---

## Future Improvements 🔧
- Enhance **accuracy** using deep learning models (e.g., **BERT**).  
- Implement a **web-based interface** using Flask or FastAPI.  
- Expand knowledge base with more **legal sources**.  
- Add **voice interaction** for accessibility.  

---

## Contribution 🤝
Feel free to **fork** the repository and submit **pull requests**. Suggestions and contributions are always welcome!  

📩 For inquiries, contact me at prasannadananjaya7@gmail.com  

---

### License 📜
This project is **open-source** and available under the **MIT License**.

