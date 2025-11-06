# News Clustering using Transformers (Mini Project 3)

### Overview
This project demonstrates how **Transformer-based models** (like Sentence Transformers) can group news articles by meaning rather than just keywords.  
Using **unsupervised learning**, the system clusters similar articles together, showcasing the power of **Attention Mechanisms** and **LLMs** in NLP.

---

### Tech Stack
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- PyTorch
- Sentence Transformers

---

### Steps
1. Load and preprocess text data  
2. Generate sentence embeddings using pretrained Transformers  
3. Apply clustering (e.g., K-Means)  
4. Evaluate and visualize clusters  

---

### Result
The model successfully groups news articles by topic, proving that Transformer embeddings capture **semantic meaning** far better than traditional text representations.

---

### How to Run
```bash
git clone https://github.com/<your-username>/news-clustering-using-transformers.git
cd news-clustering-using-transformers
pip install -r requirements.txt
jupyter notebook Mini_Project_3.ipynb

