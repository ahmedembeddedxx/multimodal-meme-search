### **Multimodal Meme Search**

This project implements a **multimodal meme search system** using **TF-IDF, CBOW, and Skip-Gram** embeddings for text-based image retrieval.

#### **Features**

- **TF-IDF** for text-based search
- **CBOW & Skip-Gram (Word2Vec)** for semantic understanding
- **Cosine Similarity** for ranking results
- **Fast inference** with precomputed embeddings

#### **How to Use**

0. Source data from [Kaggle](https://www.kaggle.com/datasets/harshittiwari007/meme-convx)
1. Train models (`cbow_model`, `skipgram_model`, `tfidf_vectorizer`).
2. Save and load models (`.model`, `.pkl`).
3. Use `recommend_word2vec()` for retrieval.

#### **Setup**

```bash
pip install -r requirements.txt
```

#### **Run Search**

```python
recommend_word2vec(query, cbow_model, w2v_df, "cbow_vector")
```

🔗 **Repo:** [GitHub](https://github.com/ahmedembeddedxx/multimodal-meme-search) 
