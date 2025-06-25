# operation-sindoor-sentiment

This project performs **sentiment analysis** on tweets related to **Operation Sindoor**, a high-profile military operation. It collects real-time data using the Twitter API, applies **Natural Language Processing (NLP)** techniques to analyze public sentiment, and generates insightful visualizations.

## 📌 Features

- 🔍 Real-time tweet collection via Twitter API  
- 💬 Text preprocessing and cleaning  
- 🧠 Sentiment classification using **VADER** and **TextBlob**  
- 📊 Visualizations:
  - Sentiment distribution pie chart  
  - Engagement by sentiment  
  - Language distribution  
  - Sentiment score histogram  
- ☁️ Word clouds for all, positive, and negative tweets  
- 📈 Key insights like top languages, most engaging tweets, and sentiment breakdown  
- 📁 Outputs include cleaned CSV and JSON insights

---

## 🛠️ Technologies Used

- **Python**, **Tweepy**, **NLTK**, **TextBlob**, **VADER Sentiment**  
- **Pandas**, **NumPy**, **Matplotlib**, **Seaborn**, **WordCloud**  
- **Jupyter Notebook**, **Twitter Developer API**

---

## 🚀 How to Run

1. **Get Twitter API credentials**  
   Sign up at [developer.twitter.com](https://developer.twitter.com/) and get your **Bearer Token**.

2. **Install dependencies**
   ```bash
   pip install tweepy nltk textblob vaderSentiment matplotlib seaborn wordcloud
   ```

3. **Run the notebook**
   Open `Sentiment_Analyzer.ipynb` and run all cells, replacing the bearer token in the `main()` function.

---

## 📊 Sample Insights

- Total Tweets Analyzed: `100`  
- Sentiment Breakdown: Positive `17%`, Neutral `48%`, Negative `35%`  
- Top Languages: English, Hindi, Urdu  
- Most Engaging Tweet:
  > “India will never forget. #OperationSindoor 🇮🇳” — 5,000+ engagements

---

## 📌 Use Cases

- Track public opinion on military or national events  
- Analyze media narratives using social media signals  
- Build dashboards for real-time awareness and engagement tracking  

---

## 📜 License

This project is for educational and analytical purposes only.
