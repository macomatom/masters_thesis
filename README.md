# 🚀 Transformer Methods for Text Analysis

## 🎯 Overview
This repository contains the implementation and research code for my **Master’s Thesis**, focusing on **fine-tuning transformer-based models for text analysis**. The goal is to develop **improved question-answering models** by leveraging **monolingual and multilingual approaches**.

📌 **Key Highlights:**
- **Custom dataset generation** using **LLMs** to create **contexts, questions, and labeled answers**.
- **Comparison of transformer models** (BERT, XLM-RoBERTa) for **question answering**.
- **Fine-tuning experiments** to improve **generalization across languages**.
- **Evaluation of question types:** General questions vs. **Boolean (Yes/No) questions**.

---

## 📂 Repository Structure
📦 thesis-repo

┣ 📂 data # Processed datasets (not included in the repo due to size)

┣ 📂 notebooks 

┣ 📂 src # Implementation scripts 

---

## 📊 Methodology
### 🔹 **1. Dataset Creation**
- **Generated & labeled** a custom dataset using **LLMs**.
- Designed **two question types**:
  - **General questions** (answer found in context).
  - **Boolean (Yes/No) questions** (answer inferred from context).

### 🔹 **2. Model Fine-Tuning**
- Fine-tuned **state-of-the-art transformer models**:  
  - **BERT (monolingual & multilingual versions)**  
  - **XLM-RoBERTa (cross-lingual adaptation)**  
- Used **Hugging Face's Transformers library** for model training.

### 🔹 **3. Evaluation Metrics**
- **F1-score, Precision, Recall** for both question types.
- **Best Model:** Fine-tuned **XLM-RoBERTa**:
  - **F1-score: 90.26% (General Questions)**  
  - **F1-score: 94.33% (Boolean Questions)**  

---

## 📈 Results
🚀 The **fine-tuned XLM-RoBERTa model** achieved the best performance:

| **Metric**               | General Questions | Boolean Questions |

| Exact Match Score    | **82.15%**        | **NA**            |

| F1 Score             | **90.26%**        | **94.33%**        |

| Accuracy             | **NA**            | **94.34%**        |

| Precision            | **91.90%**        | **94.37%**        |

| Recall               | **91.40%**        | **94.33%**        |


## 🚀 Results
🔹 The **fine-tuned XLM-RoBERTa model** achieved the best performance:

| **Metric**            | **General Questions** | **Boolean Questions** |
|----------------------|---------------------|---------------------|
| Exact Match Score   | **82.15%**          | N/A                 |
| F1 Score           | **90.26%**          | **94.33%**          |
| Accuracy           | N/A                 | **94.34%**          |
| Precision         | **91.90%**          | **94.37%**          |
| Recall            | **91.40%**          | **94.33%**          |


---

## 📩 Contact
📧 Email: baca.matko@gmail.com
🔗 GitHub: [macomatom](https://github.com/macomatom)
🔗 LinkedIn: https://www.linkedin.com/in/martin-baca-5345b6267/
