# 🎬 YouTube Comment Sentiment Analysis

This project analyzes the **sentiment of YouTube comments** — classifying them as **positive**, **negative**, or **neutral** using advanced Natural Language Processing (NLP) techniques. It uses **NLTK** for preprocessing and **BERT (Bidirectional Encoder Representations from Transformers)** for building an accurate sentiment classification model.

By understanding how users feel about a video or channel, this tool can provide deep insights into **brand perception**, **audience engagement**, and **content performance**.

---

## 📌 What This Project Does

- 🔄 **Collects comments** from YouTube videos or channels
- 🧹 **Cleans and processes** the text data
- 🧠 **Builds a sentiment analysis model** using BERT
- 📊 **Evaluates** model performance on labeled data
- 🎨 **Visualizes** sentiment trends with charts and word clouds

---

## 🔍 Key Features

1. 📥 **Data Collection**  
   Scrapes or imports YouTube comments from specific videos or playlists

2. ✂️ **Text Preprocessing**  
   - Converts to lowercase  
   - Removes punctuation, URLs, emojis  
   - Eliminates stop words  
   - Applies stemming or lemmatization using **NLTK**

3. 📐 **Feature Extraction**  
   Converts raw text into vectors (using BERT tokenizer) suitable for model input

4. 🧠 **Model Training (BERT)**  
   Fine-tunes a pre-trained BERT model to classify comment sentiment

5. 📈 **Model Evaluation**  
   Uses metrics like **accuracy, precision, recall, F1-score** to assess performance

6. 📊 **Visualization**  
   - Sentiment **bar charts**  
   - **Word clouds** for each sentiment category  
   - Optional: Time-based sentiment trend line

---

## 🛠️ Technologies Used

- **Python**
- **NLTK** – for text preprocessing
- **Transformers (HuggingFace)** – for BERT model
- **Pandas / NumPy** – for data handling
- **Matplotlib / Seaborn / WordCloud** – for visualizations
- *(Optional)* **Google API** – for YouTube comment scraping


