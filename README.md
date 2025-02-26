# **Sentiment Analysis on Social Media Data** 📊🔍  

🚀 **Project Overview**  
This project analyzes public sentiment towards specific topics, products, or events using **Natural Language Processing (NLP)**. We leverage **Twitter data** to extract sentiment scores, classify tweets, and visualize sentiment trends.  

---

## **📌 Features & Methodology**  

### 1️⃣ **Data Preprocessing**  
✔ Removed **special characters, URLs, mentions, and hashtags**  
✔ Converted text to **lowercase**  
✔ Removed **stopwords** using NLTK  

### 2️⃣ **Sentiment Analysis**  
✔ Used **VADER (Valence Aware Dictionary and sEntiment Reasoner)** to classify tweets as **Positive, Negative, or Neutral**  
✔ Extracted **sentiment scores** for deeper insights  

### 3️⃣ **Keyword & NLP Analysis**  
✔ Identified **most common words** in positive and negative tweets  
✔ Extracted **negative keywords** (e.g., *hate, worst, disappointed*)  
✔ Performed **n-gram analysis** to detect common phrases  

### 4️⃣ **Data Visualization**  
✔ **Sentiment Distribution:** Countplot of Positive, Negative, and Neutral tweets  
✔ **Sentiment Score Histogram:** Shows distribution of sentiment intensity  
✔ **Emoji & Hashtag Analysis:** Checked impact of emojis and hashtags on sentiment  
✔ **Word Clouds:** Visual representation of frequently used words  

---

## **📂 Files & Structure**  
- `tweets.csv` – Dataset containing tweet text and metadata  
- `exp7.ipynb` – Jupyter Notebook implementing sentiment analysis  
- `sentiment_analysis.py` – Python script with key functions  

---

## **🛠 Tools & Technologies Used**  
- **Python** 🐍  
- **NLTK** – Natural Language Processing  
- **VADER Sentiment Analysis** – Pre-trained sentiment model  
- **Pandas** – Data manipulation  
- **Seaborn & Matplotlib** – Data visualization  
- **WordCloud** – Generating word clouds  

---

## **🚀 Future Enhancements**  
🔹 Incorporate **Deep Learning (BERT, LSTM)** for more accurate sentiment classification  
🔹 Track **sentiment trends over time** if timestamp data is available  
🔹 Expand analysis to include **topic modeling**  

 
