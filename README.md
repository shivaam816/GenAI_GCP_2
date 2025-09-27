# GenAI_GCP_2
Created this repo for Assignment 2 purpose
# Assignment 2 - Personalized Course Recommendation Engine  

## Overview  
This project implements a **Personalized Course Recommendation Engine** for an online learning platform.  
Given a learner profile (completed courses + interest blurb), the engine recommends the **top-5 most relevant courses** from the catalog.  

The approach uses:  
- **Embeddings** for semantic understanding of course descriptions and learner queries  
- **Vector Database (FAISS)** for similarity search  
- **Cosine similarity** for ranking recommendations  

---

## Objectives & Learning Outcomes  
- Learn to compute embeddings and use them for semantic search  
- Build and query a vector database for fast retrieval  
- Implement a ranking function for recommendations  
- Evaluate the system with test profiles and comment on relevance  

---

## Tech Stack & Tools  
- **Language:** Python 3.10+  
- **Libraries:**  
  - `pandas` - data handling  
  - `langchain` - embeddings + vector store wrappers  
  - `sentence-transformers` - HuggingFace embedding model  
  - `faiss-cpu` - vector database  
- **Dataset:** [assignment2dataset.csv](https://raw.githubusercontent.com/Bluedata-Consulting/GAAPB01-training-code-base/refs/heads/main/Assignments/assignment2dataset.csv)  

---

## Sample Test Queries

"I’ve completed the 'Python Programming for Data Science' course and enjoy data visualization. What should I take next?"

"I know Azure basics and want to manage containers and build CI/CD pipelines. Recommend courses."

"My background is in ML fundamentals; I’d like to specialize in neural networks and production workflows."

"I want to learn to build and deploy microservices with Kubernetes—what courses fit best?"

"I’m interested in blockchain and smart contracts but have no prior experience. Which courses do you suggest?"

## Results