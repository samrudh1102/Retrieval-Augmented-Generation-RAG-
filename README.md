# Retrieval Augmented Generation

This is a proof-of-concept of retrieval augmented generation, using Google's PaLM API.  

Then we create embeddings (also using PaLM) for each E-Mail and store them in a vector DB (ChromaDB was used here).

Then we allow users to ask questions about the E-Mails in natural language, and answer them using a combination of embedding retrieval and LLM-based (PaLM again) text generation.
