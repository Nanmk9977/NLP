# 📌 Fine-Tuning BERT for Sentiment Analysis (IMDB Dataset)

## 🧠 Overview
This project demonstrates fine-tuning a pre-trained **BERT (bert-base-uncased)** model for sentiment classification using the IMDB movie reviews dataset. The model classifies reviews as **positive** or **negative**.

## ⚙️ Tech Stack
- Python  
- PyTorch  
- Hugging Face Transformers  
- Scikit-learn  
- Jupyter Notebook / Google Colab  

## 🔄 Workflow
Data Preprocessing → Tokenization → Model Training → Evaluation → Comparison  

## 🚀 Implementation Details
- Pre-trained Model: `bert-base-uncased`  
- Optimizer: AdamW  
- Learning Rate: 2e-5  
- Task: Binary Text Classification  

## 🧪 Experiments
- **Frozen BERT** (only classifier trained)  
- **Fine-tuned BERT** (last 2 layers unfrozen)  

Fine-tuning showed improved performance over frozen layers.

## 📊 Evaluation Metrics
- Accuracy  
- Precision  
- Recall  
- F1 Score  
- Confusion Matrix

## 📌 Results
The fine-tuned model achieved strong performance on the IMDB dataset, with improved accuracy and F1-score compared to the baseline frozen model.
