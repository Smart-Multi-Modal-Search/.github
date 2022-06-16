
This projects leverages latest natural language processing technologies to push product search beyond key-words. By utilizing embeddings, users can conduct true semantic search and identify product that meet their needs easily.

Product information and related media (images, video, etc) are converted to vectors using contextual embeddings and vector data is stored in a vector database. The project uses 
[Weaviate](https://weaviate.io/)
open source vector database.

Smart Search :http://35.224.107.49:8000/

A novel experiment is the use of CLIP (
[Constrastive Language Image Pretraining](https://github.com/openai/CLIP)
) model to enable an user to describe products in their own (natural language) and vectorize such
descriptions using CLIP embeddings and search across the web for products meeting the needs.
