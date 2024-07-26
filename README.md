# PDFQUERY
Sure, I'll remove the code snippets and provide a concise README file without them:

---

# PDF Query Using Langchain

This project demonstrates how to use Langchain to query a PDF document. It involves extracting text from a PDF, splitting the text into manageable chunks, embedding the text using OpenAI's embeddings, and then storing and querying these embeddings using FAISS.

## Installation

To get started, clone the repository and install the required packages:

```sh
git clone <repository-url>
cd <repository-directory>
pip install -r requirements.txt
```

Ensure you have the following packages installed:

- langchain
- openai
- PyPDF2
- faiss-cpu
- tiktoken

## Usage

1. Import Necessary Libraries

2. Load and Read PDF

3. Extract Text from PDF

4. Split Text into Chunks

5. Embed Text Using OpenAI

6. Store and Query Embeddings Using FAISS

## Example

To query the PDF document, provide your query text and retrieve the results.

## Dependencies

- Python 3.x
- langchain
- openai
- PyPDF2
- faiss-cpu
- tiktoken

## Notes

- Ensure you have an OpenAI API key to use the embedding functionalities.
- Modify the chunk size and overlap in the `CharacterTextSplitter` as needed for your specific PDF document.

## Credits

This project is developed using Langchain, OpenAI, PyPDF2, and FAISS.
