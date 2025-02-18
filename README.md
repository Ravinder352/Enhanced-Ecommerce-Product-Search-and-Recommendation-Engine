markdown
# Enhanced Ecommerce Product Search and Recommendation Engine  

## Overview  

The Enhanced Ecommerce Product Search and Recommendation Engine is a hybrid search system designed to improve the accuracy and relevance of product retrieval. By integrating multiple techniques—including BM25, fuzzy matching, and semantic embeddings—this system addresses common issues in product search such as typos, partial matches, and ambiguous queries.  

## Key Features  

- **Hybrid Approach**: Combines traditional information retrieval methods with advanced machine learning techniques.  
- **BM25 Algorithm**: Utilizes the BM25 ranking function for effective relevance scoring based on term frequency and document length.  
- **Fuzzy Matching**: Implements fuzzy matching to handle user queries with typos or spelling errors, ensuring users still receive relevant results.  
- **Semantic Embeddings**: Uses [SentenceTransformer](https://github.com/UKPLab/sentence-transformers) to generate semantic embeddings, allowing for context-aware recommendations and enhancing the understanding of user intent.  
- **Cosine Similarity for Ranking**: Employs cosine similarity to compare and rank product embeddings, ensuring the most relevant products are displayed to the user.  

## Data Preprocessing  

- **Spell Correction**: Integrated **SymSpell** for efficient spell correction, significantly reducing errors in user queries.  
- **Query Expansion**: Leveraged **spaCy’s word vectors** for expanding queries and improving the match potential against available products.  


Dataset Link: [Dataset](https://drive.google.com/file/d/1neFzo59lvad0KlfvZwAjE9ybaxSIj1vM/view?usp=sharing)

GoogleNews Vectors.. link : [Google News Vectors](https://docs.google.com/open?id=0B7XkCwpI5KDYNlNUTTlSS21pQmM)

**📝Make sure to downloaded these files before running project.**

