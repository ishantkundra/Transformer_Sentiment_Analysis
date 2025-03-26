# Transformer-Based Sentiment Analysis on Yelp Reviews

This repository contains a deep learning project focused on **sentiment classification** of Yelp reviews using a **custom Transformer model**. Developed for the **CSCE 633 - Machine Learning** course at **Texas A&M University**, the model classifies reviews as **Positive**, **Neutral**, or **Negative**.

---

## 🧾 Project Info

- **Course**: CSCE 633 - Machine Learning  
- **University**: Texas A&M University  
- **Author**: Ishant Kundra  
- **Model**: Transformer-based architecture with self-attention  
- **Test Accuracy**: ~85.15%

---

## 📁 Repository Structure
<pev>
transformer-sentiment-analysis/
│
├── code/                        # Jupyter Notebook with full implementation
│   └── ML_Project.ipynb
│
├── problem-question/           # Project problem statement and guidelines
│   └── CSCE633_final_project-2.pdf
│
├── report/                     # Final IEEE-style report
│   └── Kundra_Ishant_ML_Report.pdf
│
├── output/                     # Accuracy & loss training curves
│   ├── F1.png                  # Accuracy curve
│   ├── F2.png                  # Loss curve
│   └── ml.jpeg                 # Combined plot (optional)
│
└── README.md                   # You’re here!
</pev>
---

## 📈 Results Overview

| Metric              | Value       |
|---------------------|-------------|
| Training Accuracy   | ~87.24%     |
| Validation Accuracy | ~85.73%     |
| Test Accuracy       | ~85.15%     |

### 📊 Learning Curves (found in `/output`)

- **Training vs Validation Accuracy**
  ![Accuracy](output/F1.png)

- **Training vs Validation Loss**
  ![Loss](output/F2.png)

---

## ⚙️ How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/your-username/transformer-sentiment-analysis.git
cd transformer-sentiment-analysis

2. Set up a virtual environment (optional)

python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

3. Run the notebook

Launch the notebook from the /code folder using Jupyter or Colab:

jupyter notebook code/ML_Project.ipynb



⸻

🧠 Key Concepts
	•	Text Preprocessing (NLTK)
	•	Sentiment Mapping (based on star ratings)
	•	Tokenization & Padding
	•	Custom Transformer Model (3 encoder blocks)
	•	Training with SGD, EarlyStopping, LR Scheduling
	•	Evaluation using Accuracy & Loss

⸻

🔧 Libraries Used
	•	tensorflow / keras
	•	pandas
	•	nltk
	•	matplotlib

⸻

📌 References
	•	Attention is All You Need - Vaswani et al.
	•	Deep Learning for Sentiment Analysis: A Survey
	•	XLNet, BERT, GPT - NLP Benchmarks

⸻

👨‍💻 Author

Ishant Kundra
M.S. Computer Science, Texas A&M University
📬 [ishantkundra9@gmail.com]

