# i23-2568 NLP Assignment 2 — Neural NLP Pipeline

**Course:** CS-4063 Natural Language Processing — FAST NUCES  
**Student:** i23-2568 | Section B  
**Framework:** PyTorch (from scratch) — No HuggingFace, No Gensim  


---

## 📁 Repository Structure
i23-2568-NLP-Assignment2/ <br>
├── i23-2568_Assignment2_DS-B.ipynb   ← Main Kaggle notebook (all cells executed) <br>
├── report.pdf                         ← Final report (2-3 pages) <br>
├── README.md <br>
├── .gitignore <br>
 │ <br>
├── embeddings/ <br>
│   ├── tfidf_matrix.npy <br>
│   ├── ppmi_matrix.npy <br>
│   ├── embeddings_w2v.npy <br>
│   └── word2idx.json <br>
│
├── models/ <br>
│   ├── bilstm_pos.pt<br>
│   ├── bilstm_ner.pt<br>
│   └── transformer_cls.pt<br>
│ <br>
|── data/ <br>
├── pos_train.conll <br>
├── pos_test.conll <br>
├── ner_train.conll <br>
└── ner_test.conll  <br>
    
---

## ⚙️ Setup & Reproduction

### 1. Clone the Repository
```bash
git clone https://github.com/saneedkhani/i23-2568-NLP-Assignment2.git
cd i23-2568-NLP-Assignment2
```

### 2. Install Dependencies
```bash
pip install torch numpy scipy scikit-learn matplotlib seaborn conlleval
```

### 3. Required Input Files
Place these files in your working directory before running:
- `cleaned.txt` — Preprocessed BBC Urdu corpus (from Assignment 1)
- `raw.txt` — Raw BBC Urdu corpus
- `Metadata.json` — Article metadata with topic labels

### 4. Run the Notebook
Open `i23-2568_Assignment2_DS-B.ipynb` on **Kaggle** and attach the dataset `bbc-urdu-nlp`.  
Run all cells top to bottom.

---

## 📦 Parts Overview

| Part | Topic | 
|------|-------|
| Part 1 | Word Embeddings (TF-IDF, PPMI, Skip-gram Word2Vec) | 
| Part 2 | BiLSTM Sequence Labeling (POS + NER) | 
| Part 3 | Transformer Encoder (Topic Classification) |
| GitHub | Version Control |


---

## 🔗 Kaggle Notebook
> Link: *(add after publishing](https://www.kaggle.com/code/saneedullah/nlp-assigment)*

---

## 📋 Commit Convention
