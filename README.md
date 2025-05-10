# PDF Chat Assistant with Gemini Flash 1.5

🔍 **AI-Powered Document Understanding** • 🚀 **RAG Architecture** • 📄 **Multi-PDF Support**

![RAG Architecture Diagram](https://miro.medium.com/v2/resize:fit:1400/1*3sbD8x4dYU-E4OpE9j0wFw.png)

A sophisticated Question-Answering system that understands your PDF documents using state-of-the-art AI technologies.

## Features ✨

- **Multi-PDF Analysis**: Process multiple documents simultaneously
- **Context-Aware Answers**: Powered by Gemini Flash 1.5 LLM
- **Semantic Search**: FAISS vector similarity search
- **Conversational Interface**: Streamlit-based chat UI
- **Source Tracing**: Always show document sources for answers

## Technology Stack 🛠️

| Component              | Technology           |
|------------------------|----------------------|
| Text Embedding          | all-MiniLM-L6-v2     |
| Vector Store            | FAISS                |
| Language Model          | Gemini Flash 1.5     |
| PDF Processing          | pdfplumber           |
| UI Framework            | Streamlit            |

## Getting Started 🚀

### Prerequisites
- Python 3.8+
- Gemini API key ([Get it here](https://ai.google.dev/))

### Installation

1. Clone repository:
   ```bash
   git clone https://github.com/yourusername/pdf-chat.git
   cd pdf-chat
