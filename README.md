# llm_rag_techniques

## RAGs

### What is a RAG?

**Definition** - A framework that combines the strengths of retrieval-based systems and generation-based models to produce more accurate and contextual relevant response.

**Translation** - Efficient way to customize an LLM (model) with your own data.

### Components of RAG

- **Retriever**
    - Identifies and retrieves relevant documents
- **Generator**
    - Takes retrieved docs and the input query to generate coherent and contextually relevant responses.

### Naive RAG

- **Indexing**
    - Cleaning, extracting data from docs...
- **Retrieval**
    - Turn question into a vector. Vector comparasion... Retrieves closely related chunks...
- **Generation**
    - The quer, choose docs combined into a prompt. The model generates an answer...

#### Drawbacks and Challenges

1. Limited contextual understanding.
2. Inconsistent relevance and quality of retrieved documents.
3. Poor integration between retrieval and generation.
4. Inefficient handling of Large-Scale data.
5. Lack of robustness and adaptability.

## Install dependencies

`pip install openai`

`pip install chromadb`

`pip install python-dotenv`