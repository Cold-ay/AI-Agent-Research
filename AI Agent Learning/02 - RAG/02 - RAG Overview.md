# RAG Overview

## Overview

Back to [[AI Agent Learning/00 - AI Agent Knowledge Map|00 - AI Agent Knowledge Map]].

## Key Concepts

### Study Sequence

- **[[AI Agent Learning/02 - RAG/RAG|RAG]]**（檢索增強生成）
  Retrieval-augmented generation supplies retrieved external evidence to a model before it generates an answer.
- **[[AI Agent Learning/02 - RAG/Embeddings|Embeddings]]**（向量嵌入）
  Learned numeric representations that encode useful features of text or other data.
- **[[AI Agent Learning/02 - RAG/Cosine Similarity|Cosine Similarity]]**（餘弦相似度）
  A measure of vector direction agreement: cos(a,b) = (a·b) / (||a|| ||b||), for nonzero vectors.
- **[[AI Agent Learning/02 - RAG/Vector Database|Vector Database]]**（向量資料庫）
  A database or database capability that stores vectors and supports similarity retrieval, often with metadata and document references.
- **[[AI Agent Learning/02 - RAG/Chunking|Chunking]]**（文件分塊）
  Splitting source material into units suitable for retrieval and model input.
- **[[AI Agent Learning/02 - RAG/Semantic Search|Semantic Search]]**（語義搜尋）
  Retrieval based on meaning or learned relevance rather than only literal term overlap.
- **[[AI Agent Learning/02 - RAG/BM25 and Sparse Search|BM25 and Sparse Search]]**（BM25／稀疏搜尋）
  BM25 is a lexical ranking function using term frequency, inverse document frequency, and document-length normalization. Sparse retrieval is a broader family.
- **[[AI Agent Learning/02 - RAG/Hybrid Search|Hybrid Search]]**（混合搜尋）
  Combining multiple retrieval signals, commonly lexical and dense semantic retrieval.
- **[[AI Agent Learning/02 - RAG/Reciprocal Rank Fusion|Reciprocal Rank Fusion]]**（倒數排名融合）
  A method that combines ranked lists by adding contributions based on each item’s rank.
- **[[AI Agent Learning/02 - RAG/Reranking|Reranking]]**（重新排序）
  Scoring an already retrieved candidate set again with a more focused relevance method.
- **[[AI Agent Learning/02 - RAG/Metadata Filtering|Metadata Filtering]]**（元資料過濾）
  Restricting eligible records using fields such as version, tenant, date, or document type.

## Related Notes

**Next cluster:** [[AI Agent Learning/03 - Agent Core/03 - Agent Core Overview|Agent Core]].
