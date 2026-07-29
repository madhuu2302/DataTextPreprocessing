# 📝 LLM Text Preprocessing using Python

## 📌 Project Overview
This project demonstrates the basic text preprocessing steps used in Large Language Models (LLMs) and Natural Language Processing (NLP). It takes raw text as input, cleans the text using Python and Regular Expressions (Regex), and prepares it for further analysis or machine learning tasks.

---

## 🚀 Features
- Read raw text
- Convert text to lowercase
- Search patterns using Regular Expressions
- Extract numbers using `re.findall()`
- Split text into words using `re.split()`
- Remove HTML tags
- Remove URLs
- Remove Email IDs
- Remove @mentions
- Remove Hashtags
- Remove Numbers
- Remove Special Characters and Emojis
- Remove Extra Spaces
- Save cleaned data as a CSV file

---

## 🛠️ Technologies Used
- Python 3
- Pandas
- Regular Expressions (re)
- NLTK

---

## 📂 Project Structure

```
LLM-Text-Preprocessing/
│── rawtext.txt
│── preprocessing.py
│── cleaned_data.csv
│── README.md
```

---

## ▶️ How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/LLM-Text-Preprocessing.git
```

2. Open the project folder.

3. Install the required libraries.

```bash
pip install pandas nltk
```

4. Run the Python program.

```bash
python preprocessing.py
```

---

## 📥 Input

The input is a raw text file (`rawtext.txt`) containing text with:
- URLs
- Email IDs
- Phone Numbers
- Emojis
- HTML Tags
- Hashtags
- @Mentions
- Special Characters
- Extra Spaces

---

## 📤 Output

The program generates:
- Cleaned text
- Tokenized words
- Cleaned CSV file (`cleaned_data.csv`)

---

## 📸 Sample Output

### Original Text

```
🤖 AI is transforming the world! Visit https://openai.com
Email: support@example.com
#AI @OpenAI
```

### Cleaned Text

```
ai is transforming the world visit email ai
```

---

## 📚 Learning Outcomes

- Understand text preprocessing
- Learn Regular Expressions (Regex)
- Apply text cleaning techniques
- Prepare text for NLP and LLM applications

---

## 👩‍💻 Author

**Madhumitha**

B.Sc. Computer Science with Artificial Intelligence
