# Text Summarization Web Application using LLaMA2 and Flask

This web application uses the LLaMA2 model for text summarization and Flask as the web framework for users to input text and get a summary.

## Installation

1. Install the required packages:

```bash
pip install -q transformers einops accelerate langchain bitsandbytes
!huggingface-cli login
!pip install sentencepiece
pip install langchain_community
```

2. Run the Flask app:

```bash
python app.py
```

3. Access the web application at the provided URL (usually `http://localhost:5000/`).

## Usage

1. Enter a paragraph of text into the input field.
2. Click the "Summary" button to generate a summary.
3. The output summary will be displayed in the table below the input field.

## Dependencies

- Transformers
- Einops
- Accelerate
- Langchain
- Bitsandbytes
- Sentencepiece