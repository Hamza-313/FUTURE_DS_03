# FUTURE_DS_03
# **🎓 Student Feedback Analysis Project**

This project analyzes student feedback data (Google Forms CSV export) using data analysis + NLP tools to extract insights, visualize satisfaction, and generate automated reports (PDF/HTML).

## **🚀 Project Overview**

The project helps analyze student ratings and feedback comments after campus events or courses.
We use data cleaning, visualization, and sentiment analysis to provide actionable insights for event organizers and faculty.

## **📂 Features**

✅ Clean and preprocess student feedback data (CSV from Google Forms)
✅ Analyze ratings (1–10 scale) → average scores, strengths, weaknesses
✅ Perform NLP sentiment analysis on feedback comments (Positive / Neutral / Negative)
✅ Generate visualizations:

Bar charts (average ratings)

Pie charts (sentiment, rating distribution)

Heatmaps (correlations between rating factors)

Word clouds (common feedback themes)
✅ Export results as:

📄 PDF Report (charts + insights)

🌐 Interactive HTML Report

## **🛠️ Tools & Libraries**

Python 3

Pandas, NumPy → Data analysis

Matplotlib, Seaborn → Charts

NLTK (VADER), TextBlob → Sentiment analysis

WordCloud → Text visualization

FPDF → Lightweight PDF report generation

Pandas Profiling → Interactive HTML report

Google Colab → Easy execution (no local installation required)

## **📊 Example Insights**

Top Strengths: Teachers’ knowledge, explanations, student engagement

Weaknesses: Assignments too difficult, poor structure, workload too high

Sentiment Distribution: ~65% Positive, 25% Neutral, 10% Negative

Correlation: Students who rate teaching high also give better overall scores

## **Recommendations:**

Simplify assignments & reduce difficulty

Improve course structure clarity

Keep interactive teaching & doubt-solving

## **🖼️ Sample Visualizations**

📊 Average Ratings (Bar + Pie)

🔥 Correlation Heatmap

😀 Sentiment Distribution (Bar + Pie)

☁️ Word Cloud of student feedback

📑 Sentiment vs Rating Category (Stacked Bar)

## **📄 Output Reports**

The analysis produces two types of reports:

PDF Report (via FPDF)

Title & summary insights

## **Key recommendations**

All charts neatly inserted

HTML Report (via Pandas Profiling)

Interactive, clickable, and shareable

Rich data profiling

## **▶️ How to Run in Google Colab**

Open Colab: https://colab.research.google.com

Upload the notebook and your dataset (student_feedback.csv)

Run all cells step by step

Download the generated PDF or HTML report at the end

## **📂 Dataset**

You can use this dataset:
https://www.kaggle.com/datasets/ruchi798/student-feedback-survey-responses

Or export your own dataset from Google Forms.

## **📌 Future Improvements**

Add interactive dashboard (Streamlit / Dash / Plotly)

Real-time Google Forms integration

Advanced NLP with transformer models (BERT, RoBERTa)
