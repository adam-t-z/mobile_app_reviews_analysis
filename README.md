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

---

## 🧠 What Users REALLY Want (And What Drives Them Crazy!) according to our Analysis

Alright, buckle up — here’s the lowdown from the trenches of task app reviews:

🎯 **Progress Bars & Charts**: People want to see their progress like it’s a game scoreboard. Without those, motivation tanks faster than your phone battery at 2%!

🎨 **UI Woes**: “Clunky,” “sloppy,” “confusing” — yep, users don’t hold back when the interface feels like a messy desk. Clean, simple, smooth is the vibe.

🔄 **Recurring Tasks & Widgets**: If you can’t automate or glance at your to-dos on your home screen, what’s even the point? Widgets are the new cool kids.

🌙 **Dark Mode & Custom Colors**: Because everyone secretly judges an app by how good it looks at 2 AM. Night owls unite!

🧠 **Special Requests**: ADHD-friendly features, voice input, and color-coded task lists are like comfort food for many users — they need that extra love.

🐞 **Buggy Updates**: Nothing kills trust like an update that breaks your recurring tasks. Fix it fast or users will ghost you.

🔒 **Privacy Please**: Some folks want task management without feeling like Big Brother is watching. Privacy is more than a buzzword here.

💡 So, if your app nails these, you’re already on your way to being the chosen one in the crowded task jungle.


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


