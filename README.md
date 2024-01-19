
# Search Your PDF

This project is based on searching your pdf with some questions. This is an open source models. There is no OpenAI key required for this model. 


## WorkFlow

1) PDF File
2) For Text Preprocessing, Langchain is used. 
3) To Create Embeddings, Sentence Transformer is used.
https://huggingface.co/sentence-transformers/all-MiniLM-L6-v2 

4) Vector Store(ChromaDB) is used for storing those Embeddings.
5) For LLMPipeline, huggingFace is used.
https://huggingface.co/MBZUAI/LaMini-T5-738M
            
## Installation

    pip install -r requirements.txt



## Run Locally

Clone the project

```bash
  git clone https://link-to-project
```

Go to the project directory

```bash
  cd my-project
```

Install dependencies

```bash
  npm install
```

Start the server

```bash
  npm run start
```

    python ingest.py

    streamlit run app.py 
## Screenshots



