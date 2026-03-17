# Customer Support Chatbot: Fine-Tuning GPT-2

This project demonstrates fine-tuning the **GPT-2** model on a custom dataset of 200 customer support interactions to create a specialized text generation model.

## 🚀 Project Overview
The goal was to adapt a general-purpose language model to understand the specific tone and vocabulary of customer service queries and responses.

## 📊 Dataset & Model
* **Base Model:** `gpt2` (Pre-trained)
* **Dataset:** `customer_support_dataset_200.csv`
* **Task:** Causal Language Modeling (Text Generation)

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** HuggingFace `transformers`, `datasets`, `accelerate`, `torch`
* **Infrastructure:** Trained using PyTorch with a focus on GPU efficiency.

## 📋 How to Run
1. Clone the repo: `git clone https://github.com/srivastavaaishwarya-analyst/LLM---Fine-tuning.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Ensure the `.csv` file is in the root directory.
4. Run the training script: `python fine_tune_model.py`
