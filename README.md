# Fine-Tuning DeepSeek R1 Reasoning Model

This notebook walks through the process of **fine-tuning the DeepSeek R1 Reasoning Model** using the Hugging Face ecosystem. It is based on the tutorial provided by DataCamp and demonstrates how to adapt a powerful open-source LLM to a custom reasoning dataset using techniques like LoRA (Low-Rank Adaptation) for efficient training.

## 🚀 What This Notebook Does

- **Loads the DeepSeek R1 reasoning model and tokenizer** from Hugging Face.
- **Prepares a custom reasoning dataset** in a conversational prompt-response format.
- **Applies LoRA-based fine-tuning** via the PEFT (Parameter-Efficient Fine-Tuning) library.
- **Trains the model using Hugging Face’s `Trainer`** API for streamlined fine-tuning.
- **Evaluates and generates predictions** using the fine-tuned model.

## 🧠 Use Case

Fine-tuning the DeepSeek R1 model can be useful for:

- Enhancing reasoning performance on domain-specific tasks (e.g., legal, medical, academic reasoning)
- Creating a custom assistant that excels at structured problem solving

## 🛠️ Setup Instructions

To run this notebook, you'll need:

1. Python 3.8+
2. Hugging Face token to access datasets and push the trained model 
3. GPU (Google Colab) as training a model is compute intensive


## 📊 Output

After training, you’ll get a model that performs improved reasoning on the style of tasks provided in your custom dataset. You can test it interactively or deploy it via a Hugging Face model hub or inference API.
