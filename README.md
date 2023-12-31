# Chat PDF App using Langchain & OpenAI | Felix GG

**Try it out here:** [Chat PDF](https://chat-pdfs-e2d5fffecdd8.herokuapp.com/)

## Description

`chat-pdf` is an application designed to facilitate conversations with multiple PDFs using the power of OpenAI. Whether you're looking to extract specific information, get a summary, or simply interact with the content of your PDFs in a conversational manner, `chat-pdf` provides a seamless Streamlit interface to do so. Leveraging the capabilities of OpenAI, the application ensures intelligent and context-aware responses, making it a valuable tool for researchers, students, and professionals alike.

## Features

- Chat interface for multiple PDFs.
- Integration with OpenAI for context-aware responses.
- User-friendly interface ensuring smooth interactions.
- Deployed in Heroku for easy access.

## Important Note

Only documents with not many pages are supported, as the free Heroku plan has a very limited memory. On the other hand, when running it locally in my own machine (Macbook Pro M1 Pro 16GB RAM), I was able to run the application with multiple PDFs with about 100 pages each. It just took a while to load.

I therefore recommend you to run it locally if you want to use it with multiple PDFs with many pages. For that you'll need to:

- Clone the repository
- Install the requirements in `requirements.txt` and using the python version specified in `runtime.txt`
- Run `streamlit run app.py` in your terminal.

## Usage Requirements

- An OpenAI API key.

## Potential Changes

- Use Open-source models like Llama-2 instead of OpenAI
- Use Open-source Embeddings like Sentence-BERT instead of OpenAI
