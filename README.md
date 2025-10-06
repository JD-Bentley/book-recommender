# (In-Progress) Book Recommender: A Document Retrieval System.
Creating a chat bot retrieval system that finds top-n matching books to user's query using book synopses and properties.

## The Working Parts:
### The Data
The database is populated using the [CMU Book Summary Dataset](https://www.kaggle.com/datasets/ymaricar/cmu-book-summary-dataset).
* This data set contains information on 16,559 books.
* The data set includes but is not limited to: Book title, Author, Publication date, Book genres, Plot summary.

### The Vector Database
A vector database is used in this project because the user's query will be evaluated against book summaries using cosine similarity analysis. Therefore, both the user's query and the book summaries will be transformed into vectors using an embedding model.
* The database used: [Pinecone](https://www.pinecone.io/)

### The Embedding Model
The LLM used for tokenization and feature embedding is the BERT-based model: "BAAI/bge-base-en". This model can be found on [Hugging Face](https://huggingface.co/BAAI/bge-base-en)

### The RAG pipeline:
* For RAG pipeline building: [Langchain](https://python.langchain.com/docs/tutorials/rag/)
* LLM for chatbot: currently undecided.

### UI:
* [Streamlit](https://streamlit.io/)
