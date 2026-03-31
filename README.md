# 🚀 EXPERIMENT – 15  
# NLP TECHNIQUES ON TEXT DATA USING PYTHON  

---

## 👨‍🎓 STUDENT DETAILS  

**Name:** Asit Kumar Srivastava  
**PRN:** 25070123026  
**Batch:** A2  
**Subject:** Exploratory Data Analysis using Python  

---

## 🎯 AIM  

To implement fundamental Natural Language Processing (NLP) techniques on text data using Python and the NLTK library.

---

## 🎓 OBJECTIVES  

• To understand basic NLP concepts  
• To perform tokenization (word and sentence level)  
• To remove stopwords from text data  
• To implement stemming and lemmatization  
• To perform Part-of-Speech (POS) tagging  
• To analyze word frequency distribution  

---

## 📚 THEORY  

### 🔹 Natural Language Processing (NLP)  

Natural Language Processing (NLP) is a field of Artificial Intelligence that enables computers to understand, interpret, and process human language.

It is widely used in:
• Chatbots  
• Search engines  
• Text classification  
• Sentiment analysis  

---

### 🔹 Tokenization  

Tokenization is the process of breaking text into smaller units called tokens.

Types:
• Word Tokenization → Splits text into words  
• Sentence Tokenization → Splits text into sentences  

---

### 🔹 Stopwords Removal  

Stopwords are commonly used words such as:
“is”, “the”, “in”, etc., which do not add significant meaning.

Removing them:
• Reduces noise  
• Improves processing efficiency  

---

### 🔹 Stemming  

Stemming reduces words to their root form by removing suffixes.

Example:
playing → play  
fighting → fight  

Note: Output may not always be a valid word.

---

### 🔹 Lemmatization  

Lemmatization converts words into their base (dictionary) form.

Example:
running → run  
better → good  

It is:
• More accurate than stemming  
• Context-aware  

---

### 🔹 Part-of-Speech (POS) Tagging  

POS tagging assigns grammatical labels to words such as:
• Noun (NN)  
• Verb (VB)  
• Adjective (JJ)  

---

### 🔹 Frequency Distribution  

Used to count occurrences of words in text data.

Helps in:
• Identifying important words  
• Text analysis  

---

## 🧠 METHODOLOGY / IMPLEMENTATION  

### 🔸 Step 1: Installing and Importing Libraries  

```python
import nltk
nltk.download('punkt')
nltk.download('stopwords')
nltk.download('wordnet')
```

---

### 🔸 Step 2: Word Tokenization  

```python
from nltk.tokenize import word_tokenize
tokens = word_tokenize(text)
```

---

### 🔸 Step 3: Sentence Tokenization  

```python
from nltk.tokenize import sent_tokenize
sentences = sent_tokenize(text)
```

---

### 🔸 Step 4: Stopwords Removal  

```python
from nltk.corpus import stopwords
filtered_words = [w for w in words if w.lower() not in stop_words]
```

---

### 🔸 Step 5: Stemming  

```python
from nltk.stem import PorterStemmer
stemmer.stem(word)
```

---

### 🔸 Step 6: Lemmatization  

```python
from nltk.stem import WordNetLemmatizer
lemmatizer.lemmatize(word)
```

---

### 🔸 Step 7: POS Tagging  

```python
from nltk import pos_tag
pos_tag(words)
```

---

### 🔸 Step 8: Frequency Distribution  

```python
from nltk.probability import FreqDist
fd.most_common()
```

---

## ⚙️ KEY LIBRARIES USED  

```python
nltk
```

---

## 📊 OBSERVATIONS  

• Tokenization successfully splits text into meaningful units  
• Stopword removal improves clarity of text  
• Stemming reduces words but may produce non-standard outputs  
• Lemmatization provides accurate base forms  
• POS tagging helps understand grammatical structure  
• Frequency distribution highlights important words  

---

## ✅ RESULT  

All basic NLP techniques including tokenization, stopword removal, stemming, lemmatization, POS tagging, and frequency analysis were successfully implemented using Python.

---

## 💡 LEARNING OUTCOMES  

• Gained understanding of core NLP techniques  
• Learned text preprocessing methods  
• Implemented real-world text analysis operations  
• Developed foundation for advanced NLP applications  

---
