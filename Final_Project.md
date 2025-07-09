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

### 2️⃣ A Chatbot over PDF using RAG

- **Objective**
  Implement a chatbot that can answer the questions specific to any PDF.
- **Description**
  Use any Large Language Model to create a basic chatbot that takes a PDF as argument and return answer based on the context from the pdf.
  You can access the PDF from your folder, no need to integrate upload mechanism in the app.
  Use [**UG Rulebook**](https://www.iitb.ac.in/newacadhome/ugrulebook.pdf) to test your chat bot.
- **Structure**
  - LLM model initialization
  - Pdf loading and parsing
  - Text splitter
  - Vector database
  - Searching and passing the context to the prompt
  - Custom prompt passing to the model and processing the output
  - Displaying output using UI
  - Optional: Evaluate how the LLM is doing and identify quantifiable metrics for that
- **Deliverables**
  No need to make a very complex chatbot. 
  - A python script or a github repo or a Jupyter notebook or a colab notebook with the code.
  - The code should have a basic UI either in Streamlit/Gradio or just a python one.
- **Tips and advices**
  - You are free to use any other LLM you can find. Recommendation: Use Llama-2 7b parameter model using HuggingFace for simple and quick execution.
  - Upload your project to github with a good readme file. (Other submition methods are also fine)
  
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

---
Feel free to reach out if you any queries regarding the project 
