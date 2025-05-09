# Automated Business Outreach Tool using RAG
This project focuses on building an automated business outreach tool to assist software services companies in streamlining their client outreach. 
The system uses retrival augmented generation and large langauge models too generate personalized outreach emails based on job descriptions extracted from client career portals.

The process begins by scraping job descriptions from client portals using the LangChain framework. Once extracted, the job descriptions are embedded into a vector space. Each job description, D, and associated skills, S, are represented as k-dimensional vectors in ℝ^k stored in chromaDB. 
These vector representations allow the system to understand the semantics of the job posting.

# Technical Stack

## Frameworks & Libraries:

LangChain

ChromaDB

Llama 3.2

python

Databases: ChromaDB (Vector Database)

Deployment: Streamlit 

# License

This project is licensed under the MIT License.
