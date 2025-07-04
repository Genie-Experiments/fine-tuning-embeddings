# 🧠 LLM Dataset Generation & Fine-Tuning Pipeline

This repository provides a streamlined pipeline to generate structured datasets and fine-tune Large Language Models (LLMs). It includes two key stages: dataset generation and model fine-tuning, designed for experiments involving preference modeling, instruction tuning, or other supervised tasks.

---

## 📂 Notebooks Overview

### 1. `generate_dataset.ipynb`

🔧 **Purpose**:
Builds a training dataset by generating or transforming samples into a structured format suitable for fine-tuning.

💡 **Highlights**:

* Customizable input schema
* Can integrate synthetic data generation using LLMs
* Saves output as JSONL or CSV for training compatibility

---

### 2. `finetune.ipynb`

🚀 **Purpose**:
Fine-tunes a pre-trained LLM using the generated dataset.

💡 **Highlights**:

* Uses HuggingFace `transformers` and `datasets` libraries
* Supports LoRA, QLoRA, or full fine-tuning
* Includes training, evaluation, and model saving logic
* Logs performance and supports GPU acceleration

---

## 🛠️ Setup

1. **Clone the repo**

   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```

2. **Install dependencies**
   Recommended using a virtual environment.

   ```bash
   pip install -r requirements.txt
   ```

3. **Run Notebooks**
   Open the notebooks in Jupyter or VSCode:

   ```bash
   jupyter notebook
   ```




