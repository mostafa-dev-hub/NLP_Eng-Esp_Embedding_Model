# Cross-Lingual English–Spanish Word Embedding Model

## Project Overview
This project explores **cross-lingual word embeddings** by training bilingual English–Spanish models on the **ELRC-EMEA parallel corpus**. Inspired by **ArbEngVec**, the project uses a randomized sentence-level shuffling strategy to build embeddings that capture semantic alignment between English and Spanish.

The resulting embeddings can be applied to:
- Cross-lingual **information retrieval**  
- **Machine translation** evaluation  
- **Multilingual NLP applications**

---

## Team Members
- **Mustafa Mallesho** (222110520)  
- **Khaled Suwaine** (219210991)  
- **Naif Hazzaa Alrous** (222110926)  
- **Hussein Al-Sari** (221110151)  

**Supervised by:**  
- *Dr. El Moatez Billah Nagoudi*  

---

## Dataset
We use the **ELRC-EMEA English–Spanish parallel corpus**, sourced from [OPUS](https://opus.nlpl.eu/ELRC-EMEA/en&es/v1/ELRC-EMEA).  
- Format: JSONL (paired English–Spanish sentences).  
- Preprocessing includes tokenization and sentence-level shuffling.  

---

## Objectives
- Train **cross-lingual word embeddings** (English–Spanish).  
- Compare **Word2Vec (CBOW, Skip-gram)** and **FastText** approaches.  
- Evaluate embeddings with:
  - **BLEU score** (translation quality).  
  - **Cosine similarity** (sentence-level semantic alignment).  

---

## Methods & Tools
- **Gensim** (Word2Vec, FastText)  
- **FastText** embeddings  
- **MarianMT** (translation benchmarking)  
- **NLTK** (tokenization + BLEU)  
- **PyTorch / Transformers** (modeling support)  
- **Cosine similarity** (semantic evaluation)  

---

## Evaluation
- English–Spanish sentence embeddings are compared through **cosine similarity**.  
- BLEU scores validate translation alignment.  
- Models tested on multiple sentence pairs for semantic closeness.  

---

## Future Work
- Extend to **other language pairs** (e.g., English–Arabic, English–French).  
- Compare against **pre-trained multilingual embeddings** (e.g., MUSE, LASER).  
- Deploy as a **cross-lingual search or translation evaluation tool**.  

---

