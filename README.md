# Movie Recommendation RAG System

This repository contains a complete Retrieval-Augmented Generation (RAG) system built to provide personalized movie recommendations based on user text queries using **Qdrant** as a vector database and **Llama 3** as a local language model.

## System Architecture

```mermaid
graph TD
    A([1. Environment Setup]) --> B[/2. Data Ingestion/]
    B --> C[3. Infrastructure Initialization]
    C --> D[4. Collection Creation]
    D --> E[5. Vector Indexing]
    E --> F[/6. User Query Processing/]
    F --> G{7. Semantic Retrieval}
    G --> H[8. Output Visualization]
    H --> I[9. LLM Generation]
    I --> J([10. Final Recommendation])
