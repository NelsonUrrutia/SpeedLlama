# SpeedLlama

> ### A fast, focused interface for Ollama/Llama models.

## Why?
Existing tools struggle with Ollama integration (see [Zed #31788](https://github.com/zed-industries/zed/issues/31788)). 
SpeedLlama is built specifically for local models, optimizing for speed and good user experience.

## Technology Stack

| Component             | Technology                 | Purpose                 |
| --------------------- | -------------------------- | ----------------------- |
| **Local LLM**         | Ollama                     | Model inference         |
| **Database**          | SQLite                     | Metadata storage        |
| **File Storage**      | Markdown files             | Document content        |
| **Orchestration**     | Python                     | System coordination     |
| **Knowledge Base**    | Obsidian                   | Interface to edit files |
| **User Interface**    | Vite + JS                  | Interface to interact with Ollama |
| **Web Retrieval**     | Python requests/web search | External data fetching  |
| **API Communication** | HTTP/REST                  | Ollama API calls        |
