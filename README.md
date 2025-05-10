# PDF Chat Assistant with Gemini Flash 1.5

<div align="center">
  <img src="assets/demo.gif" alt="Demo" width="800">
  <p><em>(Replace with your actual demo GIF - record using <a href="https://www.screentogif.com/">ScreenToGif</a>)</em></p>
</div>

## 📌 Features
- **Multi-PDF Processing** - Analyze multiple documents simultaneously
- **Smart Q&A** - Get accurate answers powered by Gemini Flash 1.5
- **Document Understanding** - Deep semantic comprehension of your files
- **Source Tracking** - Always see which document provided the answer

## 🛠️ Technology Stack
| Component           | Technology Used      | Purpose                     |
|---------------------|----------------------|-----------------------------|
| pdfplumber          | Text Extraction      | Extract text from PDFs       |
| Sentence-Transformers | all-MiniLM-L6-v2    | Generate text embeddings     |
| FAISS               | Vector Search        | Fast similarity search       |
| Gemini Flash 1.5    | Answer Generation    | Generate contextual answers  |
| Streamlit           | Web Interface        | User-friendly UI            |

## 🚀 Getting Started

### Prerequisites
- Python 3.8+
- [Gemini API key](https://ai.google.dev/)

### Installation
```bash
git clone https://github.com/yourusername/pdf-qa-assistant.git
cd pdf-qa-assistant
pip install -r requirements.txt
cp .env.example .env  # Add your Gemini API key here
