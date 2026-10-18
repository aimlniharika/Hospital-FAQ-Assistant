# 🏥 Hospital FAQ Assistant using RAG

An AI-powered Hospital FAQ Assistant that answers common hospital-related questions by retrieving relevant information from a hospital FAQ knowledge base.

## 📌 Project Overview

The **Hospital FAQ Assistant** is a Retrieval-Augmented Generation (RAG) prototype designed to help users find answers to frequently asked questions about hospital services, appointments, registration, pharmacy, billing, laboratory services, visiting hours, and patient facilities.

Instead of relying only on a language model's internal knowledge, the system retrieves relevant information from a dedicated FAQ dataset to help generate context-based responses.

## 🎯 Objectives

- Provide answers to common hospital-related questions.
- Retrieve relevant information from a hospital FAQ knowledge base.
- Demonstrate how semantic search and RAG can support question answering.
- Reduce the effort required to search through FAQ documents manually.

## ✨ Features

- Hospital FAQ question-answering.
- PDF-based knowledge source.
- Semantic retrieval of relevant FAQ information.
- Context-based answer generation.
- Responses for common hospital services and patient queries.
- Handling of questions that may not be covered by the knowledge base.

## 🔄 System Workflow

1. **User Query:** The user asks a hospital-related question.
2. **Knowledge Base:** The hospital FAQ dataset provides the source information.
3. **Semantic Search:** Relevant FAQ content is retrieved.
4. **Context Retrieval:** The most relevant information is selected.
5. **Answer Generation:** The RAG pipeline generates a response using the retrieved context.
6. **Final Response:** The answer is displayed to the user.

## 🛠️ Technologies Used

- Python
- Google Colab
- Retrieval-Augmented Generation (RAG)
- Natural Language Processing (NLP)
- Semantic Search and Embeddings
- PDF-based FAQ dataset
- Large Language Models (LLMs)

*The specific libraries and models depend on the implementation in the notebook.*

## 📂 Project Files

- `Hospital_FAQ_Assistant.ipynb` — Google Colab notebook containing the project implementation.
- `Hospital_FAQ_Dataset.pdf` — FAQ knowledge base used by the assistant.

## 🚀 How to Run

1. Open the notebook in this repository.
2. Download the notebook or open it using Google Colab.
3. Upload or load the hospital FAQ PDF when prompted.
4. Run the notebook cells in the correct order.
5. Follow the notebook instructions to ask questions and test the assistant.

## 🧪 Example Questions

- What are the hospital visiting hours?
- How can I book a doctor appointment?
- Is emergency service available 24 hours?
- What documents are needed for patient registration?
- Is a pharmacy available?
- Where can I pay my hospital bill?

## ⚠️ Disclaimer

This project is an educational prototype developed for learning and demonstration purposes. The included FAQ dataset contains generic hospital information and is not an official hospital policy document. Information must be verified with the relevant hospital before real-world use.

This assistant is not intended to provide medical diagnoses, treatment recommendations, or emergency medical advice. In an emergency, contact local emergency services or go to the nearest emergency department.

## 👩‍💻 Author

**Niharika**

GitHub: [@aimlniharika](https://github.com/aimlniharika)

## 🌟 Future Enhancements

- Add a user-friendly web interface.
- Improve retrieval accuracy and answer relevance.
- Support additional hospital documents.
- Add multilingual question answering.
- Deploy the assistant as a web application.

---

If you find this project interesting, feel free to explore the repository and share feedback!
