# text_analyse_tool
text_analyse_tool

---

# 🧠 Text Analysis Tool

This Python-based tool allows users to analyze any text input for its key linguistic and statistical properties. It includes spelling analysis, sentiment classification, formality detection, and multiple data visualizations — all from a simple interface.

## 📌 Features

- 🔤 Tokenizes and cleans text (removes stopwords and personal pronouns)
- ✅ Spelling check and optional auto-correction
- 🗣️ Detects text formality (Formal, Informal, Neutral)
- 🌍 Language detection
- 😊 Sentiment analysis (Positive, Neutral, Negative with emoji)
- 📊 Statistical summaries (word count, unique words, sentence count, etc.)
- 📈 Visualizations:
  - Word cloud
  - Top 5 word frequency bar chart
  - Randomized extra charts (pie, line, histogram)
- 🧾 Summary Dashboard (displayed and saved to `.txt`)
- 📥 Downloadable report + ❌ Exit button for Colab users

---

## 🚀 How to Use

### 🧪 1. Run in Google Colab
1. Upload the `text_analysis_tool.py` to Colab or copy its code into a new cell.
2. Click **Runtime > Run all** or run step-by-step.
3. Paste or upload your text file when prompted.
4. Answer the optional feature toggles (they default to **yes** after 3 seconds).
5. View the summary dashboard and visualizations.
6. Download your report or exit using on-screen buttons.

---

### 📂 2. File Upload Option
- You can upload `.txt` files directly during input selection.

---

## 📄 Output

The tool generates:
- Markdown-formatted dashboard
- `.txt` summary report (with timestamp)
- Interactive plots and word cloud (auto-displayed in Colab)

---

## 🛠️ Requirements

- Python 3.7+
- Google Colab or Jupyter Notebook (for interactive output)
- Libraries:
  - `nltk`
  - `textblob`
  - `matplotlib`
  - `wordcloud`
  - `langdetect`

You can install the dependencies using:
```bash
pip install nltk textblob matplotlib wordcloud langdetect
```

---

## 👨‍💻 Author
Developed by [Your Name] — as part of a guided AI prompting project.

---

