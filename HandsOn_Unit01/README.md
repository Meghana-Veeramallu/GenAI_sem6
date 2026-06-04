# Unit 1: Generative AI & NLP Fundamentals

This is the practical session for Unit 1. This folder contains three key components designed to give a hands-on understanding of Large Language Models (LLMs) and the Hugging Face ecosystem.

## 1. The Interactive Tutorial (`Unit1_handson.ipynb`)

**Goal**: To verify understanding of the NLP pipeline and witness the difference between "Fast" and "High-Quality" models.

**What is done:**
*   **Hugging Face Setup**: Learning how to use the `transformers` library and the `pipeline()` function.
*   **Model Comparison**: Verifying the performance difference between a small model (`distilgpt2`) and a standard model (`gpt2`) on the same prompt.
*   **NLP Fundamentals**: Visualizing what happens "under the hood" (Tokenization, POS Tagging, NER).
*   **Advanced Tasks**: Runing experiments with Summarization (Fast vs. Detailed) and Masked Language Modeling.

---

## 2. The Assignment: The Benchmark Challenge (`Unit1_Benchmark.ipynb`)

**Goal**: To investigate the architectural limitations of different model types by forcing them to perform tasks they may not be designed for.

**The Experiment:**
Three specific models:
1.  **BERT** (`bert-base-uncased`)
2.  **RoBERTa** (`roberta-base`)
3.  **BART** (`facebook/bart-base`)

Run **all three models** on the following three tasks:
1.  **Text Generation**: Prompt them to complete a sentence.
2.  **Fill-Mask**: Ask them to predict a missing word.
3.  **Question Answering**: Ask them to answer a specific question based on a context.
---

## 3. The Project: Personal Diary Tracker(`Diary_MoodTracker.ipynb`)

**Goal**: Input daily diary entries and track the "Mood Graph" over a week.
**Tech**: Sentiment analysis on daily text.
**Technologies Used**:
1. **Python**
2. **HuggingFace Transformers**
3. **PyTorch**
4. **Matplotlib**