# amazon-review-granite-capstone-project
Capstone project for Amazon customer review summarization and classification using IBM Granite.
# 📦 AI-Powered Analysis of Amazon Consumer Reviews for Business Insight

## 📌 Project Overview

This capstone project aims to extract meaningful business insights from customer review data using generative AI. By leveraging IBM Granite through WatsonX Prompt Lab, this analysis focuses on text summarization and sentiment classification to support data-driven recommendations for product improvement, customer satisfaction, and marketing strategy.

The project simulates a real-world business case where a company wants to understand what customers like, dislike, and expect—based on thousands of textual product reviews.

---

## 📂 Dataset

**Source:** [Kaggle - Amazon Product Reviews](https://www.kaggle.com/datasets/datafiniti/consumer-reviews-of-amazon-products)  
**File used:** `Amazon_Consumer_Reviews.csv`  
**Content:** Titles, review texts, star ratings, and metadata from Amazon products, particularly electronics.

---

## 🔍 Insights & Findings

After applying AI summarization and classification across multiple review samples, here are the major takeaways:

### 👍 Positive Patterns:
- Clear sound quality (headphones)
- Long-lasting battery life (electronics)
- Attractive product design
- Fast delivery and clean packaging

### ⚠️ Common Complaints:
- Cables and accessories break easily
- Battery charging is slow or overheats
- Instruction manuals are confusing
- Some products stop working after a few days
- Customer service is unresponsive

### 📊 Sentiment Distribution (based on AI classification):
- 60% Positive  
- 25% Negative  
- 15% Neutral

---

## 💡 Recommendations

Based on the insights extracted through IBM Granite, the following recommendations are proposed:

1. **Improve durability** for frequently criticized components (cables, batteries)
2. **Redesign instruction manuals** to be more visual and simple (include diagrams or video QR codes)
3. **Develop tiered product lines** for different use cases (e.g., small vs. large fans)
4. **Prioritize customer service improvement**, especially for returns and replacements
5. **Leverage marketing messaging** around proven strengths: battery life, design, and fast shipping

---

## 🤖 AI Support – IBM Granite via WatsonX Prompt Lab

All insights were generated using the Granite `granite-3-3-8b-instruct` model deployed through WatsonX Prompt Lab. AI was used for both **text summarization** and **sentiment classification** based on natural language prompts.

### 📝 Sample Prompts Used

**Summarization Prompt:**

Summarize this customer review: I bought this power bank two weeks ago. It charges my phone fast, but it's heavier than expected and the cable broke after a few uses.

markdown
Copy
Edit

**Sentiment Classification Prompt:**
Classify the sentiment of this review as positive, negative, or neutral: The product looks fine and does what it’s supposed to. Nothing special, just okay.

markdown
Copy
Edit

**Insight Prompt:**
Based on this review, what should the business improve or focus on? The product works well, but users often mention the instruction manual is hard to understand and the installation is confusing.

yaml
Copy
Edit

The model returned concise summaries, sentiment labels, and even recommendations, which were interpreted and visualized further in the notebook.

---

## 📁 Project Structure

## 📊 Tools & Platforms

- **Google Colab** – for data analysis and visualization
- **WatsonX Prompt Lab** – to run AI prompts using IBM Granite
- **GitHub** – to host and share project outputs
- **Kaggle** – as data source

---

## 👩‍💻 Author

**Erline Metta Chandra**  
Capstone Project – Student Development Initiative  
IBM WatsonX · August 2025

---

## 📎 Submission Links

- 🔗 GitHub Repository: [https://github.com/erline1108/amazon-review-granite-capstone-project/edit/main/README.md]
- 🔗 Google Colab Notebook: [https://colab.research.google.com/drive/11p9cXgZj60GqBKLcmf4GG-lLNmRJBNnM?usp=sharing]
- 🔗 Slide Presentation: [https://l1nk.dev/iQdjx]
