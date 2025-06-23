# 🔤 NMT-ENG-BODO — Neural Machine Translation for English ↔️ Bodo

> 🧠 A transformer-based NMT system to bridge the language gap for the low-resource Bodo language using state-of-the-art deep learning techniques.

---

## 🌍 Project Overview

This project presents a **Neural Machine Translation (NMT)** system developed using **transformer architecture** to translate between **English** and **Bodo** — an indigenous, low-resource language of Northeast India. Built as part of my research into low-resource NLP, this project leverages **attention-based models** and parallel corpora to demonstrate scalable translation capabilities.

---

## 🚀 Highlights

- ✅ **Transformer-based encoder-decoder architecture**
- 🌐 **Low-resource language support** (Bodo)
- 📁 Parallel corpus files: `s.csv`, `sd.csv`
- 📓 Interactive Jupyter Notebook: `sd.ipynb` for training & evaluation
- 🔤 Integrated subword tokenization with `SentencePiece`
- 📊 Evaluation metrics: BLEU, METEOR, ROUGE, TER, sacreBLEU

---

## 📁 Repository Structure


---

## 🛠️ Tech Stack

| Category     | Tools Used                          |
|--------------|-------------------------------------|
| 👩‍💻 Language   | Python 3.x                           |
| 📚 Libraries  | pandas, NumPy, SentencePiece, matplotlib |
| 🧠 Frameworks | TensorFlow, Keras (Transformer APIs)  |
| 📄 Data Format | CSV parallel corpora                |

---

## 📓 Model Workflow (via `sd.ipynb`)

1. **Data Preprocessing**  
   - Load `s.csv` and `sd.csv`  
   - Normalize & clean parallel sentences  
   - Tokenize using `SentencePiece` subword units

2. **Transformer Model Definition**  
   - Encoder-decoder with multi-head attention  
   - Positional encoding, dropout, masking

3. **Training & Evaluation**  
   - Sprase Categorical cross-entropy loss
   - ADAM Optimizer.
   - Accuracy tracking + BLEU score (if configured)  
   - Training/validation loss visualization


---

## 🧪 Sample Translation Example

```python
Input: "The school is closed today."
Output (Bodo): "Skulwi dong bathw swrjao."
````

## 🌱 Why This Project Matters
Bodo is among the many underrepresented languages in NLP.
This project contributes toward:

🧑‍🏫 Democratizing AI for marginalized language speakers

🌐 Building inclusive translation systems

🔬 Advancing research on low-resource language modeling

##📜 License
MIT License © [Your Name or GitHub Handle]

Feel free to fork, modify, and contribute!
For academic or research use, attribution is appreciated.


