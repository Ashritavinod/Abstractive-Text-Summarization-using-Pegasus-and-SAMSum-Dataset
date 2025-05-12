# 📝 Abstractive Text Summarization using Pegasus and SAMSum Dataset

This project fine-tunes the `google/pegasus-cnn_dailymail` model on the SAMSum dataset for abstractive dialogue summarization.

## 📚 Dataset
- **Name:** SAMSum
- **Type:** Dialogue-based abstractive summarization

## ⚙️ Model
- **Base:** google/pegasus-cnn_dailymail
- **Library:** Hugging Face Transformers
- **Task:** Seq2Seq (Text Summarization)

## 📒 Notebook Breakdown
1. **Installation & Imports**: Required libraries (transformers, datasets, nltk, evaluate, accelerate).
2. **Loading the SAMSum Dataset**
3. **Preprocessing**: Tokenizing input/output pairs.
4. **Model Setup**: Load Pegasus and tokenizer.
5. **Fine-tuning**:
   - TrainingArguments
   - DataCollator
   - Trainer
6. **Evaluation**:
   - ROUGE score with Hugging Face `evaluate`
7. **Saving the Model**
8. **Loading for Inference**
9. **Prediction** using Hugging Face `pipeline`

## 🔧 Tools Used
- `transformers`
- `datasets`
- `evaluate`
- `nltk`
- `accelerate`
- `torch`

## 🚀 Results
The fine-tuned Pegasus model is able to generate fluent summaries of dialogue-based inputs.

## 💾 How to Run
1. Clone the repo
2. Install dependencies: `pip install -r requirements.txt`
3. Run the Jupyter Notebook: `pegasus_summarization_samsum.ipynb`


