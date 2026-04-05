# i23-2568 NLP Assignment 2 — Neural NLP Pipeline

**Course:** CS-4063 Natural Language Processing — FAST NUCES  
**Student:** i23-2568 | Section B  
**Framework:** PyTorch (from scratch) — No HuggingFace, No Gensim  


---

## 📁 Repository Structure
i23-2568-NLP-Assignment2/
├── i23-2568_Assignment2_DS-B.ipynb   ← Main Kaggle notebook (all cells executed)
├── report.pdf                         ← Final report (2-3 pages)
├── README.md
├── .gitignore
│
├── embeddings/
│   ├── tfidf_matrix.npy
│   ├── ppmi_matrix.npy
│   ├── embeddings_w2v.npy
│   └── word2idx.json
│
├── models/
│   ├── bilstm_pos.pt
│   ├── bilstm_ner.pt
│   └── transformer_cls.pt
│
└── data/
├── pos_train.conll
├── pos_test.conll
├── ner_train.conll
└── ner_test.conll

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

| Part | Topic | Marks |
|------|-------|-------|
| Part 1 | Word Embeddings (TF-IDF, PPMI, Skip-gram Word2Vec) | 25 |
| Part 2 | BiLSTM Sequence Labeling (POS + NER) | 25 |
| Part 3 | Transformer Encoder (Topic Classification) | 20 |
| GitHub | Version Control | 5 |
| **Total** | | **75** |

---

## 🔗 Kaggle Notebook
> Link: *(add after publishing)*

---

## 📋 Commit Convention
