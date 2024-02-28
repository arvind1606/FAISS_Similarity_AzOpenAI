# FAISS_Similarity_AzOpenAI
This code utilizes OpenAI's GPT-4 engine to encode text into embedding vectors, calculates cosine similarity between these vectors, and finds similar documents above a given threshold. 


Sets up OpenAI API key and endpoint using environment variables.
Defines a function encode_text to encode text using the GPT-3 engine and returns the embedding vector.
Calculates cosine similarity between two vectors using the cosine_similarity function.
Finds similar documents based on cosine similarity above a threshold using the find_similar_documents function.
Encodes example text documents and a query text using GPT-3 embeddings.
Finds similar documents to the query among the example documents and prints the indices and similarity scores of similar documents.
