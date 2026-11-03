

flowchart TD

&#x20;   A\["User / Browser"] --> B\["Frontend<br/>HTML, CSS, JavaScript"]

&#x20;   B --> C\["C++ Backend<br/>HTTP Server / REST API"]



&#x20;   C --> D\["Document Processing"]

&#x20;   D --> E\["Text Chunking"]

&#x20;   E --> F\["Ollama Embedding Model<br/>nomic-embed-text"]

&#x20;   F --> G\["Vector Database"]



&#x20;   G --> H\["HNSW / KD-Tree / Brute Force"]

&#x20;   H --> I\["Relevant Document Chunks"]



&#x20;   I --> J\["RAG Pipeline"]

&#x20;   J --> K\["Ollama LLM<br/>llama3.2"]

&#x20;   K --> L\["AI-Generated Answer"]

&#x20;   L --> A



