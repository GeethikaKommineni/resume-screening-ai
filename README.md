# 🧠 AI-Powered Resume Screening System

An intelligent NLP-based resume screening system that classifies resumes based on skills, experience, and job relevance. This project aims to automate the recruitment process and save HR teams significant time and effort.

## 📌 Features
- Automatically extracts and analyzes resume content
- Classifies candidates into categories: `Suitable`, `Potential`, `Not Suitable`
- Keyword extraction using Named Entity Recognition (NER)
- Web interface for uploading and reviewing resumes

## 📂 Dataset
- Source: [Kaggle Resume Dataset](https://www.kaggle.com/datasets/saurabhshahane/resume-dataset)
- Format: Textual resumes categorized by job roles

## ⚙️ Technologies Used
- Python
- NLP: SpaCy, NLTK
- ML: Scikit-learn, Logistic Regression, Random Forest
- Deep Learning (optional): BERT embeddings via Transformers
- Web: Flask / Streamlit
- Storage: MongoDB / SQLite

## 🛠️ How It Works
1. **Upload Resume (PDF/DOCX)**
2. **Text Extraction & Preprocessing**
3. **NER-based Info Extraction**
4. **Classification using Trained Model**
5. **Result Display with Insights**

## 🧪 Model Performance
- Accuracy: ~92% (Logistic Regression)
- Precision, Recall, and F1 Score available in report

## 🚀 Getting Started

### Clone the Repository
```bash
git clone https://github.com/yourusername/ai-resume-screener.git
cd ai-resume-screener
