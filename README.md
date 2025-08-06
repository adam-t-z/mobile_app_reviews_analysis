# 🤖 Task Management App: Google Play Review Analysis

This notebook explores user reviews from Google Play Store to extract actionable insights for building a better **AI-powered task management app**. We analyze sentiment, feature requests, and unmet user needs from popular apps in this category.

---

## 📊 Project Objective

Use user-generated content (reviews) from real-world task management apps to:

- Understand what features users love ❤️
- Identify frustrations and missing functionality 😠
- Extract **feature requests** using pattern matching and NLP
- Generate data-driven ideas for your own app 🎯

---

## 🔍 What This Notebook Does

### ✅ Data Collection

- Scrapes **4000 reviews** from 4 leading task management apps using `google-play-scraper`
- Cleans and preprocesses text for analysis

### ✅ Sentiment Analysis

- Uses `TextBlob` to calculate polarity (positive/negative sentiment)
- Visualizes sentiment distributions with boxplots and histograms
- Identifies which app had the **highest median sentiment** (📌 *TickTick*)

### ✅ Feature Request Detection

- Uses **regex-based pattern matching** to detect reviews with phrases like:
  - "I wish..."
  - "It needs..."
  - "Please add..."
- Extracts reviews that indicate **missing or desired features**

### ✅ Keyword Extraction

- Uses `RAKE` (Rapid Automatic Keyword Extraction) to summarize user needs
- Finds common user asks like:
  - **Progress bars**
  - **Reminders**
  - **Themes**
  - **ADHD-friendly features**
  - **Widgets**
  - **Recurring tasks**

### ✅ Insights Summary

- Users want better **visualizations** to track task progress
- Clear demand for **customization** (themes, UI colors, dark mode)
- Common frustrations include **buggy recurring tasks**, **missing alarms**, and **unintuitive UIs**
- **AI-powered natural language input** and **voice reminders** are highly desired

---

## 📌 Tools Used

- `google-play-scraper` – for fetching app reviews
- `pandas` – for data handling
- `TextBlob` – for sentiment scoring
- `matplotlib` / `seaborn` – for charts and graphs
- `RAKE` – for extracting keywords from reviews
- `re` – Python regex for detecting pattern-based feature requests

---

## 🧠 Why This Matters

Understanding what real users want is *the best foundation* for building a successful app. This analysis helps guide:

- Product decisions
- UX/UI design priorities
- AI feature ideas
- Marketing language and positioning

---

## 🛠 How to Use This Notebook

1. Open the notebook in [Google Colab](https://colab.research.google.com/) or any other environment.
2. Run all cells to:
   - Scrape app reviews (already cached in sample)
   - Analyze sentiment and detect feature needs
   - Extract keywords for feature planning
3. Use the insights to build or refine your own task app!

---

## 🤝 Contributions

Feel free to fork, adapt, or build upon this notebook. PRs welcome!

---

## 📬 Contact

Created by [adam-t-z]

---

