# 🪶 The Austen Engine

**The Austen Engine** is an AI-powered text generation tool that mimics the literary style of Jane Austen.  
It uses **N-Gram Language Modeling** and a **Gradio web interface** to generate sentences and short passages in a period-authentic tone.

---

## Features

- 📜 **N-Gram Model** for probabilistic text generation  
- 🔍 **Text Preprocessing & Tokenization** to structure raw text data  
- 🧠 **Sentence Generation Engine** that learns from Austen’s corpus  
- 🎨 **Interactive Gradio UI** for real-time generation and exploration  
- 💾 Option to expand with additional datasets or fine-tuning  

---

##  Tech Stack

- **Python 3.10+**
- **Libraries:**  
  - `pandas`, `numpy`, `re`, `nltk`
  - `gradio`
- **Notebook:** Jupyter/Colab (`.ipynb`)

---

## ⚙️ Installation

Clone the repository and install the required dependencies:

```bash
git clone https://github.com/yourusername/The-Austen-Engine.git
cd The-Austen-Engine
pip install -r requirements.txt
```

---

## Example Output

Input:

“Elizabeth was quite surprised to see…”

Generated Output:

“Elizabeth was quite surprised to see Mr. Darcy approach with such civility, as if every former reserve were quite forgotten.”

---

## How It Works

1. Dataset Preparation – Downloads and cleans Jane Austen’s works (via NLTK or Gutenberg).

2. Tokenization & N-Gram Formation – Builds bigrams/trigrams to learn word transitions.

3. Sentence Generation – Randomly samples words based on learned probabilities.

4. Gradio Integration – Provides a simple, elegant front-end for user interaction.

---

## Future Enhancements

- Expand corpus with other classical authors for style comparison.
- Add sentiment analysis or character-based narrative generation.
- Integrate deep learning (GPT, LSTM) for hybrid models.
- Save user-generated “Austen-like” compositions.

---

## Authors
Reya Oberoi
