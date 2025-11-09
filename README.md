# Conversational Recommender System – Validation Dataset

This repository contains the **validation dataset** used to evaluate the *Hybrid Conversational Recommender System (H-CRS)* against a baseline ChatGPT model.  
The dataset includes six conversational topics designed to test **accuracy**, **relevance**, and **factual grounding** in an e-commerce context.

---

##  Dataset Overview

Each topic represents a distinct type of conversational interaction:

1. **General Questions** – Open-ended brewing questions.  
2. **Avoid Not-Related Subjects** – Off-domain prompts used to test intent filtering.  
3. **Support for Specific Products** – Catalog-linked factual queries.  
4. **Product Recommendation** – Catalog-grounded product suggestions.  
5. **Product Comparisons** – Comparative reasoning between similar products.  
6. **Boundary and Clarification Handling** – Ambiguous user requests that require follow-up clarification.

Each entry in the dataset includes:
- The **user question**,  
- The **H-CRS response**,  
- The **ChatGPT baseline response**,  
- And an optional **expected behavior** description.

---

## Reference

Pașcan, C.O., Hajdu Măcelaru, M., & Pop, P. (2025).
Hybrid Conversational Recommender System for E-Commerce.
