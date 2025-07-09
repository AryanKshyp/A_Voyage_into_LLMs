**Mentees have the option to pick any one of these projects to work on.**
Each project explores a different aspect of modern NLP and generative AI — from building foundational models to applying them in practical use-cases.

## 📝 Projects

### 1️⃣ Build a GPT from Scratch
- **Description:**  
  Implement a mini version of GPT (Generative Pretrained Transformer) from scratch to deeply understand the internals of transformer-based language models.
- **Key Objectives:**  
  - Tokenization and embeddings  
  - Implementing self-attention & multi-head attention  
  - Training on a small corpus  
  - Generating text samples
- **Technologies:**  
  Python, PyTorch, NumPy
- **Resources:**  
  - 📺 [Karpathy’s YouTube video: "Let's build GPT from scratch"](https://www.youtube.com/watch?v=kCc8FmEb1nY)

---

### 3️⃣ Fine-Tune GPT-2 on Custom Text
- **Description:**  
  Fine-tune the free, open-source GPT-2 model on a **dataset of your choice**, such as a collection of short stories, technical articles, or blog posts, to teach it to generate text in that specific style or domain.  
  The project involves end-to-end data preparation, training, and evaluation — resulting in a mini language model specialized on your dataset.
- **Key Objectives:**  
  - Collect or prepare a text dataset in a specific domain or style (e.g. sci-fi stories, cricket blogs, etc.)
  - Tokenize and format the dataset for causal language modeling
  - Fine-tune GPT-2 using the Hugging Face `Trainer` API
  - Generate and compare text samples before and after fine-tuning to observe how the model has adapted
- **Technologies:**  
  Python, PyTorch, Hugging Face Transformers & Datasets
- **Resources:**  
  - 📓 [Hugging Face Fine-Tuning GPT-2 Notebook](https://colab.research.google.com/github/huggingface/notebooks/blob/main/examples/language_modeling.ipynb)  
  - 📚 [Transformers Docs - Language Modeling](https://huggingface.co/docs/transformers/tasks/language_modeling)
