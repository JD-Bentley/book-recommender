# Book Recommender
How to create a retrieval system using LLM embeddings, a vectorstore, and a RAG pipeline.

#### Overview
This notebook goes through key steps in creating a book recommendation system, given a user's specific request/query.

## Major libraries used:
* [NLTK](https://www.nltk.org/) & [langdetect](https://github.com/shuyo/language-detection) for text cleaning.
* [Transformers](https://pypi.org/project/transformers/) for [HuggingFace](https://huggingface.co/), LLMs, and tokenizers.
* [Pinecone](https://www.pinecone.io/product/) for the vector database.
* [Langchain](https://python.langchain.com/docs/introduction/) for APIs & RAG.

## Requirements: 
* Pinecone API key to set up a private vectorstore.
* The [CMU book summary data set](https://www.kaggle.com/datasets/ymaricar/cmu-book-summary-dataset).
