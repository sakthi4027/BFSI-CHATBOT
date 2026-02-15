Project Overview:
-This AI assistant provides fast, accurate, and compliant responses to banking and loan queries. Built with a 3-tier architecture prioritizing safety and regulatory compliance,
-it currently implements Tier 1 (Dataset Matching) with 85%+ accuracy and sub-second response times.

## Project Objective
To build a lightweight and efficient AI assistant capable of handling common Banking, Financial Services, and Insurance (BFSI) customer queries with fast and accurate responses.

The assistant provides standardized responses for:
- Loan eligibility and application status  
- EMI details and schedules  
- Interest rate information  
- Payment and transaction queries  
- Basic banking customer support  

## Features
- 150+ BFSI conversation dataset  
- Semantic search-based response system  
- Local lightweight AI model  
- Fast and accurate responses  
- Safe and compliant financial answers  
- End-to-end working demo  

## System Architecture
User Query → Dataset Similarity Search → Best Match Response  

The assistant prioritizes dataset-based responses to ensure safety, consistency, and compliance with financial guidelines.

## Tech Stack
- **Embedding Model:** sentence-transformers/all-MiniLM-L6-v2
- **Similarity Matching:** Cosine similarity (threshold: 0.85)
- **UI Framework:** Gradio
- **Platform:** Google Colab (Python 3.10+)
