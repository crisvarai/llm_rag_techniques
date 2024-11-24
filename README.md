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

## Naive RAG

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

## Advanced RAG
Introduces specific improvements to overcome the limitations of Naive RAG. Focus on enhancing retrieval quality.

Employs the following strategies:

1. Pre-retrieval
    - Improvement of the indexing structure and user's query.
    - Improves data details, organization indexes better, adding extra information, aligning things correctly...

2. Post-retrieval
    - Combine pre-retrieval data with the orginal query (re-ranking to highlight the most important content...)

#### Query Expansion (with generated answers)

Generate potential answers to the query [using an LLM] and to get relevant context.

Use cases:
- Information Retrieval
- Question Answering Systems
- E-commerce Search
- Academic Research

## Install dependencies

`pip install openai`

`pip install chromadb`

`pip install python-dotenv`

`pip install pypdf`

`pip install pandas`

`pip install langchain`

`pip install sentence-transformers`

`pip install umap-learn`

`pip install matplotlib`