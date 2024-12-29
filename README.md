## 🦙 Local RAG Agent with Llama 3.2
A local Retrieval-Augmented Generator (RAG) agent using the Phi framework & Llama 3.2 via Ollama, with Qdrant as the vector database.

### Features
- Fully local RAG implementation
- Knowledge Base: Automatically extracts and embeds information from a Thai recipe PDF.
- Vector Search: Efficiently retrieves relevant knowledge using the Qdrant vector database.
- Language Model Agent: Employs Ollama's llama3.2 model for natural language understanding and generation.
- Interactive Playground: Provides a user-friendly web interface to interact with the agent.
- No external API dependencies

### Project Structure

#### Core Components
- Agent: Uses Ollama’s llama3.2 model and connects to the knowledge base.
- Knowledge Base: Extracts text from a provided PDF and stores embeddings in Qdrant.
- Vector Database: Qdrant is used for storing and querying vectorized data.
- Playground UI: Provides a web-based interface for querying the RAG agent.

#### Libraries Used
-phi.agent: For creating the RAG Agent.
-phi.model.ollama: Integration with Ollama language models.
-phi.knowledge.pdf: PDF processing and knowledge base creation.
-phi.vectordb.qdrant: Qdrant as the vector database.
-phi.embedder.ollama: Ollama model for generating vector embeddings.
-phi.playground: Interactive user interface for querying the agent.
