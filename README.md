## Drug Repurposing using Knowledge Graph Embeddings 💊

Drug repurposing methods can identify already approved drugs to treat them efficiently, reducing development costs and time. At the same time, knowledge graph embedding techniques can encode biological information in a single structure that allows users to operate relationships, extract information, learn connections, and make predictions to discover potential new relationships between existing drugs and vector-borne diseases.

In this project, we compare seven knowledge graph embedding models (TransE, TransR, TransH, UM, DistMult, RESCAL, and ERMLP) applied to Drug Repurposing Knowledge Graph (DRKG), analyzing their predictive performance over seven different vector-borne diseases (dengue, chagas, malaria, yellow fever, leishmaniasis, filariasis, and schistosomiasis), measuring their embedding quality and external performance against a ground-truth.

This project relates to the paper **[Drug Repurposing Using Knowledge Graph Embeddings with a Focus on Vector-Borne Diseases: A Model Comparison](https://link.springer.com/chapter/10.1007/978-3-031-40942-4_8)** as developed by [Diego López Yse](https://www.linkedin.com/in/lopezyse/) and [Diego Torres](https://www.linkedin.com/in/ditorres/) for the Conference on Cloud Computing, Big Data & Emerging Topics 2023.

You can find here the data and code used for developing and evaluating the predictive models.

### Repository structure

- **[streamlit_app.py](streamlit_app.py)**: outputs a drug ranking prediction based on a chosen disease and embedding model
- **[embedding_models](embedding_models)**: contains the embedding models and predictions on target diseases performed on the DRKG dataset.


### Environment
The project was developed using Visual Studio Code 1.84 with Python 3.10.13
