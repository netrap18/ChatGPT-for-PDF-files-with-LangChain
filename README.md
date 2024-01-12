# automating-pdf-interaction-with-langchain-and-chatgpt

## Requirements

- Python 3.10
- Create a file .env and add an variable environment for OPENAI_API_KEY

  OPENAI_API_KEY=xxxxxxxx

Create your own ChatPDF clone using LangChain’s PDF loader, OpenAI Embeddings, and GPT-3.5. You will create a chatbot that can communicate with your book, legal documentation, and other important PDF documents. 
1.Loading the document
We will use the LangChain document loader to load PDFs and read the contents.
2.Creating embeddings and Vectorization
We will create embeddings using OpenAIEmbeddings class from LangChain API. After that, pass these embeddings to the Chroma class to create a vector database for the PDF document. 
3.Querying the PDF
Conclusion

This tutorial demonstrates how to use the langchain library and ChatGPT API to create a chatbot that can answer questions about the content of a PDF document. You can easily create a chatbot for any PDF document by following the steps provided.
