# 📚 AI Book Generator

> Transform your ideas into comprehensive books using state-of-the-art AI powered by Groq's ultra-fast infrastructure.

## 🌟 Features

- 📖 Complete Book Generation
- ⚡ Ultra-fast Processing with Groq
- 🎨 Customizable Content Structure
- 📑 Multiple Export Formats (PDF/Markdown)
- 🔧 Advanced Configuration Options
- 🎯 Topic-focused Structure
- 🤖 Multiple AI Model Support

## 🚀 Quick Start

### Prerequisites

- Python 3.9+
- Groq API Key
- Required system dependencies for PDF generation

### Installation

1. Clone the repository:

```bash 
git clone https://github.com/tech-rakesh-ai/ai-book-generator.git
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Create a `.env` file in the root directory and add your Groq API key:

```bash
GROQ_API_KEY=your_groq_api_key
``` 

4. Run the application:

```bash
streamlit run main.py
```

## 📚 Documentation

For more detailed information on how to use the AI Book Generator, please refer to the [Documentation](https://github.com/tech-rakesh-ai/ai-book-generator/blob/main/README.md).

## 🛠️ Features in Detail

### Basic Mode
- Simple interface for quick book generation
- Topic input and additional instructions
- Streamlined process with default settings

### Advanced Mode
- Multiple AI model selection for different generation tasks
- Customizable writing style and complexity levels
- Seed content integration
- File upload support
- Detailed generation statistics

### Export Options
- Download as PDF with styled formatting
- Export as Markdown/Text file
- Structured content with proper headings

## 🤖 Supported AI Models

- LLaMA 3.3 70B
- Mixtral 8x7B
- Gemma 2 9B
- LLaMA 3.1 8B
- Other Groq-supported models

## 🐳 Docker Support

Build and run using Docker:

```bash
docker build -t ai-book-generator .
docker run -p 8000:8000 ai-book-generator
```

## 🔧 Technical Architecture

The project is structured into several key components:

- `agents/`: AI generation logic for titles, structure, and content
- `ui/`: Streamlit interface components
- `tools/`: Utility functions for file handling
- `inference/`: Generation statistics and monitoring

## 💡 Usage Tips

1. Use advanced mode for more control over generation
2. Provide detailed instructions for better results
3. Upload seed content for context-aware generation
4. Experiment with different AI models for optimal results

## 👨‍💻 Developer

**Rakesh Kumar**
- Senior Software Engineer & AI Enthusiast
- Expertise in Prompt Engineering, GenAI, and NLP
- [LinkedIn](https://www.linkedin.com/in/tech-rakesh-ai/)
- [GitHub](https://github.com/tech-rakesh-ai/)

## 📄 License

MIT License - See LICENSE file for details

## 🙏 Acknowledgments

- Powered by Groq's Infrastructure
- Built with Streamlit
- PDF generation using WeasyPrint



