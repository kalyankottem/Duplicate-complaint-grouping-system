# Duplicate Complaint Grouping System

## Description
This project detects duplicate or similar customer complaints and groups them into issue clusters using TF-IDF vectorization and cosine similarity. It helps CRM systems identify recurring issues and improve complaint routing and analysis.

---

## Problem Statement
Customers often report the same issue in different wording. Manual grouping of duplicate complaints is inefficient and error-prone.

This project automates duplicate complaint detection and issue clustering.

---

## Objective
- Detect duplicate / similar complaints  
- Group complaints into issue clusters  
- Count complaints per issue group  
- Extract top keywords for each group  
- Generate issue summaries and CRM reports  

---

## Methodology
1. Load complaint dataset  
2. Preprocess complaint text  
3. Convert complaints into TF-IDF vectors  
4. Compute cosine similarity matrix  
5. Group similar complaints using threshold-based clustering  
6. Extract keywords and generate summaries  
7. Visualize complaint distribution by issue group  

---

## NLP Techniques Used
- Text Preprocessing  
- TF-IDF Vectorization  
- Cosine Similarity  
- Threshold-Based Clustering  
- Keyword Extraction  

---

## Technologies Used
- Python  
- Pandas  
- Scikit-learn  
- Matplotlib  

---

## Output
The project generates:
- Complaint vs Group ID Table  
- Similarity Matrix  
- Complaint Count by Group Chart  
- CRM Issue Summary Report  

---

## Applications
- CRM Ticket Deduplication  
- Issue Trend Analysis  
- Customer Support Automation  
- Complaint Routing Optimization  

---

## Future Improvements
- Use advanced clustering algorithms  
- Improve summary generation with NLP models  
- Deploy as CRM dashboard  
