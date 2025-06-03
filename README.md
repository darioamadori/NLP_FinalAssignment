# 🧠 PubMedQA - Biomedical Question Answering using NLP

## 📌 Project Overview
This project was developed as part of the Natural Language Processing course at the Polytechnic University of Milan (2024/2025). The goal was to explore the capabilities of various NLP models in classifying and answering biomedical research questions using the PubMedQA dataset.

## 🧪 Dataset
We used [PubMedQA](https://huggingface.co/datasets/qiaojin/PubMedQA), a dataset of over 270,000 medical questions and answers derived from PubMed publications. Each record includes:
- A **question** (typically a medical research query),
- A **context** (abstract without the conclusion),
- A **long answer** (abstract conclusion),
- A **label**: **yes**, **no**, or **maybe**.

## 🎯 Project Goals
We tackled two main tasks:
1. **Question Classification**: Predict whether the answer to a biomedical question is "yes", "no", or "maybe".
2. **Question Answering**: Automatically generate the correct answer based on the provided context.

## 🔧 Approach
- Performed **exploratory data analysis** to understand structure, vocabulary, and answer distributions.
- Implemented classical machine learning models (Logistic Regression, SVM) with various document representations (CountVectorizer, TF-IDF, BM25).
- Trained deep learning models: **LSTM** and **BERT-based transformer** for classification.
- Fine-tuned **FLAN-T5** for the generative QA task.
- Experimented with **LLaMA-3.2-1B**, a pretrained large language model, to answer questions with retrieval-augmented generation.

## 🚀 Results
- The fine-tuned BERT model significantly outperformed traditional baselines.
- Achieved high accuracy on the binary classification of "yes"/"no" answers.
- Demonstrated that pretrained transformer models are effective for complex biomedical NLP tasks.

## 👥 Authors
- Dario Amadori  
- Andrea Arzilli  
- Daniele Gagni  
- Mateusz Krause  

📹 [Watch our 5-minute project demo](https://youtu.be/mK0r6fndAjQ)

