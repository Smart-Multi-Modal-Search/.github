
This projects leverages latest natural language processing technologies to push product search beyond key-words. By utilizing embeddings, users can conduct true semantic search and identify product that meet their needs easily.

Product information and related media (images, video, etc) are converted to vectors using contextual embeddings and vector data is stored in a vector database. The project uses 
[Weaviate](https://weaviate.io/)
open source vector database.

Prototype Demo of Smart Search at :http://35.224.107.49:8000/

A novel experiment is the use of CLIP (
[Constrastive Language Image Pretraining](https://github.com/openai/CLIP)
) model to enable an user to describe products in their own (natural language) and vectorize such
descriptions using CLIP embeddings and search across the web for products meeting the needs.

Future plans include the ability to utilize an app that can take pictures and capture additional
product features from spoken words and utilize both to seach for the relevant products.

MLOPS DECK 
![Screen Shot 2022-06-09 at 6.27.13 PM.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/bd7642fa-6abc-42ea-b7cd-de469a2512a1/Screen_Shot_2022-06-09_at_6.27.13_PM.png)
