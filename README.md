<div align='center'>
  <img style="width:30%" src='https://github.com/user-attachments/assets/685fc2be-80ef-409f-9eb2-883976f0ada4'/>
</div>

# 🤖 ML4LLM — 50 ML Projects to Understand LLMs

> **Book:** *50 ML Projects to Understand LLMs* by Mike X Cohen  
> **My Journey:** Completed all 50 projects in Python (VS Code + Jupyter)

---

## About This Repository

This repo has all the code from Mike X Cohen’s book.  
It teaches **Large Language Models (LLMs)** using hands-on experiments, analysis, and visualizations.

---

## Project Structure

- **Projects 1–7:** Tokenization (break text into characters, words, subwords)  
- **Projects 8–15:** Embeddings (vectors for each token, similarity, analogies)  
- **Projects 16–23:** Output Logits (softmax, probabilities, biases)  
- **Projects 24–32:** Transformer Outputs (layers, residuals, logit lens)  
- **Projects 33–41:** Attention (QKV, heatmaps, head silencing)  
- **Projects 42–50:** MLP (weights, activations, neuron analysis, recommender systems)

---

## Top Findings

- **Attention Sink:** First token gets ~30% attention  
- **Layer 3 Explosion:** MLP activations very high in Layer 3  
- **4x Compression:** Tokenization reduces size 4x  
- **Gender Bias:** `doctor` → male, `nurse` → female  
- **1 Dimension Enough:** 95% info in 1 dimension in Layer 3  
- **IOI Heads:** Layer 8, Head 4 is key for name tasks

---

## Setup

**Python:** 3.14+  

**Install Packages:**
```bash
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cpu
pip install transformers tiktoken numpy pandas matplotlib scikit-learn networkx xgboost
````


---

## Models Used

* `GPT2` → main model for embeddings, attention, MLP
* `GPT2-medium` → for perplexity comparison
* `bert-base-uncased` → tokenizer comparison, RSA analysis

---

## What I Learned

* **Tokenization:** break text into numbers
* **Embeddings:** numbers → meaning
* **Attention:** tokens focus on each other
* **MLP:** store knowledge
* **Layers:** each layer adds understanding

---

*Made while learning LLM internals one project at a time.*


