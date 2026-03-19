# 🧠 Automatic Medical Text Summarization using NLP & Transformer Models

## 📌 Project Overview

Healthcare and biomedical research generate massive amounts of textual data such as **research papers, clinical reports, and medical abstracts**. Manually analyzing these documents is **time-consuming and inefficient**.

This project focuses on developing an **automated biomedical text summarization system** using advanced **Transformer-based NLP models** to generate concise and meaningful summaries from biomedical abstracts.

The system helps doctors, researchers, and healthcare professionals quickly understand key insights from large biomedical documents.

(Project details referenced from presentation )

---

## 🎯 Objectives

* Build an automated system for **biomedical text summarization**
* Apply **Transformer models** for better contextual understanding
* Compare model performance using **evaluation metrics**
* Identify the most effective model for biomedical summarization

---

## 📊 Dataset Used

**Dataset:** PubMed Multi-Label Text Classification Dataset

### Dataset Features:

* Contains biomedical research abstracts from PubMed
* Includes domain-specific medical terminology
* Complex sentence structures suitable for NLP research
* Preprocessed using:

  * Text normalization
  * Tokenization
  * Noise removal

This dataset helps models **learn medical context and terminology**, improving summarization quality.

---

## 🤖 Models Used

### ✅ 1. T5 (Text-To-Text Transfer Transformer)

**Use in Project:**
Used for **biomedical text summarization**

**Why T5 is Useful:**

* Converts every NLP task into a **text-to-text format**
* Preserves contextual meaning while summarizing
* Flexible and effective for multiple NLP tasks
* Generates **concise and readable summaries**

---

### ✅ 2. PEGASUS

**Use in Project:**
Main model for **abstractive text summarization**

**Why PEGASUS is Useful:**

* Specifically designed for summarization tasks
* Uses **Gap Sentence Generation (GSG)** training objective
* Understands important sentences in long documents
* Produces **more informative and accurate summaries**

⭐ In this project, **PEGASUS achieved the best performance.**

---

### ✅ 3. BioGPT

**Use in Project:**
Used for **biomedical text classification**

**Why BioGPT is Useful:**

* Pretrained on biomedical literature
* Understands medical terminology better than general models
* Improves classification performance in healthcare NLP tasks

---

## ⚙️ Methodology

1. Input biomedical abstracts from PubMed dataset
2. Perform preprocessing (cleaning + tokenization)
3. Apply Transformer models
4. Generate summaries
5. Evaluate summaries using performance metrics

---

## 📈 Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-Score
* BLEU Score

**BLEU Score** is used to measure similarity between **generated summary and reference summary.**

---

## ✅ Results

* T5 generated clear and concise summaries
* BioGPT performed well in classification tasks
* PEGASUS produced the **most accurate and meaningful summaries**
* Transformer models outperformed traditional summarization approaches

---

## 📤 Output

* Input → Biomedical abstract
* Processing → Transformer model
* Output → Short meaningful summary

The generated summary retains **important medical findings and context.**

---

## 🧩 Applications

* Medical research paper summarization
* Clinical report analysis
* Electronic Health Record (EHR) summarization
* Medical decision support systems

---

## 🚀 Future Scope

* Train models on larger biomedical datasets
* Integrate medical knowledge graphs
* Develop real-time summarization tools for hospitals
* Build intelligent medical assistants


Just tell 👍
