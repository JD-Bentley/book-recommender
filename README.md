# (In-Progress) Book Recommender: Document retrieval system.
Creating a retrieval system that finds top-n matching books to user's query using book properties (including summary embeddings) and a chat-based model.

#### Overview

## Major libraries/frameworks used:
* [NLTK](https://www.nltk.org/) & [langdetect](https://github.com/shuyo/language-detection) for text cleaning.
* [Transformers](https://pypi.org/project/transformers/) for [HuggingFace](https://huggingface.co/), LLMs, and tokenizers.
* [Pinecone](https://www.pinecone.io/product/) for the vector database.
* [Langchain](https://python.langchain.com/docs/introduction/) for RAG.
