# 🩺 Diabetes Mellitus Chatbot using LangChain & BioMistral

This project implements an intelligent, domain-specific chatbot designed to assist with questions related to **Diabetes Mellitus**, using the **BioMistral** large language model and **LangChain** framework.

It combines biomedical language understanding with prompt orchestration, retrieval augmentation, and optional document/question embedding for accurate, medically-informed responses.

---

## 🧠 Key Features

- 🔬 **BioMistral Model**: A biomedical-tuned LLM for understanding medical terms and generating reliable clinical answers.
- 💬 **LangChain Framework**: Enables modular and scalable conversational workflows.
- 📚 **Domain-Specific Knowledge**: Integrated retrieval and prompting tailored to **Diabetes Mellitus**, including symptoms, diagnosis, treatment, and lifestyle support.
- 🧾 Optional **RAG Support**: Incorporate structured medical documents or custom PDFs for more grounded answers.

---

## 🧪 Use Cases

- Understanding **types of diabetes** (Type 1, Type 2, Gestational)
- Medication guidance and lifestyle interventions (diet, exercise)
- Answering patient questions in natural language
- Generating summaries from medical notes or guidelines
- Supporting non-specialists in patient care

---

## 🔧 Tech Stack

- **LLM**: [BioMistral](https://huggingface.co/medalpaca/BioMistral)
- **LangChain**: Conversational framework with support for chains, memory, and tools
- **Embedding Model** : `sentence-transformers/all-MiniLM-L6-v2` or any BioEmbeddings model
- **Vector Store** : ChromaDB


---

