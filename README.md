# Measuring_Effectiveness_of_Feedback_with_NLP
NLP-based analysis of educational feedback using BERT, RoBERTa, and GPT-3.5 to objectively measure feedback effectiveness in higher education.

# Measuring Effectiveness of Feedback using NLP 🎓🤖

## 📌 Overview
This repository contains my MSc Data Science dissertation project completed at the **University of Salford (2023–2024)**.  
The project explores how **Natural Language Processing (NLP)** can be used to **objectively evaluate the effectiveness of educational feedback** in higher education.

Traditional feedback evaluation methods rely heavily on subjective surveys. This project proposes a **data-driven NLP approach** to classify feedback sentiment as **Encouraging, Neutral, or Critical**, enabling scalable and objective analysis.

---

## 🎯 Research Objectives
- Investigate whether NLP can objectively measure feedback effectiveness
- Fine-tune and compare multiple state-of-the-art NLP models
- Validate model predictions against **human-annotated feedback**
- Identify linguistic patterns associated with effective feedback

---

## 🧠 Models & Techniques
The following models were implemented and evaluated:

- **BERT (Bidirectional Encoder Representations from Transformers)**
- **RoBERTa (Robustly Optimized BERT Approach)**
- **GPT-3.5 Turbo (fine-tuned for sentiment classification)**

Each model was fine-tuned to classify feedback into:
- Encouraging
- Neutral
- Critical

---

## 🗂️ Methodology
- **Data Collection:**  
  Custom dataset collected via questionnaires distributed to university professors  
- **Pre-processing:**  
  Text cleaning, tokenization, handling missing values
- **Exploratory Data Analysis:**  
  Sentiment distribution, text length analysis, word clouds
- **Model Evaluation Metrics:**  
  Accuracy, Precision, Recall, F1-Score
- **Validation:**  
  Comparison between NLP predictions and human annotations

---

## 📊 Key Results
- Transformer-based models performed strongly in classifying feedback sentiment
- **RoBERTa and BERT** showed consistent and reliable performance
- **GPT-3.5 Turbo** demonstrated strong capability in understanding nuanced feedback language
- Encouraging feedback showed distinctive linguistic patterns linked to clarity and action-oriented phrasing

> Detailed results, evaluation plots, and comparisons are available in the dissertation and notebooks.

---

## 🛠️ Tech Stack
- **Programming:** Python
- **Libraries:** Hugging Face Transformers, PyTorch, Scikit-learn, Pandas, NumPy
- **Visualization:** Matplotlib, WordCloud
- **Environment:** Google Colab
- **Models:** BERT, RoBERTa, GPT-3.5 Turbo

---

## 📁 Repository Contents
- `notebooks/` – EDA, model training & evaluation
- `figures/` – Visualizations and performance plots
- `dissertation.pdf` – Full academic dissertation
- `requirements.txt` – Python dependencies

---

## 🔒 Ethics & Data Privacy
Due to ethical considerations, the full dataset cannot be publicly shared.  
Sample or anonymised data structures are provided for reproducibility.

---

## 🚀 Future Work
- Expand dataset size across institutions
- Explore **aspect-based sentiment analysis**
- Integrate multimodal feedback (audio/video)
- Develop a real-time feedback evaluation tool for educators

---

## 👩‍💻 Author
**Likitha Tallapally**  
MSc Data Science  
University of Salford  

📫 Feel free to connect with me on LinkedIn or explore my other projects on GitHub!
