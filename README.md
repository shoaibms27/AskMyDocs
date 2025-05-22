# AskMyDocs

AskMyDocs is an AI-based web app that allows users to upload PDF documents and ask questions related to their content. Using RAG-based architecture and the Mistral-7B model, it processes the document, retrieves relevant information, and generates precise answers to user queries.

## Features

- PDF document upload and processing
- Natural language question answering
- RAG (Retrieval-Augmented Generation) architecture
- Powered by Mistral-7B model
- User-friendly web interface built with Streamlit

## Prerequisites

- Python 3.8 or higher
- pip (Python package installer)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/AskMyDocs.git
cd AskMyDocs
```

2. Install the required dependencies:
```bash
pip install -r reqirements.txt
```

3. Set up environment variables:
Create a `.env` file in the root directory and add your API keys:
```
TOGETHER_API_KEY=your_together_api_key
```

## Usage

1. Start the application:
```bash
streamlit run app.py
```

2. Open your web browser and navigate to `http://localhost:8501`

3. Upload a PDF document using the file uploader

4. Ask questions about the document content in the text input field

## Dependencies

- streamlit - Web application framework
- python-dotenv - Environment variable management
- langchain - LLM application framework
- langchain-community - Community components for langchain
- faiss-cpu - Vector similarity search
- together - Together AI client
- huggingface-hub - Hugging Face model hub client

## Project Structure

- `app.py` - Main application file containing the Streamlit web interface
- `test.py` - Test suite for the application
- `reqirements.txt` - Python dependencies
- `.env` - Environment variables (not tracked in git)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- [Mistral AI](https://mistral.ai/) for the Mistral-7B model
- [Together AI](https://www.together.ai/) for model hosting
- [Streamlit](https://streamlit.io/) for the web framework
