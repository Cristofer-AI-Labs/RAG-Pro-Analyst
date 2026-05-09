# RAG-Pro-Analyst
"Advanced RAG system with 90% accuracy, featuring a two-stage re-ranking architecture and Pandas integration for private document analysis."

## 🚀 System Capabilities
The **RAG Pro Analyst** enables chatting with files (PDF, CSV, Excel), ensuring that the information used in responses comes exclusively from the provided context.

- **Semantic Precision:** Text fragment retrieval using high-density embeddings.
- **Mathematical Analysis:** Structured data processing for financial audits and real-time calculations.
- **Zero Hallucinations:** Responses validated against the original data source.
- **Streaming Response:** Smooth interface via WebSockets for an immediate user experience.

---

## 🛠️ Technical Architecture
The system integrates multiple processing layers to ensure the relevance of every response:

1.  **AI Engine:** Integration with state-of-the-art Large Language Models (LLM) (Gemini 2.0).
2.  **Vector Database:** Persistent storage in **ChromaDB**.
3.  **Retrieval Pipeline:**
    - **Vector Search:** Initial filtering by similarity.
    - **Semantic Re-ranking:** Use of a `Cross-Encoder` to prioritize fragments with the highest information density relative to the query.
4.  **Data Processing:** Use of **Pandas** for extracting and analyzing tables and financial reports.
5.  **Security:** Session management through **JWT** and automatic history clearing.

---

## 📊 Use Cases
The system has been validated in high-complexity scenarios:
- Audit of loans and interest rates.
- Summaries of marketing campaigns and accumulated ROI.
- Comparative analysis of financial periods.

---

## 🔒 Code Status
The source code for this project is kept in a **private repository**. This documentation serves as a demonstration of technical capabilities implemented in the fields of Artificial Intelligence and Natural Language Processing (NLP).

---
*Technical documentation of the RAG Artificial Intelligence system.*
